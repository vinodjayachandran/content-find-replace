# Content Find & Replace #

**A Utility to find & replace content in files (including .zip files) ...**

Search & replace for some content in a folder on your hard disk.

Existing close prior arts
  1. Windows search
  1. Any text editors, for example notepad++, textpad, eclipse, pspad etc
  1. Combination of grep,find and cut commands, if OS is linux
  1. grepWin

![http://crypticarticles.files.wordpress.com/2012/12/content-find-replace1.jpg](http://crypticarticles.files.wordpress.com/2012/12/content-find-replace1.jpg)

**What's new ? Y this tool**
  1. **_Find within Nested Zip Files_** Normal editors searches for contents in files under a folder, but not in files inside a zip file. This tool searches for contents in files not in zip files but in nested zip files as well.
  1. **_Replace within Zip Files_** It enables you to replace content in files that are present inside zip files unlike other tools which allow only on files directly under a folder.
  1. **_Exclude File List_** Filters in other search utilities supports only include list. For example , you can restrict your search to **.java,**.html etc. But you can't specify an exclusion list. You can exclude a set of files from search (for example binaries)that match a regular expression.
  1. **_Filters based on folders_** Filters in other search utilities supports only inclusion list, that too only for files. With this tool, you can filter to include, exclude or both a set of folders using a regular expression.
  1. **_Export search result to file_** When the search result becomes very large (order of 1000s) then it gets difficult to manage them and often human eyes tend to over see or miss out few. With content-search tool, you can export the search result to a csv file so that it gets easier to track and manage. Please use .csv as extension for the file
  1. Includes all other major search features provided by other search utilities, such as **_Skip/Include sub folders_**, **_Match case_**, **_Skip/Include hidden folders_**,**_Open file from the tool on double click_** etc ...

**Limitations**
  1. Replace functionality is **_Replace All_** and can't do any specific replace
  1. Doesn't support content replace under nested zip files. Will replace only one level (i.e) Files directly under a .zip file

Prerequisite : JVM 1.6 or above

Blog http://crypticarticles.wordpress.com/2012/12/11/content-find-replace-tool/

_If you have any suggestions or issues, you may report it in projects page itself under issues or alternatively e-mail to vinodjayachandran@gmail.com_