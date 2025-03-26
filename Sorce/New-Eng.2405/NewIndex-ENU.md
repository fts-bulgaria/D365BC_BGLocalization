## 2.8. Postpone tax credit within the permitted 12-month period

### 2.8.1. Setup

In BG, VAT and VIES Setup, the Postponed VAT Account is replenished, as
well as a template and batch for a general journal:

![A screenshot of a computer Description automatically
generated](.\media/image1.png){width="5.283085083114611in"
height="3.5396555118110236in"}

### 2.8.2. Postponed VAT before posting invoice

Enter the invoice and place a check mark in the Postponed VAT field in
the Invoice Details tab:

![A screenshot of a computer Description automatically
generated](.\media/image2.png){width="6.531944444444444in"
height="3.807638888888889in"}

If the Postponed VAT field is marked, a check mark is automatically
placed in the Do Not Include in VAT field.

If the check mark in the Postponed VAT field is removed, the check mark
in the Do Not Include in VAT field is also automatically removed.

When the invoice is posted, the tax credit will be reflected in the G/L
account in the Postponed VAT Account field in BG, VAT and VIES Setup. In
the VAT Entries filtered by the document number, there is a check mark
in the Postponed VAT field and Do Not Include in VAT Ledgers.

### 2.8.3. Postponed VAT on a posted invoice

A purchase VAT ledger opens and the invoices that must enter the Journal
for the selected month are generated. After generation, the Postponed
VAT function can be started:

![A screenshot of a computer Description automatically
generated](.\media/image3.png){width="6.531944444444444in"
height="4.572916666666667in"}

After this action on a screen, the VAT journal lines are displayed and
by placing a check mark for the invoices to be included in the VAT
ledger of purchases in the next period:

![A screenshot of a computer Description automatically
generated](.\media/image4.png){width="6.531944444444444in"
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

### 2.8.4. Use of postponed tax credit

To include a purchase invoice whose VAT has been postponed with the
function described above, you must start the Change VAT Period page by
selecting Change VAT Period from the Search button:

![A screenshot of a computer Description automatically
generated](.\media/image5.png){width="4.299818460192476in"
height="2.1255971128608926in"}

A list of documents marked with Postponed VAT that are not yet included
in the VAT Ledgers is displayed on the screen.

![A screenshot of a computer Description automatically
generated](.\media/image6.png){width="6.531944444444444in"
height="1.8243055555555556in"}

By placing a check mark in the Change VAT Period field (first column),
select the documents to include in a selected VAT period. The selection
is confirmed by the Change VAT Period function in the ribbon above. The
following window appears on the screen:

![A screenshot of a computer Description automatically
generated](.\media/image7.png){width="6.531944444444444in"
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
displayed in the relevant ledger

# 4.5. Changes in posting with Deferral Templates 

In Deferral Templates two new fields were added:

![A screenshot of a computer Description automatically
generated](.\media/image8.png){width="6.531944444444444in"
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
    account) / Credit account for vendors with the amount of 100 (posted
    with the Posting date)

-   Debit account for Deferral expense (65\* for BG chart of account) /
    Credit account for expenses account (starting with 60\* in BG chart
    of account) with the amount of 100 (posted with the Posting date)

-   Debit Expenses account (starting with 60\* in BG chart of account) /
    Credit Deferral account (65\* for BG chart of account) posted with
    the dates from the schedule

The change, related to this development, is as follows:

-   Debit [Account for change]{.mark} (the new field in Deferral
    Template) / Credit Vendor accountwith the amount of 100 (posted with
    the Posting date)

-   Debit Deferral Account from the Deferral Template (65\* for BG chart
    of account) / Credit [Account for change]{.mark} (the new field in
    Deferral Template) with the amount of 100 (posted with the Posting
    date of the invoice)

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
    account (75\* in BG Chart of account) with the amount of 100 (posted
    with the Posting date of the invoice)

-   Debit Deferral account (75\* in BG Chart of account) / Credit income
    account (703 in BG Chart of account) with the dates from the
    Deferral Schedule

The change, related to this development, is as follows:

-   Debit Customer account / Credit [Account for change]{.mark} with the
    amount of 100 (posted with the Posting date of invoice)

-   Debit [Account for change]{.mark} / Credit Deferral account (75\*
    from BG Chart of account) with the amount of 100 (posted with the
    Posting date of invoice)

-   Debit Deferral account / Credit Income account from the lines with
    the dates from the Deferral schedule

When posting the invoice transaction, system uses the Account for change
from the Deferral Template, but the actual deferral of the income will
use the exact Income account from the sales lines and the Deferral
account from the template.

# 

# 

# 7.4. Default Dimension in Item Category

An Item Category can be assigned to each item from a defined list. Added
the ability to place default dimensions to the item category. This
happens to the Item Category card:

![A screenshot of a computer Description automatically
generated](.\media/image9.png){width="6.531944444444444in"
height="2.48125in"}

On the BG, VAT and VIES Setup page, a setting has been added to the
Items tab related to copying the dimensions from the item category to
the item itself:

![A screenshot of a computer Description automatically
generated](.\media/image10.png){width="6.531944444444444in"
height="5.814583333333333in"}

When this setting is checked, then the default dimensions from the item
category card will be transferred to the item when the item is assigned
to the item category.

The system has another setup in case of conflict between the dimension
values. In the Inventory Setup, there is a setup for item groups
dimension:

![A screenshot of a login screen Description automatically
generated](.\media/image11.png){width="6.531944444444444in"
height="3.6881944444444446in"}

If an item has default dimensions for the Inventory Setup dimension, but
fills in the Category that has no dimension value from Inventory Setup,
then the same dimension will be removed from the item card.

# 
