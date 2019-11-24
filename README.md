# visual-studio-code-configuration-js-web-app
Simple Configration for setting file in vsCode for Js and HTML files
just go to file--> Preferences > Settings.
Past this:

```
{
  "window.zoomLevel": 0,
  "prettier.printWidth": 100,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "all",
  "html.format.enable": true,
  "files.autoSave": "onWindowChange",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": true
  },
  "atomKeymap.promptV3Features": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": true,
  // Maximum amount of characters per line (0 = disable).
  "html.format.wrapLineLength": 120,
  // List of tags, comma separated, that shouldn't be reformatted. 'null' defaults to all tags listed at https://www.w3.org/TR/html5/dom.html#phrasing-content.
  "html.format.unformatted": "a, abbr, acronym, b, bdo, big, br, button, cite, code, dfn, em, i, img, input, kbd, label, map, object, q, samp, select, small, span, strong, sub, sup, textarea, tt, var",
  // List of tags, comma separated, where the content shouldn't be reformatted. 'null' defaults to the 'pre' tag.
  "html.format.contentUnformatted": "pre",
  // Indent <head> and <body> sections.
  "html.format.indentInnerHtml": true,
  // Whether existing line breaks before elements should be preserved. Only works before elements, not inside tags or for text.
  "html.format.preserveNewLines": true,
  // Maximum number of line breaks to be preserved in one chunk. Use 'null' for unlimited.
  "html.format.maxPreserveNewLines": null,
  // Format and indent {{#foo}} and {{/foo}}.
  "html.format.indentHandlebars": true,
  // End with a newline.
  "html.format.endWithNewline": true,
  // List of tags, comma separated, that should have an extra newline before them. 'null' defaults to "head, body, /html".
  "html.format.extraLiners": "head, body, /html",
  // Wrap attributes.
  "html.format.wrapAttributes": "auto",
  // Configures if the built-in HTML language support suggests Angular V1 tags and properties.
  "html.suggest.angular1": true,
  // Configures if the built-in HTML language support suggests Ionic tags, properties and values.
  "html.suggest.ionic": true,
  // Configures if the built-in HTML language support suggests HTML5 tags, properties and values.
  "html.suggest.html5": true,
  // Configures if the built-in HTML language support validates embedded scripts.
  "html.validate.scripts": true,
  // Configures if the built-in HTML language support validates embedded styles.
  "html.validate.styles": true,
  // Traces the communication between VS Code and the HTML language server.
  "html.trace.server": "off",
}
```
