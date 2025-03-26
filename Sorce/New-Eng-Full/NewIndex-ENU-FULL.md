# **CONTENTS** {#contents .TOC-Heading}

[1. Executive summary [5](#executive-summary)](#executive-summary)

[2. VAT functionality [7](#vat-functionality)](#vat-functionality)

[2.1. VAT setup [7](#vat-setup)](#vat-setup)

[2.2. VAT protocols [13](#vat-protocols)](#vat-protocols)

[2.3. VAT on customs declaration
[22](#vat-on-customs-declaration)](#vat-on-customs-declaration)

[2.4. VAT ledgers and VAT declaration
[24](#vat-ledgers-and-vat-declaration)](#vat-ledgers-and-vat-declaration)

[2.5. VAT for private use of assets
[36](#vat-for-private-use-of-assets)](#vat-for-private-use-of-assets)

[2.6. Set up VAT Cash Regime
[39](#set-up-vat-cash-regime)](#set-up-vat-cash-regime)

[2.7. VAT Setup when carrying out activities under Art. 163
[43](#vat-setup-when-carrying-out-activities-under-art.-163)](#vat-setup-when-carrying-out-activities-under-art.-163)

[2.8. Postpone tax credit within the permitted 12-month period
[47](#postpone-tax-credit-within-the-permitted-12-month-period)](#postpone-tax-credit-within-the-permitted-12-month-period)

[3. Intrastat [51](#intrastat)](#intrastat)

[3.1. Intrastat Setup [51](#intrastat-setup)](#intrastat-setup)

[3.2. Creating a new Intrastat declaration
[59](#creating-a-new-intrastat-declaration)](#creating-a-new-intrastat-declaration)

[3.3. Creating files for Intrastat declaration
[61](#creating-files-for-intrastat-declaration)](#creating-files-for-intrastat-declaration)

[4. Finances -- localization settings
[63](#finances-localization-settings)](#finances-localization-settings)

[4.1. Automatic Create Default Dimensions
[63](#automatic-create-default-dimensions)](#automatic-create-default-dimensions)

[4.2. General Journal [63](#general-journal)](#general-journal)

[4.3. Trial Balance Register
[64](#trial-balance-register)](#trial-balance-register)

[4.4. Fixed assets [66](#fixed-assets)](#fixed-assets)

[4.5. Changes in posting with Deferral Templates
[68](#changes-in-posting-with-deferral-templates)](#changes-in-posting-with-deferral-templates)

[5. Purchases -- localization settings
[70](#purchases-localization-settings)](#purchases-localization-settings)

[5.1. Purchases & Payables Setup
[70](#purchases-payables-setup)](#purchases-payables-setup)

[5.2. Vendor card [71](#vendor-card)](#vendor-card)

[5.3. Purchase invoice [72](#purchase-invoice)](#purchase-invoice)

[5.4. Purchase credit memos
[75](#purchase-credit-memos)](#purchase-credit-memos)

[5.5. Void posted invoices and credit memos
[76](#void-posted-invoices-and-credit-memos)](#void-posted-invoices-and-credit-memos)

[5.6. Change data in posted purchase documents
[78](#change-data-in-posted-purchase-documents)](#change-data-in-posted-purchase-documents)

[5.7. Void a purchase invoice in next tax period
[80](#void-a-purchase-invoice-in-next-tax-period)](#void-a-purchase-invoice-in-next-tax-period)

[6. Sales -- localization settings
[81](#sales-localization-settings)](#sales-localization-settings)

[6.1. User setup [81](#user-setup)](#user-setup)

[6.2. Sales & Receivables Setup
[82](#sales-receivables-setup)](#sales-receivables-setup)

[6.3. Company information setup
[83](#company-information-setup)](#company-information-setup)

[6.4. Contact card [84](#contact-card)](#contact-card)

[6.5. Customer card [84](#customer-card)](#customer-card)

[6.6. Sales invoice [87](#sales-invoice)](#sales-invoice)

[6.7. Sales credit memos [90](#sales-credit-memos)](#sales-credit-memos)

[6.8. Print Sales invoices and credit memos
[92](#print-sales-invoices-and-credit-memos)](#print-sales-invoices-and-credit-memos)

[6.9. Sales protocol [97](#sales-protocol)](#sales-protocol)

[6.10. Cancel Sales invoices or credit memos
[98](#cancel-sales-invoices-or-credit-memos)](#cancel-sales-invoices-or-credit-memos)

[6.11. Change data in posted sales documents
[100](#change-data-in-posted-sales-documents)](#change-data-in-posted-sales-documents)

[7. Inventory -- localization settings
[102](#inventory-localization-settings)](#inventory-localization-settings)

[7.1. Assembly Setup [103](#assembly-setup)](#assembly-setup)

[7.2. Inventory Setup [103](#inventory-setup)](#inventory-setup)

[7.3. Item Journal [104](#item-journal)](#item-journal)

[7.4. Default Dimension in Item Category
[104](#default-dimension-in-item-category)](#default-dimension-in-item-category)

[8. Irrecoverable Receivable
[107](#irrecoverable-receivable)](#irrecoverable-receivable)

[8.1. Irrecoverable Receivable for purchases
[107](#irrecoverable-receivable-for-purchases)](#irrecoverable-receivable-for-purchases)

[8.2. Irrecoverable Receivable for sales
[109](#irrecoverable-receivable-for-sales)](#irrecoverable-receivable-for-sales)

[9. Service [112](#service)](#service)

[9.1. Function Copy Document in Service Credit Memo
[112](#function-copy-document-in-service-credit-memo)](#function-copy-document-in-service-credit-memo)

Specifies the VAT specification of the involved item or resource to link
transactions made for this record with the appropriate general ledger
account according to the VAT posting setup.

Specifies the VAT specification of the involved customer or vendor to
link transactions made for this record with the appropriate general
ledger account according to the VAT posting setup.

# Executive summary

FTS Bulgaria provides completely localized version of Dynamics 365 BC,
translated into Bulgarian language, and in consistency with the
requirements of Bulgarian legislation. The system offers possibility for
adjustment, publishing and printing of financial reports and
statements/references such as Trial balance, VAT ledgers and
declaration, including VIES, INTRASTAT declarations and other documents,
all required by Bulgarian legislation and accounting standards.

The localization package includes the following functionalities:

-   Registration of purchase and sales documents in accordance with the
    legislation requirements

-   VAT sales and purchase ledgers

-   Monthly VAT and VIES declaration

-   VAT protocols creation and printouts

-   Export of VAT ledgers and declarations

-   INTRASTAT

-   Posted sales and purchase documents voiding

-   Advance payments from customers

-   Trial balance register

-   Fixed assets reports (depreciation plan for corporate tax and
    accounting purposes)

-   Sales invoices and credit memos print forms

When creating a new company, it is necessary to activate the
localization package for Bulgaria. Activation is performed in the
**General Ledger Setup** page from the menu **Actions**, **Functions** -
**Change BG Localization Activation Status**.

After activation it is necessary to check the status in the **BG
localization Settings** section.

![](.\/media/image1.png){width="6.531944444444444in"
height="3.1006944444444446in"}

# VAT functionality

The VAT functionality, as part of the localization package for Bulgaria,
meets the requirements for VAT statutory reporting.

The main menu for working with the functionality is in the role center
"Accountant".

![](.\/media/image2.png){width="6.531944444444444in"
height="2.3958333333333335in"}

## VAT setup

### General setup

The initial setup is in page **BG, VAT and VIES setup**

![](.\/media/image3.png){width="6.531944444444444in"
height="2.172222222222222in"}

This table contains data on specific localization setup regarding:
checks of VAT registration numbers, bank codes, VAT, VIES and INTRASTAT,
setup of VAT files export (names of files), standard VAT subject for the
purposes of VAT ledgers for sales and purchase documents.

![A screenshot of a computer Description automatically generated with
low confidence](.\/media/image4.png){width="6.531944444444444in"
height="3.05625in"}

-   **Checks**

<!-- -->

-   **Skip Check for Identification No -** check this field, if the
    check for Identification No. should not be activated.

-   **Foreigner VAT reg. No. -** enter a standard foreigner VAT reg.
    number (999999999999999). The system checks if the VAT number,
    entered in the vendor or customer card, is the same as the number,
    entered in this field.

-   **Foreigner Identification No. -** enter a standard foreigner
    Identification No. (9999999999). The system checks if the
    identification number, entered in the vendor or customer card, is
    the same as the number, entered in this field.

-   **Posting Purchase Invoice -** Specifies whether it is allowed
    posting a purchase invoice with the same document number and
    different date.

<!-- -->

-   **VAT export setup**

<!-- -->

-   **Sales VAT subject -** define the standard VAT sales subject for
    the purposes of the VAT sales ledger (length: 30 symbols). If no
    specific VAT subject is entered in the sales document before posting
    (invoice/credit memo/sales protocol), the VAT subject for the VAT
    sales ledger is taken from this field.

-   **Purchase VAT subject -** define the standard VAT subject for the
    purposes of for the VAT purchase ledger (length: 30 symbols). If no
    specific VAT subject is entered in the purchase document before
    posting (invoice/credit memo), the VAT subject for the VAT purchase
    ledger is taken from this field.

-   **Incl. sales with customs declarations** - if this option is
    enabled, the document will be included in the sales VAT ledger, if
    you fill in the SAD number in the sales document.

-   **Incl. purchases with customs declaration** - if this option is
    enabled, the document will be included in the purchase VAT ledger,
    if you fill in the field SAD number in the purchase document.

<!-- -->

-   **VAT Label**

<!-- -->

-   **Authorized Person -** enter the ID/name of the company
    representative (the value of this field is used in the exported file
    with the VAT monthly declaration)

-   **VAT registration date -** enter the company registration date
    under the VAT regime.

-   **VAT registration expiry date -** enter the date of termination of
    the registration under the VAT regime

<!-- -->

-   **VAT Declarations**

![](.\/media/image5.png){width="6.531944444444444in"
height="1.1027777777777779in"}

-   **Declaration signed-off -** enter the name of the company
    representative, submitting the VAT files. The value of this field is
    taken for the print form of the VAT monthly ledgers.

-   **Job Position -** enter the job position of the company
    representative. The value of this field is taken for the print form
    of the VAT ledgers.

<!-- -->

-   **Local properties**

<!-- -->

-   BG country/region code -- enter the code of Bulgaria (BG) -- for
    system purposes.

-   Local language code -- enter BGR. The setup is related to the print
    forms in Bulgarian.

### VAT combinations

Here only the fields, related to the localization package, will be
discussed.

![](.\/media/image6.png){width="3.6083333333333334in"
height="3.2583333333333333in"}

The main fields for the setup of the VAT combinations for the Bulgarian
localization are:

-   **Transaction type** -- options: **Purchase, Sales, Both**. Option
    **Both** is used for the VAT protocols

-   **Purchase VAT refund type --** options: **full refund**, **partial
    refund**, **no refund**, **annual corrections**. This column defines
    in which columns the transaction will be included:

**Full refund -** the sums will be included in the columns for VAT base
and VAT amount.

> **No refund -** the purchase invoice with a VAT combination with **No
> refund** will be included in the column for purchases with no refund.
>
> **Partial refund --** when **Partial refund** is selected, the sums
> will be included in the columns for transactions with **Partial VAT
> credit.**
>
> **Annual correction-** used for column for transactions under art. 73,
> p. 8 in the purchase VAT ledger.

-   **Calculate VAT for Personal Use** - used for protocols for private
    use of assets. The document is included in the VAT sales ledger.

-   **Vat classification code** -- if no code is entered, enter code 00.

+----+------------------------------------+----------------------------+
| Co | Description                        | Comments                   |
| de |                                    |                            |
+====+====================================+============================+
| 00 | Local transactions                 |                            |
+----+------------------------------------+----------------------------+
| 01 | Other Cases Normal VAT             | For VAT for private use.   |
+----+------------------------------------+----------------------------+
| 02 | Purchases according to art. 82,    | Used in VAT purchase       |
|    | p.2-5                              | protocols                  |
+----+------------------------------------+----------------------------+
| 03 | Subject to 0% VAT acc. to Ch.3 of  | The transaction is         |
|    | the VAT Act                        | included in column 19      |
|    |                                    | (sales under chapter 3 of  |
|    |                                    | the VAT Act)               |
+----+------------------------------------+----------------------------+
| 04 | Subject to 0% VAT, acc. to art.    | The transaction is         |
|    | 140,146 and 173, p.1 and 4 of the  | included in column 21      |
|    | VAT Act                            | (deliveries with VAT rate  |
|    |                                    | 0% по чл. 140, чл. 146,    |
|    |                                    | ал. 1 и чл. 173 ЗДДС)      |
+----+------------------------------------+----------------------------+
| 05 | Sales subject to 0% VAT, acc. to   | The transaction is         |
|    | art.21, p.3 and art. 22-24 of the  | included in column 22 (Tax |
|    | VAT Act                            | base for supplies of       |
|    |                                    | services under Art. 21,    |
|    |                                    | para. 2 of the VAT Act,    |
|    |                                    | with a place of            |
|    |                                    | performance on the         |
|    |                                    | territory of another EU    |
|    |                                    | Member Country)            |
+----+------------------------------------+----------------------------+
| 06 | Transactions acc. to art. 69, p.2  | Used for Sale type and     |
|    | of the VAT Act                     | Both type.                 |
|    |                                    |                            |
|    |                                    | Code 06 in the sales       |
|    |                                    | journal is included in     |
|    |                                    | column 23 (Tax base of     |
|    |                                    | supplies under Article 69, |
|    |                                    | paragraph 2 of the VAT     |
|    |                                    | Act, including Tax base of |
|    |                                    | supplies under the         |
|    |                                    | conditions of distance     |
|    |                                    | sales, with a place of     |
|    |                                    | performance in the         |
|    |                                    | territory of another EU    |
|    |                                    | Member Country).           |
|    |                                    |                            |
|    |                                    | In the purchase ledger,    |
|    |                                    | when it is a protocol and  |
|    |                                    | is entitled to a full tax  |
|    |                                    | credit, it reflects in     |
|    |                                    | columns 10 (TO the         |
|    |                                    | received deliveries, VAT,  |
|    |                                    | the received deliveries    |
|    |                                    | art. the received          |
|    |                                    | deliveries, used for       |
|    |                                    | making deliveries under    |
|    |                                    | art. 69, para 2 of the VAT |
|    |                                    | Act with the right to a    |
|    |                                    | full tax credit) and 11    |
|    |                                    | (VAT with the right to a   |
|    |                                    | full tax credit).          |
|    |                                    |                            |
|    |                                    | In the purchase journal,   |
|    |                                    | when entitled to a partial |
|    |                                    | tax credit - in columns 12 |
|    |                                    | (TO the received supplies, |
|    |                                    | VAT, received supplies     |
|    |                                    | Art. 82, para 2-5 of the   |
|    |                                    | VAT Act, imports, as well  |
|    |                                    | as TO the received         |
|    |                                    | supplies used for making   |
|    |                                    | supplies under Article 69, |
|    |                                    | paragraph 2 of the VAT Act |
|    |                                    | with the right to a        |
|    |                                    | partial tax credit) and 13 |
|    |                                    | (VAT with the right to a   |
|    |                                    | partial tax credit)        |
+----+------------------------------------+----------------------------+
| 07 | Subject to 7% VAT charge           | It is related to taxable   |
|    |                                    | supplies at a rate of 7 or |
|    |                                    | 9%. It is reflected in     |
|    |                                    | column 17 of the sales     |
|    |                                    | ledger.                    |
+----+------------------------------------+----------------------------+
| 08 | Intra-community purchases          | For VAT purchase protocols |
|    |                                    | for intracommunity         |
|    |                                    | purchases                  |
+----+------------------------------------+----------------------------+
| 09 | Distant sales effected within the  | Code 09 in the sales       |
|    | territory of another EU member     | journal is included in     |
|    | country                            | column 23 (Tax base of     |
|    |                                    | supplies under Article 69, |
|    |                                    | paragraph 2 of the VAT     |
|    |                                    | Act, including Tax base of |
|    |                                    | supplies under the         |
|    |                                    | conditions of distance     |
|    |                                    | sales, with a place of     |
|    |                                    | performance in the         |
|    |                                    | territory of another EU    |
|    |                                    | Member Country)            |
+----+------------------------------------+----------------------------+
| 10 | Sales and Intra-community          | The transaction goes to    |
|    | acquisitions exempt from VAT       | column 24 of the sales     |
|    |                                    | ledger (Sales and          |
|    |                                    | Intra-community            |
|    |                                    | acquisitions exempt from   |
|    |                                    | VAT).                      |
+----+------------------------------------+----------------------------+
| 11 | Import                             | Only for VAT purchase      |
|    |                                    | ledger for import from     |
|    |                                    | non-EU countries           |
|    |                                    |                            |
|    |                                    | When in combination        |
|    |                                    | Without the right to a tax |
|    |                                    | credit in the purchases,   |
|    |                                    | it reflects in column 9    |
|    |                                    | (TO and tax on supplies    |
|    |                                    | received, VAT, supplies    |
|    |                                    | received under Article 82, |
|    |                                    | paragraphs 2-5 of the VAT  |
|    |                                    | Act and the import without |
|    |                                    | tax).                      |
|    |                                    |                            |
|    |                                    | In the purchase ledger,    |
|    |                                    | when it is a protocol and  |
|    |                                    | is entitled to a full tax  |
|    |                                    | credit, it reflects in     |
|    |                                    | columns 10 (TO the         |
|    |                                    | received deliveries, VAT,  |
|    |                                    | the received deliveries,   |
|    |                                    | used for making deliveries |
|    |                                    | under art. 69, para 2 of   |
|    |                                    | the VAT Act with the right |
|    |                                    | to a full tax credit) and  |
|    |                                    | 11 (VAT with the right to  |
|    |                                    | a full tax credit).        |
|    |                                    |                            |
|    |                                    | In the purchase ledger,    |
|    |                                    | when it is entitled to a   |
|    |                                    | partial tax credit in      |
|    |                                    | column 12 (TO the received |
|    |                                    | deliveries, VAT, the       |
|    |                                    | received deliveries Art.   |
|    |                                    | 82, para 2-5 of the VAT    |
|    |                                    | Act, the import, as well   |
|    |                                    | as TO the received         |
|    |                                    | deliveries, used for       |
|    |                                    | making of supplies under   |
|    |                                    | Article 69, paragraph 2 of |
|    |                                    | the VAT Act with the right |
|    |                                    | to a partial tax credit)   |
|    |                                    | and column 13 (VAT with    |
|    |                                    | the right to a partial tax |
|    |                                    | credit)                    |
+----+------------------------------------+----------------------------+
| 12 | Intermediary in triangular         | For deliveries as          |
|    | operations                         | Intermediary in triangular |
|    |                                    | operations                 |
+----+------------------------------------+----------------------------+
| 13 | Intra-community sales              | Related to sales ledger    |
|    |                                    | and column 20 (TO supplies |
|    |                                    | with 0% Intra-community    |
|    |                                    | sales)                     |
+----+------------------------------------+----------------------------+
| 50 | VAT protocol for fuel compensation | In the page VAT posting    |
|    |                                    | setup, in the Edit mode of |
|    |                                    | the VAT combination for    |
|    |                                    | the compensation, in the   |
|    |                                    | General section there is a |
|    |                                    | field Compensation         |
|    |                                    | protocol, which must be    |
|    |                                    | checked. Based on this     |
|    |                                    | check, when a VAT ledger   |
|    |                                    | is generated, a VAT        |
|    |                                    | protocol with these        |
|    |                                    | combination will enter     |
|    |                                    | with code 50.              |
+----+------------------------------------+----------------------------+
| 83 | Fuel compensation sales            | In the page of BG, VAT and |
|    |                                    | VIES settings in the VAT   |
|    |                                    | label section, a field     |
|    |                                    | \"Compensation customer    |
|    |                                    | code\" has been added. In  |
|    |                                    | this field, you must       |
|    |                                    | indicate the client for    |
|    |                                    | whom the invoices will be  |
|    |                                    | issued with the fuel that  |
|    |                                    | will be compensated. The   |
|    |                                    | sales of this customer in  |
|    |                                    | the VAT ledger will be     |
|    |                                    | entered with code 83, they |
|    |                                    | will be entered document   |
|    |                                    | by document, because they  |
|    |                                    | use invoice numbering.     |
+----+------------------------------------+----------------------------+
| 84 | Delivery of bread                  | In the VAT classification  |
|    |                                    | code, 00 is filled in for  |
|    |                                    | the VAT combination, and   |
|    |                                    | in the column \"Specific   |
|    |                                    | purchase par. 163a\" code  |
|    |                                    | 07 is filled in. In this   |
|    |                                    | case, the type of the      |
|    |                                    | document will be changed   |
|    |                                    | to 84 in the VAT ledger    |
+----+------------------------------------+----------------------------+
| 85 | Delivery of flour                  | In the VAT classification  |
|    |                                    | code, 00 is filled in for  |
|    |                                    | the VAT combination, and   |
|    |                                    | in the column \" Specific  |
|    |                                    | purchase par. 163a \",     |
|    |                                    | code 08 is filled in. In   |
|    |                                    | this case, the type of     |
|    |                                    | document will be changed   |
|    |                                    | to 85 in the VAT ledger    |
+----+------------------------------------+----------------------------+
| 90 | Only in VAT Sales Ledger           | When posting a VAT Sales   |
|    |                                    | protocol with the relevant |
|    |                                    | VAT combination - this     |
|    |                                    | record will be entered     |
|    |                                    | only in a sales ledger     |
|    |                                    | with code 09 and only the  |
|    |                                    | amount of VAT is recorded  |
|    |                                    | in column 12 (VAT charged  |
|    |                                    | for purchases on c.11 and  |
|    |                                    | (20%) according to other   |
|    |                                    | cases), without base.      |
+----+------------------------------------+----------------------------+
| 92 | Purchases according to art. 82,    | Used in the VAT protocols  |
|    | p.2-5                              | described below            |
+----+------------------------------------+----------------------------+
| 98 | Intra-community purchases          | Used in the VAT protocols  |
|    |                                    | described below            |
+----+------------------------------------+----------------------------+

## VAT protocols

The VAT protocols are created from page „Purchase VAT protocols" and
„Sales VAT protocols". The posted protocols could be found in pages
„Posted Purchase VAT protocols" and „Posted Sales VAT Protocols".

You can see them in the **Accountant** role center:

![](.\/media/image7.png){width="6.531944444444444in"
height="2.5395833333333333in"}

### VAT Protocols Setup

In **General ledger setup** the number series for VAT protocols and
posted VAT protocols are set up in fileds VAT Protocol Nos. and Posted
VAT Protocol Nos.

![](.\/media/image8.png){width="5.39986220472441in"
height="3.5025054680664915in"}

In **Purchase and Payables setup** the VAT Business posting group for
VAT protocols is set up in field EU VAT Bus.Posting Group

![](.\/media/image9.png){width="6.196592300962379in"
height="3.779486001749781in"}

In **Sales and Receivables setup** the VAT Business posting group for
VAT protocols is set up in field EU VAT Bus.Posting Group

![](.\/media/image10.png){width="6.531944444444444in"
height="3.379861111111111in"}

### Creation of VAT purchase protocols

To create a new VAT purchase protocol, go to **VAT reporting- Purchase
VAT protocols**

![](.\/media/image11.png){width="6.531944444444444in" height="1.1875in"}

To create a new protocol, Choose **New.**

![](.\/media/image12.emf){width="6.531944444444444in"
height="1.1201388888888888in"}

Choose vendor and press Enter, so that a new protocol to be created.

![](.\/media/image13.png){width="6.531944444444444in"
height="4.302777777777778in"}

Choose **Copy document**, and choose the document, from which the
protocol should be created. Several options are available:

![](.\/media/image14.png){width="3.347536089238845in"
height="3.2850306211723534in"}

-   **Posted VAT protocol** -- copy from a posted VAT protocol

-   **Posted invoice** -- copy from a posted purchase invoice

-   **Posted credit memo** -- copy from a posted purchase credit memo

-   **Ledger entries** -- copy from entries, created in **General
    journal**.

> **Include header** -- mark this field, if the data from the selected
> document header have to be used. If **Ledger entries** is selected,
> the header has to be filled in manually.
>
> **Compress lines** -- if the field is not marked, the lines of the
> posted document are copied to the protocol. If the field is marked,
> the lines are compressed into one line.

After the document is selected, press OK and the data is filled in the
protocol.

![](.\/media/image15.png){width="5.99496719160105in"
height="2.5353313648293963in"}

In the VAT protocol header, fill in **Composed by** and **Ground for
issue.**

You can also fill a **VAT description** field. The description is filled
in which is reflected in the VAT Ledgers in the column VAT description.
If left blank, it will be populated with the value of Sales VAT
Subject/Purchase Vat Subjest VAT fields from page BG, VAT and VIES
setup;

VAT protocols can be created for several documents. In order to use this
functionality, from the list of the protocols choose the button Create
Purch. VAT protocol.

![](.\/media/image16.png){width="6.531944444444444in"
height="1.6743055555555555in"}

In the window that opens, fill in the following fields:

![](.\/media/image17.png){width="4.489583333333333in"
height="6.54166447944007in"}

-   **Document date -** enter the VAT protocol document date. Valid for
    all protocols that will be issued.

-   **Posting date** -- enter the VAT protocol posting date. Valid for
    all protocols that will be issued.

-   **VAT date** -- if left empty, the field will be filled in with the
    date of the copied posted document

-   **Create from invoices** -- if this option is marked, the system
    will create the invoices from the posted purchase invoices

-   **Create from credit memos** -- if this option is marked, the system
    will create the invoices from the posted purchase credit memos

-   **New protocol per document** -- when selecting this option,
    separate protocols will be created for each invoice / credit memo.
    Otherwise, the system will summarize the invoices and CMs for each
    vendor in one protocol.

-   **Compress lines** -- if this option is checked, the system will
    summarize all lines of the invoice or CM in one line. Otherwise, all
    lines of the source document will be copied to the protocol.

-   **Ground for Issue --** if a ground for issue is selected from the
    list, it will be populated in the created VAT protocols.

-   **Skip the EU check for creation VAT Protocol** -- if the toggle is
    On VAT protocols for non EU vendor's documents will be created.

-   **Create protocol for BG contragent** - when this option is marked
    the tool will create VAT protocols for the selected document types
    issued by local (bulgarian) vendors.

**Vendor**, **Invoice** and **Credit Memo** help to further filter the
documents. For example, you can specify in the Filter **Vendor,** VAT
business posting group with the value that applicable for EU suppliers
(VEND EU). This will filter only those documents that are from EU
vendors.

Once the protocols are posted, in the list of posted invoices and credit
memos, the system automatically marks the documents for which VAT
protocols are issued. This avoids the re-generation of protocols for
these documents.

### VAT combinations in VAT protocols

The VAT combination defines in which columns of the VAT ledgers the
protocol will be included.

![](.\/media/image18.png){width="6.531944444444444in"
height="1.7881944444444444in"}

When the combination is with classification code 08, the protocol is
included in the VAT purchase ledger in columns 10 and 11, and in VAT
sales ledger in columns 9, 10, 13, 15.

When the combination is with classification code 02, the protocol is
included in the VAT purchase ledger in columns 10 and 11, and in VAT
sales ledger in columns 9, 10, 14, 15.

![](.\/media/image19.png){width="6.531944444444444in"
height="1.9145833333333333in"}

When the protocol has to be included in the VAT purchase ledger with no
VAT refund, and the VAT amount has to be included in this sum, it is
necessary to select a combination, that has VAT classification codes 98
and 92, for which "No refund" is selected. In this case only for these
two codes the amount, including the VAT amount, will be included in the
VAT purchase ledger. The columns in the VAT sales ledger are similar to
those for code 02 and 08.

### VAT protocol included only in the VAT Sales Ledger

When a VAT protocol should be registered only in the VAT Sales Ledger we
can use the functionality of VAT for private use of assets, described in
this document. The protocol will be included only in the VAT Sales
Ledger. It is necessary to set a new VAT combination, which should be
marked for personal use, as well as the protocol itself to be marked as
a protocol for personal use of assets.

Vat Classification code 90 is also used for these cases. When posting a
VAT Sales protocol with the relevant VAT combination, this record will
be entered only in a sales ledger with code 09 and only the amount of
VAT is recorded in column 12 (VAT charged for purchases on c.11 and
(20%) according to other cases), without base.

### Voiding VAT Protocol

When the VAT protocol has to be voided, go to the posted VAT protocol,
choose Actions - Functions- Voiding VAT Protocol.

Reversing GL entries are posted, and the protocol is included in the VAT
ledgers with 0 amounts.

![](.\/media/image20.png){width="5.4815091863517065in"
height="3.9985247156605426in"}

Reversing GL entries are posted with the selected voiding date. If the
voiding date is in the reporting month the protocol is included in the
VAT ledgers with 0 amounts. But if the voiding date is in the next month
the reversing entries will be included in the VAT ledgers for the next
month with negative amounts.

### Reversing VAT protocol (credit protocol)

When you create a reversing VAT protocol, the field Correction has to be
marked. When the protocol is created from a posted purchase credit memo,
the field is marked automatically.

![](.\/media/image21.png){width="6.531944444444444in"
height="2.015277777777778in"}

## VAT on customs declaration

VAT on customs declaration is posted in General Journal. In the General
Journal, fill in the following fields:

-   **GL account -** select the account for VAT on purchase

-   **Posting date**

-   **SAD No.** - Customs declaration number

-   **General posting type** -- Purchase;

-   **Amount** -- amount of VAT on the customs declaration

-   **VAT subject** -- if not filled in, the transaction will be
    included with subject Purchase in the VAT purchase ledger

-   **VAT Business posting group**-- ZVAT MD (the VAT Business posting
    group for VAT on customs declarations);

-   **VAT product posting group** -- VAT20

![](.\/media/image22.png){width="6.531944444444444in"
height="1.8076388888888888in"}

In the VAT Posting Setup the VAT posting groups combination has to be
set up as follows:

-   **VAT%** - 20;

-   **VAT calculation type** -- Full VAT;

-   **Transaction type** -- Purchase;

-   **Purchase VAT refund type** -- Full refund

-   **VAT classification code**- 00

![](.\/media/image23.png){width="5.618055555555555in"
height="3.0555555555555554in"}

In the VAT purchase ledger, the transaction is included as a document
type 07.

## VAT ledgers and VAT declaration

In accordance with the Bulgarian tax law, the following VAT statutory
reports are submitted to tax authorities on a monthly basis:

-   VAT declaration

-   VAT Purchase ledger

-   VAT Sales ledger

-   VIES Return

VAT purchase and sales ledgers are books, that include each taxable
sales or purchase transaction with a posting date in the specified
month, for which the ledgers are created.

VAT ledgers have a set of mandatory data that are to be entered for
every transaction -- invoice number, document type, invoice date,
customer/vendor name and VAT number, transaction description, VAT base,
and VAT amount.

The sales/purchase document tax base amount and tax amount are included
in different columns of the VAT ledgers, depending on the tax law
articles compliance.

Some transactions should be excluded from VAT ledgers (e.g. purchases
from non-EU countries, that are included in the VAT purchase ledger with
the customs declaration number after posting the VAT on customs
declaration).

### VAT ledgers creation

The posting date of the document defines in which monthly VAT ledgers
the transaction will be included.

To create a new VAT ledger, go to the main menu of role center
Accountant, section VAT Reporting.

![](.\/media/image24.png){width="6.531944444444444in"
height="2.547222222222222in"}

A new ledger can be created from the Purchase Ledger List or the Sales
Ledger List page, and an existing ledger can also be viewed, edited,
deleted, or printed.

![](.\/media/image25.png){width="6.531944444444444in"
height="1.34375in"}

Creating a new ledger is done by selecting the action **New**. A window
opens in which it is necessary to enter the first day of the respective
month for which the ledger is created - in the field **Period** **Start
date.**

![](.\/media/image26.png){width="6.531944444444444in"
height="2.5840277777777776in"}

Then it is necessary to select **Create**. When performing this action,
the data is loaded in the lines of the ledger as in the screenshot
below:

![](.\/media/image27.png){width="6.531944444444444in"
height="2.984027777777778in"}

The entries included in the ledger are those that are posted in the
system at the time of creating the ledger and their posting date is
within the period for which the ledger is created. In case, after
generating a ledger, more documents for the period are posted, it is
necessary to generate the ledger again with the Create button.

The fields in the VAT ledger that provide information about the status
of the ledger are the following:

• Created - indicates that the ledger has created rows with data from
the posted documents.

• Exported - indicates whether the ledger data was exported in files for
submission to the tax administration. A ledger marked as Exported cannot
be changed.

• Status - indicates the status of the ledger: Open or Started. Status
Open means that the Create action can be performed, and in case the
ledger has already been created, the data in it can be changed. Status
Started means that the ledger data cannot be changed and the Create
action cannot be performed on it.

For each VAT ledger certain actions can be performed. You can find them
in menu Actions - Functions.

![](.\/media/image28.png){width="6.531944444444444in"
height="2.9451388888888888in"}

• **Create** - creates lines in the ledger with data from the posted
documents. For one log, the action can be performed repeatedly. Each
execution of the action removes the existing rows in the log and reloads
them. In order for the action to be performed, the status of the ledger
must be Open. Status Open for a ledger that has already acquired the
status Started is obtained with the action Reopen.

In case the Create action is performed for a ledger that has the status
Open, but is marked as Exported, then the system displays a warning
message that the log has already been exported.

• **Check** - checks the created ledger for errors that would prevent
the acceptance of the ledger by the tax administration. Example of
error: Contragent ID field is not filled in.

• **Release** - changes the status of the ledger from Open to Released.
For a ledger with Status Released, no changes can be made and the Create
action cannot be performed.

• **Reopen** - changes the status of the ledger from Released to Open.
Only for a ledger with the status Open, the Create action can be
performed.

After a ledger is exported in a file with a format for submission to the
tax administration (described in item 2.4.4. Creating VAT files), the
ledger is automatically marked as Exported. In addition, in the ledger
list and in the ledger itself, its status is changed to Released.

If corrections are needed in an already exported ledger, it must be
opened again with the Reopen action, then re-created or corrected. Once
the adjustments have been made, new VAT files should be created for the
ledger.

When a ledger is selected, Statistics related to it is displayed on the
right side of the screen, where summary information about the entries
included in the ledger can be obtained.

![](.\/media/image29.png){width="6.531944444444444in"
height="3.3513888888888888in"}

Using the Print action, the ledger can be displayed on a screen, printed
on a printer, or saved as a file:

![](.\/media/image30.png){width="6.531944444444444in"
height="3.428472222222222in"}

### VAT declaration creation

The VAT declaration is created from the main menu of the Accountant role
center.

![](.\/media/image31.png){width="6.531944444444444in"
height="1.2840277777777778in"}

A new declaration is created using the Create button. In the new line
that appears in the list of declarations, the Period Start date - the
first day of the declared month - must be entered. All fields for
amounts in the lines of the declaration are filled in manually (not
calculable), including the amounts of VAT for refund and deduction.

![](.\/media/image32.png){width="6.531944444444444in"
height="0.9548611111111112in"}

The declaration is generated after the purchase and sales ledgers have
been generated. To display the Declaration itself, it is necessary to
select the **Print** button. The data for the person responsible for
preparing and submitting the declaration are entered once and after
printing the document on a printer or saving it in a file, they are
saved and do not need to be entered for the next printing. It is
necessary to mark that this person is a Representative of the company,
as well as to indicate a Confirmation of correctness of the data. After
this data is filled in, select View or Print.

![](.\/media/image33.png){width="4.271593394575678in"
height="5.1650415573053365in"}

The report is visualized and from it you can see the amount of VAT to be
paid or deducted. This amount must then be entered on the lines of the
declaration (field VAT effectively paid).

![](.\/media/image34.png){width="6.186111111111111in"
height="7.436805555555556in"}

![](.\/media/image35.png){width="5.377083333333333in"
height="7.428472222222222in"}

### VIES declaration creation

The VIES declaration is created from the main menu of the Accountant
role center.

![](.\/media/image36.png){width="6.531944444444444in"
height="1.3493055555555555in"}

A new declaration is created using the **New** button.

![](.\/media/image37.png){width="6.531944444444444in"
height="1.0486111111111112in"}

A new line appears in the list of declarations, in which the Period
Start date must be entered - the first day of the declared month, as
well as data about the employee responsible for preparing and submitting
the declaration - ID, Name, Position (Authorized person, Procurator),
Address.

The Print button opens a window in which the declaration is prepared for
printing.

![](.\/media/image38.png){width="3.591891951006124in"
height="3.8561220472440945in"}

![](.\/media/image39.png){width="6.504693788276465in"
height="6.85494750656168in"}

### VAT ledgers export

VAT files are created on the VAT Ledgers Export page. For the role
center Accountant, it is located in the main menu, in the VAT Reporting
section.

![](.\/media/image40.png){width="6.531944444444444in"
height="1.9840277777777777in"}

In the page opened, you can specify:

• Period - month and year for which data is exported

• Ledgers and declarations for which files will be created

• The names of the files to be created

![](.\/media/image41.png){width="4.316666666666666in" height="4.85in"}

The fields for the file names are filled in automatically with values,
according to the requirements for their submission to the tax
administration:

-   PRODAGBI.TXT -- VAT Sales ledger

-   POKUPKI.TXT -- VAT Purchase ledger

-   DEKLAR.TXT - VAT declaration

-   VIES.TXT - VIES Declaration

By selecting the OK button, one archive file is created that contains
all marked diaries and declarations.

![](.\/media/image42.png){width="6.531944444444444in"
height="3.223611111111111in"}

Once the export files for the ledgers are generated, the system
automatically marks these ledgers as Exported. Files for VAT ledgers and
declarations can be generated repeatedly if necessary to correct the
data.

## VAT for private use of assets

### **General terms of the VAT for private use of assets**

The rules for VAT for private use of assets are applied according to
Art. 6, para. 3, item 1 and Art. 9, para. 3, item 1 of the VAT Act and
the need for VAT registered companies to declare the tax on the assets
used for personal needs when submitting the monthly declaration and the
ledgers for purchases and sales to the tax administration.

The VAT for private use of assets is charged by issuing a protocol not
later than 15 days from the date on which the tax has become due - Art.
117, para. 1, item 3 of the VAT Act.

The protocol should contain the following details:

-   number and date;

-   the name and the identification number under Art. 94, para. 2 of the
    registered vendor;

-   the quantity and type of goods or type of service;

-   the date of occurrence of the tax event on the supply;

-   the tax base;

-   the tax rate;

-   the grounds for charging the tax by the company - art. 82, para. 1
    of the VAT Act;

-   the amount of tax.

In Art. 80 of the VAT Act, additional requirements are set regarding the
protocols, such as permanently entered details, numbering and
cancellation and storage.

The report shall be included in the sales journal with document code
(09), the amount of tax charged being reflected in column 16 - Tax
charged on supplies of goods or services for personal use.

The amount of the tax should be included in determining the result for
the respective tax period in the monthly VAT declaration under Art. 125
for this tax period in cell 23 - Tax charged on supplies of goods or
services for personal use.

When companies choose to use assets for personal needs, in Dynamics 365
Business Central it is necessary to follow the steps described below.

###  Setup of VAT Business and Product posting groups in VAT Posting Setup for VAT for private use of assets

In **VAT posting setup,** the following fields are set up:

![](.\/media/image43.png){width="6.531944444444444in"
height="1.2833333333333334in"}

The combination of the VAT business posting group and VAT product
posting group has the following parameters:

-   **VAT calculation type -** full VAT

-   **VAT % -** 20**;**

-   **Sales VAT account --** xxxxx (the account for VAT on sales)

-   **Purchase VAT account --** xxxxx (an expense account for the VAT
    paid for private use of assets);

-   **Transaction type --** Sales;

-   **VAT classification code --** 01;

-   **Calculate VAT for personal use -**
    ![](.\/media/image44.png){width="0.21666666666666667in"
    height="0.23333333333333334in"}

**Note:** When posting documents (VAT protocol) with this combination,
the amount of VAT will be reflected in column 16 -- VAT charged for
purchases of goods or services for personal needs of the Sales Ledger
and in cell 23 - VAT charged for purchases of goods or services for
personal needs of the VAT monthly declaration.

There must be no posting groups in the account card referred to as \"VAT
Purchases Account\" in VAT Posting Setup.

### Setup in VAT Purchase Protocol

For incurring VAT for private use a VAT purchase protocol is created. In
the VAT purchase protocol header a new field "Calculate VAT for personal
use" is added.

This field should be marked, if the protocol is for VAT for private use.
The protocol will be included in the VAT Sales Ledger only.

![](.\/media/image45.png){width="5.3974354768153985in"
height="2.62951990376203in"}

In the VAT protocol lines the specific VAT Product posting group should
be selected.

![](.\/media/image46.png){width="5.756624015748032in"
height="1.1092596237970254in"}

**Note:** the system makes the following checks:

-   **The field "VAT for personal use" is checked in VAT posting groups
    combination (VAT posting setup)**;

-   **The field "VAT for personal use" is checked in the VAT purchase
    protocol header, tab General**

Only if these two fields are checked, the VAT protocol for VAT for
personal use will be posted.

If only one of the fields is checked, the system displays a warning
message for a discrepancy and does not allow posting until the
discrepancy is rectified:

![](.\/media/image47.png){width="3.4736646981627297in"
height="1.2083737970253718in"}

**Note:** When creating a **Purchase Protocol**, it is advisable that
the **Copy document** function is used and the **Include Header** field
is checked. Thus, the type and number of the copied document are
recorded in the **Purchase Protocol** header, in the fields **Original
Document Type** and **Original Document No.** The content of these
fields cannot be edited subsequently. If **Copy document** does not use
checking of the **Include Header** field, then the fields in the
protocol remain blank and in the printed form of the protocol the field
**To document / Date** remains blank as well.

![](.\/media/image48.png){width="4.557638888888889in"
height="1.4618055555555556in"}

## Set up VAT Cash Regime 

The introduction of the VAT Cash Regime in the National Tax legislation
is aimed at supporting small businesses that encounter difficulty to pay
value added tax to the budget before they have received payment from
their customers for the goods and services supplied by them.

The cash regime is applied in cases where there is a taxable supply at a
rate of 20% VAT, payment is be made by bank transfer, the vendor and the
recipient are registered pursuant to the Bulgarian VAT Act, and are not
related parties.

The following steps should be followed to do the required setup in
Dynamics 365 Business Central.

### General Setup

You need to search for and open the **General Ledger Setup** page.

![](.\/media/image49.png){width="6.5in" height="2.0in"}

You must check the fields **Unrealized VAT** and **Prepayment Unrealized
VAT**.

### Create new VAT Business Posting Group

After **Unrealized VAT** check box is selected, the **VAT Business
Posting Groups** page opens.

![](.\/media/image50.png){width="6.531944444444444in"
height="2.109027777777778in"}

In the example below, the ZKasova group is created (the name is
user-selectable). In the column **Article 151**, the group for cash
payments must be checked.

![](.\/media/image51.png){width="6.531944444444444in"
height="1.6409722222222223in"}

### Set up VAT Business Posting Groups 

The Setup button is selected and a new combination is created.

![](.\/media/image52.png){width="5.243001968503937in"
height="1.3440879265091863in"}

In the column **Unrealized VAT Type**, the option **Percent** is filled
in. In the column **Purchase VAT Unrealized Account**, VAT account for
unrealized VAT is filled in.

The rest of the fields are filled in as in the case of standard charging
of VAT:

-   **VAT %** - 20;

-   **VAT Calculation Type** -- VAT;

-   **Transaction type** -- Purchase;

-   **Purchase VAT Refund Type** -- Full refund

-   **VAT Clause Code** - 00

![](.\/media/image53.png){width="6.531944444444444in"
height="1.1541666666666666in"}

Once the VAT combination is set up, the new VAT business posting group
must be entered in the card of Cash registered suppliers. Thus, for each
purchase, the invoice will automatically load this VAT Business Posting
Group and the system will identify the invoice and payments on it as
Cash.

### Change a VAT Group in invoices when paying in cash

When an invoice is entered for supply by a vendor registered under this
regime, and if it is a cash invoice, you need to consider it as a
regular invoice. For this purpose, in the invoice you need to change the
**VAT Business Posting Group** from the one indicated as VAT Cash Group,
to one that is standard for Bulgarian vendors.

The above change is made in the header of the Purchase Order / Purchase
Invoice in the **Invoice Details** section.

![](.\/media/image54.png){width="4.615438538932634in"
height="1.9130719597550305in"}

From the list of **VAT Business Posting Groups** the required group is
selected. After the group is changed, the program displays a warning
message in which you must select \"Yes\".

![](.\/media/image55.png){width="2.9625754593175855in"
height="1.206713692038495in"}

**Note**: It is advisable to change the **VAT Business Posting Group**
before you start populating the lines in the purchase order / invoice.
If an account has already been entered along the lines, the amount will
be deleted and you need to re-enter it. If an item has been entered and
a manual correction has been made to the price or discount in the line,
they must also be re-entered.

When posting a document, the system displays a warning message to
prevent accidental error when groups are changed. If it is a cash
payment, reply to the message with \"No\".

![](.\/media/image56.png){width="2.9745188101487314in"
height="1.0715627734033246in"}

### **Reflect payments for invoices under Cash Regime** 

When an invoice is posted under the Cash regime, the VAT on it is posted
to a separate account. When the Invoice is linked to the Payment, the
amount is automatically transferred from this account to the VAT
account. The date on which the transaction is posted is the date on
which the payment is linked. The invoice can be linked to the payment
before the Protocol for this payment has come. It is advisable that the
linking should be made in the payment and not in the invoice.

### Enter protocols for payment of invoices under Cash Regime 

The protocol is entered from the **Vendor Ledger Entries** (**Vendor
Card** - **Entries**). You must select the invoice for which a Protocol
has been received. After you mark the invoice, you need to select the
**Protocols input** option from the **Functions** button.

![](.\/media/image57.png){width="6.5256944444444445in"
height="2.7305555555555556in"}

All entries for payments of the respective invoice are displayed. In the
fields **Protocol Date** and **Protocol No**. the date and number of the
protocol must be entered. An invoice can be paid with several protocols.
The protocols entered so far to the selected invoice will also be
displayed in this screen.

![](.\/media/image58.png){width="6.531944444444444in"
height="1.5451388888888888in"}

After you enter the date and number, you must close the screen. The
protocol date must be within the month in which the entry was linked,
otherwise the system will display an error message. The entry for the
Protocol is reflected in the ledger in the month in which the entry is
linked (date of accounting for VAT). In case of discrepancy in the
months of linking and of protocol, you need to unlink the payment from
the invoice and link it again with a date of the month in which the
protocol was issued. The generation of the VAT ledgers and the VAT
Monthly declaration is done in the standard way.

## VAT Setup when carrying out activities under Art. 163

According to the Bulgarian legislation, special VAT reverse charge
schemes have been introduced when reflecting transactions involving
waste and cereals and industrial crops. Reverse charging is a specific
tax tool in which tax is charged by the recipient and not by the vendor.
The mechanism requires that the tax is chargeable to the recipient in
the transaction, who must be a VAT registered person, regardless of
whether the vendor is a VAT registered person or not. In connection with
these requirements in Dynamics 365 Business central, you need to make
the following settings.

### Create new VAT Product Posting Groups 

You need to create new **VAT Product Posting Groups**. Using the search
button we can find this page in the menu:

![](.\/media/image59.png){width="5.724412729658793in"
height="1.7373654855643044in"}

In the example below the groups VAT_GRAIN and WASTE are created.

![](.\/media/image60.png){width="6.5256944444444445in"
height="1.7305555555555556in"}

### Set up a combination of VAT groups in Sales

In **Posting Setup**, the following settings are made for the new
groups:

![](.\/media/image61.png){width="6.519444444444445in"
height="1.2305555555555556in"}

A combination of a **VAT Business Posting Group** of customers from
Bulgaria and the new **VAT Product Posting Groups** is selected. The
fields are filled in as follows:

-   **VAT calculation type --** VAT

-   **VAT % -** 0

-   **Sales VAT Account --** xxxxx

-   **Transaction Type --** Sales

-   **Specific Purchase Art.163a --** 01 or 02

-   **VAT Classification Code --** 00

A new column **Specific Purchase Art.163a** has been added. Code 01 is
entered against the combination for the sale of waste, and code 02 -
against the sale of cereals.

  -----------------------------------------------------------------------
  Code    Description
  ------- ---------------------------------------------------------------
  01      Supply under part I, appendix 2 of the VAT Act

  02      Supply under part II, appendix 2 of the VAT Act
  -----------------------------------------------------------------------

When selling items that are included in this group, you need to change
the **VAT Product Posting Group** in the item card. When you select
income G/L account in the lines of the sales document, it is good to
have an account with this kind of a **VAT Product Posting Group**. In
case you decide to use the same account for the sale of taxable and
non-taxable sales, then you need to change the **VAT Product Posting
Group** in the lines of the Sales Order / Sales Invoice.

### Set up a combination of VAT groups in purchases

In this case, the tax is charged by the recipients of the supplies by
issuing a protocol. The protocol may be common to all supplies for which
the tax has become chargeable in the relevant tax period, when the
suppliers are non-taxable physical persons. Invoices for reverse charge
supplies must specify as a ground for issue \"reverse charge under Art.
163a (2) of the VAT Act\".

Reverse charge is not applied to Intra-Community supplies and
acquisitions (supplies from and to Bulgarian persons with counterparties
from EU Member States), in the case of tripartite transactions, imports
and zero-rated supplies of goods outside the territory of the European
Union.

In the **VAT Posting Setup menu**, the following settings are made for
the new groups:

![](.\/media/image62.png){width="6.5in" height="1.25in"}

A combination of **VAT Business Posting Group** of suppliers from
Bulgaria and the new **VAT Product Posting Groups** is selected. The
fields are filled in as follows:

-   **VAT Business Posting Group --** Supplier from Bulgaria**;**

-   **VAT calculation type --** VAT**;**

-   **VAT % -** 0**;**

-   **Purchases VAT Account --** xxxxx**;**

-   **Transaction Type -- Purchases;**

-   **Document with header info only --** Yes**;**

-   **Specific Purchase Art.163a -** 01 or 02

-   **VAT Classification Code --** 00**;**

If posting of the supply is directly to a general ledger account, you
need to change the **VAT Product Posting Group** in the line of the
purchase document.

When you purchase an item that is set up as waste or cereals, the
document must be included in the VAT ledger without amount.

### Reverse charge protocol 

For reverse charge protocols, a new combination needs to be added that
includes a **VAT Product Posting Group**.

In the **VAT Posting Setup**, the following settings are made for the
new groups:

![](.\/media/image63.png){width="6.5256944444444445in"
height="1.2243055555555555in"}

A combination of **VAT Business Posting Group** for VAT protocols and
the new **VAT Product Posting Groups** is selected. The fields are
filled in as follows:

-   **VAT calculation type --** Full VAT**;**

-   **VAT % -** 20**;**

-   **Sales VAT Account --** xxxxx**;**

-   **Purchases VAT Account --** xxxxx**;**

-   **VAT Refund Account --** xxxxx**;**

-   **Transaction Type --** Total**;**

-   **Specific Purchase Art.163а --** 01 or 02**;**

-   **VAT Classification Code --** 02**;**

A new **\"Ground for Issue\"** of a reverse charge protocol is entered -
**\"VAT reverse charge Art.163a (2) of the VAT Act\"**, as well as a new
**\"Ground for Non-issue of VAT\"** - **\"VAT reverse charge Art.163a
(2) of the VAT Act"**.

**Note:** When posting a Protocol for waste or cereals, you need to
change the **VAT Product Posting Group** along the lines. If not
changed, the protocol will be displayed in the ledger without the
required details.

![](.\/media/image64.png){width="4.96159230096238in"
height="2.4171719160104987in"}

## Postpone tax credit within the permitted 12-month period

### Setup

In BG, VAT and VIES Setup, the Postponed VAT Account is replenished, as
well as a template and batch for a general journal:

![](.\/media/image65.png){width="5.283085083114611in"
height="3.5396555118110236in"}

### Postponed VAT before posting invoice

Enter the invoice and place a check mark in the Postponed VAT field in
the Invoice Details tab:

![](.\/media/image66.png){width="6.531944444444444in"
height="3.807638888888889in"}

If the Postponed VAT field is marked, a check mark is automatically
placed in the Do Not Include in VAT field.

If the check mark in the Postponed VAT field is removed, the check mark
in the Do Not Include in VAT field is also automatically removed.

When the invoice is posted, the tax credit will be reflected in the G/L
account in the Postponed VAT Account field in BG, VAT and VIES Setup. In
the VAT Entries filtered by the document number, there is a check mark
in the Postponed VAT field and Do Not Include in VAT Ledgers.

### Postponed VAT on a posted invoice

A purchase VAT ledger opens and the invoices that must enter the Journal
for the selected month are generated. After generation, the Postponed
VAT function can be started:

![](.\/media/image67.png){width="6.531944444444444in"
height="4.572916666666667in"}

After this action on a screen, the VAT journal lines are displayed and
by placing a check mark for the invoices to be included in the VAT
ledger of purchases in the next period:

![](.\/media/image68.png){width="6.531944444444444in"
height="2.0881944444444445in"}

When postponed VAT invoices are marked, the Approve Postpone VAT
function is selected. In this action, the following occurs:

-   For the selected invoices, an general ledger entry is made
    automatically, through which the amount of VAT on an invoice is
    transferred with an operation

    -   Debit account VAT purchases / Credit account Postponed VAT
        (minus sign)

-   Selected invoices are removed from the purchase journal

-   Place a check mark automatically in the postponed VAT and Do Not
    Include in VAT Ledger field on VAT Entries and the posted purchase
    invoice.

### Use of postponed tax credit

To include a purchase invoice whose VAT has been postponed with the
function described above, you must start the Change VAT Period page by
selecting Change VAT Period from the Search button:

![](.\/media/image69.png){width="4.299818460192476in"
height="2.1255971128608926in"}

A list of documents marked with Postponed VAT that are not yet included
in the VAT Ledgers is displayed on the screen.

![](.\/media/image70.png){width="6.531944444444444in"
height="1.8243055555555556in"}

By placing a check mark in the Change VAT Period field (first column),
select the documents to include in a selected VAT period. The selection
is confirmed by the Change VAT Period function in the ribbon above. The
following window appears on the screen:

![](.\/media/image71.png){width="6.531944444444444in"
height="3.966666666666667in"}

The first day of the month in which the marked invoice is to be included
should be indicated here.

The system includes the invoice in the relevant month and creates
entries for the transfer of the VAT amount from the Postponed VAT
account to the VAT account for the purchases. These automatically
generated records can be found in the journal and folder selected in the
setting from item 2.8.1. After reviewing the suggested entries, you can
post them by selecting the Post button from the relevant journal.

When creating/refreshing the VAT ledger, the selected invoice will be
displayed in the relevant ledger.

# Intrastat

Intrastat is the system for collecting information on Intra-Community
dispatches and / or arrivals of goods made between the Republic of
Bulgaria and the EU Member States. Companies obliged to submit Intrastat
declarations, namely, Intrastat operators, are those companies
registered under the Value Added Tax Act, who carry out Intra-European
Union trade with goods in annual volumes of  a value above the
declaration thresholds. Intrastat operators are obliged to submit a
monthly Intrastat declaration.

Below are some standard features of the system, as well as additions to
the Localization package for Bulgaria, which help with Intrastat
reporting.

## Intrastat Setup

The data required for Intrastat declarations are reduced to the fields
below. Some of the data can be set in advance and filled in by default
in the documents.

  

Example:

  ------------------------------------------------------------------------------------------------------------------------------------
  Country/Region   Country/Region   Transaction   Transport   Shpt.    Area   Transport        Quantity   Net      Amount   Tariff No.
  Code             of Origin Code   Type          Method      Method          Country/Region              Weight            
                                                              Code            Code                                          
  ---------------- ---------------- ------------- ----------- -------- ------ ---------------- ---------- -------- -------- ----------
                                                                                                                            

  DE               DE               11            3           CPT      VAR    DE               3          10       250      90184990
  ------------------------------------------------------------------------------------------------------------------------------------

### General Setup

The following fields are entered in advance in the **Vendor card**:

-   **Country/Region code**

-   **Shipment Method Code**

-   **Transaction Type**

-   **Transport Method**

![](.\/media/image72.png){width="6.531944444444444in"
height="3.40625in"}

They are transferred to the purchase order if they have been entered for
the respective vendor selected in the order.

In the **Item** card, the following fields are filled in:

-   **Country/Region of Origin Code**

-   **Net Weight**

-   **Tariff No.**

![](.\/media/image73.png){width="6.531944444444444in" height="3.325in"}

In the **Purchase Order**, the following fields are filled in:

-   **Area** -- for arrivals, this is a region (district) in Bulgaria

-   **Transport Country/Region Code -** Nationality of the means of
    transport (You must specify the 2-character alphabetical  codе of
    the country whose carrier is used to transport the goods. The
    specified code may be that of any of the countries in the
    Geonomenclature.)

It is advisable that these fields be filled in the purchase order before
its posting. The data can be found in the **Foreign Trade** tab of the
Purchase Order.

 

![](.\/media/image74.png){width="6.531944444444444in"
height="4.229861111111111in"}

 

In the **VAT Reports Configuration** page, you need to set the relevant
settings once.

![](.\/media/image75.png){width="6.531944444444444in"
height="1.0638888888888889in"}

-   **VAT Report Type** -- Intrastat Report

-   **VAT Report Version** -- 2020

-   **Suggest Lines Codeunit ID** -- 46026517 or 60013 (FTS Get
    Intrastat Entries) or 46026525 (FBG Intrastat Report Get Lines)

-   **Content Codeunit ID** -- 46026519 or 60015 (FTS Export Intrastat
    XML) or 46026530 (FBG Intrastat Content)

-   **Validate Codeunit ID --** 46026518 or 60014 (FTS Check Intrastat
    Error) or 46026529 (FBG Intrastat Validate)

In the **Intrastat Report Setup** page, the following settings are set:

![](.\/media/image76.png){width="6.531944444444444in"
height="3.2597222222222224in"}

-   **Report Receipts** -- to be checked if needed to generate a
    declaration for receipts only

-   **Report Shipments** -- to be checked if needed to generate a
    declaration for shipments only

-   **Default Transport Type --** specify the default transaction type
    for shipping notes and purchase receipts (11 Standard Purchase /
    Sale)

-   **Default Transport Type -- Returns --** specify the default
    transaction type for the return of shipping notes and purchase
    receipts (11 Standard Purchase / Sale)

-   **No Item Charges in Intrastat --** if checked, the system does not
    allow the additional cost to be included in the amounts for
    Intrastat transactions

-   **Default Country / Region code** - specify the default receiving
    country code. The field is populated by default with the value of
    the **Shipping Country/Region Code** field from **Company
    Information**

The system has built-in checks for filling in the Intrastat required
fields when posting an EU document and the document includes an item. In
the Intrastat declaration the data for the Tariff No. and Net Weight is
taken from the Item Card, and the Country of Origin - from the Purchase
Receipt and the Sales Shipment.

The Item Country of Origin is transferred to these documents from the
Item Card, but it can be changed in them. If not entered in the Receipt
or Shipment documents, the country code will not enter the ledger
either.

### Checkmark countries, subject to Intrastat declarations 

When filling in an Intrastat declaration, a nomenclature of countries
and territories is used, or the so called Geonomenclature, according to
Commission Implementing Regulation (EU) 2020/1197.

In Dynamics 365 Business central in the page **Countries/Regions**
against each country you must fill in the corresponding code for
Intrastat.

![](.\/media/image77.png){width="6.531944444444444in"
height="1.3972222222222221in"}

Subject to Intrastat declaration are the entries for items that are
delivered / sold to counterparties of a country with an Intrastat code
in the table of countries (regardless of the country of origin of the
items).

### Intrastat nomenclatures

In Finance - Setup - Intrastat, there are all specific nomenclatures
that are used in generating an Intrastat declaration. Because they are
part of the standard Dynamics 365 Business Central package, completing
and setting them up is not covered in this documentation.

These nomenclatures can also be found by typing part of the name in the
Search field on the main menu.

![](.\/media/image78.png){width="5.270562117235346in"
height="4.179019028871391in"}

### Setup of Item charges included in the amounts of Intrastat declaration

The Localization package for Bulgaria allows you to set the item charge
as part of the value in the Intrastat declaration.

On the Item Charge page, the following columns should be marked:

![](.\/media/image79.png){width="5.807191601049869in"
height="2.536247812773403in"}

-   **Include in Intrastat amount** -- must be checked if we want the
    item charge to be included in the column Amount

-   **Include in Intrastat statistic value** -- must be checked if we
    want the item charge to be included in column Statistical value

On the **Shipment Methods** page, check this method, for which the cost
of transport is included in the amount for Intrastat.

![](.\/media/image80.png){width="6.531944444444444in"
height="1.9291666666666667in"}

In Purchases & payables setup the field **Intrastat Journal incl. Item
charge**, must be marked if we want the item charge to be added to the
amount for Intrastat.

![](.\/media/image81.png){width="6.531944444444444in"
height="3.2368055555555557in"}

### Settings for creating the Intrastat declaration

In **BG, VAT and VIES Setup,** a new **Intrastat** section has been
created, where it is necessary to fill in the data of the Contact Person
responsible for Declaration submitting. In general, the Contact person
data must be identical to the data of the person on whose behalf the
declaration is submitted to the NRA e-services portal.

![](.\/media/image82.png){width="3.245148731408574in"
height="3.4355938320209973in"}

## Creating a new Intrastat declaration

A new Intrastat declaration is created from the **Intrastat Report
List** page.

![](.\/media/image83.png){width="6.5in"
height="1.4926640419947506in"}

In the list of created declarations, select the **+New** action.

![](.\/media/image84.png){width="6.531944444444444in"
height="1.3972222222222221in"}

In the **General** section of the header of the declaration, the
following fields are filled in:

• **Description** -- name of the declaration

• **Statistical Period** -- is entered by first writing the last two
digits of the year and then the month for which the declaration will be
submitted. Example of Statistical period: 2501 - January 2025

• **Declaration Type** -- must be selected Original

• **Subsequent Declaration No**. -- 1.

![](.\/media/image85.png){width="6.531944444444444in"
height="4.311805555555556in"}

After the declaration is created, the **Suggest Lines** action is
selected. The system generates lines with items. These are the entries
marked as \"Intrastat transaction\" and for which the Country / Region
Code field contains codes indicated as Intrastat Code in the country
table, regardless of the country of origin of the item.

![](.\/media/image86.png){width="6.5in"
height="2.053472222222222in"}

It is necessary to check for missing data. If there are any, they can be
filled in manually in the journal. The other option is to fill them in
the relevant cards (items, vendors, etc.), and then run the Suggest Line
action again. It is recommended for the items to be filled in with net
weights and tariff numbers (in their cards) in advance. Without these
fields, the declaration will not be submitted correctly.

In the table Item Ledger Entries there are some additional fields
related to Intrastat transactions such as - tariff number, customs
declaration, net weight, country of origin, country of transport, method
of transport, etc. They can be used for additional reporting.

It is advisable to check the value of the declaration as well. The
following check is possible: In Item Ledger entries items to be filtered
by the respective posting period, Record type (Purchase) and by Country
/ region code (\<\> '' & \<\> BG). The column Cost amount (actual) is
compared with the value of the declaration - Statistical value.

The amount in Cost amount (actual) includes transport costs, if such are
allocated as item charges in purchase orders.

## Creating files for Intrastat declaration

After the data in the declaration lines have been verified, they are
exported using the **Create file** action.

Localization allows both creating a file with a ready Intrastat
declaration and creating only transaction files that can be loaded into
the Intrastat program and from there the declaration can be submitted.
In this case, the **Export transactions only** option is used.

If the declarations must include a statistical value, the **Export
Statistical Value** option is also marked.

![](.\/media/image87.png){width="6.531944444444444in"
height="2.564583333333333in"}

When selecting the **Create File** action, you can choose which of the
files to generate - for import (receipts) or for export (sends), as well
as create both at the same time.

![](.\/media/image88.png){width="6.531944444444444in"
height="2.729861111111111in"}

The generated files can be found in the Downloads folder on your
computer.

#  Finances -- localization settings

The Localization package for Bulgaria supports additional
functionalities that upgrade the main Finance module in Dynamics 365
Business Central.

## Automatic Create Default Dimensions

Every time you create a new customer or vendor, the automatic creation
of dimension helps to enter the value of dimensions.

To set up this you need:

-   to search in the **General Ledger Setup** menu

-   to complete in **Create Default Dimensions** section:

    -   **Table Customer** - in the Dimension field select Dimension for
        Customer (it must be created in advance).

    -   **Table Vendor** in the Dimension field select Dimension for
        Vendor (it must be created in advance).

![](.\/media/image89.png){width="6.5in" height="2.25in"}

When you create a new customer or vendor card, the system automatically
generates value in dimensions with the code and name of that customer or
vendor. When you change the name in customer / vendor card, it also
changes in the dimensions.

When you create a new customer or vendor, the system automatically adds
the created dimension to their cards. When the customer or vendor is
used in transactions, dimension is copied along the lines. This allows
the generation of detailed reports and Analysis by dimensions.

## General Journal 

The following fields have been added to the General Journal:

-   SAD No. -- related to the option to post customs declarations;

-   **VAT Subject** -- the description of the transaction (good or
    service) is filled in which is reflected in the **VAT Purch. Ledger
    List** in the column **VAT description**. If left blank, it will be
    filled in with the value of **VAT description of purchases** field
    from page **BG, VAT and VIES setup**

![](.\/media/image90.png){width="6.525in" height="2.033333333333333in"}

## Trial Balance Register 

The Trial Balance Register report is a further developed report, which
serves to present the data on accounts in a way that makes it easy to
track the opening balance, the turnover for the respective period (debit
and credit) and the closing balance.

You can start the report from the main screen of the Accountant Role
Center:

![](.\/media/image91.png){width="6.531944444444444in"
height="1.7944444444444445in"}

or by searching the menu:

![](.\/media/image92.png){width="6.531944444444444in"
height="2.1659722222222224in"}

When the report is started, select the following options:

![](.\/media/image93.png){width="4.583333333333333in"
height="4.753311461067367in"}

-   **From Date** -- start date of the period

-   **To Date** -- end date of the period

-   **Include Closing** -- if you want to include records after closing
    of accounts

-   **Type** -- Synthetic or Analytic. The Synthetic Trial Balance shows
    the accounts of the Total type, when similar accounts have been set
    up in the Chart of accounts. For example, if several accounts from
    group 602 have been entered and account 60290 has been created as a
    totaling account, which is specified as of Total type, and the
    Indent function was used for the summation (begin-total --
    end-total), then only account 60290 will be displayed in the report.
    Account 60290 will not be displayed in the Analytic Trial Balance,
    but all accounts included in the summation.

-   **Additional Currency** -- specified when an additional reporting
    currency is used

-   **For export (no lines)** -- lines are not printed in the report

> Additionally, selected accounts can be specified in the **Filter:
> Account** section.
>
> Upon confirmation by pressing the View button, the report is displayed
> on the screen:

![](.\/media/image94.png){width="4.9in"
height="4.483333333333333in"}

## Fixed assets

In addition to the reports in the Fixed Asset module, the Localization
package for Bulgaria also provides reports developed for tax and
accounting depreciation plans.

The **Changes in Fixed Asset** report contains all the information
needed for Tax depreciation plan and Accounting depreciation plan. It is
found in the main screen of the Accountant Role Center:

![](.\/media/image95.png){width="6.531944444444444in"
height="1.7777777777777777in"}

or by searching the menu:

![](.\/media/image96.png){width="4.521835083114611in"
height="1.5534787839020123in"}

The following options in the report must be filled in:

![](.\/media/image97.png){width="3.6128226159230095in"
height="3.78040135608049in"}

-   **Depreciation book** -- Depreciation book is selected -- accounting
    or tax;

-   **Start Date** -- start date of the period;

-   **End Date** -- end date of the period;

-   **Group grand total** -- one of the totaling options must be
    specified - by FA class, FA subclass, FA location or global
    dimensions;

-   **With details for FA** - if you do not check this option, only the
    totaling rows under the above-mentioned option **Group grand total**
    will be displayed. When checked, rows will be displayed for each
    fixed asset and grand total under the Group grand total option.

In the tabs **Filter: FA Posting groups** and **Filter: Fixed asset**,
filters for certain fixed assets or their groups can be specified.

**Note:** Due to the fact that you cannot fit all columns on one page
for printing, it is advisable to export the report to Excel where all
required columns are visible.

![](.\/media/image98.emf){width="6.531944444444444in"
height="1.7201388888888889in"}

## Changes in posting with Deferral Templates 

In Deferral Templates two new fields were added:

![](.\/media/image99.png){width="6.531944444444444in"
height="3.6277777777777778in"}

-   **Use Account For Change** -- If there is no mark in the field, the
    deferral process will be standard. If there is a mark in the field,
    deferral process will use the GL account from the following field.

-   **Account for change** -- field should be filled with the account
    which deferral uses when posting the invoice transaction. Those
    transaction are explained in details below.

***[EXAMPLES in PURCHASES]{.underline}***

The standard deferral process expects the expense account to be inserted
in the purchase line. The same account will be used for deferral the
expense in the certain schedule. In the deferral template we include the
account for Future expenses. Transactions are as follows:

-   Debit account Expenses account (starting with 60\* in BG chart of
    account) / Credit account for vendors with the amount of 100
    (posted with the Posting date)

-   Debit account for Deferral expense (65\* for BG chart of account) /
    Credit account for expenses account (starting with 60\* in BG
    chart of account) with the amount of 100 (posted with the Posting
    date)

-   Debit Expenses account (starting with 60\* in BG chart of account) /
    Credit Deferral account (65\* for BG chart of account) posted with
    the dates from the schedule

The change, related to this development, is as follows:

-   Debit Account for change (the new field in Deferral Template) /
    Credit Vendor accountwith the amount of 100 (posted with the
    Posting date)

-   Debit Deferral Account from the Deferral Template (65\* for BG chart
    of account) / Credit Account for change (the new field in Deferral
    Template) with the amount of 100 (posted with the Posting date of
    the invoice)

-   Debit Expenses account (starting with 60\* in BG chart of account) /
    Credit Deferral account from the Deferral Template (65\* for BG
    chart of account) with the dates from the Deferral schedule.

When posting the invoice transaction, system uses the Account for change
from the Deferral Template, but the actual deferral of the expense will
use the exact Expenses account from the purchase lines and the Deferral
account from the template.

***[EXAMPLE in SALES]{.underline}***

The standard deferral process expects the income account to be inserted
in the sales line. The same account will be used for deferral the income
in the certain schedule. In the deferral template we include the account
for Deferral (future) income. Transactions are as follows:

-   Debit Customers account / Credit Income account (703 in BG chart of
    account) with the amount of 100 (posted with the Posting date of
    invoice)

<!-- -->

-   Debit income account (703 in BG Chart of account) / Credit Deferral
    account (75\* in BG Chart of account) with the amount of 100
    (posted with the Posting date of the invoice)

-   Debit Deferral account (75\* in BG Chart of account) / Credit income
    account (703 in BG Chart of account) with the dates from the
    Deferral Schedule

The change, related to this development, is as follows:

-   Debit Customer account / Credit Account for change with the amount
    of 100 (posted with the Posting date of invoice)

-   Debit Account for change / Credit Deferral account (75\* from BG
    Chart of account) with the amount of 100 (posted with the Posting
    date of invoice)

-   Debit Deferral account / Credit Income account from the lines with
    the dates from the Deferral schedule

When posting the invoice transaction, system uses the Account for change
from the Deferral Template, but the actual deferral of the income will
use the exact Income account from the sales lines and the Deferral
account from the template.

# Purchases -- localization settings

The localization package for Bulgaria has some additional settings in
the Purchasing module.

## Purchases & Payables Setup

In the **Purchase & Payables Setup** there are some additional fields
related to VAT protocols for purchases and Intrastat and also a setting
for mandatory payment method code.

![](.\/media/image100.png){width="6.121825240594926in"
height="2.446621828521435in"}

-   **EU VAT Bus. posting group** -- VAT business posting group linked
    to VAT protocols is filled in;

-   **Intr. Jnl. Incl. Item charges** -- it has to be checked if you
    want to include the additional charges in the Intrastat declaration

-   **Payment Metod mandatory** - specifies whether the Payment Method
    Code is mandatory for posting.

## Vendor card

In the Vendor card there have been added some fields related to
Intrastat transactions (Transport method, Transaction specification,
etc.). When filling in these fields in the vendor card and upon
selecting the vendor in the purchase document, they are transferred by
default. For more details see the Intrastat section in the present
document.

![](.\/media/image101.png){width="6.525in"
height="4.5in"}

## Purchase invoice

The localization fields are displayed in the Purchase order and Purchase
invoice as follows:

**General tab**

-   **VAT Date** -- the date of the taxable event is filled in

![](.\/media/image102.png){width="5.991666666666666in"
height="2.4581200787401576in"}

**Invoice Details tab**

-   **Identification No.** -- Vendor's BULSTAT or Personal ID;

-   **VAT Subject** -- the description of the transaction (good or
    service) is filled in which is reflected in the **VAT Purch. Ledger
    List** in the column **VAT description**. If left blank, it will be
    filled in with the value of **VAT description of purchases** field
    from page **BG, VAT and VIES setup**;

-   **Debit Memo**-- to be checked if the document is for increasing the
    amount or quantity of an invoice;

-   **To Invoice No.** -- select the invoice from a list of posted
    purchase invoices or enter manually the number of the invoice to
    which the debit memo is issued;

-   **To Invoice Date --** filled in automatically if the invoice is
    selected from a list of posted purchase invoices or filled in
    manually if the number of the invoice was entered manually**;**

-   **Do Not include in VAT ledger** -- to be checked if the invoice
    should not be reflected in the VAT ledger;

-   **VAT Exempt Ground**-- select the ground on the basis of which VAT
    is not charged in the invoice

> ![](.\/media/image103.png){width="6.4375in"
> height="4.854166666666667in"}

**Foreign Trade tab**

In this tab you must fill in data for the Intrastat transactions if the
document is a purchase from the EU and contains items. The system
displays warning messages if data is not present.

**Note:** In **Company information** in the **Shipping** tab - **Ship-to
Country/Region Code** field must be filled in with the BG code. If BG
code is not present there, when posting invoices from Bulgaria the
system requires that the fields in the **Foreign Trade** tab must be
filled in.

![](.\/media/image104.png){width="6.531944444444444in"
height="1.8659722222222221in"}

## Purchase credit memos

In the Purchase credit memo and Purchase return order pages there have
been added a few fields related to localization.

**General tab**

-   **VAT Date** -- the date of the taxable event is filled in

![](.\/media/image105.png){width="6.525in"
height="2.75in"}

**Invoice Details tab**

-   **Identification No.** -- vendor BULSTAT or Personal ID

-   **VAT Subject** -- the description of the transaction (good or
    service) is filled in which is reflected in the **VAT Purch. Ledger
    List** in the column **VAT description**. If left blank, it will be
    filled in with the value of **VAT description of purchases** field
    from page **BG, VAT and VIES setup;**

-   **Do Not include in VAT ledger** -- to be checked if the invoice
    should not be reflected in the VAT journal;

-   **VAT Exempt Ground** -- select the ground on the basis of which VAT
    is not charged in the invoice

![](.\/media/image106.emf){width="6.531944444444444in"
height="2.229861111111111in"}

**Application tab**

-   **To Invoice No.** -- select the invoice from a list of posted
    purchase invoices or enter manually the number of the invoice to
    which the credit memo is issued;

-   **To Invoice Date --** filled in automatically if the invoice is
    selected from a list of posted purchase invoices or filled in
    manually if the number of the invoice was entered manually**.**

![](.\/media/image107.png){width="6.5in"
height="1.4166666666666667in"}

## Void posted invoices and credit memos 

If you need to void a document, you must open the posted purchase
document. Under the **Actions -- Correct** menu you have to select
**Voiding Invoice**.

![](.\/media/image108.png){width="6.531944444444444in"
height="3.6326388888888888in"}

The system displays a page where you must enter the **Cancellation
date**. Confirm by pressing the **Close** button.

![](.\/media/image109.png){width="6.525in"
height="2.933333333333333in"}

The system displays the following message:

![](.\/media/image110.png){width="5.091666666666667in"
height="1.825in"}

Upon pressing the **Yes** button, the document is marked as voided by
the system. It will appear in the VAT ledger with zero value. To reverse
the G/L postings, you must issue a Credit memo or Invoice which you must
also void.

## Change data in posted purchase documents

It is possible to change data in a posted purchase invoice and in a
posted purchase credit memo.

The change is made from the posted document page

### Update a posted purchase invoice

If you need to update a document, you must open the posted purchase
invoice. Under the **Actions -- Other** menu you have to select **Update
Document**.

![](.\/media/image111.png){width="6.215738188976378in"
height="2.5096391076115485in"}

On the Posted Purch. Invoice - Update page, you can update the data in
the following fields:

Invoice Details tab

• Payment Reference -- you can update the Payment Reference field in the
posted invoice

• Payment Method Code -- you can update the Payment Method Code field

• Creditor No. -- you can update the field Creditor No.

• Vendor Invoice №. -- you can update the invoice number in the posted
invoice

• Document date -- you can update Document Date in the posted invoice

• Do not include in VAT Ledgers - you can update the field Do not
include in VAT Ledgers

• SAD No.

Shipping tab

• Ship-to address code -- you can update the shipping address code

![](.\/media/image112.png){width="6.188976377952756in"
height="2.6644608486439196in"}

Confirm with **OK** to update the data.

### Update a posted purchase credit memo

If you need to update a document, you must open the posted purchase
credit memo. Under the **Actions -- Other** menu you have to select
**Update Document**.

![](.\/media/image113.png){width="6.254448818897638in"
height="2.1739807524059493in"}

In the page Posted Purch. Cr.Memo - Update the data in the following
fields can be updated:

• Payment method code -- you can update the Payment Method Code field

• Vendor Cr.Memo No -- you can update Vendor Cr.Memo No

• Document date -- you can update Document Date

• Do not include in VAT Ledgers - you can update Do not include in VAT
Ledgers

![](.\/media/image114.png){width="6.402899168853893in"
height="2.710022965879265in"}

Confirm with **OK** to update the data.

## Void a purchase invoice in next tax period

When a vendor void an invoice that has been posted and data was exported
in files for submission to the tax administration , the cancellation
must be reflected in a next tax period.

It is necessary to issue a new Purchase Credit Memo. Enter the number of
the posted invoice that has been canceled in Vendor Cr. Memo No and
check the \"Credit Memo for Invoice Voiding\".

In this way, the posted credit memo will be reflected in the VAT ledger
entries with code 01.

![](.\/media/image115.png){width="6.008562992125984in"
height="2.386971784776903in"}

# Sales -- localization settings

The Localization package for Bulgaria adds the following settings in the
Sales and Marketing module.

## User setup

![](.\/media/image116.png){width="6.531944444444444in"
height="1.2270833333333333in"}

In the **User setup** **-- Card** **Usersetup** page there is an
additional field called **Posting date** **\<\>** **Work date**. If this
field is checked, the system will not check for differences between the
posting date and work date when an order or a sales invoice is posted.

The **Edit Sales document\`s price and discounts** field allows you to
restrict a user from editing prices and discounts along the lines of the
sales document. By default, users are created with their edit rights
disabled. In this case, they can only select Item along the lines of the
sales document. If users need to have edit rights, you must select the
option **Full Access**.

![](.\/media/image117.png){width="6.531944444444444in"
height="1.3166666666666667in"}

## Sales & Receivables Setup

The following fields have been added to the page **Sales & Receivables
Setup:**

**Number series** tab

-   **Sales Protocol Nos.** - number series for the Sales protocol
    before posting

-   **Posted Sales Protocol Nos.** - number series for the Sales
    protocol after posting

They are included in the VAT Sales journal under code 81.

**Specific Settings** tab

-   **Intr. Jnl. Incl. Item charges**. - If item charges need to be
    included in the Intrastat journal for shipments, you must check this
    option

-   **Payment Metod mandatory** - specifies whether the Payment Method
    Code is mandatory for posting.

![](.\/media/image118.png){width="6.205791776027996in"
height="2.9949136045494313in"}

## Company information setup

The following fields have been added to the page **Company
Information**:

-   **Identification No. -** the unique identification number (UIC) of
    the company

-   **Name in English --** the name of the company, written in Latin
    symbols. Used when printing documents.

-   **Address in English** - the address of the company -- street and
    number, written in Latin symbols. Used when printing documents.

-   **City in English** - the city from the address of the company,
    written in Latin symbols. Used when printing documents.

-   **Picture 2 -** option for second picture, logo when printing
    documents

![](.\/media/image119.png){width="6.531944444444444in"
height="2.8333333333333335in"}

## Contact card

The **Identification No.** field has been added to the contact card.
When creating a customer or vendor from a contact, this field is
transferred to the corresponding customer or vendor card.

![](.\/media/image120.png){width="6.531944444444444in"
height="3.325in"}

## Customer card

The following fields have been added to the page **Customer Card**:

**Invoicing** tab

-   **Identification No. -** the unique identification number (UIC) of
    the company

![](.\/media/image121.png){width="5.4145756780402445in"
height="3.3531681977252843in"}

**Sell-to Customer Sales History** tab

-   **Advance Paid (LCY) -** shows the amount of the advance paid by the
    customer

![](.\/media/image122.png){width="6.531944444444444in"
height="2.8625in"}

Functionality for advance payment by customer has been added.

When under an advance account set in the **General posting setup** an
amount is posted for the given **General business posting group**, it is
displayed in the customer card and also in the **Sales history** tab in
**Sales order** and **Sales invoice**. The advance payment is visible in
the Sales document too.

![](.\/media/image123.png){width="6.5in"
height="2.9166666666666665in"}

**Shipping tab**

Some fields related to Intrastat have been added, which are transferred
to the sales documents once the customer is selected. The fields are
following:

-   **Transaction Type**

-   **Transaction Specification**

-   **Transport Method**

![](.\/media/image124.png){width="6.531944444444444in"
height="4.429861111111111in"}

## Sales invoice

The localization fields are displayed in the Sales order and Sales
invoice as follows:

**General tab**

-   **VAT Date** -- by default, it is populated with the posting date,
    but it can be changed by the user;

-   **Sales Location** -- populated with value from Company information,
    but it can be changed manually;

-   **Composed By** -- filled in manually by the user name;

-   **Advance Paid (LCY)** -- if there is an advance payment by a
    customer, it will be displayed on the FactBox of the page.

![](.\/media/image125.png){width="6.531944444444444in"
height="2.5375in"}

**Invoice Details tab**

-   **Bank No.** -- by default, the bank account details frоm **Company
    information** are displayed on the printed sales document. If you
    want to specify another bank account for a sale, you must select in
    this field the Bank from the Bank Accounts list;

-   **VAT Subject** - the description of the transaction (good or
    service) is filled in which is reflected in the **VAT Sales Ledger**
    in the column **VAT description**. If left blank, it will be
    populated with the value of **VAT description of sales** field from
    page **BG, VAT and VIES setup;**

-   **Debit Memo** -- to be checked if the document is for increasing
    the amount of the invoice;

-   **To Invoice No.** -- select the invoice from a list of posted sales
    invoices or enter manually the number of the invoice to which the
    debit memo is issued;

-   **To Invoice date --** automatically populated if the invoice is
    selected from a list of posted sales invoices or manually filled in
    if the number of the invoice was entered manually**;**

-   **Do not include in VAT ledgers** -- to be checked if the document
    is for internal consumption;

-   **VAT Exempt Ground**-- select the ground on the basis of which VAT
    is not charged in the invoice. Used for tax-exempt transactions.

![](.\/media/image126.png){width="6.531944444444444in"
height="4.536111111111111in"}

**Foreign Trade tab**

In this tab you must fill in data for the Intrastat transactions if the
document is a sale to the EU and contains items. The system displays
warning messages if data is not present. This data can be specified in
the **Customer card** and populated by default in the sales invoice.

![](.\/media/image127.png){width="6.525in"
height="1.7416666666666667in"}

**Note:** In **Company information** in the **Shipping** tab **- Ship-to
Country/Region Code** field must be filled in with the BG code. If BG
code is not present there, when posting invoices from Bulgaria the
system requires that the fields in the **Foreign Trade** tab are filled
in.

## Sales credit memos 

The localization fields are displayed in the Sales return order and
Sales credit memo and are positioned as follows:

**General tab**

-   **VAT Date** -- by default, it is populated with the posting date,
    but it can be changed by the user;

-   **Sales Location** -- populated with value from Company information,
    but it can be changed manually;

-   **Composed By** -- filled in manually by the user;

-   **To Invoice No.** -- select the invoice from a list of posted sales
    invoices or enter manually the number of the invoice to which the
    credit memo is issued;

-   **To Invoice date --** automatically populated if the invoice is
    selected from a list of posted sales invoices or manually filled in
    if the number of the invoice was entered manually**;**

![](.\/media/image128.png){width="6.531944444444444in"
height="3.392361111111111in"}

**Credit memo details tab**

-   **Bank No.** -- by default, the bank account details frоm **Company
    information** are displayed on the printed sales document. If you
    want to specify another bank account for a sale, you must select in
    this field the Cash from the cash list;

-   **VAT Subject** - the description of the transaction (good or
    service) is filled in which is reflected in the **Sales journal** in
    the column **VAT description**. If left blank, it will be populated
    with the value of the **VAT description of sales** field on page
    **BG, VAT and VIES setup;**

-   **Do not include in VAT ledgers** -- to be checked if the document
    must not be included in the VAT Sales ledger;

-   **VAT Exempt Ground** -- select the ground on the basis of which VAT
    is not charged in the invoice. Used for tax-exempt transactions.

![](.\/media/image129.png){width="6.531944444444444in"
height="4.429166666666666in"}

**Foreign trade tab**

In this tab you must fill in data for the Intrastat transactions if the
document is a sale to the EU and contains items. The system displays
warning messages if data is not present. This data can be specified in
the **Customer card** and populated by default in the sales credit memo.

![](.\/media/image130.png){width="6.5in"
height="1.5in"}

## Print Sales invoices and credit memos

The following setup is required before printing an invoice or credit
memo. In the **Report Selection - Sales** page select the option
**Invoice** (as shown below) and the object responsible for the invoice
-- XXXXX (Sales -- Invoice). By selecting the option Credit memo, fill
in the object XXXXX (Credit memo) in the **Report ID** field.

![](.\/media/image131.png){width="6.525in"
height="2.283333333333333in"}

The invoice or credit memo are printed by pressing the **Print** button
in the list of posted invoices or credit memos.

![](.\/media/image132.png){width="6.531944444444444in"
height="1.4166666666666667in"}

A page opens with the following options:

![](.\/media/image133.png){width="6.531944444444444in"
height="3.8979166666666667in"}

-   **Language** -- you must select the language in which the document
    will be printed -- for English select ENU;

-   **No. of Copies** -- specify the number of copies to be printed in
    addition to the original document;

-   **Log Integration** -- the printing of the invoice can be registered
    as interaction in the CRM module of the system;

-   **Show line discount -- Always** (the Discount column is always
    printed in the document), **Never** (the Discount column is not
    printed in the document) and **Auto** (If there is a discount, it
    will appear as a column, if there isn't -- the column will not be
    printed);

-   **Currency** -- the options are -- **Invoice Amount** (amounts are
    displayed in the original currency of the document) and **LCY** (the
    amounts are displayed in the local currency, BGN);

After selecting **Preview**, **Print** or **Send** **to...**, the
invoice and credit memo are visualized in the following way:

![](.\/media/image134.png){width="6.531944444444444in"
height="5.8805555555555555in"}

![](.\/media/image135.png){width="6.531944444444444in"
height="5.904166666666667in"}

In the table below you can find information about the fields in the
documents and their source fields for printing in Bulgarian and in
English:

  -----------------------------------------------------------------------
  **Document        **Source (Bulgarian)**     **Source (English)**
  field**                                      
  ----------------- -------------------------- --------------------------
  Customer -- name  Invoice -- Bill-to         Invoice -- Bill-to
                    Customer -- Name field     Customer -- Name field

  Customer -        Invoice -- Bill-to         Invoice -- Bill-to
  address           Customer -- Address field  Customer -- Address field
                                               (if entered in Bulgarian,
                                               the system will
                                               automatically translate it
                                               in English)

  Customer - city   Invoice -- Bill-to         Invoice -- Bill-to
                    Customer -- City field     Customer -- City field (if
                    (entered in Bulgarian in   entered in Bulgarian, the
                    the nomenclature)          system will automatically
                                               translate it in English)

  Customer -        Invoice -- Bill-to         Invoice -- Bill-to
  country           Customer -- Country code   Customer -- Country code
                    field                      field (Names of countries
                                               are provided in English in
                                               the startup configuration
                                               package)

  Customer -- Tax   Invoice -- Bill-to         Invoice -- Bill-to
  ID No.            Customer -- VAT            Customer -- VAT
                    Registration No. field     Registration No. field

  Customer -- ID    Invoice -- Bill-to         Invoice -- Bill-to
  No.               Customer -- Identification Customer -- Identification
                    No. field                  No. field

  Customer --       Customer -- Address &      Customer -- Address &
  Responsibility    Contact -- Contact Name    Contact -- Contact Name
  person                                       

  Vendor -- Logo,   In the Company information In the Company information
  Name, Address,    page -- General tab        page -- General tab
  City, Country, ID                            
  No., Tax ID No.                              

  Vendor -- Bank,   In the Company information In the Company information
  IBAN, Swift code  page -- Payments tab       page -- Payments tab

  Invoice No.       Invoice -- General - No.   Invoice -- General - No.
                    field                      field

  Date              Invoice -- General --      Invoice -- General --
                    Document date field        Document date field

  Due date          Invoice -- General - Due   Invoice -- General -- Due
                    date field                 date field

  №                 Invoice - Lines -- Line    Invoice - Lines -- Line
                    No.                        No.

  Art. No.          Invoice - Lines -- Item    Invoice - Lines -- Item
                    No. field, G/L account,    No. field, G/L account,
                    fixed asset                fixed asset

  Description       Invoice -- Lines --        Invoice - Lines --
                    Description field          Description field (the
                                               translation in English is
                                               taken from Item card --
                                               menu Related -- Item --
                                               Translations)

  Unit of measure   Invoice - Lines -- Unit of Invoice - Lines -- Unit of
                    measure code field         measure code field (the
                                               translation in English is
                                               taken from Units of
                                               measure page -- menu
                                               Related -- Units of
                                               measure -- Translations)

  Quantity          Invoice - Lines --         Invoice - Lines --
                    Quantity field             Quantity field

  Base price        Invoice - Lines -- Unit    Invoice - Lines -- Unit
                    price excl. VAT field,     price excl. VAT field,
                    before Discount            before Discount

  Discount.%        Invoice - Lines -- Line    Invoice - Lines -- Line
                    discount % field           discount % field

  Unit price        Invoice - Lines -- Unit    Invoice - Lines -- Unit
                    price after discount       price after discount
                    (calculated field)         (calculated field)

  Amount (excl.     Invoice - Lines -- Line    Invoice - Lines -- Line
  VAT)              amount excl. VAT field     amount excl. VAT field

  VAT base BGN      Invoice -- Total amount    Invoice -- Total amount
                    excl. VAT (BGN) field      excl. VAT (BGN) field

  20% VAT           Invoice -- Total VAT (BGN) Invoice -- Total VAT (BGN)
                    field. VAT % is determined field. VAT % is determined
                    by the VAT combinations in by the VAT combinations in
                    the first line.            the first line.

  Amount due        Invoice -- Amount due      Invoice -- Amount due
                    (incl. VAT) (BGN) field    (incl. VAT) (BGN) field

  External document Invoice -- Invoice details Invoice -- Invoice details
  No.               -- External document No.   -- External document No.
                    field                      field

  Payment method    Invoice -- Invoice details Invoice -- Invoice details
                    -- Payment method code     -- Payment method code
                    field                      field (translation)

  Delivery terms    Invoice -- Shipping        Invoice -- Shipping
                    details -- Shipment Method details -- Shipment Method
                    field                      field (the translation is
                                               taken from the Shipment
                                               methods page --
                                               Translations)

  Sales Location    Invoice - General -- Sales Invoice - General -- Sales
                    Location field (to be      Location field (to be
                    filled in the invoice with filled in the invoice with
                    the value of the field     the value of the field
                    City from page Company     City from page Company
                    Information, General tab)  Information, General tab)

  VAT Date          Invoice -- General -- VAT  Invoice -- General -- VAT
                    Date field                 Date field

  VAT exempt ground Invoice -- Invoice details Invoice -- Invoice details
                    -- VAT exempt ground field -- VAT exempt ground field
                                               (the translation is taken
                                               from the VAT clauses page
                                               -- Translation)

  Received by:      Invoice -- Bill-to         Invoice -- Bill-to
                    Customer -- Contact field  Customer -- Contact field

  Composed By:      Invoice -- General --      Invoice -- General --
                    Composed by field          Composed by field (if
                                               entered in Bulgarian, the
                                               system will automatically
                                               translate it in English)

  To Invoice - No.  Invoice (Debit note) /     Invoice (Debit note) /
                    Credit memo -- Invoice     Credit memo -- Invoice
                    details -- To invoice No.  details -- To invoice No.
                    field                      field

  To Invoice - Date Invoice (Debit note) /     Invoice (Debit note) /
                    Credit memo -- Invoice     Credit memo -- Invoice
                    details -- To invoice date details -- To invoice date
                    field                      field
  -----------------------------------------------------------------------

## Sales protocol

Like Sales invoices, Sales protocols have a list of unposted protocols.

![](.\/media/image136.png){width="4.666666666666667in"
height="2.6324781277340334in"}

The protocol is displayed as a sales invoice, but it is in a separate
list and is marked as protocol.

Once posted the protocols are stored in the list of posted invoices and
can be identified as Sales protocols by the check in the Sales Protocol
field. Their number series for posting must not coincide with these of
invoices. Filling them in is similar to filling in a Sales invoice. This
type of document is presented under code 81 in the VAT sales ledger.

The protocol is printed in a similar printed form like the Invoice, but
is titled Sales protocol.

![](.\/media/image137.png){width="6.531944444444444in"
height="5.925in"}

## Cancel Sales invoices or credit memos 

If you need to cancel a sales document, you must open the posted
document and select **Voiding invoice** from the **Actions -- Voiding
Invoice** menu**.**

![](.\/media/image138.png){width="6.531944444444444in"
height="3.0381944444444446in"}

The system displays a page where you must enter the **Cancellation
date**. Confirm by pressing the **Close** button.

![](.\/media/image139.png){width="4.316666666666666in"
height="1.9460837707786527in"}

The system displays the following message:

![](.\/media/image140.png){width="5.141666666666667in"
height="1.8416666666666666in"}

Upon pressing the **Yes** button, the document is marked as cancelled by
the system. It will appear in the VAT Sales Ledger with zero value. To
reverse the G/L postings, you must issue a Credit memo or Invoice which
you must also cancel.

## Change data in posted sales documents

It is possible to change data in a posted sales invoice and in a posted
sales credit memo.

The change is made from the posted document page.

### Update a posted sales invoice

If you need to update a document, you must open the posted sales
invoice. Under the **Actions -- Other** menu you have to select **Update
Document**.

![](.\/media/image141.png){width="5.976080489938758in"
height="2.5424759405074364in"}

On the Posted Sales Inv.- Update page, you can update the data in the
following fields:

Invoice Details tab

• Do not include in VAT Ledgers -- you can update the field Do not
include in VAT Ledgers

Payment tab

• Payment Method Code -- you can update the Payment Method Code field

• Payment Reference -- you can update the field Payment Reference

• Company Bank Account Code -- you can update the Company Bank Account
Code

• Bank No.

![](.\/media/image142.png){width="6.091473097112861in"
height="2.657962598425197in"}

Confirm with **OK** to update the data.

### Update a posted sales credit memo

If you need to update a document, you must open the posted sales credit
memo. Under the **Actions -- Other** menu you have to select **Update
Document**.

![](.\/media/image143.png){width="6.228659230096238in"
height="2.4128969816272967in"}

In the page Posted Sales. Cr.Memo - Update, the data in the following
fields can be updated:

Invoice Details tab

• Do not include in VAT Ledgers -- you can update the field Do not
include in VAT Ledgers

Shipping tab

• Agent -- you can update the field Agent

• Agent Service -- you can update the field Agent Service

• Package Tracking No-- you can update the field Package Tracking No

Payment tab

• Company Bank Account Code -- you can update the Company Bank Account
Code

• Payment Method Code -- you can update the Payment Method Code field

![](.\/media/image144.png){width="6.133333333333334in"
height="2.591666666666667in"}

Confirm with **OK** to update the data.

# Inventory -- localization settings

The Localization package for Bulgaria adds the following settings in the
Inventory module.

## Assembly Setup

Added Default General Business Posting Group field in **Assembly
Setup**.

![](.\/media/image145.png){width="6.166666666666667in"
height="2.3833333333333333in"}

When creating an assembly order, this group will be fill in the assembly
order General Business Posting Group field.

![](.\/media/image146.png){width="5.725in"
height="2.558333333333333in"}

## Inventory Setup

Added Gen. Bus. Posting Group (Transfer) field in **Inventory Setup**.
When creating a transfer order, this General Business Posting Group will
be fill in the transfer order.

![](.\/media/image147.png){width="5.683333333333334in"
height="2.3666666666666667in"}

## Item Journal

Added column for Default General Business Posting Group in Item Journal
Batches. If you fill a default group for a folder, then these General
Business Posting Group will be fill in item journal lines of that
folder.

![](.\/media/image148.png){width="6.108333333333333in"
height="0.9333333333333333in"}

![](.\/media/image149.png){width="6.033333333333333in"
height="1.6916666666666667in"}

## Default Dimension in Item Category

An Item Category can be assigned to each item from a defined list. Added
the ability to place default dimensions to the item category. This
happens to the Item Category card:

![](.\/media/image150.png){width="6.531944444444444in"
height="2.48125in"}

On the BG, VAT and VIES Setup page, a setting has been added to the
Items tab related to copying the dimensions from the item category to
the item itself:

![](.\/media/image151.png){width="6.531944444444444in"
height="5.814583333333333in"}

When this setting is checked, then the default dimensions from the item
category card will be transferred to the item when the item is assigned
to the item category.

The system has another setup in case of conflict between the dimension
values. In the Inventory Setup, there is a setup for item groups
dimension:

![A screenshot of a login screen Description automatically
generated](.\/media/image152.png){width="6.531944444444444in"
height="3.6881944444444446in"}

If an item has default dimensions for the Inventory Setup dimension, but
fills in the Category that has no dimension value from Inventory Setup,
then the same dimension will be removed from the item card.

# Irrecoverable Receivable

This point provides Dynamics 365 Business Central users with
instructions for the required sequence of actions in the in the process
of recording irrecoverable receivables for sales and purchases.

## Irrecoverable Receivable for purchases

When entering a credit note for a purchase related to an irrecoverable
receivable, a new field **Credit Memo according to art.126b, paragraph 1
of VAT Law** has been created in the header, where you can mark if the
credit memo is related to an irrecoverable receivable:

![](.\/media/image153.png){width="6.130952537182852in"
height="2.4694367891513562in"}

All other details of the credit note, as well as its entry and posting,
are in a standard way.

In the List of posted credit memos, a filter can be made on the
Irrecoverable Receivable field and only the documents issued in
connection with an irrecoverable receivable will be visualized:

![](.\/media/image154.png){width="6.531944444444444in"
height="1.4078423009623797in"}

The same field is also transferred to the VAT records, where again a
filter can be made on it:

![](.\/media/image155.png){width="6.152234251968504in"
height="1.6256813210848644in"}

After the purchase credit memo is posted, the document is with Document
Type 23 in the VAT Purchase Journals:

![](.\/media/image156.png){width="5.817428915135608in"
height="2.278911854768154in"}

## Irrecoverable Receivable for sales

### Sales Credit Memos for irrecoverable receivable

When entering a credit note for sale related to an irrecoverable
receivable, in the header part there is a new field **Credit Memo
according to art.126b, paragraph 1 of VAT Law**, where you can mark if
the credit note is related to an irrecoverable receivable:

![](.\/media/image157.png){width="5.9545384951881015in"
height="2.387673884514436in"}

All other details of the credit note, as well as its entry and posting,
are in a standard way.

After the sales credit memo is posted, the document is with Document
Type 23 in the VAT Sales Journal.

A filter can be made on the Irrecoverable Receivable field in the list
of posted sales credit memos and VAT Entries, and only the documents
issued in connection with an irrecoverable receivable will be
visualized.

### Debit memo for irrecoverable receivable

If a credit memo has been issued in relation to irrecoverable
receivable, but then a payment has been made for it, a debit memo should
be issued. Two new fields have been created:

![](.\/media/image158.png){width="6.1367672790901135in"
height="2.448905293088364in"}

If the **Irrecoverable Receivable** field is checked, the system opens
the **To sales credit memo field** for filling, where the list of sales
credit memos is filtered by customer and **Irrecoverable Receivable**
field. When the **Irrecoverable Receivable** field is checked in the
invoice header, the **Debit Memo** field is also checked automatically.
**ONLY** in the case when Debit notice and Irrecoverable Receivable are
checked, the system does not look for mandatory To invoice number field.

After the sales debit memo is posted, the document is with Document Type
02 in the VAT Sales Journal.

![](.\/media/image159.png){width="6.021580271216098in"
height="2.2719739720034995in"}

A filter can be made on the Irrecoverable Receivable field in the list
of posted sales invoices and VAT Entries, and only the documents issued
in connection with an irrecoverable receivable will be visualized.

### Protocol for irrecoverable receivable

If you have receivables from customers who have bankrupt and you have
irrecoverable receivable, a VAT report is issued.

When you create a sales protocol for irrecoverable receivable you have
to check the new field **Protocol according to art.126b, paragraph 2 and
7 of VAT Law**:

![](.\/media/image160.png){width="5.9741283902012245in"
height="2.5311286089238845in"}

After posting the protocol, it is entered in the VAT journals with Type
of document 29:

![](.\/media/image161.png){width="6.349292432195975in"
height="2.516905074365704in"}

# Service

## Function Copy Document in Service Credit Memo

Added new functionality - copy document in Service Credit Memo:

![](.\/media/image162.png){width="6.531944444444444in"
height="1.801388888888889in"}

The functionality allows you to select a posted service invoice whose
data is copied to the service credit memo.
