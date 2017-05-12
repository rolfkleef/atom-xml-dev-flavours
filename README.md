# Atom XML flavoured development

This Atom package contains snippets for the development of XML-based
software: a quick way to write XML, XSLT, Xspec, and so on. It works with
the existing [language-xml](https://atom.io/packages/language-xml) package.
It should also work with the
[XML Common Schemata](https://atom.io/packages/xml-common-schemata) package,
which offers schema-based auto-completion.

## XML

The language-xml package offers `xml` to start a document with
`<?xml version="1.0" encoding="UTF-8"?>`.

Add common namespace declarations to any element.
Start typing `functx`, select `functx (namespace)` to add
`xmlns:functx="http://www.functx.com"`.

Included are:

  * functx (http://www.functx.com)
  * xs (http://www.w3.org/2001/XMLSchema)
  * xlink (http://www.w3.org/1999/xlink)

## XSLT

Add namespace `xsl` if needed (http://www.w3.org/1999/XSL/Transform).

Add common stylesheet elements by typing their name and selecting the right
variant: `stylesheet`, `template`, `param`, etc.

## Xspec

For files with the suffix `xspec`. The grammar is shown as Xspec, with scope `text.xml.xspec`.

Add namespace `xspec` to an element if needed
(http://www.jenitennison.com/xslt/xspec).

Add common Xspec elements like `description`, `scenario`, `expect`, etc.

## Roadmap

More snippets and other additions or recommendations are welcome.
I plan to add Schematron, Ant,
and possibly other snippets for various XML flavours, based on what I
use or need myself.

## Acknowledgements

The package is derived from the [xml-demo-package](https://github.com/aerhard/xml-demo-package) by Alexander Erhard.

## License

MIT License
