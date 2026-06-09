Link Converting Word to MD:
https://www.vertopal.com/en/convert/doc-to-md
https://www.docstomarkdown.pro/convert-word-to-markdown/


>pandoc -t gfm --extract-media . "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2025\02.2025\02.2025 FTS Bulgarian Basic Localization Package.docx" -o c:\temp\main.md
>pandoc -t gfm --extract-media . "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2025\02.2025\02.2025 FTS Bulgarian Basic Localization Package_ENU.docx" -o c:\temp\main_ENU.md

>pandoc -t gfm "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2026\02.2026\02.2026 FTS Bulgarian Basic Localization Package.docx" -o D:\AL\D365BC_BGLocalization\bg\index.md --extract-media D:\AL\D365BC_BGLocalization\bg
>pandoc -t gfm "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2026\02.2026\02.2026 FTS Bulgarian Basic Localization Package_ENU.docx" -o D:\AL\D365BC_BGLocalization\en\index.md --extract-media D:\AL\D365BC_BGLocalization\en

>pandoc -t gfm "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2026\02.2026\02.2026 FTS Bulgarian Basic Localization Package.docx" -o D:\AL\D365BC_BGLocalization\bg.2026\index.md --extract-media D:\AL\D365BC_BGLocalization\bg.2026
>pandoc -t gfm "C:\Users\egecov\FTS Bulgaria LTD\FTS Bulgaria - General\NAVISION\05 Localization\Документация\Ръководство редакция 2026\02.2026\02.2026 FTS Bulgarian Basic Localization Package_ENU.docx" -o D:\AL\D365BC_BGLocalization\en.2026\index.md --extract-media D:\AL\D365BC_BGLocalization\en.2026

(2026.06.09)
>pandoc -t gfm "D:\AL\D365BC_BGLocalization\Source\BG-Full.2026.05\05.2026 FTS Bulgarian Basic Localization Package.docx" -o D:\AL\D365BC_BGLocalization\bg\index.md --extract-media D:\AL\D365BC_BGLocalization\bg
>pandoc -t gfm "D:\AL\D365BC_BGLocalization\Source\EN-Full.2026.05\05.2026 FTS Bulgarian Basic Localization Package_ENU.docx" -o D:\AL\D365BC_BGLocalization\en\index.md --extract-media D:\AL\D365BC_BGLocalization\en
