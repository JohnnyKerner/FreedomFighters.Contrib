# Translations - how to

Translations are kept as CSV files for several reasons:
- they can be worked with without Enfusion tools
- they can be imported and exported from any serious editor
- they are easy to version and track with Git

In particular you can import and export these files with Excel or LibreOffice Calc (the latter is free). When saving it back, make sure to use the **UTF-8** encoding. When updating an existing language file, you can sort it by the `Translation` column to display empty rows first to see which texts require filling in.

A row with the comment `REVIEW: English source changed` has a translation of an older English text. Compare it with the `Source` column, correct the translation if needed, then delete the comment.

When submitting a pull request, do not modify the language status in README.
