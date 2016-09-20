# Links

Markdown supporte deux style de liens: inline et reference.

Pour les deux styles, le lien du texte est délimité par [des crochets].

Pour créer un lien inline, utilisez des parentheses immédiatement après le texte du lien fermé par un crochet. Dans les parentheses, inserez le lien url que vous voulez ciblez, avec un titre optionnel pour les liens, entouré par des guillemets. Par exemple:
```markdown
[Je suis un lien inline-style](https://www.google.com)

[Je suis un lien de type inline avec un titre](https://www.google.com "Page d'accueil Google")

[Je suis un lien de type reference][Arbitrary case-insensitive reference text]

[Je suis une référence relative à un fichier](../blob/master/LICENSE)
```

Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:
```markdown
This is [an example][id] reference-style link.
```

You can optionally use a space to separate the sets of brackets:
```markdown
This is [an example] [id] reference-style link.
```

Then, anywhere in the document, you define your link label like this, on a line by itself:
```markdown
[id]: http://example.com/  "Optional Title Here"
```

**GitHub** and **GitBook** supports URL autolinking. They will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.


---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---
