# alfred
Stuff I developed for alfred (MacOS productivity app)

# Workflows

## Clipboard to Tabs

Who does not know this situation: a long list of links in a browser window which I would all like to open, and doing cmd-click on each of them manually is simply tedious. 

This can be simplified by selecting the respective region and copying it to the clipboard which will then contain the text with all its formatting and metadata (like hyperlinks). 

This is where this workflow comes in. After copying the desired region to the clipboard it will extract the links in it and open all of them in the standard browser (assuming that the standard browser will automatically create tabs for each link which most nowadays do). 

The workflow can be triggered by a keyword or a hotkey. It has been tested with Sasfari, Chrome-based browsers and Firefox. It can also use TextEdit's clipboard. Support for other sources can be added rather easily if necessary (it's just a shell script).

Download the workflow here: [clipboard-to-tabs.alfredworkflow](https://github.com/mbert/alfred/raw/main/workflows/clipboard-to-tabs.alfredworkflow).
