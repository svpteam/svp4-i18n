# SVP 4 Manager Translations

https://www.svp-team.com


## How to deal with translation files

- Get ***Qt Linguist***. 
If you don't have Qt installed you can download minimal distribution here:
https://www.svp-team.com/files/tools/qt-linguist-550.zip

- Run Qt Linguist, open any ***.ts*** file (preferably in your native language ;)).

- If your language is not here copy ***empty.ts*** to ***\<your-lang-code\>.ts***, open it and choose the language.

- Find a two-letter <your-lang-code> value in that table: http://www.lingoes.net/en/translator/langcode.htm

- Make the changes!

- When done, use File -> Compile to produce ***.qm*** file, place it into ***SVP/i18n*** folder and restart SVP to check your modifications.


## Notes for the translators

* All SVP4 versions use the same translation files, so you'll need either SVP 4 Full or Developer build to test your work.

* Please don't drop rich-text format tags when there're present in the source text.
Example: "Using icons from \<b\>Icons8\<\/b\>".
