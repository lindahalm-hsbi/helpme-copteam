# Dateiname: 
- Benennung der Datei nach folgendem Schema: YYYYMMDD_Kurzer-Titel
- Dateiendung: .md
- Wichtig: Dateinamen dürfen keine Umlaute bzw. ß oder Leerstellen enthalten

# Inhalt der Datei:
- Alle Sonderzeichen (wie z.B. das kleine blaue Dreicksymbol vor unseren Links in HumHub) oder Emojis löschen.
- Trennlinien können entgegen erster Vermutungen doch problemlos genutzt werden und erzeugen keine Fehler.
- Im MarkdownMonster kümmern wir uns noch nicht um die Bilder aus den CoP-Artikeln. Das dort ein Bild vewendet wurde, sieht man in der Markdown-Datei im Editiermodus zwar, aber die Bilddatei zeigt auf HumHub und das wird beim Upload auf einen Fehler laufen. Nicht schlimm: die Bilder fügen wir danach hinzu.
- In die erste Zeile (also die Üebrschrift, die mit einer RAUTE vorweg gekennzeichnet wird) dürfen keine Sternchen verwendet werden (um z.B. was fett zu stellen). In der Preview sieht das zwar ok aus, aber auf der Landing Page wird dann die Überschrift nicht im Inhaltsverzeichnis angezeigt.
- 

# Potentielle Probleme bei der Bearbeitung der Datei in MarkdownMonster:
- Mit F12 könnt ihr zwischen dem Präsentations- und dem Einfügenmodus wechseln
- Kopierte Inhalte können über das Menü "Edit > Paste HTML as markdown" eingefügt werden. Falls das nicht funktioniert, kann man stattdessen die Tastenkombination control + shift + v nutzen.
- Wenn das auch nicht geht und Marlkdown Monster eine Lizenz verkaufen möchte, dann ein paar mal das wiederholen und z.B. in die erste Zeile mal ein paar Textzeichen schreiben.

# Previewbild
- Das Previewbild muss .png Format sein und rechteckig.
- es wird in den mainbranch hochgeladen
- Danach die Metadaten.yml ändern und die folgenden Zeilen hinzufügen:

  image: >-
   https://raw.githubusercontent.com/lindahalm-hsbi/infOERmiert/main/blog-cc0-oer.png

  Der Anfang des Links  https://raw.githubusercontent.com/ ist etwas seltsam, muss aber so geschrieben werden. Ich weiß auch nicht warum. Am Ende steht der Dateiname der Bilddatei. ´
