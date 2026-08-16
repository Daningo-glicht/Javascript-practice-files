# Javascript-mini-project
XML Book Catalog Transformer

A single-page HTML/JS tool that lets users upload an XML file and a matching XSL stylesheet in the browser, then applies an XSLT transformation client-side to render the result directly on the page.

Features:
Upload an XML data file and an XSL stylesheet via simple file inputs
Client-side XSLT transformation using the browser's built-in XSLTProcessor
Instant preview of the transformed output — no server or build step required
Clean, minimal UI with basic styling

Usage:
Open index.html in a browser
Upload your .xml file
Upload your .xsl stylesheet
Click Transform and View to render the result

Tech stack: Vanilla HTML, CSS, and JavaScript (DOMParser, XSLTProcessor) — no dependencies.

Note: Since XSLTProcessor is a legacy browser API, this works best in Firefox/Chrome-based browsers with continued support; behavior may vary across browsers.
