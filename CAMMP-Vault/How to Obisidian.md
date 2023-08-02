![[Pasted image 20230730225740.png]]
von [[https://kadavy.net/blog/posts/zettelkasten-method-slip-box-digital-example/|hier]].

## Formatierung  
- **Fett** und __Fett__             `**Fett** und __Fett__ `
- *Italic* und _Italic_           `*Italic* und _Italic_`
- ~~Durchgestrichen~~        `~~Durchgestrichen~~`
- ==Markiert==                    `==Markiert==`
- ***Fett und italic***           `==Markiert==`

> Zitat                 `> Zitat ` 

^76ed48

 
>[!info]
>Hervorgehobenes Zitat 
>`>[!info] `
>`>Hervorgehobenes Zitat`
Weitere [[https://help.obsidian.md/Editing+and+formatting/Callouts|Callout Layouts]]
## Code
Code innerhalb eines Satzes `durch Backtiks` `

	Tabs oder 4 blank spaces um eine Code-Zeile zu starten

```
Code innerhalb eines eigenen Feldes durch drei Backticks ```
```

```python
print('Syntax highlight durch hinzufügen von python/julia... nach den backticks')
```
[Unterstützte Programmiersprachen](https://prismjs.com/#supported-languages)


## Links
- [Link mithilfe einer URL](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)   `[Beschreibung](Link-URL)`
- Links innerhalb von Obisdian
	-  [[How to Obisidian]]    `[[How to Obsidian]]`
	- Link direkt zu einem Kapitel [[How to Obisidian#Links]]   `[[How to Obisidian#Links]]`
	- Link mit eigener Beschreibung [[How to Obisidian|Klicke hier]]  `[[How to Obisidian|Klicke hier]]`
- Um eine Vorschau zu einem Link zu erhalten, drücke Ctrl (oder Cmd in macOS) während du mit der Maus drüber fährst
- Um direkt einen Block verlinken zu können, füge ein ^ gefolgt von einem Wort hinzu ^Blockverlinkung
	- Diese kann dann über [[How to Obisidian#^Blockverlinkung]] verlinkt werden
	  `[[How to Obisidian#^Blockverlinkung]]`
- Wenn die Verlinkung Leerzeichen enthält, ersetze sie durch `%20` oder setze die gesamte URL in Größer-Kleiner-Zeichen `<URL>`

## Bilder
- Externe Bilder können mit  URLs hinzugefügt werden durch ein ! vor der Verlinkung
  ![Smiley|100](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.pngitem.com%2Fpimgs%2Fm%2F18-181430_happy-face-emoji-png-image-free-download-searchpng.png&f=1&nofb=1&ipt=cf74de6ae4e7fa624693ccadc4daecbaabde859277ab4cf61fb1234992f94b6c&ipo=images)
  - Bilder können per Drag-and-Drop hinzugefügt werden. Dann wird innerhalb des Vaults eine Kopie des Bildes erstellt und darauf verlinkt
  - Die Größe des Bildes kann angepasst werden: `[Name|width](Link)`


## Listen
- Ungeordnete Listen durch ein '-' beginnen
	- ..
	- ..
- Nummerierte Listen durch ein '1.' beginnen
	1. ..
	2. ..
- Aufgabenlisten durch `- []` beginnen
	- [ ] ..
	- [ ] ..

## Weiteres
- Horizontale Linien hinzufügen durch  `***` oder `****` oder `- - - ` ...
---
- Fußnoten[^1] können erstellt werden indem `[^1]` hinter ein Wort geschrieben wird
	- Unten muss dann durch `[^1]: Inhalt der Fußnote` der Inhalt nachgetragen werden
- Es können auch Inline Fußnoten^[Inline Fußnote] erstellt werden durch `^[Inhalt der Fußnote]` 
-  Kommentare können durch `%% Kommentar %%` hinzugefügt werden. Sie sind nur im Bearbeiten-Modus sichtbar %% Kommentar %%
	- Wenn der Kommentar mehrere Zeilen lang sein soll:
	  ```
	  %%
	  Kommentar
	  %%
	  ```
%%
Kommentar über 
mehrere Zeilen
%%


[^1]: Das ist der Inhalt der Fußnote


Weitere Informationen: 
- [Link zu "Basic formatting syntax"](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax) 
- https://help.obsidian.md/Editing+and+formatting/Advanced+formatting+syntax