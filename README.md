## Biber

biber folder/main

## Instalação

sudo apt install texlive-full -y

instalar as dependencias do vscode


## Configurações

{
	"latex-workshop.latex.tools": [
		{
			"name": "pdflatex",
			"command": "pdflatex",
			"args": [
				"--shell-escape",
				"-synctex=1",
				"-interaction=nonstopmode",
				"-file-line-error",
				"%DOC%"
			]
		}
	],
	"latex-workshop.latex.recipes": [
		{
			"name": "pdflatex",
			"tools": [
				"pdflatex"
			]
		}
	]
}
