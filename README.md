# ProPa-Subtitles

Suggest changes per pull requests, please.

Note that the *editor settings* provided as an `.editorconfig` file can be enforced by most editors either [directly](https://editorconfig.org/#pre-installed) or [after installing some plugin](https://editorconfig.org/#download).

Some initial ideas for pull requests:

- Annotate the beginnings of individual slides in the respective subtitle files as in [this commit](https://github.com/fmidue/ProPa-Subtitles/commit/3f216c790cff243715c61ea989c09c4ecf1fed3f).
- Use ChatGPT to improve German and English grammar. For example, the changes in [this commit](https://github.com/fmidue/ProPa-Subtitles/commit/cca7d86160aad7b84bdd29df26d2972006d1e32d) were produced using the prompts
  > Bitte korrigiere Grammatikfehler in den folgenden Untertiteln. Aendere keine Zeilenumbrueche. Aendere nicht die Zuordnung von Zeitstempeln. Wenn die Grammatik korrekt ist, gib die vorgegebenen Untertitel genau so zurueck, wie sie sind. Hier sind die vorgegebenen Untertitel: ...

  and
  > Please correct grammar mistakes in the following subtitles. Do not change line breaks. Do not change the assignment of time stamps. If the grammar is correct, return the given subtitles exactly as they are. Here are the given subtitles: ...

  respectively. (But blindly taking over ChatGPT-produced changes will not work satisfactorily. Instead, going through them individually, and selecting the appropriate line changes, will most likely be necessary. Maybe use a tool like [Beyond Compare](https://www.beyondcompare.de/) or hunk staging with `git add -p` to facilitate this.)

Concerning use of quotation marks, try to follow rules that mirror the following examples:

- `When we call 'rectangle', something happens on screen.`
- `Wenn wir 'rectangle' aufrufen, erscheint ein Rechteck auf dem Bildschirm.`
- `When we call the 'rectangle' function, something happens on screen.`
- `Wenn wir die rectangle-Funktion aufrufen, erscheint ein Rechteck auf dem Bildschirm.`
- `We could say: "This 'rectangle' function is a strange thing."`
- `Wir könnten sagen: "Diese rectangle-Funktion ist echt merkwürdig."`
- `Wir könnten sagen: "Jeder Aufruf von 'rectangle' macht etwas mit uns."`
- `Doing what we just did is a bit "funny".`
- `Was wir gerade getan haben, ist "lustig".`
- `The QuickCheck library has been copied in many other programming languages.`
- `Die Bibliothek QuickCheck wurde in vielen Programmiersprachen nachgeahmt.`
- `The variable xs is used here to stand for a list.`
- `Die Variable xs wird hier als Platzhalter für eine Liste benutzt.`
- `For the case n = 1 everything is very simple.`
- `Der Fall n = 1 ist wirklich einfach.`
- `The type String is pre-defined, but we can also define our own types like Tree.`
- `Der Typ 'String' ist vordefiniert, aber wir können auch eigene Typen wie 'Tree' definieren.`

## Leader board

| GitHub username | Lines |
| :-- | --: |
