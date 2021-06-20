- 👋 Hi, I’m @CindyPuff
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
CindyPuff/CindyPuff is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
=============

This demonstrates [turndown](https://github.com/domchristie/turndown) – an HTML to Markdown converter in JavaScript.

Usage
-----

    var turndownService = new TurndownService()
    console.log(
      turndownService.turndown('<h1>Hello world</h1>')
    )

* * *

It aims to be [CommonMark](http://commonmark.org/) compliant, and includes options to style the output. These options include:

*   headingStyle (setext or atx)
*   horizontalRule (\*, -, or \_)
*   bullet (\*, -, or +)
*   codeBlockStyle (indented or fenced)
*   fence (\` or ~)
*   emDelimiter (\_ or \*)
*   strongDelimiter (\*\* or \_\_)
*   linkStyle (inlined or referenced)
*   linkReferenceStyle (full, collapsed, or shortcut)
