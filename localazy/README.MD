## Install localazy
npm install -g @localazy/cli

## Configuration
Set Applicatiuon Keys in 
[/localazy/localazy.keys.json](/localazy/localazy.keys.json)
Adjust [/localazy/localazy.json](/localazy/localazy.json) to set the upload an download parameters.

## Run
- `localazy upload -s` to test the upload of a source file
- `localazy upload` to upload the source file. After a successful upload the file will be vissible in the website's section: *File Managemnent* and in the section *Translations - Add Languages* target languages with 'Phrases translated' percentages will becomes visible.
- `localazy upload existing -s` after adjusting file path and pattern in config to test the upload of additional existing translations
- `localazy upload existing` to upload the additional translations. This only works after the language has been added to the app in the web application.
- `localazy download` to download translation files after translation have been done on https://localazy.com/p/bpmn-io.bpmn-js

## References
https://localazy.com/docs/cli/command-line-options
https://localazy.com/docs/cli/upload-reference
https://localazy.com/docs/cli/download-reference
https://localazy.com/docs/cli/javascript-format




