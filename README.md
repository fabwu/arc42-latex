# LaTeX Template für arc42

Dieses Repository enthält eine LaTeX-Vorlage für die arc42 Architekturdokumentation. 

Weitere Informationen zu arc42 findet man unter http://www.arc42.de/.

Die Vorlage enthält alle Überschriften und ein Glossar. Um die Vorlage in ein PDF zu konvertieren müssen folgende Befehle ausgeführt werden:
```bash
pdflatex arc42-template.tex
makeglossaries arc42-template
pdflatex arc42-template.tex
pdflatex arc42-template.tex
```
