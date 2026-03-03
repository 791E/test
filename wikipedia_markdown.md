---
title: "Markdown - Wikipedia"
author: "Contributors to Wikimedia projects"
published: 2005-08-09T19:56:00Z
source: "https://en.wikipedia.org/wiki/Markdown"
domain: "en.wikipedia.org"
word_count: 2235
---

**Markdown** <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-philosophy-9"><span>[</span>9<span>]</span></a></sup> is a [lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language "Lightweight markup language") for creating [formatted text](https://en.wikipedia.org/wiki/Formatted_text "Formatted text") using a [plain-text editor](https://en.wikipedia.org/wiki/Text_editor "Text editor"). [John Gruber](https://en.wikipedia.org/wiki/John_Gruber "John Gruber") created Markdown in 2004 as an easy-to-read [markup language](https://en.wikipedia.org/wiki/Markup_language "Markup language").<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-philosophy-9"><span>[</span>9<span>]</span></a></sup> Markdown is widely used for [blogging](https://en.wikipedia.org/wiki/Blog "Blog"), [instant messaging](https://en.wikipedia.org/wiki/Instant_messaging "Instant messaging"), and [large language models](https://en.wikipedia.org/wiki/Large_language_models "Large language models"),<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-llm-markdown-10"><span>[</span>10<span>]</span></a></sup> and also used elsewhere in [online forums](https://en.wikipedia.org/wiki/Online_forums "Online forums"), [collaborative software](https://en.wikipedia.org/wiki/Collaborative_software "Collaborative software"), [documentation](https://en.wikipedia.org/wiki/Documentation "Documentation") pages, and [readme files](https://en.wikipedia.org/wiki/README "README").

The initial description of Markdown <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-11"><span>[</span>11<span>]</span></a></sup> contained ambiguities and raised unanswered questions, causing implementations to both intentionally and accidentally diverge from the original version. This was addressed in 2014 when long-standing Markdown contributors released [CommonMark](https://en.wikipedia.org/wiki/Markdown#Standardization), an unambiguous specification and test suite for Markdown.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-FutureOfMarkdown-12"><span>[</span>12<span>]</span></a></sup>

## History

Markdown was inspired by pre-existing [conventions](https://en.wikipedia.org/wiki/Convention_\(norm\) "Convention (norm)") for marking up [plain text](https://en.wikipedia.org/wiki/Plain_text "Plain text") in [email](https://en.wikipedia.org/wiki/Email "Email") and [usenet](https://en.wikipedia.org/wiki/Usenet "Usenet") posts,<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-ArsTechnica2014-13"><span>[</span>13<span>]</span></a></sup> such as the earlier markup languages [setext](https://en.wikipedia.org/wiki/Setext "Setext") (c.1992), [Textile](https://en.wikipedia.org/wiki/Textile_\(markup_language\) "Textile (markup language)") (c.2002), and [reStructuredText](https://en.wikipedia.org/wiki/ReStructuredText "ReStructuredText") (c.2002).<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-philosophy-9"><span>[</span>9<span>]</span></a></sup>

In 2002 [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz "Aaron Swartz") created [atx](https://en.wikipedia.org/wiki/Atx_\(markup_language\) "Atx (markup language)") and referred to it as "the true structured text format". Gruber created the Markdown language in 2004 with Swartz as his "sounding board".<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-Gruber-14"><span>[</span>14<span>]</span></a></sup> The goal of the language was to enable people "to write using an easy-to-read and easy-to-write plain text format, optionally convert it to structurally valid [XHTML](https://en.wikipedia.org/wiki/XHTML "XHTML") (or [HTML](https://en.wikipedia.org/wiki/HTML "HTML"))".<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-md-5"><span>[</span>5<span>]</span></a></sup>

Another key design goal was *readability*, that the language be readable as-is, without looking like it has been marked up with tags or formatting instructions,<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-philosophy-9"><span>[</span>9<span>]</span></a></sup> unlike text formatted with "heavier" [markup languages](https://en.wikipedia.org/wiki/Markup_language "Markup language"), such as [Rich Text Format](https://en.wikipedia.org/wiki/Rich_Text_Format "Rich Text Format") (RTF), HTML, or even [wikitext](https://en.wikipedia.org/wiki/Wikitext "Wikitext") (each of which have obvious in-line tags and formatting instructions which can make the text more difficult for humans to read).

Gruber wrote a [Perl](https://en.wikipedia.org/wiki/Perl "Perl") script, `Markdown.pl`, which converts marked-up text input to valid, [well-formed](https://en.wikipedia.org/wiki/Well-formed_document "Well-formed document") XHTML or HTML, encoding angle brackets (`<`, `>`) and [ampersands](https://en.wikipedia.org/wiki/Ampersand "Ampersand") (`&`), which would be misinterpreted as special characters in those languages. It can take the role of a standalone script, a plugin for [Blosxom](https://en.wikipedia.org/wiki/Blosxom "Blosxom") or a [Movable Type](https://en.wikipedia.org/wiki/Movable_Type "Movable Type"), or of a text filter for [BBEdit](https://en.wikipedia.org/wiki/BBEdit "BBEdit").<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-md-5"><span>[</span>5<span>]</span></a></sup>

As Markdown's popularity grew rapidly, many Markdown [implementations](https://en.wikipedia.org/wiki/Implementation "Implementation") appeared, driven mostly by the need for additional features such as [tables](https://en.wikipedia.org/wiki/Table_\(information\) "Table (information)"), [footnotes](https://en.wikipedia.org/wiki/Note_\(typography\) "Note (typography)"), definition lists,<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-17"><span>[</span>note 1<span>]</span></a></sup> and Markdown inside HTML blocks.

The behavior of some of these diverged from the reference implementation, as Markdown was only characterised by an informal [specification](https://en.wikipedia.org/wiki/Specification_\(technical_standard\) "Specification (technical standard)") <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-18"><span>[</span>17<span>]</span></a></sup> and a [Perl](https://en.wikipedia.org/wiki/Perl "Perl") implementation for conversion to HTML.

At the same time, a number of ambiguities in the informal specification had attracted attention.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-gfm_on_github-why_spec-19"><span>[</span>18<span>]</span></a></sup> These issues spurred the creation of tools such as Babelmark <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-babelmark-2-20"><span>[</span>19<span>]</span></a></sup> <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-babelmark-3-21"><span>[</span>20<span>]</span></a></sup> to compare the output of various implementations,<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-22"><span>[</span>21<span>]</span></a></sup> and an effort by some developers of Markdown [parsers](https://en.wikipedia.org/wiki/Parsing "Parsing") for standardization. However, Gruber has argued that complete standardization would be a mistake: "Different sites (and people) have different needs. No one syntax would make all happy." <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-23"><span>[</span>22<span>]</span></a></sup>

Gruber avoided using curly braces in Markdown to unofficially reserve them for implementation-specific extensions.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-curlyBraces-24"><span>[</span>23<span>]</span></a></sup>

## Standardization

In 2012, a group of people, including [Jeff Atwood](https://en.wikipedia.org/wiki/Jeff_Atwood "Jeff Atwood") and [John MacFarlane](https://en.wikipedia.org/wiki/John_MacFarlane_\(philosopher\) "John MacFarlane (philosopher)"), launched what Atwood characterised as a standardization effort.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-FutureOfMarkdown-12"><span>[</span>12<span>]</span></a></sup>

A community website now aims to "document various tools and resources available to document authors and developers, as well as implementors of the various Markdown implementations".<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-27"><span>[</span>26<span>]</span></a></sup>

In September 2014, Gruber objected to the usage of "Markdown" in the name of this effort and it was rebranded as "CommonMark".<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-ArsTechnica2014-13"><span>[</span>13<span>]</span></a></sup> <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-28"><span>[</span>27<span>]</span></a></sup> <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-29"><span>[</span>28<span>]</span></a></sup> CommonMark.org published several versions of a specification, reference implementation, test suite, and "\[plans\] to announce a finalized 1.0 spec and test suite in 2019".<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-commonmark.org-30"><span>[</span>29<span>]</span></a></sup>

The finalized 1.0 spec has not been released, as major issues still remain unsolved.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-31"><span>[</span>30<span>]</span></a></sup>

Nonetheless, the following websites and projects have adopted CommonMark: [Codeberg](https://en.wikipedia.org/wiki/Codeberg "Codeberg"), [Discourse](https://en.wikipedia.org/wiki/Discourse_\(software\) "Discourse (software)"), [GitHub](https://en.wikipedia.org/wiki/GitHub "GitHub"), [GitLab](https://en.wikipedia.org/wiki/GitLab "GitLab"), [Reddit](https://en.wikipedia.org/wiki/Reddit "Reddit"), [Qt](https://en.wikipedia.org/wiki/Qt_\(software\) "Qt (software)"), [Stack Exchange](https://en.wikipedia.org/wiki/Stack_Exchange "Stack Exchange") ([Stack Overflow](https://en.wikipedia.org/wiki/Stack_Overflow "Stack Overflow")), and [Swift](https://en.wikipedia.org/wiki/Swift_\(programming_language\) "Swift (programming language)").

In March 2016, two relevant informational Internet [RFCs](https://en.wikipedia.org/wiki/Request_for_Comments "Request for Comments") were published:

- RFC [7763](https://www.rfc-editor.org/rfc/rfc7763) –" The text/markdown Media Type," <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-rfc7763-2"><span>[</span>2<span>]</span></a></sup> *Informational.*
	Introduces [MIME](https://en.wikipedia.org/wiki/MIME "MIME") type `text/markdown`.
- RFC [7764](https://www.rfc-editor.org/rfc/rfc7764) –" Guidance on Markdown: Design Philosophies, Stability Strategies, and Select Registrations," <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-rfc7764-7"><span>[</span>7<span>]</span></a></sup> *Informational.*

## Variants

Websites like [Bitbucket](https://en.wikipedia.org/wiki/Bitbucket "Bitbucket"), [Diaspora](https://en.wikipedia.org/wiki/Diaspora_\(social_network\) "Diaspora (social network)"), [Discord](https://en.wikipedia.org/wiki/Discord "Discord"),<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-33"><span>[</span>32<span>]</span></a></sup> [GitHub](https://en.wikipedia.org/wiki/Markdown#GFM),<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-gfm_on_github-34"><span>[</span>33<span>]</span></a></sup> [OpenStreetMap](https://en.wikipedia.org/wiki/OpenStreetMap "OpenStreetMap"), [Reddit](https://en.wikipedia.org/wiki/Reddit "Reddit"),<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-35"><span>[</span>34<span>]</span></a></sup> [SourceForge](https://en.wikipedia.org/wiki/SourceForge "SourceForge") <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-36"><span>[</span>35<span>]</span></a></sup> and [Stack Exchange](https://en.wikipedia.org/wiki/Stack_Exchange "Stack Exchange") <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-37"><span>[</span>36<span>]</span></a></sup> use variants of Markdown to make discussions between users easier.

Depending on implementation, basic inline [HTML tags](https://en.wikipedia.org/wiki/HTML_tag "HTML tag") may be supported.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-38"><span>[</span>37<span>]</span></a></sup>

Italic text may be implemented by `_underscores_` or `*single-asterisks*`.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-italic-39"><span>[</span>38<span>]</span></a></sup>

[GitHub](https://en.wikipedia.org/wiki/GitHub "GitHub") had been using its own variant of Markdown since as early as 2009,<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-40"><span>[</span>39<span>]</span></a></sup> which added support for additional formatting such as tables and nesting [block content](https://en.wikipedia.org/wiki/HTML_element#Block_elements "HTML element") inside list elements, as well as GitHub-specific features such as auto-linking references to commits, issues, usernames, etc.

In 2017, GitHub released a formal specification of its [GitHub Flavored Markdown](https://github.github.com/gfm/) (GFM) that is based on [CommonMark](https://en.wikipedia.org/wiki/CommonMark "CommonMark").<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-gfm_on_github-34"><span>[</span>33<span>]</span></a></sup> It is a [strict superset](https://en.wikipedia.org/wiki/Superset "Superset") of CommonMark, following its specification exactly except for tables, [strikethrough](https://en.wikipedia.org/wiki/Strikethrough "Strikethrough"), [autolinks](https://en.wikipedia.org/wiki/Automatic_hyperlinking "Automatic hyperlinking") and task lists, which GFM adds as extensions.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-41"><span>[</span>40<span>]</span></a></sup>

Accordingly, GitHub also changed the parser used on their sites, which required that some documents be changed. For instance, GFM now requires that the [hash symbol](https://en.wikipedia.org/wiki/Number_sign "Number sign") that creates a heading be separated from the heading text by a space character.

### Markdown Extra

Markdown Extra is a [lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language "Lightweight markup language") based on Markdown implemented in [PHP](https://en.wikipedia.org/wiki/PHP "PHP") (originally), [Python](https://en.wikipedia.org/wiki/Python_\(programming_language\) "Python (programming language)") and [Ruby](https://en.wikipedia.org/wiki/Ruby_\(programming_language\) "Ruby (programming language)").<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-fortin-2018-42"><span>[</span>41<span>]</span></a></sup> It adds the following features that are not available with regular Markdown:

- Markdown markup inside [HTML](https://en.wikipedia.org/wiki/HTML "HTML") blocks
- Elements with id/class attribute
- "Fenced code blocks" that span multiple lines of code
- Tables <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-43"><span>[</span>42<span>]</span></a></sup>
- Definition lists
- Footnotes
- Abbreviations

Markdown Extra is supported in some [content management systems](https://en.wikipedia.org/wiki/Content_management_system "Content management system") such as [Drupal](https://en.wikipedia.org/wiki/Drupal "Drupal"),<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-44"><span>[</span>43<span>]</span></a></sup> [Grav (CMS)](https://en.wikipedia.org/wiki/Grav_\(CMS\) "Grav (CMS)"), [Textpattern CMS](https://en.wikipedia.org/wiki/Textpattern "Textpattern") <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-45"><span>[</span>44<span>]</span></a></sup> and [TYPO3](https://en.wikipedia.org/wiki/TYPO3 "TYPO3").<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-46"><span>[</span>45<span>]</span></a></sup>

## Examples

Text using Markdown syntax

Corresponding HTML produced by a Markdown processor

Text viewed in a browser

```
Heading
=======

Sub-heading
-----------

# Alternative heading

## Alternative sub-heading

Paragraphs are separated 
by a blank line.

Two spaces at the end of a line  
produce a line break.
```

```
<h1>Heading</h1>

<h2>Sub-heading</h2>

<h1>Alternative heading</h1>

<h2>Alternative sub-heading</h2>

<p>Paragraphs are separated
by a blank line.</p>

<p>Two spaces at the end of a line<br />
produce a line break.</p>
```

Heading

Sub-heading

Alternative heading

Alternative sub-heading

Paragraphs are separated by a blank line.

Two spaces at the end of a line  
produce a line break.

```
Text attributes _italic_, **bold**, \`monospace\`.

Horizontal rule:

---
```

```
<p>Text attributes <em>italic</em>, <strong>bold</strong>, <code>monospace</code>.</p>

<p>Horizontal rule:</p>

<hr />
```

Text attributes *italic*, **bold**, `monospace`.

Horizontal rule:

---

```
Bullet lists nested within numbered list:

  1. fruits
     * apple
     * banana
  2. vegetables
     - carrot
     - broccoli
```

```
<p>Bullet lists nested within numbered list:</p>

<ol>
  <li>fruits <ul>
      <li>apple</li>
      <li>banana</li>
  </ul></li>
  <li>vegetables <ul>
      <li>carrot</li>
      <li>broccoli</li>
  </ul></li>
</ol>
```

Bullet lists nested within numbered list:
1. fruits
	- apple
	- banana
2. vegetables
	- carrot
	- broccoli

```
A [link](http://example.com).

![Image](Icon-pictures.png "icon")

> Markdown uses email-style
characters for blockquoting.
>
> Multiple paragraphs need to be prepended individually.

Most inline <abbr title="Hypertext Markup Language">HTML</abbr> tags are supported.
```

```
<p>A <a href="http://example.com">link</a>.</p>

<p><img alt="Image" title="icon" src="Icon-pictures.png" /></p>

<blockquote>
<p>Markdown uses email-style characters for blockquoting.</p>
<p>Multiple paragraphs need to be prepended individually.</p>
</blockquote>

<p>Most inline <abbr title="Hypertext Markup Language">HTML</abbr> tags are supported.</p>
```

A [link](http://example.com/).

![Image](https://upload.wikimedia.org/wikipedia/commons/5/5c/Icon-pictures.png)

> Markdown uses email-style characters for blockquoting.
> 
> Multiple paragraphs need to be prepended individually.

Most inline HTML tags are supported.

## Implementations

Implementations of Markdown are available for over a dozen [programming languages](https://en.wikipedia.org/wiki/Programming_language "Programming language"); in addition, many [applications](https://en.wikipedia.org/wiki/Application_software "Application software"), platforms and [frameworks](https://en.wikipedia.org/wiki/Software_framework "Software framework") support Markdown.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-47"><span>[</span>46<span>]</span></a></sup> For example, Markdown [plugins](https://en.wikipedia.org/wiki/Plug-in_\(computing\) "Plug-in (computing)") exist for every major [blogging](https://en.wikipedia.org/wiki/Blog "Blog") platform.<sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-ArsTechnica2014-13"><span>[</span>13<span>]</span></a></sup>

While Markdown is a minimal markup language and is read and edited with a normal [text editor](https://en.wikipedia.org/wiki/Text_editor "Text editor"), there are specially designed editors that preview the files with styles, which are available for all major platforms. Many general-purpose text and [code editors](https://en.wikipedia.org/wiki/Source-code_editor "Source-code editor") have [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting "Syntax highlighting") plugins for Markdown built into them or available as optional download. Editors may feature a side-by-side preview window or render the code directly in a [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG "WYSIWYG") fashion.

## See also

- [Comparison of document markup languages](https://en.wikipedia.org/wiki/Comparison_of_document_markup_languages "Comparison of document markup languages")
- [Comparison of documentation generators](https://en.wikipedia.org/wiki/Comparison_of_documentation_generators "Comparison of documentation generators")
- [Comparison of wiki software](https://en.wikipedia.org/wiki/Comparison_of_wiki_software "Comparison of wiki software")
- [Lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language "Lightweight markup language")
- [List of markup languages](https://en.wikipedia.org/wiki/List_of_markup_languages "List of markup languages")
- [List of text editors](https://en.wikipedia.org/wiki/List_of_text_editors "List of text editors")
- [Wiki markup](https://en.wikipedia.org/wiki/Wiki_markup "Wiki markup")

## Explanatory notes

## References

## External links

- [Official website](https://daringfireball.net/projects/markdown/) for original John Gruber markup

[^1]: Technically HTML description lists

[^2]: Gruber, John (8 January 2014). ["The Markdown File Extension"](https://daringfireball.net/linked/2014/01/08/markdown-extension). The Daring Fireball Company, LLC. [Archived](https://web.archive.org/web/20200712120733/https://daringfireball.net/linked/2014/01/08/markdown-extension) from the original on 12 July 2020. Retrieved 27 March 2022. Too late now, I suppose, but the only file extension I would endorse is ".markdown", for the same reason offered by Hilton Lipschitz: *We no longer live in a 8.3 world, so we should be using the most descriptive file extensions. It's sad that all our operating systems rely on this stupid convention instead of the better creator code or a metadata model, but great that they now support longer file extensions.*

[^3]: S. Leonard (March 2016). [*The text/markdown Media Type*](https://www.rfc-editor.org/rfc/rfc7763). [Internet Engineering Task Force](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force "Internet Engineering Task Force"). [doi](https://en.wikipedia.org/wiki/Doi_\(identifier\) "Doi (identifier)"):[10.17487/RFC7763](https://doi.org/10.17487%2FRFC7763). [ISSN](https://en.wikipedia.org/wiki/ISSN_\(identifier\) "ISSN (identifier)") [2070-1721](https://search.worldcat.org/issn/2070-1721). [RFC](https://en.wikipedia.org/wiki/Request_for_Comments "Request for Comments") [7763](https://datatracker.ietf.org/doc/html/rfc7763). *Informational.*

[^4]: [Swartz, Aaron](https://en.wikipedia.org/wiki/Aaron_Swartz "Aaron Swartz") (2004-03-19). ["Markdown"](http://www.aaronsw.com/weblog/001189). *Aaron Swartz: The Weblog*. [Archived](https://web.archive.org/web/20171224200232/http://www.aaronsw.com/weblog/001189) from the original on 2017-12-24. Retrieved 2013-09-01.

[^5]: [Gruber, John](https://en.wikipedia.org/wiki/John_Gruber "John Gruber"). ["Markdown"](https://web.archive.org/web/20040311230924/https://daringfireball.net/projects/markdown/index.text). *[Daring Fireball](https://en.wikipedia.org/wiki/Daring_Fireball "Daring Fireball")*. Archived from [the original](http://daringfireball.net/projects/markdown/index.text) on 2004-03-11. Retrieved 2022-08-20.

[^6]: Markdown 1.0.1 readme source code ["Daring Fireball – Markdown"](https://web.archive.org/web/20040402182332/http://daringfireball.net/projects/markdown/). 2004-12-17. Archived from [the original](http://daringfireball.net/projects/markdown/) on 2004-04-02.

[^7]: S. Leonard (March 2016). [*Guidance on Markdown: Design Philosophies, Stability Strategies, and Select Registrations*](https://www.rfc-editor.org/rfc/rfc7764). [Internet Engineering Task Force](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force "Internet Engineering Task Force"). [doi](https://en.wikipedia.org/wiki/Doi_\(identifier\) "Doi (identifier)"):[10.17487/RFC7764](https://doi.org/10.17487%2FRFC7764). [ISSN](https://en.wikipedia.org/wiki/ISSN_\(identifier\) "ISSN (identifier)") [2070-1721](https://search.worldcat.org/issn/2070-1721). [RFC](https://en.wikipedia.org/wiki/Request_for_Comments "Request for Comments") [7764](https://datatracker.ietf.org/doc/html/rfc7764). *Informational.*

[^8]: ["RMarkdown Reference site"](https://rmarkdown.rstudio.com/). [Archived](https://web.archive.org/web/20200303054734/https://rmarkdown.rstudio.com/) from the original on 2020-03-03. Retrieved 2019-11-21.

[^9]: Markdown Syntax ["Daring Fireball – Markdown – Syntax"](http://daringfireball.net/projects/markdown/syntax#philosophy). 2013-06-13. "Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions. While Markdown's syntax has been influenced by several existing text-to-HTML filters — including Setext, atx, Textile, reStructuredText, Grutatext <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-grutatext-15"><span>[</span>15<span>]</span></a></sup>, and EtText <sup><a href="https://en.wikipedia.org/wiki/Markdown#cite_note-ettext-16"><span>[</span>16<span>]</span></a></sup> — the single biggest source of inspiration for Markdown's syntax is the format of plain text email."

[^10]: Dillet, Romain (6 March 2025). ["Mistral adds a new API that turns any PDF document into an AI-ready Markdown file"](https://techcrunch.com/2025/03/06/mistrals-new-ocr-api-turns-any-pdf-document-into-an-ai-ready-markdown-file/). *TechCrunch*. Retrieved 7 September 2025.

[^11]: ["Daring Fireball: Introducing Markdown"](https://daringfireball.net/2004/03/introducing_markdown). *daringfireball.net*. [Archived](https://web.archive.org/web/20200920182442/https://daringfireball.net/2004/03/introducing_markdown) from the original on 2020-09-20. Retrieved 2020-09-23.

[^12]: Atwood, Jeff (2012-10-25). ["The Future of Markdown"](https://web.archive.org/web/20140211233513/http://www.codinghorror.com/blog/2012/10/the-future-of-markdown.html). CodingHorror.com. Archived from [the original](http://www.codinghorror.com/blog/2012/10/the-future-of-markdown.html) on 2014-02-11. Retrieved 2014-04-25.

[^13]: Gilbertson, Scott (October 5, 2014). ["Markdown throwdown: What happens when FOSS software gets corporate backing?"](https://arstechnica.com/information-technology/2014/10/markdown-throwdown-what-happens-when-foss-software-gets-corporate-backing/). *[Ars Technica](https://en.wikipedia.org/wiki/Ars_Technica "Ars Technica")*. [Archived](https://web.archive.org/web/20201114231130/https://arstechnica.com/information-technology/2014/10/markdown-throwdown-what-happens-when-foss-software-gets-corporate-backing/) from the original on November 14, 2020. Retrieved June 14, 2017. [CommonMark](https://en.wikipedia.org/wiki/CommonMark "CommonMark") fork could end up better for users... but original creators seem to disagree.

[^14]: @gruber (June 12, 2016). ["I should write about it, but it's painful. More or less: Aaron was my sounding board, my muse"](https://x.com/gruber/status/741989829173510145) ([Tweet](https://en.wikipedia.org/wiki/Tweet_\(social_media\) "Tweet (social media)")) – via [Twitter](https://en.wikipedia.org/wiki/Twitter "Twitter").

[^15]: ["Un naufragio personal: The Grutatxt markup"](https://web.archive.org/web/20220630230546/https://triptico.com/docs/grutatxt_markup.html). *triptico.com*. Archived from [the original](https://triptico.com/docs/grutatxt_markup.html) on 2022-06-30. Retrieved 2022-06-30.

[^16]: ["EtText: Documentation: Using EtText"](http://ettext.taint.org/doc/ettext.html). *ettext.taint.org*. Retrieved 2022-06-30.

[^17]: ["Markdown Syntax Documentation"](https://daringfireball.net/projects/markdown/syntax). Daring Fireball. [Archived](https://web.archive.org/web/20190909051956/https://daringfireball.net/projects/markdown/syntax) from the original on 2019-09-09. Retrieved 2018-03-09.

[^18]: ["GitHub Flavored Markdown Spec – Why is a spec needed?"](https://github.github.com/gfm/#why-is-a-spec-needed-). *github.github.com*. [Archived](https://web.archive.org/web/20200203204734/https://github.github.com/gfm/#why-is-a-spec-needed-) from the original on 2020-02-03. Retrieved 2018-05-17.

[^19]: ["Babelmark 2 – Compare markdown implementations"](http://johnmacfarlane.net/babelmark2/). Johnmacfarlane.net. [Archived](https://web.archive.org/web/20170718113552/http://johnmacfarlane.net/babelmark2/) from the original on 2017-07-18. Retrieved 2014-04-25.

[^20]: ["Babelmark 3 – Compare Markdown Implementations"](https://babelmark.github.io/). github.io. [Archived](https://web.archive.org/web/20201112043521/https://babelmark.github.io/) from the original on 2020-11-12. Retrieved 2017-12-10.

[^21]: ["Babelmark 2 – FAQ"](http://johnmacfarlane.net/babelmark2/faq.html). Johnmacfarlane.net. [Archived](https://web.archive.org/web/20170728115918/http://johnmacfarlane.net/babelmark2/faq.html) from the original on 2017-07-28. Retrieved 2014-04-25.

[^22]: [Gruber, John \[@gruber\]](https://en.wikipedia.org/wiki/John_Gruber "John Gruber") (4 September 2014). ["@tobie @espadrine @comex @wycats Because different sites (and people) have different needs. No one syntax would make all happy"](https://x.com/gruber/status/507670720886091776) ([Tweet](https://en.wikipedia.org/wiki/Tweet_\(social_media\) "Tweet (social media)")) – via [Twitter](https://en.wikipedia.org/wiki/Twitter "Twitter").

[^23]: Gruber, John (19 May 2022). ["Markdoc"](https://daringfireball.net/linked/2022/05/19/markdoc). *Daring Fireball*. [Archived](https://web.archive.org/web/20220519202920/https://daringfireball.net/linked/2022/05/19/markdoc) from the original on 19 May 2022. Retrieved May 19, 2022. I love their syntax extensions — very true to the spirit of Markdown. They use curly braces for their extensions; I'm not sure I ever made this clear, publicly, but I avoided using curly braces in Markdown itself — even though they are very tempting characters — to unofficially reserve them for implementation-specific extensions. Markdoc's extensive use of curly braces for its syntax is exactly the sort of thing I was thinking about.

[^24]: ["UTI of a CommonMark document"](https://talk.commonmark.org/t/uti-of-a-commonmark-document/2406). 12 April 2017. [Archived](https://web.archive.org/web/20181122140119/https://talk.commonmark.org/t/uti-of-a-commonmark-document/2406) from the original on 22 November 2018. Retrieved 29 September 2017.

[^25]: ["CommonMark specification"](http://spec.commonmark.org/). [Archived](https://web.archive.org/web/20170807052756/http://spec.commonmark.org/) from the original on 2017-08-07. Retrieved 2017-07-26.

[^26]: ["Markdown Community Page"](https://markdown.github.io/). GitHub. [Archived](https://web.archive.org/web/20201026161924/http://markdown.github.io/) from the original on 2020-10-26. Retrieved 2014-04-25.

[^27]: ["Standard Markdown is now Common Markdown"](http://blog.codinghorror.com/standard-markdown-is-now-common-markdown/). Jeff Atwood. 4 September 2014. [Archived](https://web.archive.org/web/20141009181014/http://blog.codinghorror.com/standard-markdown-is-now-common-markdown/) from the original on 2014-10-09. Retrieved 2014-10-07.

[^28]: ["Standard Markdown Becomes Common Markdown then CommonMark"](http://www.infoq.com/news/2014/09/markdown-commonmark). *InfoQ*. [Archived](https://web.archive.org/web/20200930150521/https://www.infoq.com/news/2014/09/markdown-commonmark/) from the original on 2020-09-30. Retrieved 2014-10-07.

[^29]: ["CommonMark"](http://commonmark.org/). [Archived](https://web.archive.org/web/20160412211434/http://commonmark.org/) from the original on 12 April 2016. Retrieved 20 Jun 2018. The current version of the CommonMark spec is complete, and quite robust after a year of public feedback … but not quite final. With your help, we plan to announce a finalized 1.0 spec and test suite in 2019.

[^30]: ["Issues we MUST resolve before 1.0 release \[6 remaining\]"](https://talk.commonmark.org/t/issues-we-must-resolve-before-1-0-release-6-remaining/1287). *CommonMark Discussion*. 2015-07-26. [Archived](https://web.archive.org/web/20210414032229/https://talk.commonmark.org/t/issues-we-must-resolve-before-1-0-release-6-remaining/1287) from the original on 2021-04-14. Retrieved 2020-10-02.

[^31]: ["Markdown Variants"](https://www.iana.org/assignments/markdown-variants/markdown-variants.xhtml). [IANA](https://en.wikipedia.org/wiki/Internet_Assigned_Numbers_Authority "Internet Assigned Numbers Authority"). 2016-03-28. [Archived](https://web.archive.org/web/20201027005128/https://www.iana.org/assignments/markdown-variants/markdown-variants.xhtml) from the original on 2020-10-27. Retrieved 2016-07-06.

[^32]: ["Markdown Text 101 (Chat Formatting: Bold, Italic, Underline)"](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline). *Discord*. 2024-10-03. Retrieved 2025-02-07.

[^33]: ["GitHub Flavored Markdown Spec"](https://github.github.com/gfm/). GitHub. [Archived](https://web.archive.org/web/20200203204734/https://github.github.com/gfm/) from the original on 2020-02-03. Retrieved 2020-06-11.

[^34]: ["Reddit markdown primer. Or, how do you do all that fancy formatting in your comments, anyway?"](https://www.reddit.com/r/reddit.com/comments/6ewgt/reddit_markdown_primer_or_how_do_you_do_all_that/). Reddit. [Archived](https://web.archive.org/web/20190611185827/https://www.reddit.com/r/reddit.com/comments/6ewgt/reddit_markdown_primer_or_how_do_you_do_all_that/) from the original on 2019-06-11. Retrieved 2013-03-29.

[^35]: ["SourceForge: Markdown Syntax Guide"](https://sourceforge.net/p/forge/documentation/markdown_syntax/). [SourceForge](https://en.wikipedia.org/wiki/SourceForge "SourceForge"). [Archived](https://web.archive.org/web/20190613130356/https://sourceforge.net/p/forge/documentation/markdown_syntax/) from the original on 2019-06-13. Retrieved 2013-05-10.

[^36]: ["Markdown Editing Help"](https://stackoverflow.com/editing-help). StackOverflow.com. [Archived](https://web.archive.org/web/20140328061854/http://stackoverflow.com/editing-help) from the original on 2014-03-28. Retrieved 2014-04-11.

[^37]: ["Markdown Syntax Documentation"](https://daringfireball.net/projects/markdown/syntax#html). *daringfireball.net*. [Archived](https://web.archive.org/web/20190909051956/https://daringfireball.net/projects/markdown/syntax#html) from the original on 2019-09-09. Retrieved 2021-03-01.

[^38]: ["Basic Syntax: Italic"](https://www.markdownguide.org/basic-syntax/#italic). *The Markdown Guide*. Matt Cone. [Archived](https://web.archive.org/web/20220326234942/https://www.markdownguide.org/basic-syntax/#italic) from the original on 26 March 2022. Retrieved 27 March 2022. To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

[^39]: [Tom Preston-Werner](https://en.wikipedia.org/wiki/Tom_Preston-Werner "Tom Preston-Werner"). ["GitHub Flavored Markdown Examples"](https://github.com/mojombo/github-flavored-markdown/issues/1). *GitHub*. [Archived](https://web.archive.org/web/20210513154115/https://github.com/mojombo/github-flavored-markdown/issues/1) from the original on 2021-05-13. Retrieved 2021-04-02.

[^40]: ["A formal spec for GitHub Flavored Markdown"](https://githubengineering.com/a-formal-spec-for-github-markdown/). *GitHub Engineering*. 14 March 2017. [Archived](https://web.archive.org/web/20200203205138/https://githubengineering.com/a-formal-spec-for-github-markdown/) from the original on 3 February 2020. Retrieved 16 Mar 2017.

[^41]: Fortin, Michel (2018). ["PHP Markdown Extra"](https://michelf.ca/projects/php-markdown/extra). *Michel Fortin website*. [Archived](https://web.archive.org/web/20210117015819/https://michelf.ca/projects/php-markdown/extra/) from the original on 2021-01-17. Retrieved 2018-12-26.

[^42]: ["PHP Markdown Extra"](https://michelf.ca/projects/php-markdown/extra). *Michel Fortin*. [Archived](https://web.archive.org/web/20210117015819/https://michelf.ca/projects/php-markdown/extra/) from the original on 2021-01-17. Retrieved 2018-12-26.

[^43]: ["Markdown editor for BUEditor"](https://drupal.org/project/markdowneditor). 4 December 2008. [Archived](https://web.archive.org/web/20200917172201/https://www.drupal.org/project/markdowneditor) from the original on 17 September 2020. Retrieved 15 January 2017.

[^44]: ["Plugin: wet\_textfilter\_markdown"](https://plugins.textpattern.com/plugins/wet_textfilter_markdown). *Textpattern CMS plugins*. 2025-04-27.

[^45]: ["Markdown for TYPO3 (markdown\_content)"](https://extensions.typo3.org/extension/markdown_content/). *extensions.typo3.org*. [Archived](https://web.archive.org/web/20210201205749/https://extensions.typo3.org/extension/markdown_content/) from the original on 2021-02-01. Retrieved 2019-02-06.

[^46]: ["W3C Community Page of Markdown Implementations"](https://www.w3.org/community/markdown/wiki/MarkdownImplementations). *W3C Markdown Wiki*. [Archived](https://web.archive.org/web/20200917231621/https://www.w3.org/community/markdown/wiki/MarkdownImplementations) from the original on 17 September 2020. Retrieved 24 March 2016.