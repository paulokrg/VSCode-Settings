# VSCode settings.json file:

```json
{
	// Disable default welcome page:
	"workbench.startupEditor": "none",
	// Editor associations:
	"workbench.editorAssociations": {
		"*.ipynb": "jupyter.notebook.ipynb"
	},
	// Do not show folders in a compact view:
	"explorer.compactFolders": false,
	// Do not confirm default deletion (goes to trash):
	"explorer.confirmDelete": false,
	// VSCode editor features:
	// Lines will wrap at viewport width:
	"editor.wordWrap": "on",
	// Colorizes openning and closing brackets:
	"editor.bracketPairColorization.enabled": true,
	// Automatically format on save:
	"editor.formatOnType": false,
	"editor.formatOnPaste": false,
	"editor.formatOnSave": true,
	"editor.formatOnSaveMode": "file",
	// Automatically updates the closing HTML tag when modified
	"editor.linkedEditing": true,
	// Trim white spaces:
	"editor.trimAutoWhitespace": true,
	"editor.renderWhitespace": "boundary",
	"diffEditor.ignoreTrimWhitespace": false,
	// Minimap configuration:
	"editor.minimap.enabled": true,
	"editor.minimap.autohide": false,
	"editor.minimap.showSlider": "always",
	// Show vertical ruler, let you know when the line is getting too long:
	"editor.rulers": [100],
	// Indentation:
	"editor.guides.indentation": true,
	"editor.autoIndent": "advanced",
	"editor.detectIndentation": true,
	// "editor.tabSize": 4,
	// "editor.insertSpaces": true,
	"files.insertFinalNewline": true,

	// IntelliSense configuration:
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"tabnine.experimentalAutoImports": true,

	// Live Share configuration:
	"liveshare.presence": true,
	"liveshare.authenticationProvider": "GitHub",

	// Code Runner configuration:
	"code-runner.runInTerminal": true,
	"code-runner.saveAllFilesBeforeRun": true,
	"code-runner.preserveFocus": false,
	"code-runner.clearPreviousOutput": true,
	"code-runner.ignoreSelection": true,
	"code-runner.executorMap": {
		"javascript": "node",
		"java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
		// "c": "cd $dir && gcc '$fileNameWithoutExt.c' -o 'coderunner.exe' && ./'coderunner.exe'",
		"c": "cd $dir && gcc '$fileNameWithoutExt.c' -o C:/CodeRunner/coderunner.exe && C:/CodeRunner/coderunner.exe",
		"cpp": "cd $dir && g++ '$fileName' -o 'coderunner.exe' && ./'coderunner.exe'",
		"objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
		"php": "php",
		"python": "python -u",
		"perl": "perl",
		"perl6": "perl6",
		"ruby": "ruby",
		"go": "go run",
		"lua": "lua",
		"groovy": "groovy",
		"powershell": "powershell -ExecutionPolicy ByPass -File",
		"bat": "cmd /c",
		"shellscript": "bash",
		"fsharp": "fsi",
		// "csharp": "scriptcs",
		"csharp": "dotnet run",
		"vbscript": "cscript //Nologo",
		"typescript": "ts-node",
		"coffeescript": "coffee",
		"scala": "scala",
		"swift": "swift",
		"julia": "julia",
		"crystal": "crystal",
		"ocaml": "ocaml",
		"r": "Rscript",
		"applescript": "osascript",
		"clojure": "lein exec",
		"haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
		"rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
		"racket": "racket",
		"scheme": "csi -script",
		"ahk": "autohotkey",
		"autoit": "autoit3",
		"dart": "dart",
		"pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
		"d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
		"haskell": "runhaskell",
		"nim": "nim compile --verbosity:0 --hints:off --run",
		"lisp": "sbcl --script",
		"kit": "kitc --run",
		"v": "v run",
		"sass": "sass --style expanded",
		"scss": "scss --style expanded",
		"less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
		"FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
		"fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
		"fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
		"fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
	},

	// Prettier and other linters configuration:
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"markdownlint.run": "onSave",
	"prettier.tabWidth": 4,
	"prettier.useTabs": true,
	"[settings.json]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[json]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[css]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[typescript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[typescriptreact]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[vue]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[markdown]": {
		"editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
	},
	"markdownlint.config": {
		"code_blocks": false,
		"no-inline-html": false,
		"allowed_elements": true,
		"first-line-h1": false
	},
	"[yaml]": {
		"editor.defaultFormatter": "redhat.vscode-yaml"
	},
	"[c]": {
		"editor.defaultFormatter": "ms-vscode.cpptools"
	},
	"[prisma]": {
		"editor.defaultFormatter": "Prisma.prisma"
	},
	"editor.codeActionsOnSave": {},
	"redhat.telemetry.enabled": false,
	"notebook.consolidatedRunButton": true,

	// Thunder Client configuration:
	"thunder-client.codeSnippetLanguage": "cs-httpclient",

	// Spelling extensions configuration:
	"cSpell.language": ["pt-BR", "en", "en-GB"],
	"spellright.notificationClass": "information",
	"spellright.configurationScope": "user",
	"spellright.language": ["en", "pt"],
	"spellright.documentTypes": ["*", "html", "markdown", "plaintext"]
}
```
