# XSLT Kata

Create a stylesheet, convert.xslt, that transforms lov.xml into a document, with the same content, that 

- Unwraps text paragraphs (`<p>`) in text paragraphs, i.e. illegal paragraphs.
- Converts text paragraphs that looks like unordered lists into unordered lists (`<ul>`) or list elements (`<li>`)
- The document validates, see document.rng
