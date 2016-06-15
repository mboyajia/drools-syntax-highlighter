# drools-syntax-highlighter
Syntax highlighting for Drools Rules Language.

Steps to use

1. Download SublimeText 3
2. Install SublimeText's Package Control utility
3. Install the PackageDev package
	While in SublimeText:
		Ctrl + Shift + P
		Begin typing "Package Control: Install Package" and select that option
		Begin typing "PackageDev" and select that option (author is guillermooo)
	If the above doesn't work, you can try installing it directly from here
4. Close SublimeText
5. Do one of the following actions below within this folder:  ".../SUBLIME_HOME/Packages/User/"
	Create a new syntax definition file in the proper folder and copy the contents of my file into it
		Ctrl + Shift + P
		Begin typing "PackageDev: New JSON Syntax Definition" and select that option
	Copy my file directly into the proper folder
6. Open SublimeText & open the syntax definition file (Drools.JSON-tmLanguage)
7. Convert the JSON-tmLanguage file to a plain tmLanguage
	Ctrl + Shift + P
	Begin typing "PackageDev: Convert (YAML, JSON, PList) to..." and select this option when it appears
8. Set .drl files to open with this new syntax highlighter (if it doesn't automatically do it already)
	Open a .drl file
	View > Syntax > Open all with current extension as... > Drools
	If "Drools" does not appear in the list, the files are likely not in the proper directory
