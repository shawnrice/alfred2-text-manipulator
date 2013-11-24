# Note: This thing is a bit wonky right now, but I haven't had time to fix it. I'll do that later. For now, don't download it.

## Text Manipulator

This workflow simply changes the cases for selected text. Right now, it just abuses an applescript found on the web (check the readme in the workflow for the source) with a few tweaks. It needs improvements before it's released.

Hotkeys are added in for each text case.

### Benefits over others

Another case workflow exists on the forums (forgot where), but it makes you select the text and copy it before you change the case. This workflow removes the need to copy the text... just select it. It should work in every application (even non-scriptable ones!) because it relies on system events because it actually exits Alfred, copies the text, changes the case, then pastes it again. Fun.

### Todo

* Rewrite applescript into php
* Convert to script filter that will show the case for the first x characters of the selected text
* Have the workflow accept arguments instead of reduplicating the script
* Move scripts out of the workflow and into separate files
* Add Alleyoop update capability
* Probably a few other things
