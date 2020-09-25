### Hi there 👋
<!DOCTYPE html>
    <html>
    <head>
        <meta charset="UTF-8">
        <title>Ingeniería en sistemas computaciones, Tecnologías de la información y comunicación, e Informática</title
        <style>
/* From extension bierner.markdown-checkbox */
.contains-task-list {
    padding-left: 0;
}

.contains-task-list li {
    margin-left: 24px;
}

.contains-task-list .task-list-item {
    list-style: none;
    padding-left: 0;
    margin-left: 0;
}

.contains-task-list .contains-task-list {
    padding-left: 20px;
} 
/* From extension bierner.markdown-preview-github-styles */
body {
    background: white;
}

.vscode-body {
    box-sizing: border-box;
    min-width: 200px;
    max-width: 980px;
    margin: 0 auto;
    padding: 40px;
    border: 1px solid transparent;
}

.vscode-body blockquote {
    background-color: initial;
}

.vscode-body pre {
    color: initial;
    background: #f7f7f7 !important;
}

.vscode-body code {
    color: inherit;
}

.vscode-body pre code {
    color: initial;
}

.vscode-body code > div {
    background: none
}

.vscode-body table th,
.vscode-body table td {
    border: 1px solid #ddd !important;
}

.vscode-body.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(0, 0, 0, 0.15);
}

.vscode-body.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(0, 0, 0, 0.40);
}

.vscode-body.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-body p,
.vscode-body blockquote,
.vscode-body ul,
.vscode-body ol,
.vscode-body dl,
.vscode-body table,
.vscode-body pre {
  margin-top: 16px;
  margin-bottom: 16px;
}

body.vscode-body::-webkit-scrollbar {
    background-color: white;
}
body.vscode-body::-webkit-scrollbar-thumb {
    background-color: rgba(100, 100, 100, 0.4);
}
body.vscode-body::-webkit-scrollbar-thumb:hover {
    background-color: rgba(100, 100, 100, 0.7);
}

/* Generated from 'node_modules/github-markdown-css/github-markdown.css' */
@font-face {
  font-family: octicons-link;
  src: url(data:font/woff;charset=utf-8;base64,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) format('woff');
}

.vscode-body {
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  line-height: 1.5;
  color: #24292e;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 16px;
  line-height: 1.5;
  word-wrap: break-word;
}

.vscode-body .pl-c {
  color: #6a737d;
}

.vscode-body .pl-c1,
.vscode-body .pl-s .pl-v {
  color: #005cc5;
}

.vscode-body .pl-e,
.vscode-body .pl-en {
  color: #6f42c1;
}

.vscode-body .pl-smi,
.vscode-body .pl-s .pl-s1 {
  color: #24292e;
}

.vscode-body .pl-ent {
  color: #22863a;
}

.vscode-body .pl-k {
  color: #d73a49;
}

.vscode-body .pl-s,
.vscode-body .pl-pds,
.vscode-body .pl-s .pl-pse .pl-s1,
.vscode-body .pl-sr,
.vscode-body .pl-sr .pl-cce,
.vscode-body .pl-sr .pl-sre,
.vscode-body .pl-sr .pl-sra {
  color: #032f62;
}

.vscode-body .pl-v,
.vscode-body .pl-smw {
  color: #e36209;
}

.vscode-body .pl-bu {
  color: #b31d28;
}

.vscode-body .pl-ii {
  color: #fafbfc;
  background-color: #b31d28;
}

.vscode-body .pl-c2 {
  color: #fafbfc;
  background-color: #d73a49;
}

.vscode-body .pl-c2::before {
  content: "^M";
}

.vscode-body .pl-sr .pl-cce {
  font-weight: bold;
  color: #22863a;
}

.vscode-body .pl-ml {
  color: #735c0f;
}

.vscode-body .pl-mh,
.vscode-body .pl-mh .pl-en,
.vscode-body .pl-ms {
  font-weight: bold;
  color: #005cc5;
}

.vscode-body .pl-mi {
  font-style: italic;
  color: #24292e;
}

.vscode-body .pl-mb {
  font-weight: bold;
  color: #24292e;
}

.vscode-body .pl-md {
  color: #b31d28;
  background-color: #ffeef0;
}

.vscode-body .pl-mi1 {
  color: #22863a;
  background-color: #f0fff4;
}

.vscode-body .pl-mc {
  color: #e36209;
  background-color: #ffebda;
}

.vscode-body .pl-mi2 {
  color: #f6f8fa;
  background-color: #005cc5;
}

.vscode-body .pl-mdr {
  font-weight: bold;
  color: #6f42c1;
}

.vscode-body .pl-ba {
  color: #586069;
}

.vscode-body .pl-sg {
  color: #959da5;
}

.vscode-body .pl-corl {
  text-decoration: underline;
  color: #032f62;
}

.vscode-body .octicon {
  display: inline-block;
  vertical-align: text-top;
  fill: currentColor;
}

.vscode-body a {
  background-color: transparent;
}

.vscode-body a:active,
.vscode-body a:hover {
  outline-width: 0;
}

.vscode-body strong {
  font-weight: inherit;
}

.vscode-body strong {
  font-weight: bolder;
}

.vscode-body h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

.vscode-body img {
  border-style: none;
}

.vscode-body code,
.vscode-body kbd,
.vscode-body pre {
  font-family: monospace, monospace;
  font-size: 1em;
}

.vscode-body hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible;
}

.vscode-body input {
  font: inherit;
  margin: 0;
}

.vscode-body input {
  overflow: visible;
}

.vscode-body [type="checkbox"] {
  box-sizing: border-box;
  padding: 0;
}

.vscode-body * {
  box-sizing: border-box;
}

.vscode-body input {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

.vscode-body a {
  color: #0366d6;
  text-decoration: none;
}

.vscode-body a:hover {
  text-decoration: underline;
}

.vscode-body strong {
  font-weight: 600;
}

.vscode-body hr {
  height: 0;
  margin: 15px 0;
  overflow: hidden;
  background: transparent;
  border: 0;
  border-bottom: 1px solid #dfe2e5;
}

.vscode-body hr::before {
  display: table;
  content: "";
}

.vscode-body hr::after {
  display: table;
  clear: both;
  content: "";
}

.vscode-body table {
  border-spacing: 0;
  border-collapse: collapse;
}

.vscode-body td,
.vscode-body th {
  padding: 0;
}

.vscode-body h1,
.vscode-body h2,
.vscode-body h3,
.vscode-body h4,
.vscode-body h5,
.vscode-body h6 {
  margin-top: 0;
  margin-bottom: 0;
}

.vscode-body h1 {
  font-size: 32px;
  font-weight: 600;
}

.vscode-body h2 {
  font-size: 24px;
  font-weight: 600;
}

.vscode-body h3 {
  font-size: 20px;
  font-weight: 600;
}

.vscode-body h4 {
  font-size: 16px;
  font-weight: 600;
}

.vscode-body h5 {
  font-size: 14px;
  font-weight: 600;
}

.vscode-body h6 {
  font-size: 12px;
  font-weight: 600;
}

.vscode-body p {
  margin-top: 0;
  margin-bottom: 10px;
}

.vscode-body blockquote {
  margin: 0;
}

.vscode-body ul,
.vscode-body ol {
  padding-left: 0;
  margin-top: 0;
  margin-bottom: 0;
}

.vscode-body ol ol,
.vscode-body ul ol {
  list-style-type: lower-roman;
}

.vscode-body ul ul ol,
.vscode-body ul ol ol,
.vscode-body ol ul ol,
.vscode-body ol ol ol {
  list-style-type: lower-alpha;
}

.vscode-body dd {
  margin-left: 0;
}

.vscode-body code {
  font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
  font-size: 12px;
}

.vscode-body pre {
  margin-top: 0;
  margin-bottom: 0;
  font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
  font-size: 12px;
}

.vscode-body .octicon {
  vertical-align: text-bottom;
}

.vscode-body .pl-0 {
  padding-left: 0 !important;
}

.vscode-body .pl-1 {
  padding-left: 4px !important;
}

.vscode-body .pl-2 {
  padding-left: 8px !important;
}

.vscode-body .pl-3 {
  padding-left: 16px !important;
}

.vscode-body .pl-4 {
  padding-left: 24px !important;
}

.vscode-body .pl-5 {
  padding-left: 32px !important;
}

.vscode-body .pl-6 {
  padding-left: 40px !important;
}

.vscode-body::before {
  display: table;
  content: "";
}

.vscode-body::after {
  display: table;
  clear: both;
  content: "";
}

.vscode-body>*:first-child {
  margin-top: 0 !important;
}

.vscode-body>*:last-child {
  margin-bottom: 0 !important;
}

.vscode-body a:not([href]) {
  color: inherit;
  text-decoration: none;
}

.vscode-body .anchor {
  float: left;
  padding-right: 4px;
  margin-left: -20px;
  line-height: 1;
}

.vscode-body .anchor:focus {
  outline: none;
}

.vscode-body p,
.vscode-body blockquote,
.vscode-body ul,
.vscode-body ol,
.vscode-body dl,
.vscode-body table,
.vscode-body pre {
  margin-top: 0;
  margin-bottom: 16px;
}

.vscode-body hr {
  height: 0.25em;
  padding: 0;
  margin: 24px 0;
  background-color: #e1e4e8;
  border: 0;
}

.vscode-body blockquote {
  padding: 0 1em;
  color: #6a737d;
  border-left: 0.25em solid #dfe2e5;
}

.vscode-body blockquote>:first-child {
  margin-top: 0;
}

.vscode-body blockquote>:last-child {
  margin-bottom: 0;
}

.vscode-body kbd {
  display: inline-block;
  padding: 3px 5px;
  font-size: 11px;
  line-height: 10px;
  color: #444d56;
  vertical-align: middle;
  background-color: #fafbfc;
  border: solid 1px #c6cbd1;
  border-bottom-color: #959da5;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 #959da5;
}

.vscode-body h1,
.vscode-body h2,
.vscode-body h3,
.vscode-body h4,
.vscode-body h5,
.vscode-body h6 {
  margin-top: 24px;
  margin-bottom: 16px;
  font-weight: 600;
  line-height: 1.25;
}

.vscode-body h1 .octicon-link,
.vscode-body h2 .octicon-link,
.vscode-body h3 .octicon-link,
.vscode-body h4 .octicon-link,
.vscode-body h5 .octicon-link,
.vscode-body h6 .octicon-link {
  color: #1b1f23;
  vertical-align: middle;
  visibility: hidden;
}

.vscode-body h1:hover .anchor,
.vscode-body h2:hover .anchor,
.vscode-body h3:hover .anchor,
.vscode-body h4:hover .anchor,
.vscode-body h5:hover .anchor,
.vscode-body h6:hover .anchor {
  text-decoration: none;
}

.vscode-body h1:hover .anchor .octicon-link,
.vscode-body h2:hover .anchor .octicon-link,
.vscode-body h3:hover .anchor .octicon-link,
.vscode-body h4:hover .anchor .octicon-link,
.vscode-body h5:hover .anchor .octicon-link,
.vscode-body h6:hover .anchor .octicon-link {
  visibility: visible;
}

.vscode-body h1 {
  padding-bottom: 0.3em;
  font-size: 2em;
  border-bottom: 1px solid #eaecef;
}

.vscode-body h2 {
  padding-bottom: 0.3em;
  font-size: 1.5em;
  border-bottom: 1px solid #eaecef;
}

.vscode-body h3 {
  font-size: 1.25em;
}

.vscode-body h4 {
  font-size: 1em;
}

.vscode-body h5 {
  font-size: 0.875em;
}

.vscode-body h6 {
  font-size: 0.85em;
  color: #6a737d;
}

.vscode-body ul,
.vscode-body ol {
  padding-left: 2em;
}

.vscode-body ul ul,
.vscode-body ul ol,
.vscode-body ol ol,
.vscode-body ol ul {
  margin-top: 0;
  margin-bottom: 0;
}

.vscode-body li {
  word-wrap: break-all;
}

.vscode-body li>p {
  margin-top: 16px;
}

.vscode-body li+li {
  margin-top: 0.25em;
}

.vscode-body dl {
  padding: 0;
}

.vscode-body dl dt {
  padding: 0;
  margin-top: 16px;
  font-size: 1em;
  font-style: italic;
  font-weight: 600;
}

.vscode-body dl dd {
  padding: 0 16px;
  margin-bottom: 16px;
}

.vscode-body table {
  display: block;
  width: 100%;
  overflow: auto;
}

.vscode-body table th {
  font-weight: 600;
}

.vscode-body table th,
.vscode-body table td {
  padding: 6px 13px;
  border: 1px solid #dfe2e5;
}

.vscode-body table tr {
  background-color: #fff;
  border-top: 1px solid #c6cbd1;
}

.vscode-body table tr:nth-child(2n) {
  background-color: #f6f8fa;
}

.vscode-body img {
  max-width: 100%;
  box-sizing: content-box;
  background-color: #fff;
}

.vscode-body img[align=right] {
  padding-left: 20px;
}

.vscode-body img[align=left] {
  padding-right: 20px;
}

.vscode-body code {
  padding: 0.2em 0.4em;
  margin: 0;
  font-size: 85%;
  background-color: rgba(27,31,35,0.05);
  border-radius: 3px;
}

.vscode-body pre {
  word-wrap: normal;
}

.vscode-body pre>code {
  padding: 0;
  margin: 0;
  font-size: 100%;
  word-break: normal;
  white-space: pre;
  background: transparent;
  border: 0;
}

.vscode-body .highlight {
  margin-bottom: 16px;
}

.vscode-body .highlight pre {
  margin-bottom: 0;
  word-break: normal;
}

.vscode-body .highlight pre,
.vscode-body pre {
  padding: 16px;
  overflow: auto;
  font-size: 85%;
  line-height: 1.45;
  background-color: #f6f8fa;
  border-radius: 3px;
}

.vscode-body pre code {
  display: inline;
  max-width: auto;
  padding: 0;
  margin: 0;
  overflow: visible;
  line-height: inherit;
  word-wrap: normal;
  background-color: transparent;
  border: 0;
}

.vscode-body .full-commit .btn-outline:not(:disabled):hover {
  color: #005cc5;
  border-color: #005cc5;
}

.vscode-body kbd {
  display: inline-block;
  padding: 3px 5px;
  font: 11px "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
  line-height: 10px;
  color: #444d56;
  vertical-align: middle;
  background-color: #fafbfc;
  border: solid 1px #d1d5da;
  border-bottom-color: #c6cbd1;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 #c6cbd1;
}

.vscode-body :checked+.radio-label {
  position: relative;
  z-index: 1;
  border-color: #0366d6;
}

.vscode-body .task-list-item {
  list-style-type: none;
}

.vscode-body .task-list-item+.task-list-item {
  margin-top: 3px;
}

.vscode-body .task-list-item input {
  margin: 0 0.2em 0.25em -1.6em;
  vertical-align: middle;
}

.vscode-body hr {
  border-bottom-color: #eee;
}

/*

github.com style (c) Vasily Polovnyov <vast@whiteants.net>

*/

.hljs {
  display: block;
  overflow-x: auto;
  padding: 0.5em;
  color: #333;
  background: #f8f8f8;
}

.hljs-comment,
.hljs-quote {
  color: #998;
  font-style: italic;
}

.hljs-keyword,
.hljs-selector-tag,
.hljs-subst {
  color: #333;
  font-weight: bold;
}

.hljs-number,
.hljs-literal,
.hljs-variable,
.hljs-template-variable,
.hljs-tag .hljs-attr {
  color: #008080;
}

.hljs-string,
.hljs-doctag {
  color: #d14;
}

.hljs-title,
.hljs-section,
.hljs-selector-id {
  color: #900;
  font-weight: bold;
}

.hljs-subst {
  font-weight: normal;
}

.hljs-type,
.hljs-class .hljs-title {
  color: #458;
  font-weight: bold;
}

.hljs-tag,
.hljs-name,
.hljs-attribute {
  color: #000080;
  font-weight: normal;
}

.hljs-regexp,
.hljs-link {
  color: #009926;
}

.hljs-symbol,
.hljs-bullet {
  color: #990073;
}

.hljs-built_in,
.hljs-builtin-name {
  color: #0086b3;
}

.hljs-meta {
  color: #999;
  font-weight: bold;
}

.hljs-deletion {
  background: #fdd;
}

.hljs-addition {
  background: #dfd;
}

.hljs-emphasis {
  font-style: italic;
}

.hljs-strong {
  font-weight: bold;
}

/* From extension geeklearningio.graphviz-markdown-preview */
div.graphviz {
    margin:0;
    padding:0;
    
}

div.graphviz svg {
    margin:0;
    padding:0;
}
/* From extension goessner.mdmath */
@font-face{font-family:KaTeX_AMS;src:url(fonts/KaTeX_AMS-Regular.woff2) format("woff2"),url(fonts/KaTeX_AMS-Regular.woff) format("woff"),url(fonts/KaTeX_AMS-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Caligraphic;src:url(fonts/KaTeX_Caligraphic-Bold.woff2) format("woff2"),url(fonts/KaTeX_Caligraphic-Bold.woff) format("woff"),url(fonts/KaTeX_Caligraphic-Bold.ttf) format("truetype");font-weight:700;font-style:normal}@font-face{font-family:KaTeX_Caligraphic;src:url(fonts/KaTeX_Caligraphic-Regular.woff2) format("woff2"),url(fonts/KaTeX_Caligraphic-Regular.woff) format("woff"),url(fonts/KaTeX_Caligraphic-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Fraktur;src:url(fonts/KaTeX_Fraktur-Bold.woff2) format("woff2"),url(fonts/KaTeX_Fraktur-Bold.woff) format("woff"),url(fonts/KaTeX_Fraktur-Bold.ttf) format("truetype");font-weight:700;font-style:normal}@font-face{font-family:KaTeX_Fraktur;src:url(fonts/KaTeX_Fraktur-Regular.woff2) format("woff2"),url(fonts/KaTeX_Fraktur-Regular.woff) format("woff"),url(fonts/KaTeX_Fraktur-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Main;src:url(fonts/KaTeX_Main-Bold.woff2) format("woff2"),url(fonts/KaTeX_Main-Bold.woff) format("woff"),url(fonts/KaTeX_Main-Bold.ttf) format("truetype");font-weight:700;font-style:normal}@font-face{font-family:KaTeX_Main;src:url(fonts/KaTeX_Main-BoldItalic.woff2) format("woff2"),url(fonts/KaTeX_Main-BoldItalic.woff) format("woff"),url(fonts/KaTeX_Main-BoldItalic.ttf) format("truetype");font-weight:700;font-style:italic}@font-face{font-family:KaTeX_Main;src:url(fonts/KaTeX_Main-Italic.woff2) format("woff2"),url(fonts/KaTeX_Main-Italic.woff) format("woff"),url(fonts/KaTeX_Main-Italic.ttf) format("truetype");font-weight:400;font-style:italic}@font-face{font-family:KaTeX_Main;src:url(fonts/KaTeX_Main-Regular.woff2) format("woff2"),url(fonts/KaTeX_Main-Regular.woff) format("woff"),url(fonts/KaTeX_Main-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Math;src:url(fonts/KaTeX_Math-BoldItalic.woff2) format("woff2"),url(fonts/KaTeX_Math-BoldItalic.woff) format("woff"),url(fonts/KaTeX_Math-BoldItalic.ttf) format("truetype");font-weight:700;font-style:italic}@font-face{font-family:KaTeX_Math;src:url(fonts/KaTeX_Math-Italic.woff2) format("woff2"),url(fonts/KaTeX_Math-Italic.woff) format("woff"),url(fonts/KaTeX_Math-Italic.ttf) format("truetype");font-weight:400;font-style:italic}@font-face{font-family:"KaTeX_SansSerif";src:url(fonts/KaTeX_SansSerif-Bold.woff2) format("woff2"),url(fonts/KaTeX_SansSerif-Bold.woff) format("woff"),url(fonts/KaTeX_SansSerif-Bold.ttf) format("truetype");font-weight:700;font-style:normal}@font-face{font-family:"KaTeX_SansSerif";src:url(fonts/KaTeX_SansSerif-Italic.woff2) format("woff2"),url(fonts/KaTeX_SansSerif-Italic.woff) format("woff"),url(fonts/KaTeX_SansSerif-Italic.ttf) format("truetype");font-weight:400;font-style:italic}@font-face{font-family:"KaTeX_SansSerif";src:url(fonts/KaTeX_SansSerif-Regular.woff2) format("woff2"),url(fonts/KaTeX_SansSerif-Regular.woff) format("woff"),url(fonts/KaTeX_SansSerif-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Script;src:url(fonts/KaTeX_Script-Regular.woff2) format("woff2"),url(fonts/KaTeX_Script-Regular.woff) format("woff"),url(fonts/KaTeX_Script-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Size1;src:url(fonts/KaTeX_Size1-Regular.woff2) format("woff2"),url(fonts/KaTeX_Size1-Regular.woff) format("woff"),url(fonts/KaTeX_Size1-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Size2;src:url(fonts/KaTeX_Size2-Regular.woff2) format("woff2"),url(fonts/KaTeX_Size2-Regular.woff) format("woff"),url(fonts/KaTeX_Size2-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Size3;src:url(fonts/KaTeX_Size3-Regular.woff2) format("woff2"),url(fonts/KaTeX_Size3-Regular.woff) format("woff"),url(fonts/KaTeX_Size3-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Size4;src:url(fonts/KaTeX_Size4-Regular.woff2) format("woff2"),url(fonts/KaTeX_Size4-Regular.woff) format("woff"),url(fonts/KaTeX_Size4-Regular.ttf) format("truetype");font-weight:400;font-style:normal}@font-face{font-family:KaTeX_Typewriter;src:url(fonts/KaTeX_Typewriter-Regular.woff2) format("woff2"),url(fonts/KaTeX_Typewriter-Regular.woff) format("woff"),url(fonts/KaTeX_Typewriter-Regular.ttf) format("truetype");font-weight:400;font-style:normal}.katex{font:normal 1.21em KaTeX_Main,Times New Roman,serif;line-height:1.2;text-indent:0;text-rendering:auto}.katex *{-ms-high-contrast-adjust:none!important}.katex .katex-version:after{content:"0.11.1"}.katex .katex-mathml{position:absolute;clip:rect(1px,1px,1px,1px);padding:0;border:0;height:1px;width:1px;overflow:hidden}.katex .katex-html>.newline{display:block}.katex .base{position:relative;white-space:nowrap;width:min-content}.katex .base,.katex .strut{display:inline-block}.katex .textbf{font-weight:700}.katex .textit{font-style:italic}.katex .textrm{font-family:KaTeX_Main}.katex .textsf{font-family:KaTeX_SansSerif}.katex .texttt{font-family:KaTeX_Typewriter}.katex .mathdefault{font-family:KaTeX_Math;font-style:italic}.katex .mathit{font-family:KaTeX_Main;font-style:italic}.katex .mathrm{font-style:normal}.katex .mathbf{font-family:KaTeX_Main;font-weight:700}.katex .boldsymbol{font-family:KaTeX_Math;font-weight:700;font-style:italic}.katex .amsrm,.katex .mathbb,.katex .textbb{font-family:KaTeX_AMS}.katex .mathcal{font-family:KaTeX_Caligraphic}.katex .mathfrak,.katex .textfrak{font-family:KaTeX_Fraktur}.katex .mathtt{font-family:KaTeX_Typewriter}.katex .mathscr,.katex .textscr{font-family:KaTeX_Script}.katex .mathsf,.katex .textsf{font-family:KaTeX_SansSerif}.katex .mathboldsf,.katex .textboldsf{font-family:KaTeX_SansSerif;font-weight:700}.katex .mathitsf,.katex .textitsf{font-family:KaTeX_SansSerif;font-style:italic}.katex .mainrm{font-family:KaTeX_Main;font-style:normal}.katex .vlist-t{display:inline-table;table-layout:fixed}.katex .vlist-r{display:table-row}.katex .vlist{display:table-cell;vertical-align:bottom;position:relative}.katex .vlist>span{display:block;height:0;position:relative}.katex .vlist>span>span{display:inline-block}.katex .vlist>span>.pstrut{overflow:hidden;width:0}.katex .vlist-t2{margin-right:-2px}.katex .vlist-s{display:table-cell;vertical-align:bottom;font-size:1px;width:2px;min-width:2px}.katex .msupsub{text-align:left}.katex .mfrac>span>span{text-align:center}.katex .mfrac .frac-line{display:inline-block;width:100%;border-bottom-style:solid}.katex .hdashline,.katex .hline,.katex .mfrac .frac-line,.katex .overline .overline-line,.katex .rule,.katex .underline .underline-line{min-height:1px}.katex .mspace{display:inline-block}.katex .clap,.katex .llap,.katex .rlap{width:0;position:relative}.katex .clap>.inner,.katex .llap>.inner,.katex .rlap>.inner{position:absolute}.katex .clap>.fix,.katex .llap>.fix,.katex .rlap>.fix{display:inline-block}.katex .llap>.inner{right:0}.katex .clap>.inner,.katex .rlap>.inner{left:0}.katex .clap>.inner>span{margin-left:-50%;margin-right:50%}.katex .rule{display:inline-block;border:0 solid;position:relative}.katex .hline,.katex .overline .overline-line,.katex .underline .underline-line{display:inline-block;width:100%;border-bottom-style:solid}.katex .hdashline{display:inline-block;width:100%;border-bottom-style:dashed}.katex .sqrt>.root{margin-left:.27777778em;margin-right:-.55555556em}.katex .fontsize-ensurer.reset-size1.size1,.katex .sizing.reset-size1.size1{font-size:1em}.katex .fontsize-ensurer.reset-size1.size2,.katex .sizing.reset-size1.size2{font-size:1.2em}.katex .fontsize-ensurer.reset-size1.size3,.katex .sizing.reset-size1.size3{font-size:1.4em}.katex .fontsize-ensurer.reset-size1.size4,.katex .sizing.reset-size1.size4{font-size:1.6em}.katex .fontsize-ensurer.reset-size1.size5,.katex .sizing.reset-size1.size5{font-size:1.8em}.katex .fontsize-ensurer.reset-size1.size6,.katex .sizing.reset-size1.size6{font-size:2em}.katex .fontsize-ensurer.reset-size1.size7,.katex .sizing.reset-size1.size7{font-size:2.4em}.katex .fontsize-ensurer.reset-size1.size8,.katex .sizing.reset-size1.size8{font-size:2.88em}.katex .fontsize-ensurer.reset-size1.size9,.katex .sizing.reset-size1.size9{font-size:3.456em}.katex .fontsize-ensurer.reset-size1.size10,.katex .sizing.reset-size1.size10{font-size:4.148em}.katex .fontsize-ensurer.reset-size1.size11,.katex .sizing.reset-size1.size11{font-size:4.976em}.katex .fontsize-ensurer.reset-size2.size1,.katex .sizing.reset-size2.size1{font-size:.83333333em}.katex .fontsize-ensurer.reset-size2.size2,.katex .sizing.reset-size2.size2{font-size:1em}.katex .fontsize-ensurer.reset-size2.size3,.katex .sizing.reset-size2.size3{font-size:1.16666667em}.katex .fontsize-ensurer.reset-size2.size4,.katex .sizing.reset-size2.size4{font-size:1.33333333em}.katex .fontsize-ensurer.reset-size2.size5,.katex .sizing.reset-size2.size5{font-size:1.5em}.katex .fontsize-ensurer.reset-size2.size6,.katex .sizing.reset-size2.size6{font-size:1.66666667em}.katex .fontsize-ensurer.reset-size2.size7,.katex .sizing.reset-size2.size7{font-size:2em}.katex .fontsize-ensurer.reset-size2.size8,.katex .sizing.reset-size2.size8{font-size:2.4em}.katex .fontsize-ensurer.reset-size2.size9,.katex .sizing.reset-size2.size9{font-size:2.88em}.katex .fontsize-ensurer.reset-size2.size10,.katex .sizing.reset-size2.size10{font-size:3.45666667em}.katex .fontsize-ensurer.reset-size2.size11,.katex .sizing.reset-size2.size11{font-size:4.14666667em}.katex .fontsize-ensurer.reset-size3.size1,.katex .sizing.reset-size3.size1{font-size:.71428571em}.katex .fontsize-ensurer.reset-size3.size2,.katex .sizing.reset-size3.size2{font-size:.85714286em}.katex .fontsize-ensurer.reset-size3.size3,.katex .sizing.reset-size3.size3{font-size:1em}.katex .fontsize-ensurer.reset-size3.size4,.katex .sizing.reset-size3.size4{font-size:1.14285714em}.katex .fontsize-ensurer.reset-size3.size5,.katex .sizing.reset-size3.size5{font-size:1.28571429em}.katex .fontsize-ensurer.reset-size3.size6,.katex .sizing.reset-size3.size6{font-size:1.42857143em}.katex .fontsize-ensurer.reset-size3.size7,.katex .sizing.reset-size3.size7{font-size:1.71428571em}.katex .fontsize-ensurer.reset-size3.size8,.katex .sizing.reset-size3.size8{font-size:2.05714286em}.katex .fontsize-ensurer.reset-size3.size9,.katex .sizing.reset-size3.size9{font-size:2.46857143em}.katex .fontsize-ensurer.reset-size3.size10,.katex .sizing.reset-size3.size10{font-size:2.96285714em}.katex .fontsize-ensurer.reset-size3.size11,.katex .sizing.reset-size3.size11{font-size:3.55428571em}.katex .fontsize-ensurer.reset-size4.size1,.katex .sizing.reset-size4.size1{font-size:.625em}.katex .fontsize-ensurer.reset-size4.size2,.katex .sizing.reset-size4.size2{font-size:.75em}.katex .fontsize-ensurer.reset-size4.size3,.katex .sizing.reset-size4.size3{font-size:.875em}.katex .fontsize-ensurer.reset-size4.size4,.katex .sizing.reset-size4.size4{font-size:1em}.katex .fontsize-ensurer.reset-size4.size5,.katex .sizing.reset-size4.size5{font-size:1.125em}.katex .fontsize-ensurer.reset-size4.size6,.katex .sizing.reset-size4.size6{font-size:1.25em}.katex .fontsize-ensurer.reset-size4.size7,.katex .sizing.reset-size4.size7{font-size:1.5em}.katex .fontsize-ensurer.reset-size4.size8,.katex .sizing.reset-size4.size8{font-size:1.8em}.katex .fontsize-ensurer.reset-size4.size9,.katex .sizing.reset-size4.size9{font-size:2.16em}.katex .fontsize-ensurer.reset-size4.size10,.katex .sizing.reset-size4.size10{font-size:2.5925em}.katex .fontsize-ensurer.reset-size4.size11,.katex .sizing.reset-size4.size11{font-size:3.11em}.katex .fontsize-ensurer.reset-size5.size1,.katex .sizing.reset-size5.size1{font-size:.55555556em}.katex .fontsize-ensurer.reset-size5.size2,.katex .sizing.reset-size5.size2{font-size:.66666667em}.katex .fontsize-ensurer.reset-size5.size3,.katex .sizing.reset-size5.size3{font-size:.77777778em}.katex .fontsize-ensurer.reset-size5.size4,.katex .sizing.reset-size5.size4{font-size:.88888889em}.katex .fontsize-ensurer.reset-size5.size5,.katex .sizing.reset-size5.size5{font-size:1em}.katex .fontsize-ensurer.reset-size5.size6,.katex .sizing.reset-size5.size6{font-size:1.11111111em}.katex .fontsize-ensurer.reset-size5.size7,.katex .sizing.reset-size5.size7{font-size:1.33333333em}.katex .fontsize-ensurer.reset-size5.size8,.katex .sizing.reset-size5.size8{font-size:1.6em}.katex .fontsize-ensurer.reset-size5.size9,.katex .sizing.reset-size5.size9{font-size:1.92em}.katex .fontsize-ensurer.reset-size5.size10,.katex .sizing.reset-size5.size10{font-size:2.30444444em}.katex .fontsize-ensurer.reset-size5.size11,.katex .sizing.reset-size5.size11{font-size:2.76444444em}.katex .fontsize-ensurer.reset-size6.size1,.katex .sizing.reset-size6.size1{font-size:.5em}.katex .fontsize-ensurer.reset-size6.size2,.katex .sizing.reset-size6.size2{font-size:.6em}.katex .fontsize-ensurer.reset-size6.size3,.katex .sizing.reset-size6.size3{font-size:.7em}.katex .fontsize-ensurer.reset-size6.size4,.katex .sizing.reset-size6.size4{font-size:.8em}.katex .fontsize-ensurer.reset-size6.size5,.katex .sizing.reset-size6.size5{font-size:.9em}.katex .fontsize-ensurer.reset-size6.size6,.katex .sizing.reset-size6.size6{font-size:1em}.katex .fontsize-ensurer.reset-size6.size7,.katex .sizing.reset-size6.size7{font-size:1.2em}.katex .fontsize-ensurer.reset-size6.size8,.katex .sizing.reset-size6.size8{font-size:1.44em}.katex .fontsize-ensurer.reset-size6.size9,.katex .sizing.reset-size6.size9{font-size:1.728em}.katex .fontsize-ensurer.reset-size6.size10,.katex .sizing.reset-size6.size10{font-size:2.074em}.katex .fontsize-ensurer.reset-size6.size11,.katex .sizing.reset-size6.size11{font-size:2.488em}.katex .fontsize-ensurer.reset-size7.size1,.katex .sizing.reset-size7.size1{font-size:.41666667em}.katex .fontsize-ensurer.reset-size7.size2,.katex .sizing.reset-size7.size2{font-size:.5em}.katex .fontsize-ensurer.reset-size7.size3,.katex .sizing.reset-size7.size3{font-size:.58333333em}.katex .fontsize-ensurer.reset-size7.size4,.katex .sizing.reset-size7.size4{font-size:.66666667em}.katex .fontsize-ensurer.reset-size7.size5,.katex .sizing.reset-size7.size5{font-size:.75em}.katex .fontsize-ensurer.reset-size7.size6,.katex .sizing.reset-size7.size6{font-size:.83333333em}.katex .fontsize-ensurer.reset-size7.size7,.katex .sizing.reset-size7.size7{font-size:1em}.katex .fontsize-ensurer.reset-size7.size8,.katex .sizing.reset-size7.size8{font-size:1.2em}.katex .fontsize-ensurer.reset-size7.size9,.katex .sizing.reset-size7.size9{font-size:1.44em}.katex .fontsize-ensurer.reset-size7.size10,.katex .sizing.reset-size7.size10{font-size:1.72833333em}.katex .fontsize-ensurer.reset-size7.size11,.katex .sizing.reset-size7.size11{font-size:2.07333333em}.katex .fontsize-ensurer.reset-size8.size1,.katex .sizing.reset-size8.size1{font-size:.34722222em}.katex .fontsize-ensurer.reset-size8.size2,.katex .sizing.reset-size8.size2{font-size:.41666667em}.katex .fontsize-ensurer.reset-size8.size3,.katex .sizing.reset-size8.size3{font-size:.48611111em}.katex .fontsize-ensurer.reset-size8.size4,.katex .sizing.reset-size8.size4{font-size:.55555556em}.katex .fontsize-ensurer.reset-size8.size5,.katex .sizing.reset-size8.size5{font-size:.625em}.katex .fontsize-ensurer.reset-size8.size6,.katex .sizing.reset-size8.size6{font-size:.69444444em}.katex .fontsize-ensurer.reset-size8.size7,.katex .sizing.reset-size8.size7{font-size:.83333333em}.katex .fontsize-ensurer.reset-size8.size8,.katex .sizing.reset-size8.size8{font-size:1em}.katex .fontsize-ensurer.reset-size8.size9,.katex .sizing.reset-size8.size9{font-size:1.2em}.katex .fontsize-ensurer.reset-size8.size10,.katex .sizing.reset-size8.size10{font-size:1.44027778em}.katex .fontsize-ensurer.reset-size8.size11,.katex .sizing.reset-size8.size11{font-size:1.72777778em}.katex .fontsize-ensurer.reset-size9.size1,.katex .sizing.reset-size9.size1{font-size:.28935185em}.katex .fontsize-ensurer.reset-size9.size2,.katex .sizing.reset-size9.size2{font-size:.34722222em}.katex .fontsize-ensurer.reset-size9.size3,.katex .sizing.reset-size9.size3{font-size:.40509259em}.katex .fontsize-ensurer.reset-size9.size4,.katex .sizing.reset-size9.size4{font-size:.46296296em}.katex .fontsize-ensurer.reset-size9.size5,.katex .sizing.reset-size9.size5{font-size:.52083333em}.katex .fontsize-ensurer.reset-size9.size6,.katex .sizing.reset-size9.size6{font-size:.5787037em}.katex .fontsize-ensurer.reset-size9.size7,.katex .sizing.reset-size9.size7{font-size:.69444444em}.katex .fontsize-ensurer.reset-size9.size8,.katex .sizing.reset-size9.size8{font-size:.83333333em}.katex .fontsize-ensurer.reset-size9.size9,.katex .sizing.reset-size9.size9{font-size:1em}.katex .fontsize-ensurer.reset-size9.size10,.katex .sizing.reset-size9.size10{font-size:1.20023148em}.katex .fontsize-ensurer.reset-size9.size11,.katex .sizing.reset-size9.size11{font-size:1.43981481em}.katex .fontsize-ensurer.reset-size10.size1,.katex .sizing.reset-size10.size1{font-size:.24108004em}.katex .fontsize-ensurer.reset-size10.size2,.katex .sizing.reset-size10.size2{font-size:.28929605em}.katex .fontsize-ensurer.reset-size10.size3,.katex .sizing.reset-size10.size3{font-size:.33751205em}.katex .fontsize-ensurer.reset-size10.size4,.katex .sizing.reset-size10.size4{font-size:.38572806em}.katex .fontsize-ensurer.reset-size10.size5,.katex .sizing.reset-size10.size5{font-size:.43394407em}.katex .fontsize-ensurer.reset-size10.size6,.katex .sizing.reset-size10.size6{font-size:.48216008em}.katex .fontsize-ensurer.reset-size10.size7,.katex .sizing.reset-size10.size7{font-size:.57859209em}.katex .fontsize-ensurer.reset-size10.size8,.katex .sizing.reset-size10.size8{font-size:.69431051em}.katex .fontsize-ensurer.reset-size10.size9,.katex .sizing.reset-size10.size9{font-size:.83317261em}.katex .fontsize-ensurer.reset-size10.size10,.katex .sizing.reset-size10.size10{font-size:1em}.katex .fontsize-ensurer.reset-size10.size11,.katex .sizing.reset-size10.size11{font-size:1.19961427em}.katex .fontsize-ensurer.reset-size11.size1,.katex .sizing.reset-size11.size1{font-size:.20096463em}.katex .fontsize-ensurer.reset-size11.size2,.katex .sizing.reset-size11.size2{font-size:.24115756em}.katex .fontsize-ensurer.reset-size11.size3,.katex .sizing.reset-size11.size3{font-size:.28135048em}.katex .fontsize-ensurer.reset-size11.size4,.katex .sizing.reset-size11.size4{font-size:.32154341em}.katex .fontsize-ensurer.reset-size11.size5,.katex .sizing.reset-size11.size5{font-size:.36173633em}.katex .fontsize-ensurer.reset-size11.size6,.katex .sizing.reset-size11.size6{font-size:.40192926em}.katex .fontsize-ensurer.reset-size11.size7,.katex .sizing.reset-size11.size7{font-size:.48231511em}.katex .fontsize-ensurer.reset-size11.size8,.katex .sizing.reset-size11.size8{font-size:.57877814em}.katex .fontsize-ensurer.reset-size11.size9,.katex .sizing.reset-size11.size9{font-size:.69453376em}.katex .fontsize-ensurer.reset-size11.size10,.katex .sizing.reset-size11.size10{font-size:.83360129em}.katex .fontsize-ensurer.reset-size11.size11,.katex .sizing.reset-size11.size11{font-size:1em}.katex .delimsizing.size1{font-family:KaTeX_Size1}.katex .delimsizing.size2{font-family:KaTeX_Size2}.katex .delimsizing.size3{font-family:KaTeX_Size3}.katex .delimsizing.size4{font-family:KaTeX_Size4}.katex .delimsizing.mult .delim-size1>span{font-family:KaTeX_Size1}.katex .delimsizing.mult .delim-size4>span{font-family:KaTeX_Size4}.katex .nulldelimiter{display:inline-block;width:.12em}.katex .delimcenter,.katex .op-symbol{position:relative}.katex .op-symbol.small-op{font-family:KaTeX_Size1}.katex .op-symbol.large-op{font-family:KaTeX_Size2}.katex .op-limits>.vlist-t{text-align:center}.katex .accent>.vlist-t{text-align:center}.katex .accent .accent-body{position:relative}.katex .accent .accent-body:not(.accent-full){width:0}.katex .overlay{display:block}.katex .mtable .vertical-separator{display:inline-block;min-width:1px}.katex .mtable .arraycolsep{display:inline-block}.katex .mtable .col-align-c>.vlist-t{text-align:center}.katex .mtable .col-align-l>.vlist-t{text-align:left}.katex .mtable .col-align-r>.vlist-t{text-align:right}.katex .svg-align{text-align:left}.katex svg{display:block;position:absolute;width:100%;height:inherit;fill:currentColor;stroke:currentColor;fill-rule:nonzero;fill-opacity:1;stroke-width:1;stroke-linecap:butt;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1}.katex svg path{stroke:none}.katex img{border-style:none;min-width:0;min-height:0;max-width:none;max-height:none}.katex .stretchy{width:100%;display:block;position:relative;overflow:hidden}.katex .stretchy:after,.katex .stretchy:before{content:""}.katex .hide-tail{width:100%;position:relative;overflow:hidden}.katex .halfarrow-left{position:absolute;left:0;width:50.2%;overflow:hidden}.katex .halfarrow-right{position:absolute;right:0;width:50.2%;overflow:hidden}.katex .brace-left{position:absolute;left:0;width:25.1%;overflow:hidden}.katex .brace-center{position:absolute;left:25%;width:50%;overflow:hidden}.katex .brace-right{position:absolute;right:0;width:25.1%;overflow:hidden}.katex .x-arrow-pad{padding:0 .5em}.katex .mover,.katex .munder,.katex .x-arrow{text-align:center}.katex .boxpad{padding:0 .3em}.katex .fbox,.katex .fcolorbox{box-sizing:border-box;border:.04em solid}.katex .cancel-pad{padding:0 .2em}.katex .cancel-lap{margin-left:-.2em;margin-right:-.2em}.katex .sout{border-bottom-style:solid;border-bottom-width:.08em}.katex-display{display:block;margin:1em 0;text-align:center}.katex-display>.katex{display:block;text-align:center;white-space:nowrap}.katex-display>.katex>.katex-html{display:block;position:relative}.katex-display>.katex>.katex-html>.tag{position:absolute;right:0}.katex-display.leqno>.katex>.katex-html>.tag{left:0;right:auto}.katex-display.fleqn>.katex{text-align:left}

/* style for html inside of browsers */
.katex { font-size: 1em !important; } /* align KaTeX font-size to surrounding text */

eq { display: inline-block; }
eqn { display: block}
section.eqno {
    display: flex;
    flex-direction: row;
    align-content: space-between;
    align-items: center;
}
section.eqno > eqn {
    width: 100%;
    margin-left: 3em;
}
section.eqno > span {
    width:3em;
    text-align:right;
}

p { text-align: justify; }

table {
    display: table !important;
    width: auto !important;
    margin-left: auto !important;
    margin-right: auto !important; 
    border-collapse: collapse !important;
}

table th, table td {
    border-left: none !important;
    border-right: none !important;
    border-top: 1px solid #000 !important;
    border-bottom: 1px solid #000 !important;
}

figure {
    margin: 0.5em auto;
}
figure > img {
    display: block;
    margin: 0 auto;
    page-break-inside: avoid;
}
figcaption { 
    display: block;
    text-align: center;
    margin-top: 0.5em;
}

</style>
        
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Microsoft/vscode/extensions/markdown-language-features/media/markdown.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Microsoft/vscode/extensions/markdown-language-features/media/highlight.css">
<style>
            body {
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe WPC', 'Segoe UI', system-ui, 'Ubuntu', 'Droid Sans', sans-serif;
                font-size: 14px;
                line-height: 1.6;
            }
        </style>
        <style>
.task-list-item { list-style-type: none; } .task-list-item-checkbox { margin-left: -20px; vertical-align: middle; }
</style>
        
        
        <script type="text/javascript">
/* From extension geeklearningio.graphviz-markdown-preview */
/*
Viz.js 2.1.2 (Graphviz 2.40.1, Expat 2.2.5, Emscripten 1.37.36)
Copyright (c) 2014-2018 Michael Daines
Licensed under MIT license

This distribution contains other software in object code form:

Graphviz
Licensed under Eclipse Public License - v 1.0
http://www.graphviz.org

Expat
Copyright (c) 1998, 1999, 2000 Thai Open Source Software Center Ltd and Clark Cooper
Copyright (c) 2001, 2002, 2003, 2004, 2005, 2006 Expat maintainers.
Licensed under MIT license
http://www.libexpat.org

zlib
Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
http://www.zlib.net/zlib_license.html
*/
(function (global, factory) {
  typeof exports === 'object' && typeof module !== 'undefined' ? module.exports = factory() :
  typeof define === 'function' && define.amd ? define(factory) :
  (global.Viz = factory());
}(this, (function () { 'use strict';

  var _typeof = typeof Symbol === "function" && typeof Symbol.iterator === "symbol" ? function (obj) {
    return typeof obj;
  } : function (obj) {
    return obj && typeof Symbol === "function" && obj.constructor === Symbol && obj !== Symbol.prototype ? "symbol" : typeof obj;
  };

  var classCallCheck = function (instance, Constructor) {
    if (!(instance instanceof Constructor)) {
      throw new TypeError("Cannot call a class as a function");
    }
  };

  var createClass = function () {
    function defineProperties(target, props) {
      for (var i = 0; i < props.length; i++) {
        var descriptor = props[i];
        descriptor.enumerable = descriptor.enumerable || false;
        descriptor.configurable = true;
        if ("value" in descriptor) descriptor.writable = true;
        Object.defineProperty(target, descriptor.key, descriptor);
      }
    }

    return function (Constructor, protoProps, staticProps) {
      if (protoProps) defineProperties(Constructor.prototype, protoProps);
      if (staticProps) defineProperties(Constructor, staticProps);
      return Constructor;
    };
  }();

  var _extends = Object.assign || function (target) {
    for (var i = 1; i < arguments.length; i++) {
      var source = arguments[i];

      for (var key in source) {
        if (Object.prototype.hasOwnProperty.call(source, key)) {
          target[key] = source[key];
        }
      }
    }

    return target;
  };

  var WorkerWrapper = function () {
    function WorkerWrapper(worker) {
      var _this = this;

      classCallCheck(this, WorkerWrapper);

      this.worker = worker;
      this.listeners = [];
      this.nextId = 0;

      this.worker.addEventListener('message', function (event) {
        var id = event.data.id;
        var error = event.data.error;
        var result = event.data.result;

        _this.listeners[id](error, result);
        delete _this.listeners[id];
      });
    }

    createClass(WorkerWrapper, [{
      key: 'render',
      value: function render(src, options) {
        var _this2 = this;

        return new Promise(function (resolve, reject) {
          var id = _this2.nextId++;

          _this2.listeners[id] = function (error, result) {
            if (error) {
              reject(new Error(error.message, error.fileName, error.lineNumber));
              return;
            }
            resolve(result);
          };

          _this2.worker.postMessage({ id: id, src: src, options: options });
        });
      }
    }]);
    return WorkerWrapper;
  }();

  var ModuleWrapper = function ModuleWrapper(module, render) {
    classCallCheck(this, ModuleWrapper);

    var instance = module();
    this.render = function (src, options) {
      return new Promise(function (resolve, reject) {
        try {
          resolve(render(instance, src, options));
        } catch (error) {
          reject(error);
        }
      });
    };
  };

  // https://developer.mozilla.org/en-US/docs/Web/API/WindowBase64/Base64_encoding_and_decoding


  function b64EncodeUnicode(str) {
    return btoa(encodeURIComponent(str).replace(/%([0-9A-F]{2})/g, function (match, p1) {
      return String.fromCharCode('0x' + p1);
    }));
  }

  function defaultScale() {
    if ('devicePixelRatio' in window && window.devicePixelRatio > 1) {
      return window.devicePixelRatio;
    } else {
      return 1;
    }
  }

  function svgXmlToImageElement(svgXml) {
    var _ref = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
        _ref$scale = _ref.scale,
        scale = _ref$scale === undefined ? defaultScale() : _ref$scale,
        _ref$mimeType = _ref.mimeType,
        mimeType = _ref$mimeType === undefined ? "image/png" : _ref$mimeType,
        _ref$quality = _ref.quality,
        quality = _ref$quality === undefined ? 1 : _ref$quality;

    return new Promise(function (resolve, reject) {
      var svgImage = new Image();

      svgImage.onload = function () {
        var canvas = document.createElement('canvas');
        canvas.width = svgImage.width * scale;
        canvas.height = svgImage.height * scale;

        var context = canvas.getContext("2d");
        context.drawImage(svgImage, 0, 0, canvas.width, canvas.height);

        canvas.toBlob(function (blob) {
          var image = new Image();
          image.src = URL.createObjectURL(blob);
          image.width = svgImage.width;
          image.height = svgImage.height;

          resolve(image);
        }, mimeType, quality);
      };

      svgImage.onerror = function (e) {
        var error;

        if ('error' in e) {
          error = e.error;
        } else {
          error = new Error('Error loading SVG');
        }

        reject(error);
      };

      svgImage.src = 'data:image/svg+xml;base64,' + b64EncodeUnicode(svgXml);
    });
  }

  function svgXmlToImageElementFabric(svgXml) {
    var _ref2 = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
        _ref2$scale = _ref2.scale,
        scale = _ref2$scale === undefined ? defaultScale() : _ref2$scale,
        _ref2$mimeType = _ref2.mimeType,
        mimeType = _ref2$mimeType === undefined ? 'image/png' : _ref2$mimeType,
        _ref2$quality = _ref2.quality,
        quality = _ref2$quality === undefined ? 1 : _ref2$quality;

    var multiplier = scale;

    var format = void 0;
    if (mimeType == 'image/jpeg') {
      format = 'jpeg';
    } else if (mimeType == 'image/png') {
      format = 'png';
    }

    return new Promise(function (resolve, reject) {
      fabric.loadSVGFromString(svgXml, function (objects, options) {
        // If there's something wrong with the SVG, Fabric may return an empty array of objects. Graphviz appears to give us at least one <g> element back even given an empty graph, so we will assume an error in this case.
        if (objects.length == 0) {
          reject(new Error('Error loading SVG with Fabric'));
        }

        var element = document.createElement("canvas");
        element.width = options.width;
        element.height = options.height;

        var canvas = new fabric.Canvas(element, { enableRetinaScaling: false });
        var obj = fabric.util.groupSVGElements(objects, options);
        canvas.add(obj).renderAll();

        var image = new Image();
        image.src = canvas.toDataURL({ format: format, multiplier: multiplier, quality: quality });
        image.width = options.width;
        image.height = options.height;

        resolve(image);
      });
    });
  }

  var Viz = function () {
    function Viz() {
      var _ref3 = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {},
          workerURL = _ref3.workerURL,
          worker = _ref3.worker,
          Module = _ref3.Module,
          render = _ref3.render;

      classCallCheck(this, Viz);

      if (typeof workerURL !== 'undefined') {
        this.wrapper = new WorkerWrapper(new Worker(workerURL));
      } else if (typeof worker !== 'undefined') {
        this.wrapper = new WorkerWrapper(worker);
      } else if (typeof Module !== 'undefined' && typeof render !== 'undefined') {
        this.wrapper = new ModuleWrapper(Module, render);
      } else if (typeof Viz.Module !== 'undefined' && typeof Viz.render !== 'undefined') {
        this.wrapper = new ModuleWrapper(Viz.Module, Viz.render);
      } else {
        throw new Error('Must specify workerURL or worker option, Module and render options, or include one of full.render.js or lite.render.js after viz.js.');
      }
    }

    createClass(Viz, [{
      key: 'renderString',
      value: function renderString(src) {
        var _ref4 = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {},
            _ref4$format = _ref4.format,
            format = _ref4$format === undefined ? 'svg' : _ref4$format,
            _ref4$engine = _ref4.engine,
            engine = _ref4$engine === undefined ? 'dot' : _ref4$engine,
            _ref4$files = _ref4.files,
            files = _ref4$files === undefined ? [] : _ref4$files,
            _ref4$images = _ref4.images,
            images = _ref4$images === undefined ? [] : _ref4$images,
            _ref4$yInvert = _ref4.yInvert,
            yInvert = _ref4$yInvert === undefined ? false : _ref4$yInvert,
            _ref4$nop = _ref4.nop,
            nop = _ref4$nop === undefined ? 0 : _ref4$nop;

        for (var i = 0; i < images.length; i++) {
          files.push({
            path: images[i].path,
            data: '<?xml version="1.0" encoding="UTF-8" standalone="no"?>\n<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">\n<svg width="' + images[i].width + '" height="' + images[i].height + '"></svg>'
          });
        }

        return this.wrapper.render(src, { format: format, engine: engine, files: files, images: images, yInvert: yInvert, nop: nop });
      }
    }, {
      key: 'renderSVGElement',
      value: function renderSVGElement(src) {
        var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

        return this.renderString(src, _extends({}, options, { format: 'svg' })).then(function (str) {
          var parser = new DOMParser();
          return parser.parseFromString(str, 'image/svg+xml').documentElement;
        });
      }
    }, {
      key: 'renderImageElement',
      value: function renderImageElement(src) {
        var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
        var scale = options.scale,
            mimeType = options.mimeType,
            quality = options.quality;


        return this.renderString(src, _extends({}, options, { format: 'svg' })).then(function (str) {
          if ((typeof fabric === 'undefined' ? 'undefined' : _typeof(fabric)) === "object" && fabric.loadSVGFromString) {
            return svgXmlToImageElementFabric(str, { scale: scale, mimeType: mimeType, quality: quality });
          } else {
            return svgXmlToImageElement(str, { scale: scale, mimeType: mimeType, quality: quality });
          }
        });
      }
    }, {
      key: 'renderJSONObject',
      value: function renderJSONObject(src) {
        var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
        var format = options.format;


        if (format !== 'json' || format !== 'json0') {
          format = 'json';
        }

        return this.renderString(src, _extends({}, options, { format: format })).then(function (str) {
          return JSON.parse(str);
        });
      }
    }]);
    return Viz;
  }();

  return Viz;

})));

</script>
<script type="text/javascript">
/* From extension geeklearningio.graphviz-markdown-preview */
/*
Viz.js 2.1.2 (Graphviz 2.40.1, Expat 2.2.5, Emscripten 1.37.36)
*/
(function(global) {
var Module = function(Module) {
  Module = Module || {};
var Module=typeof Module!=="undefined"?Module:{};var moduleOverrides={};var key;for(key in Module){if(Module.hasOwnProperty(key)){moduleOverrides[key]=Module[key]}}Module["arguments"]=[];Module["thisProgram"]="./this.program";Module["quit"]=(function(status,toThrow){throw toThrow});Module["preRun"]=[];Module["postRun"]=[];var ENVIRONMENT_IS_WEB=false;var ENVIRONMENT_IS_WORKER=false;var ENVIRONMENT_IS_NODE=false;var ENVIRONMENT_IS_SHELL=false;if(Module["ENVIRONMENT"]){if(Module["ENVIRONMENT"]==="WEB"){ENVIRONMENT_IS_WEB=true}else if(Module["ENVIRONMENT"]==="WORKER"){ENVIRONMENT_IS_WORKER=true}else if(Module["ENVIRONMENT"]==="NODE"){ENVIRONMENT_IS_NODE=true}else if(Module["ENVIRONMENT"]==="SHELL"){ENVIRONMENT_IS_SHELL=true}else{throw new Error("Module['ENVIRONMENT'] value is not valid. must be one of: WEB|WORKER|NODE|SHELL.")}}else{ENVIRONMENT_IS_WEB=typeof window==="object";ENVIRONMENT_IS_WORKER=typeof importScripts==="function";ENVIRONMENT_IS_NODE=typeof process==="object"&&typeof require==="function"&&!ENVIRONMENT_IS_WEB&&!ENVIRONMENT_IS_WORKER;ENVIRONMENT_IS_SHELL=!ENVIRONMENT_IS_WEB&&!ENVIRONMENT_IS_NODE&&!ENVIRONMENT_IS_WORKER}if(ENVIRONMENT_IS_NODE){var nodeFS;var nodePath;Module["read"]=function shell_read(filename,binary){var ret;ret=tryParseAsDataURI(filename);if(!ret){if(!nodeFS)nodeFS=require("fs");if(!nodePath)nodePath=require("path");filename=nodePath["normalize"](filename);ret=nodeFS["readFileSync"](filename)}return binary?ret:ret.toString()};Module["readBinary"]=function readBinary(filename){var ret=Module["read"](filename,true);if(!ret.buffer){ret=new Uint8Array(ret)}assert(ret.buffer);return ret};if(process["argv"].length>1){Module["thisProgram"]=process["argv"][1].replace(/\\/g,"/")}Module["arguments"]=process["argv"].slice(2);if(typeof module!=="undefined"){module["exports"]=Module}process["on"]("uncaughtException",(function(ex){if(!(ex instanceof ExitStatus)){throw ex}}));process["on"]("unhandledRejection",(function(reason,p){process["exit"](1)}));Module["inspect"]=(function(){return"[Emscripten Module object]"})}else if(ENVIRONMENT_IS_SHELL){if(typeof read!="undefined"){Module["read"]=function shell_read(f){var data=tryParseAsDataURI(f);if(data){return intArrayToString(data)}return read(f)}}Module["readBinary"]=function readBinary(f){var data;data=tryParseAsDataURI(f);if(data){return data}if(typeof readbuffer==="function"){return new Uint8Array(readbuffer(f))}data=read(f,"binary");assert(typeof data==="object");return data};if(typeof scriptArgs!="undefined"){Module["arguments"]=scriptArgs}else if(typeof arguments!="undefined"){Module["arguments"]=arguments}if(typeof quit==="function"){Module["quit"]=(function(status,toThrow){quit(status)})}}else if(ENVIRONMENT_IS_WEB||ENVIRONMENT_IS_WORKER){Module["read"]=function shell_read(url){try{var xhr=new XMLHttpRequest;xhr.open("GET",url,false);xhr.send(null);return xhr.responseText}catch(err){var data=tryParseAsDataURI(url);if(data){return intArrayToString(data)}throw err}};if(ENVIRONMENT_IS_WORKER){Module["readBinary"]=function readBinary(url){try{var xhr=new XMLHttpRequest;xhr.open("GET",url,false);xhr.responseType="arraybuffer";xhr.send(null);return new Uint8Array(xhr.response)}catch(err){var data=tryParseAsDataURI(url);if(data){return data}throw err}}}Module["readAsync"]=function readAsync(url,onload,onerror){var xhr=new XMLHttpRequest;xhr.open("GET",url,true);xhr.responseType="arraybuffer";xhr.onload=function xhr_onload(){if(xhr.status==200||xhr.status==0&&xhr.response){onload(xhr.response);return}var data=tryParseAsDataURI(url);if(data){onload(data.buffer);return}onerror()};xhr.onerror=onerror;xhr.send(null)};if(typeof arguments!="undefined"){Module["arguments"]=arguments}Module["setWindowTitle"]=(function(title){document.title=title})}Module["print"]=typeof console!=="undefined"?console.log.bind(console):typeof print!=="undefined"?print:null;Module["printErr"]=typeof printErr!=="undefined"?printErr:typeof console!=="undefined"&&console.warn.bind(console)||Module["print"];Module.print=Module["print"];Module.printErr=Module["printErr"];for(key in moduleOverrides){if(moduleOverrides.hasOwnProperty(key)){Module[key]=moduleOverrides[key]}}moduleOverrides=undefined;var STACK_ALIGN=16;function staticAlloc(size){assert(!staticSealed);var ret=STATICTOP;STATICTOP=STATICTOP+size+15&-16;return ret}function dynamicAlloc(size){assert(DYNAMICTOP_PTR);var ret=HEAP32[DYNAMICTOP_PTR>>2];var end=ret+size+15&-16;HEAP32[DYNAMICTOP_PTR>>2]=end;if(end>=TOTAL_MEMORY){var success=enlargeMemory();if(!success){HEAP32[DYNAMICTOP_PTR>>2]=ret;return 0}}return ret}function alignMemory(size,factor){if(!factor)factor=STACK_ALIGN;var ret=size=Math.ceil(size/factor)*factor;return ret}function getNativeTypeSize(type){switch(type){case"i1":case"i8":return 1;case"i16":return 2;case"i32":return 4;case"i64":return 8;case"float":return 4;case"double":return 8;default:{if(type[type.length-1]==="*"){return 4}else if(type[0]==="i"){var bits=parseInt(type.substr(1));assert(bits%8===0);return bits/8}else{return 0}}}}function warnOnce(text){if(!warnOnce.shown)warnOnce.shown={};if(!warnOnce.shown[text]){warnOnce.shown[text]=1;Module.printErr(text)}}var jsCallStartIndex=1;var functionPointers=new Array(0);var funcWrappers={};function dynCall(sig,ptr,args){if(args&&args.length){return Module["dynCall_"+sig].apply(null,[ptr].concat(args))}else{return Module["dynCall_"+sig].call(null,ptr)}}var GLOBAL_BASE=8;var ABORT=0;var EXITSTATUS=0;function assert(condition,text){if(!condition){abort("Assertion failed: "+text)}}function getCFunc(ident){var func=Module["_"+ident];assert(func,"Cannot call unknown function "+ident+", make sure it is exported");return func}var JSfuncs={"stackSave":(function(){stackSave()}),"stackRestore":(function(){stackRestore()}),"arrayToC":(function(arr){var ret=stackAlloc(arr.length);writeArrayToMemory(arr,ret);return ret}),"stringToC":(function(str){var ret=0;if(str!==null&&str!==undefined&&str!==0){var len=(str.length<<2)+1;ret=stackAlloc(len);stringToUTF8(str,ret,len)}return ret})};var toC={"string":JSfuncs["stringToC"],"array":JSfuncs["arrayToC"]};function ccall(ident,returnType,argTypes,args,opts){var func=getCFunc(ident);var cArgs=[];var stack=0;if(args){for(var i=0;i<args.length;i++){var converter=toC[argTypes[i]];if(converter){if(stack===0)stack=stackSave();cArgs[i]=converter(args[i])}else{cArgs[i]=args[i]}}}var ret=func.apply(null,cArgs);if(returnType==="string")ret=Pointer_stringify(ret);if(stack!==0){stackRestore(stack)}return ret}function setValue(ptr,value,type,noSafe){type=type||"i8";if(type.charAt(type.length-1)==="*")type="i32";switch(type){case"i1":HEAP8[ptr>>0]=value;break;case"i8":HEAP8[ptr>>0]=value;break;case"i16":HEAP16[ptr>>1]=value;break;case"i32":HEAP32[ptr>>2]=value;break;case"i64":tempI64=[value>>>0,(tempDouble=value,+Math_abs(tempDouble)>=+1?tempDouble>+0?(Math_min(+Math_floor(tempDouble/+4294967296),+4294967295)|0)>>>0:~~+Math_ceil((tempDouble- +(~~tempDouble>>>0))/+4294967296)>>>0:0)],HEAP32[ptr>>2]=tempI64[0],HEAP32[ptr+4>>2]=tempI64[1];break;case"float":HEAPF32[ptr>>2]=value;break;case"double":HEAPF64[ptr>>3]=value;break;default:abort("invalid type for setValue: "+type)}}var ALLOC_STATIC=2;var ALLOC_NONE=4;function allocate(slab,types,allocator,ptr){var zeroinit,size;if(typeof slab==="number"){zeroinit=true;size=slab}else{zeroinit=false;size=slab.length}var singleType=typeof types==="string"?types:null;var ret;if(allocator==ALLOC_NONE){ret=ptr}else{ret=[typeof _malloc==="function"?_malloc:staticAlloc,stackAlloc,staticAlloc,dynamicAlloc][allocator===undefined?ALLOC_STATIC:allocator](Math.max(size,singleType?1:types.length))}if(zeroinit){var stop;ptr=ret;assert((ret&3)==0);stop=ret+(size&~3);for(;ptr<stop;ptr+=4){HEAP32[ptr>>2]=0}stop=ret+size;while(ptr<stop){HEAP8[ptr++>>0]=0}return ret}if(singleType==="i8"){if(slab.subarray||slab.slice){HEAPU8.set(slab,ret)}else{HEAPU8.set(new Uint8Array(slab),ret)}return ret}var i=0,type,typeSize,previousType;while(i<size){var curr=slab[i];type=singleType||types[i];if(type===0){i++;continue}if(type=="i64")type="i32";setValue(ret+i,curr,type);if(previousType!==type){typeSize=getNativeTypeSize(type);previousType=type}i+=typeSize}return ret}function Pointer_stringify(ptr,length){if(length===0||!ptr)return"";var hasUtf=0;var t;var i=0;while(1){t=HEAPU8[ptr+i>>0];hasUtf|=t;if(t==0&&!length)break;i++;if(length&&i==length)break}if(!length)length=i;var ret="";if(hasUtf<128){var MAX_CHUNK=1024;var curr;while(length>0){curr=String.fromCharCode.apply(String,HEAPU8.subarray(ptr,ptr+Math.min(length,MAX_CHUNK)));ret=ret?ret+curr:curr;ptr+=MAX_CHUNK;length-=MAX_CHUNK}return ret}return UTF8ToString(ptr)}var UTF8Decoder=typeof TextDecoder!=="undefined"?new TextDecoder("utf8"):undefined;function UTF8ArrayToString(u8Array,idx){var endPtr=idx;while(u8Array[endPtr])++endPtr;if(endPtr-idx>16&&u8Array.subarray&&UTF8Decoder){return UTF8Decoder.decode(u8Array.subarray(idx,endPtr))}else{var u0,u1,u2,u3,u4,u5;var str="";while(1){u0=u8Array[idx++];if(!u0)return str;if(!(u0&128)){str+=String.fromCharCode(u0);continue}u1=u8Array[idx++]&63;if((u0&224)==192){str+=String.fromCharCode((u0&31)<<6|u1);continue}u2=u8Array[idx++]&63;if((u0&240)==224){u0=(u0&15)<<12|u1<<6|u2}else{u3=u8Array[idx++]&63;if((u0&248)==240){u0=(u0&7)<<18|u1<<12|u2<<6|u3}else{u4=u8Array[idx++]&63;if((u0&252)==248){u0=(u0&3)<<24|u1<<18|u2<<12|u3<<6|u4}else{u5=u8Array[idx++]&63;u0=(u0&1)<<30|u1<<24|u2<<18|u3<<12|u4<<6|u5}}}if(u0<65536){str+=String.fromCharCode(u0)}else{var ch=u0-65536;str+=String.fromCharCode(55296|ch>>10,56320|ch&1023)}}}}function UTF8ToString(ptr){return UTF8ArrayToString(HEAPU8,ptr)}function stringToUTF8Array(str,outU8Array,outIdx,maxBytesToWrite){if(!(maxBytesToWrite>0))return 0;var startIdx=outIdx;var endIdx=outIdx+maxBytesToWrite-1;for(var i=0;i<str.length;++i){var u=str.charCodeAt(i);if(u>=55296&&u<=57343)u=65536+((u&1023)<<10)|str.charCodeAt(++i)&1023;if(u<=127){if(outIdx>=endIdx)break;outU8Array[outIdx++]=u}else if(u<=2047){if(outIdx+1>=endIdx)break;outU8Array[outIdx++]=192|u>>6;outU8Array[outIdx++]=128|u&63}else if(u<=65535){if(outIdx+2>=endIdx)break;outU8Array[outIdx++]=224|u>>12;outU8Array[outIdx++]=128|u>>6&63;outU8Array[outIdx++]=128|u&63}else if(u<=2097151){if(outIdx+3>=endIdx)break;outU8Array[outIdx++]=240|u>>18;outU8Array[outIdx++]=128|u>>12&63;outU8Array[outIdx++]=128|u>>6&63;outU8Array[outIdx++]=128|u&63}else if(u<=67108863){if(outIdx+4>=endIdx)break;outU8Array[outIdx++]=248|u>>24;outU8Array[outIdx++]=128|u>>18&63;outU8Array[outIdx++]=128|u>>12&63;outU8Array[outIdx++]=128|u>>6&63;outU8Array[outIdx++]=128|u&63}else{if(outIdx+5>=endIdx)break;outU8Array[outIdx++]=252|u>>30;outU8Array[outIdx++]=128|u>>24&63;outU8Array[outIdx++]=128|u>>18&63;outU8Array[outIdx++]=128|u>>12&63;outU8Array[outIdx++]=128|u>>6&63;outU8Array[outIdx++]=128|u&63}}outU8Array[outIdx]=0;return outIdx-startIdx}function stringToUTF8(str,outPtr,maxBytesToWrite){return stringToUTF8Array(str,HEAPU8,outPtr,maxBytesToWrite)}function lengthBytesUTF8(str){var len=0;for(var i=0;i<str.length;++i){var u=str.charCodeAt(i);if(u>=55296&&u<=57343)u=65536+((u&1023)<<10)|str.charCodeAt(++i)&1023;if(u<=127){++len}else if(u<=2047){len+=2}else if(u<=65535){len+=3}else if(u<=2097151){len+=4}else if(u<=67108863){len+=5}else{len+=6}}return len}var UTF16Decoder=typeof TextDecoder!=="undefined"?new TextDecoder("utf-16le"):undefined;function allocateUTF8(str){var size=lengthBytesUTF8(str)+1;var ret=_malloc(size);if(ret)stringToUTF8Array(str,HEAP8,ret,size);return ret}function demangle(func){return func}function demangleAll(text){var regex=/__Z[\w\d_]+/g;return text.replace(regex,(function(x){var y=demangle(x);return x===y?x:x+" ["+y+"]"}))}function jsStackTrace(){var err=new Error;if(!err.stack){try{throw new Error(0)}catch(e){err=e}if(!err.stack){return"(no stack trace available)"}}return err.stack.toString()}function stackTrace(){var js=jsStackTrace();if(Module["extraStackTrace"])js+="\n"+Module["extraStackTrace"]();return demangleAll(js)}var PAGE_SIZE=16384;var buffer,HEAP8,HEAPU8,HEAP16,HEAPU16,HEAP32,HEAPU32,HEAPF32,HEAPF64;function updateGlobalBufferViews(){Module["HEAP8"]=HEAP8=new Int8Array(buffer);Module["HEAP16"]=HEAP16=new Int16Array(buffer);Module["HEAP32"]=HEAP32=new Int32Array(buffer);Module["HEAPU8"]=HEAPU8=new Uint8Array(buffer);Module["HEAPU16"]=HEAPU16=new Uint16Array(buffer);Module["HEAPU32"]=HEAPU32=new Uint32Array(buffer);Module["HEAPF32"]=HEAPF32=new Float32Array(buffer);Module["HEAPF64"]=HEAPF64=new Float64Array(buffer)}var STATIC_BASE,STATICTOP,staticSealed;var STACK_BASE,STACKTOP,STACK_MAX;var DYNAMIC_BASE,DYNAMICTOP_PTR;STATIC_BASE=STATICTOP=STACK_BASE=STACKTOP=STACK_MAX=DYNAMIC_BASE=DYNAMICTOP_PTR=0;staticSealed=false;function abortOnCannotGrowMemory(){abort("Cannot enlarge memory arrays. Either (1) compile with  -s TOTAL_MEMORY=X  with X higher than the current value "+TOTAL_MEMORY+", (2) compile with  -s ALLOW_MEMORY_GROWTH=1  which allows increasing the size at runtime but prevents some optimizations, (3) set Module.TOTAL_MEMORY to a higher value before the program runs, or (4) if you want malloc to return NULL (0) instead of this abort, compile with  -s ABORTING_MALLOC=0 ")}function enlargeMemory(){abortOnCannotGrowMemory()}var TOTAL_STACK=Module["TOTAL_STACK"]||5242880;var TOTAL_MEMORY=Module["TOTAL_MEMORY"]||16777216;if(TOTAL_MEMORY<TOTAL_STACK)Module.printErr("TOTAL_MEMORY should be larger than TOTAL_STACK, was "+TOTAL_MEMORY+"! (TOTAL_STACK="+TOTAL_STACK+")");if(Module["buffer"]){buffer=Module["buffer"]}else{{buffer=new ArrayBuffer(TOTAL_MEMORY)}Module["buffer"]=buffer}updateGlobalBufferViews();function getTotalMemory(){return TOTAL_MEMORY}HEAP32[0]=1668509029;HEAP16[1]=25459;if(HEAPU8[2]!==115||HEAPU8[3]!==99)throw"Runtime error: expected the system to be little-endian!";function callRuntimeCallbacks(callbacks){while(callbacks.length>0){var callback=callbacks.shift();if(typeof callback=="function"){callback();continue}var func=callback.func;if(typeof func==="number"){if(callback.arg===undefined){Module["dynCall_v"](func)}else{Module["dynCall_vi"](func,callback.arg)}}else{func(callback.arg===undefined?null:callback.arg)}}}var __ATPRERUN__=[];var __ATINIT__=[];var __ATMAIN__=[];var __ATEXIT__=[];var __ATPOSTRUN__=[];var runtimeInitialized=false;var runtimeExited=false;function preRun(){if(Module["preRun"]){if(typeof Module["preRun"]=="function")Module["preRun"]=[Module["preRun"]];while(Module["preRun"].length){addOnPreRun(Module["preRun"].shift())}}callRuntimeCallbacks(__ATPRERUN__)}function ensureInitRuntime(){if(runtimeInitialized)return;runtimeInitialized=true;callRuntimeCallbacks(__ATINIT__)}function preMain(){callRuntimeCallbacks(__ATMAIN__)}function exitRuntime(){callRuntimeCallbacks(__ATEXIT__);runtimeExited=true}function postRun(){if(Module["postRun"]){if(typeof Module["postRun"]=="function")Module["postRun"]=[Module["postRun"]];while(Module["postRun"].length){addOnPostRun(Module["postRun"].shift())}}callRuntimeCallbacks(__ATPOSTRUN__)}function addOnPreRun(cb){__ATPRERUN__.unshift(cb)}function addOnPostRun(cb){__ATPOSTRUN__.unshift(cb)}function writeArrayToMemory(array,buffer){HEAP8.set(array,buffer)}function writeAsciiToMemory(str,buffer,dontAddNull){for(var i=0;i<str.length;++i){HEAP8[buffer++>>0]=str.charCodeAt(i)}if(!dontAddNull)HEAP8[buffer>>0]=0}if(!Math["imul"]||Math["imul"](4294967295,5)!==-5)Math["imul"]=function imul(a,b){var ah=a>>>16;var al=a&65535;var bh=b>>>16;var bl=b&65535;return al*bl+(ah*bl+al*bh<<16)|0};Math.imul=Math["imul"];if(!Math["clz32"])Math["clz32"]=(function(x){x=x>>>0;for(var i=0;i<32;i++){if(x&1<<31-i)return i}return 32});Math.clz32=Math["clz32"];if(!Math["trunc"])Math["trunc"]=(function(x){return x<0?Math.ceil(x):Math.floor(x)});Math.trunc=Math["trunc"];var Math_abs=Math.abs;var Math_cos=Math.cos;var Math_sin=Math.sin;var Math_tan=Math.tan;var Math_acos=Math.acos;var Math_asin=Math.asin;var Math_atan=Math.atan;var Math_atan2=Math.atan2;var Math_exp=Math.exp;var Math_log=Math.log;var Math_sqrt=Math.sqrt;var Math_ceil=Math.ceil;var Math_floor=Math.floor;var Math_pow=Math.pow;var Math_imul=Math.imul;var Math_fround=Math.fround;var Math_round=Math.round;var Math_min=Math.min;var Math_max=Math.max;var Math_clz32=Math.clz32;var Math_trunc=Math.trunc;var runDependencies=0;var runDependencyWatcher=null;var dependenciesFulfilled=null;function getUniqueRunDependency(id){return id}function addRunDependency(id){runDependencies++;if(Module["monitorRunDependencies"]){Module["monitorRunDependencies"](runDependencies)}}function removeRunDependency(id){runDependencies--;if(Module["monitorRunDependencies"]){Module["monitorRunDependencies"](runDependencies)}if(runDependencies==0){if(runDependencyWatcher!==null){clearInterval(runDependencyWatcher);runDependencyWatcher=null}if(dependenciesFulfilled){var callback=dependenciesFulfilled;dependenciesFulfilled=null;callback()}}}Module["preloadedImages"]={};Module["preloadedAudios"]={};var memoryInitializer=null;var dataURIPrefix="data:application/octet-stream;base64,";function isDataURI(filename){return String.prototype.startsWith?filename.startsWith(dataURIPrefix):filename.indexOf(dataURIPrefix)===0}var ASM_CONSTS=[(function($0,$1){var path=Pointer_stringify($0);var data=Pointer_stringify($1);FS.createPath("/",PATH.dirname(path));FS.writeFile(PATH.join("/",path),data)})];function _emscripten_asm_const_iii(code,a0,a1){return ASM_CONSTS[code](a0,a1)}STATIC_BASE=GLOBAL_BASE;STATICTOP=STATIC_BASE+194160;__ATINIT__.push();memoryInitializer="data:application/octet-stream;base64,AAAAAAAA8D8AAAAAAADwPwAAAAAAAPA/AAAAAAAA8D8AAAAAAADwPwAAAAAAAPA/AAAAAAAA8D8AAAAAAADwPwAAAAAAAPA/AAAAAAAA8D8AAAAAAADwPwAAAAAAAPA/ACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABQAAAAAAAAAAIMEAAAAAAAAAAAAAAAAAAAAAAAAAAAABAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABSQAAAAAAAAFJAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFJAAAAAAAAAUkAAIMEAAAAAAAAAAAAAAAAAAAAAAAAAAAAFAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABSQAAAAAAAAFJAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFJAAAAAAAAAUkACEAAAAAAAAAAAAAAAABBAoC8AAAgAAAABAAAAAAAAAAIQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAICWQAAAAAAAgJZABJDDAAAAAAAAAAAAAAAQQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWEAAAAAAAABYQAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABYQAAAAAAAAFhAAAAAAAAAAAAAAAAAAAAQQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAUkAAAAAAAABSQAAgAwIAAAAAAAAAAAAAEEAAAAAAAAAAAAAAAAAAAAAAYAAAAAAAAAAAAAAAAABCQAAAAAAAAEJAAAAAAAAgg0AAAAAAAMCIQAAAAAAAAFJAAAAAAAAAUkAAAAAAAAAAAAAAAAAAAEJAAAAAAAAAQkAAAAAAACCDQAAAAAAAwIhAAAAAAAAAUkAAAAAAAABSQACwwQAAAAAAAAAAAAAAEEBANgAAkwAAAAEAAAAAAAAAQAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFJAAAAAAAAAUkAAEAACAAAAAAAAAAAAABBAAAAAAAAAAAAFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABYQAAAAAAAAFhAALDBAAAAAAAAAAAAAAAAABw6AAAQAAAAAQAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWEAAAAAAAABYQEAgPgMAAAAAAAAAAAAAEEAkOwAAegAAAAEAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAFJAAAAAAAAAUkAAAAAAAAAAAAAAAAAAABBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABSQAAAAAAAAFJA////////73/////////vf////////+//////////7/8AAAAAAAD4PzMzMzMzM9M/PAAAAAAAAACamZmZmZmpPwEAAAAAAAAAAQAAAAAAAAAAAAAAAADwPwEAAAAAAAAAAgAAAAAAAAAAAAAAAADwPwIAAAAAAAAAAwAAAAAAAAAAAAAAAADgPwMAAAAAAAAABAAAAAAAAAAAAAAAAADwPwQAAAAAAAAABQAAAAAAAAAzMzMzMzPzPwUAAAAAAAAABgAAAAAAAACamZmZmZnpPwYAAAAAAAAABwAAAAAAAAAAAAAAAADwPwcAAAAAAAAACAAAAAAAAAAAAAAAAADgPwgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAEAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAABAAAAAAAAAAAAAAAAAAAAMzMzMzMz078AAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAgEZAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAmpmZmZmZ2b8AAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAzMzMzMzPjPwAAAAAAAAAAAAAAAAEAAAAFAAAAAAAAAAAAAAAAAAAAexSuR+F65L8AAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAGAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAHAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAEAAAATAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABqQVQAAAQAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAIAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMAAAAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAADAAAAAAAAAAAAAAAAgGZAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAgGZAmpmZmZmZ2b8AAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAFAAAAAAAAAAAAAAAAgGZAexSuR+F65L8AAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAgEZAAAAAAAAAAAAAAAAAAAAAABgAAAAAAAAAAQAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAAAAAAAAAQAAAAEAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABgAAAAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAYAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAcAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABEAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABIAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABMAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABQAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABUAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAoAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAwAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA0AAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA4AAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA8AAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABAAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABYAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABgAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABcAAAAAAAAAAAEAAAAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABkAAAAAAAAAAAEAAAAKAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACIVQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPC/AAAAAAAAAQAAAAAAAAAAAAAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAAAADQPwAAAAAAANA/AAAAAAAA0D8AAAAA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YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z9R2ht8YTLjP1HaG3xhMuM/UdobfGEy4z/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP/RsVn2uttY/tRX7y+7J4T+1FfvL7snhP8RCrWnecew/EHo2qz5X5T/129eBc0bMP1ioNc07TtU/WKg1zTtO1T+IhVrTvOPYPwFNhA1Pr+I/07zjFB3J0T9YqDXNO07VP9O84xQdydE/07zjFB3J0T+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T+1FfvL7snhP9O84xQdydE/07zjFB3J0T8BTYQNT6/iPwFNhA1Pr+I/AU2EDU+v4j+1FfvL7snhP8xdS8gHPfA/EHo2qz5X5T8QejarPlflP9JvXwfOGec/0m9fB84Z5z8QejarPlflP3gLJCh+jOM/at5xio7k6D/Sb18HzhnnP9O84xQdydE/AAAAAAAA4D8QejarPlflP7UV+8vuyeE/LNSa5h2n6j/Sb18HzhnnP2recYqO5Og/EHo2qz5X5T9q3nGKjuToP9JvXwfOGec/EHo2qz5X5T94CyQofozjP9JvXwfOGec/EHo2qz5X5T+GONbFbTTuPxB6Nqs+V+U/EHo2qz5X5T94CyQofozjP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP6YKRiV1At4/tRX7y+7J4T9Iv30dOGfMP7UV+8vuyeE/tRX7y+7J4T8AAAAAAADgP7UV+8vuyeE/tRX7y+7J4T/TvOMUHcnRP7UV+8vuyeE/tRX7y+7J4T9Iv30dOGfMP0i/fR04Z8w/AAAAAAAA4D9Iv30dOGfMPyzUmuYdp+o/tRX7y+7J4T+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T9YqDXNO07VPwAAAAAAAOA/07zjFB3J0T+1FfvL7snhPwAAAAAAAOA/0m9fB84Z5z8AAAAAAADgPwAAAAAAAOA/AAAAAAAA4D8Cmggbnl7VP+C+DpwzotA/ApoIG55e1T8BTYQNT6/iP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/WKg1zTtO1T+1FfvL7snhP7UV+8vuyeE/PujZrPpcxT+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T+1FfvL7snhPx04Z0Rpb8g/WKg1zTtO1T+1FfvL7snhP1ioNc07TtU/WKg1zTtO1T8AAAAAAADgPwAAAAAAAOA/07zjFB3J0T+1FfvL7snhP7UV+8vuyeE/tRX7y+7J4T/TvOMUHcnRP9O84xQdydE/5x2n6Egu4T+itDf4wmTWP0i/fR04Z8w/WKg1zTtO1T9YqDXNO07VP7UV+8vuyeE/AAAAAAAA8D8AAAAAAADwP9O84xQdydE/eAskKH6M4z/TvOMUHcnRP1ioNc07TtU/WKg1zTtO1T9YqDXNO07VP1ioNc07TtU/WKg1zTtO1T9YqDXNO07VP1ioNc07TtU/WKg1zTtO1T/TvOMUHcnRP1ioNc07TtU/WKg1zTtO1T/TvOMUHcnRP1ioNc07TtU/WKg1zTtO1T9YqDXNO07VPwAAAAAAAPA/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T8AAAAAAADwP9O84xQdydE/6pWyDHGs1z/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP7UV+8vuyeE/at5xio7k6D8AAAAAAADwP5jdk4eFWtc/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP8RCrWnecew/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP9O84xQdydE/SL99HThnzD94CyQofozjP4Y41sVtNO4/eAskKH6M4z/TvOMUHcnRP9O84xQdydE/07zjFB3J0T/TvOMUHcnRP1GgT+RJ0g5AtMh2vp86NcA6It+l1CXVv/OCPkeaLoo/n+V5cHfW+b9+/RAbLJzmP5bs2AjE68w/zc6idyrg0D+w479AECDtv62h1F5E29g/O6F85lGWdj/TbnD5eoR7P4HMzqJ3KuS/0a3X9KCgyD9q3zcZsD+EP77KkBle/4Q/HJYGflTDxL+lSSno9uIjQKnZA63AkME/CMSQQZNpiT/6RJ4kXTPQvwHwmTYtwl4/DZx9L8+Ulz+JtfgUAOOJP+WpWEY0y7G/jwDJz6Fnpr9ctcb7zLSIP02kj1Q6s5A/5scEoWHWoL/HaWccE/eCvyp/a+UtcFy/5FdiVAiadT/R8YdVcgS3P5XUCWgiPDPAZCMQr+t3EMCnIarwZ3jHP9r/AGvVrsE/TihEwCFU97+qSIWxhSD1P51oVyHlJ/Y/TS7GwDqOzT9Zayi1F9HcvwM/qmG/J8w/pkdTPZl/2j+2gTtQpzyuP1FM3gAz37m/9XaV/9oLpj/UpTW8D/aUPx+tILws3JA/KCzxgLLJI0AjWuFMAoq3P0ijZVGWKX8/u7SG98Gekz8XqHtTR32gvyErruBtlIs/M3PchNYetb+geISJ9fyPP2k1JO6x9JG/uM0zel6/aj+SPq2iPzTNv36w58ZPPpi/ByObUC3HpD8+GMJ7WLmRvy18fa1LjcY/AAAAQPsh+T8AAAAALUR0PgAAAICYRvg8AAAAYFHMeDsAAACAgxvwOQAAAEAgJXo4AAAAgCKC4zYAAAAAHfNpNQAAAAAAAPC/VAQBAOgqAAADAAAAEC0AAAMAAADoLwAAAwAAALAwAAADAAAAADIAAAMAAAB4NQAAAwAAALQ4AAADAAAAxC4AAAMAAAB8OQAAAwAAAIQ6AAADAAAAED8AAAMAAAA0PQAAAAAAANQsAAAAAAAAwC8AAAAAAAAQMAAAAAAAANgxAAAAAAAAKDIAAAAAAACMOAAAAAAAAGAuAAAAAAAAVDkAAAAAAABcOgAAAAAAAOg+AAAAAAAADD0AAAQAAAA4PwAAAAAAAAAAAAAAAAAAAAAAAAEAAAACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAUAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAACAAAAAQAAAAEAAAADAAAAAAAAAAAAAAAAzQIAEM0CACDNAgAwzQIAQM0CAFDNAgBgzQIAcM0CABDNAgAQzQIAUM0CAFDNAgAfAAAAPwAAAH8AAAAAAAAA0HkBAAEAAACoKwAAaAAAAAQAAABtCAEAAQAAACAsAACIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACAUBAAEAAAAAAAAA4AAAAAAAAAAQBQEAAQAAAAAAAADgAAAAAQAAABcFAQABAAAAAAAAAKgAAAACAAAAIQUBAAEAAAAAAAAA4AAAAAMAAAArBQEAAQAAAAAAAADgAAAABAAAADkFAQABAAAAAAAAAOAAAAAFAAAAQwUBAAEAAAAAAAAA4AAAAAYAAABQBQEAAQAAAAAAAADgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAYAAAAHAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAA/////wAAAAAAAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAcggBAAEAAADELQAAGAEAAAEAAAB3CAEAAQAAAMQtAAAYAQAAAgAAAH0IAQABAAAAxC0AABgBAAADAAAAhggBAAEAAADELQAAGAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAJAIAQABAAAAAAAAAHABAAABAAAAmggBAAEAAAAAAAAAcAEAAAIAAAClCAEAAQAAAAAAAAA4AQAAAwAAALMIAQABAAAAAAAAADgBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACAAAAAkAAAAAAAAAAAAAAAoAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACwAAAAwAAAANAAAADgAAAAAAAAAAAAAAAAAAAAAAAAAFAAAAAQAAAAYAAAACAAAAAgAAAAcAAAACAAAAAAAAAFgMAgBd9QEA7vYBAC79AQAlBAIAZAgCAOQLAgD1CwIAAAAAAPoIAQABAAAAKC8AAKgBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD+CAEAAQAAAAAAAADIAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAABAAAABgkBAAEAAAA4MAAAAAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADwAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAD4KAQABAAAAAAAAACACAAACAAAASAoBAAEAAAAAAAAAWAIAAAAAAABRCgEAAQAAAAAAAABYAgAAAwAAAFoKAQABAAAAAAAAAFgCAAAAAAAAZAoBAAEAAAAAAAAAIAIAAAMAAABwCgEAAQAAAAAAAAAgAgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABEAAAASAAAAAAAAAAAAAAATAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABQAAAAVAAAAFgAAABcAAAAAAAAAAAAAAAAAAAAAAAAACAAAAAMAAAAJAAAAAwAAAAMAAAAKAAAABAAAAAAAAABYDAIAXfUBAC79AQDu9gEAZAgCACUEAgD1CwIA5AsCAAAAAAAAAAAALQwBAP////88MQAAkAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADAMAQD/////AAAAALACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADWgQEAAQAAAFAyAADoAgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAYAAAAGQAAABoAAAAAAAAABAAAAAAAAAAbAAAAHAAAAB0AAAAeAAAAAAAAAAAAAAAAAAAAAAAAAB8AAAAgAAAAIQAAACIAAAACAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAMAAAABQAAAAQAAAANAAAABQAAAAMAAAAtEAEAOxABAFEQAQDr7QIAXxABAG4QAQBzEAEAkRABAOvtAgCjEAEA0xABAOvtAgDxEAEAGREBACcRAQBWEQEAihEBAJsRAQDAEQEA4xEBAOkRAQAFEgEAIhIBAD0SAQBeEgEAeBIBAJoSAQC5EgEA3xIBAPcSAQAXEwEANBMBAFgTAQBkEwEA6+0CAG8TAQCVEwEAuRMBAN8TAQDr7QIAFRQBAC0UAQA6FAEAaRQBAGQTAQDr7QIAdhQBAH8UAQCgFAEA2xQBACYVAQB6FQEAnBUBALEVAQDIFQEA3hUBAPYVAQDr7QIADBYBACcWAQBLFgEAbxYBAJQWAQDr7QIAtRYBAM8WAQDhFgEA7hYBAPsWAQAPFwEAHhcBACYXAQA7FwEASRcBAIcXAQCSFwEAZBMBAOvtAgCYFwEApBcBALMXAQDjEQEA6+0CAMYXAQDvFwEADRgBAB0YAQAuGAEANRgBAEQYAQBUGAEAmBgBAJ8YAQDjEQEA6+0CAKkYAQDVGAEA4BgBAOkYAQDyGAEAAxkBABQZAQAoGQEAZBMBAOvtAgA0GQEARBkBAFIZAQBgGQEAbRkBAHoZAQCQGQEAmRkBAKgZAQC1GQEAxhkBAGQTAQDr7QIA0RkBAPAZAQDr7QIAAhoBABEaAQBBGgEASxoBAFgaAQBlGgEAchoBAH8aAQCCGgEA6+0CAIYaAQDr7QIAqRoBANoaAQAJGwEAIBsBADsbAQBWGwEAZBMBAOvtAgByGwEA6+0CAJobAQCmGwEAuRsBAMwbAQDhGwEA9hsBAPobAQDjEQEA6+0CAAYcAQDr7QIAFhwBACQcAQAwHAEAPRwBAF0cAQBzHAEA6+0CAIccAQDQHAEAFh0BAEYdAQB5HQEAgB0BAKcdAQDOHQEA6+0CANMdAQAAAAAAAAAAAJFHAQABAAAAAAAAAAgDAAABAAAARx4BAAEAAAAAAAAACAMAAAIAAACKRwEAAQAAAAAAAABAAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAjAAAAAAAAACQAAAAlAAAABgAAACYAAAAnAAAAKAAAACkAAAAqAAAAAAAAAAAAAAAAAAAAAAAAACsAAAAsAAAALQAAAC4AAAAEAAAALwAAAAAAAAAAAAAADgAAAAAAAAAPAAAABwAAAAUAAAAQAAAABgAAAAAAAAB19AEAf/QBABExAQDE9AEA//QBACH1AQAn9QEAWAwCAE71AQBd9QEAevUBAIX1AQCn9QEA3fUBABP2AQBO9gEAhPYBAKb2AQC19gEA5vYBAO72AQDXJAEA4CQBAAv3AQDpJAEAVfcBAPIkAQBf9wEA+yQBAGn3AQC49wEA8/cBAAclAQAu+AEAOfgBAH74AQCM+AEA1vgBAOT4AQDy+AEA/fgBAC75AQBu+QEAdvkBAH75AQC5+QEA7/kBAPv5AQAWMQEAB/oBABH6AQAc+gEAOfoBAG/6AQAu/QEAUP0BAFz9AQAbAAIATAACAHgAAgCuAAIAuwACAN0AAgD/AAIACAECAFIBAgBcAQIAoQECANcBAgDiAQIAZwICAHwCAgAPJQEAhgICAJACAgDGAgIABgMCABQDAgBoAwIAdwMCAIYDAgDVAwIAHjEBABUEAgAfBAIAJQQCAFEEAgB4BAIAiQQCAJQEAgDZBAIAHgUCAC0FAgA9BQIATwUCAF8FAgBvBQIAfAUCAIYFAgC8BQIAxQUCAAUGAgAYBgIAIzEBACAGAgBWBgIAfQYCALMGAgDaBgIA6AYCAB4HAgBoBwIAsgcCAL0HAgDzBwIA+AcCABUIAgAyCAIAPQgCAGQIAgB8CAIAsggCAOgIAgD0CAIAGwkCACYJAgBXCQIAiAkCABA8AQCvCQIA2wkCABEKAgBHCgIAUQoCAG4KAgCuCgIA5AoCACkxAQD8CgIAKAsCAE8LAgCFCwIAwgsCAOQLAgDqCwIA9QsCABwMAgAAAAAA2YEBAAEAAADINQAAeAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAGhIAQABAAAAAAAAAJgDAAAAAAAAAAAAAAAAAAAAAAAAAAAAADAAAAAAAAAAMQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMgAAAAAAAAAzAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAARAAAAAAAAABIAAAAIAAAABgAAABMAAAAHAAAAAAAAAAAAAABFJgEAAQAAANw4AADQAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAASCYBAAEAAAAAAAAA8AMAAAAAAAAAAAAAAAAAAAAAAAAAAAAANAAAAAAAAAA1AAAANgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABQAAADcAAAAAAAAAAAAAABQAAAAAAAAAFQAAAAkAAAAHAAAAFgAAAAgAAAAAAAAAETEBAFgMAgBd9QEAFjEBAG/6AQAu/QEAHjEBAFEEAgAFBgIAIzEBAD0IAgBkCAIAEDwBACkxAQDkCwIA9QsCAAAAAAAuMQEAAQAAAKQ5AAAoBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMjEBAAEAAAAAAAAASAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAOAAAAAAAAAA5AAAAOgAAAAoAAAA7AAAAPAAAAD0AAAA+AAAAPwAAAAAAAAAAAAAAAAAAAAAAAABAAAAAQQAAAEIAAABDAAAAAAAAAAAAAAAAAAAAAAAAABcAAAAAAAAAGAAAAAsAAAAIAAAAGQAAAAkAAAAAAAAAxPQBAKY6AQBYDAIAXfUBAHr1AQCxOgEAtzoBAMI6AQDJOgEAhfUBAN31AQDROgEA1zoBAOI6AQCE9gEApvYBAO72AQDpOgEAVfcBAGn3AQDz9wEA8zoBAH74AQCM+AEA1vgBAP46AQDk+AEABjsBAA87AQAdOwEAJzsBALn5AQAwOwEA+/kBABz6AQA5+gEANjsBAID6AQCr+gEA1PoBAPf6AQAg+wEAQ/sBAGz7AQCP+wEAuPsBANv7AQAE/AEAJ/wBAFD8AQBz/AEAnPwBAL/8AQDo/AEAC/0BAC79AQA9OwEAUP0BAEk7AQB4AAIA3QACAKEBAgBWOwEAhgMCAGM7AQAVBAIAJQQCAG07AQBRBAIAeAQCAIkEAgB8OwEAjjsBAJQEAgAeBQIALQUCAD0FAgBPBQIAXwUCAJ47AQCpOwEAtDsBAG8FAgAFBgIACgYCALk7AQDCOwEAyzsBANs7AQDiOwEAVgYCAH0GAgCzBgIA6AYCAPgHAgAVCAIA6jsBAGQIAgDxOwEA9AgCAPo7AQAmCQIAAjwBAIgJAgAQPAEArwkCANsJAgAXPAEAbgoCAK4KAgAhPAEA5AoCAPwKAgBPCwIAKzwBADk8AQCFCwIAjAsCAMILAgDkCwIA9QsCABwMAgAAAAAASzwBAAEAAACsOgAAgAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAE88AQABAAAAAAAAAKAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAARAAAAEUAAAAAAAAAAAAAAEYAAABHAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAaAAAAAAAAABsAAAAMAAAACQAAABwAAAAKAAAAAAAAAEFCAADelQEAQUkAALiVAQBBUgAAi5UBAEFYAADzlQEAQiAAAC+YAQBCSQAAQJgBAENCAAB4lgEAQ08AAGaWAQBDWAAAhZYBAEggAACplgEASEIAALOWAQBISQAAP5cBAEhYAADClgEASGIAAPOWAQBIaQAAJpcBAEhyAADYlgEASHgAAAmXAQBJIAAAUZgBAEtCAAAKlgEAS0kAAFKWAQBLUgAAPpYBAEtYAAArlgEATkIAAFGXAQBOSQAAmJcBAE5SAACwlwEATlgAAHyXAQBQQQAAEZgBAFBCAADNlwEAUEkAAAGYAQBQWAAA7ZcBAFIgAAAImgEAUyAAACCYAQBaRAAAjpgBAAAAAAAAAAAAAQAAAAAAAAD+RgEA/////1w9AADYBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkcBAP////8AAAAA+AQAAAAAAAAAAAAAAAAAAAAAAAAAAAAADwAAAApHAQABAAAAIEMAAAAAAAAQAAAAEkcBAAEAAAAgQwAAAAAAABEAAAAaRwEAAQAAACBDAAAAAAAAEQAAACNHAQABAAAAIEMAAAAAAAARAAAAK0cBAAEAAAAgQwAAAAAAABMAAAAzRwEAAQAAACRDAAAAAAAAFAAAADtHAQABAAAAJEMAAAAAAAAVAAAAQ0cBAAEAAAAkQwAAAAAAABUAAABMRwEAAQAAACRDAAAAAAAAFQAAAFRHAQABAAAAJEMAAAAAAAAWAAAAXEcBAAEAAAAoQwAAAAAAABcAAABlRwEAAQAAAChDAAAAAAAAGAAAAG5HAQABAAAAKEMAAAAAAAAYAAAAeEcBAAEAAAAoQwAAAAAAABgAAACBRwEAAQAAAChDAAAAAAAAGQAAAIpHAQABAAAALEMAAAAAAAAZAAAAkUcBAAEAAAAsQwAAAAAAABoAAACXRwEAAQAAADBDAAAAAAAACgAAAKBHAQABAAAANEMAAAAAAAALAAAAqEcBAAEAAAA0QwAAAAAAAAwAAACwRwEAAQAAADRDAAAAAAAADAAAALlHAQABAAAANEMAAAAAAAAMAAAAwUcBAAEAAAA0QwAAAAAAAA4AAADJRwEAAQAAADRDAAAAAAAADgAAANBHAQABAAAANEMAAAAAAAANAAAA2EcBAAEAAAA0QwAAAAAAAAUAAADgRwEAAQAAADRDAAAAAAAABgAAAOhHAQABAAAANEMAAAAAAAAHAAAA8EcBAAEAAAA0QwAAAAAAAAcAAAD5RwEAAQAAADRDAAAAAAAABwAAAAFIAQABAAAANEMAAAAAAAAJAAAACUgBAAEAAAA0QwAAAAAAAAkAAAAQSAEAAQAAADRDAAAAAAAACAAAABhIAQABAAAANEMAAAAAAAAAAAAAIEgBAAEAAAA4QwAAAAAAAAEAAAApSAEAAQAAADhDAAAAAAAAAgAAADJIAQABAAAAOEMAAAAAAAACAAAAPEgBAAEAAAA4QwAAAAAAAAIAAABFSAEAAQAAADhDAAAAAAAABAAAAE5IAQABAAAAOEMAAAAAAAAEAAAAVkgBAAEAAAA4QwAAAAAAAAMAAABfSAEAAQAAADhDAAAAAAAAEgAAAGhIAQABAAAAIEMAAAAAAAAbAAAAcEgBAAEAAAA8QwAAAAAAABwAAAB4SAEAAQAAADxDAAAAAAAAHQAAAIBIAQABAAAAPEMAAAAAAAAdAAAAiUgBAAEAAAA8QwAAAAAAAB0AAACRSAEAAQAAADxDAAAAAAAAHgAAAJlIAQABAAAAQEMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA0AAAAOAAAADwAAABAAAAARAAAAEgAAABMAAAAUAAAAFQAAAARMAQBMQwAAAQAAAGhDAAAAAAAAAAAAAEgAAABJAAAAAQAAAAAAAADQeQEAAAAAAFxDAABkQwAAAAAAAAAAAAAAAAAAAAAAAAAAAAABAAAAAgAAAAAAAAABAAAAAQAAAAEAAAABAAAAAgAAAAIAAAABAAAAAgAAAAQAAAAYAQAAMAEAALAAAAApVAEALlQBADJUAQA5VAEAPVQBAAAAAAABAAAAAgAAAAMAAAAEAAAABQAAAAAAAAAdAAAAAAAAAAAAAAAeAAAAAAAAAAAAAAAfAAAAAAAAAAAAAAAyWQEAKEQAAAEAAAB4RAAAAAAAAAAAAABKAAAASwAAAEwAAABNAAAATgAAAE8AAABQAAAAUQAAAFIAAABLAAAAUwAAAEsAAABUAAAAVQAAAFYAAABXAAAAAAAAAD9ZAQAAAAAAOEQAACDPAgABAAAARVkBAAAAAABARAAAIM8CAAMAAABJWQEAAAAAAEhEAAAgzwIABAAAAE9ZAQAAAAAAUEQAACDPAgAFAAAAVVkBAAAAAABoRAAAIM8CAAYAAABfWQEAAAAAAHBEAAAgzwIABwAAAGVZAQAAAAAAWEQAACDPAgAHAAAAaVkBAAAAAABYRAAAIM8CAAcAAABuWQEAAAAAAGBEAAAgzwIAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAAMAAAAAAAAAABAAAAIAAAAAEAAAAAAAAAAAAAAAAAAAADAAAABAAAAAAAAAAAAAAA6+0CAAAAAAATBgIAAQAAAHRkAQAHAAAAOGQBAAMAAAC8GQIABQAAAHxkAQAPAAAAvoEBAAgAAAC+gQEAEAAAAIRkAQAEAAAAhGQBABEAAACJZAEABQAAAIlkAQACAAAAj2QBAAYAAACWZAEABAAAAKJkAQAHAAAAqmQBAAcAAAC6ZAEABQAAAMBkAQAIAAAA12QBAAgAAADAZAEACQAAAOBkAQAHAAAA6GQBAAoAAAACZQEABwAAAAplAQALAAAAJGUBAAYAAAArZQEADAAAAEllAQAJAAAAK2UBAA0AAABTZQEACAAAAFxlAQAOAAAAfWUBAAgAAACGZQEAEgAAAKdlAQAFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIAAAABAAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAAAAAAAAAAAAAAAAACAAAAAwAAAACAAAAAAAAAAMAAAAAAAAAAAAAAAAAAAAIAAAABAAAAAAAAAADAAAAIQAAAAQAAAAAAAAAAAAAAAAAAAAIAAAABAAAAAAAAAAEAAAAIgAAAAUAAAAAAAAAAAAAAAAAAAAFAAAAQAAAACBHAAAwRwAABgAAAAQAAAA8RwAABgAAAAgAAAAGAAAABAAAAERHAAAABAAACAAAAP////8AAAAAAAAAACMAAAAAAAAAAAAAAAAAAAAAAAAANQAAAAAAAAAAAAAAIAAAAAAAAAAAAAAABgAAAAAAAAAHAAAAAAAAAAAAAAAAAAAA/////wAAAAAAAAAABgAAAAAAAAAHAAAAAAAAAAAAAAAAAAAAGAAAAAAAAAAAAAAACAAAAAAAAAAHAAAAAAAAAAAAAAAAAAAA/////wAAAAAAAAAACAAAAAAAAAAHAAAAAAAAAAAAAAAAAAAAHAAAAAAAAAAAAAAACQAAAAAAAAAHAAAAAAAAAAkAAAALAAAACAAAAAoAAADISAAATEgAALBIAAABAAAAAQAAAAoAAAAWAAAACwAAAFgAAAAkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMAAAAAAAAAAcAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAAAAAAANAAAAAAAAAAcAAAAAAAAABwAAAAIAAAAFAAAACAAAAAAAAAAAAAAABgAAAAMAAAAOAAAACwAAAAAAAAAAAAAAAAAAAAgAAAAAAAAAAAAAAA8AAAAAAAAABwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAJQAAABAAAAAAAAAABwAAAAAAAAAIAAAACAAAAAAAAAAAAAAAJgAAAAAAAAAAAAAAAAAAAAAAAAAQAAAA/////wAAAAAAAAAAJwAAAAAAAAAAAAAABwAAAAAAAAABAAAAAAAAAAEAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAAAgAAAAMAAAABAAAAAQAAAAIAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAAAQAAAAEAAAACAAAAAQAAAAQAAAAFAAAAAQAAAAEAAAABAAAAAQAAAAEAAAABAAAABgAAAAEAAAABAAAABwAAAAgAAAAJAAAACgAAAAoAAAAKAAAACgAAAAoAAAAKAAAACgAAAAoAAAAKAAAACgAAAAEAAAABAAAACwAAAAEAAAAMAAAAAQAAAA0AAAAOAAAADwAAABAAAAARAAAAEgAAABMAAAAUAAAAFQAAABYAAAATAAAAEwAAABMAAAATAAAAFwAAABgAAAAZAAAAEwAAABoAAAAbAAAAHAAAAB0AAAATAAAAEwAAABMAAAATAAAAEwAAAAEAAAAeAAAAAQAAAAEAAAATAAAAAQAAAB8AAAAgAAAAIQAAACIAAAAjAAAAEwAAACQAAAAlAAAAJgAAABMAAAATAAAAEwAAABMAAAAnAAAAKAAAACkAAAATAAAAKgAAACsAAAAsAAAALQAAABMAAAATAAAAEwAAABMAAAATAAAAAQAAAAEAAAABAAAAAQAAAAEAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAAC4AAAATAAAAEwAAABMAAAAvAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAAwAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAABMAAAATAAAAEwAAAAAAAAABAAAAAQAAAAIAAAADAAAAAQAAAAQAAAABAAAABQAAAAEAAAAGAAAABwAAAAcAAAABAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAMAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAAAGAAAABgAAAAYAAACAAAAAb6cBAFCnAQAWcAEAfKcBAHSnAQCCpwEAAAAAABx0AQAldAEALHQBADp0AQBBdAEAmKcBAEh0AQBPdAEAAQAAAAgAAAD/////AAAAAAAAAAAoAAAAAAAAAAAAAAAAAAAAAAAAAO11AQAIAAAAAwAAAPZ1AQD6dQEACwAAAAYAAADWgQEABnYBAAIAAAABAAAACXYBAA12AQAEAAAAAgAAABJ2AQAWdgEABAAAAAQAAAAbdgEAIHYBAAUAAAAFAAAAJnYBACp2AQAEAAAABwAAAC92AQAzdgEABQAAAAkAAAA5dgEAPXYBAAQAAAAKAAAAQnYBAEd2AQAEAAAADAAAAEx2AQAQewEAAAAAAAEAAAAYewEAAQAAAAAAAACjpgEAAQAAAAEAAAATBgIAAAAAAAAAAAAAAAAAAAAAAAAAAAD5eQEAMQAAAAAAAAAAAAAA0aEBABAAAAA7EgIAgAAAAPJ5AQBAAAAAPJQBABAAAAD0eQEAQAAAAAAAAAAAAAAAwHkBAAEAAADHeQEAAgAAAMx5AQADAAAA+poBAAQAAABekQEABQAAANB5AQAGAAAAEwYCAAgAAADUeQEAIQAAANh5AQAiAAAA3HkBACIAAADgeQEAAQAAAOV5AQAHAAAA63kBACcAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAP////8AAAAAKQAAAAAAAAAAAAAAAAAAAAAAAAArfwEAMn8BAAAAAADTgQEA1oEBANmBAQAAAAAAAAAAAAEAAAACAAAA/////5aBAQCcgQEAEwYCAAAAAABkAAAAZQAAAGYAAABkAAAACAAAAAgAAAAAAAAAAAAAACoAAAARAAAAAAAAAAAAAAAAAAAACAAAAAgAAAAAAAAACQAAACsAAAARAAAAAAAAAAAAAAAAAAAACAAAAP////8AAAAAAAAAACwAAAAAAAAAAAAAAAAAAAAAAAAA+poBAPhUAACABgAAAAAAACeRAQD4VAAAsAYAAAAAAAAAmgEA+FQAAOAGAAAAAAAAL5EBAPhUAADgBgAAAAAAADSRAQD4VAAAEAcAAAAAAAA7kQEAEFUAABAHAAAAAAAAQZEBAPhUAABABwAAAAAAAEWRAQD4VAAAcAcAAAAAAAATBgIA+FQAAKAHAAAAAAAATpEBAPhUAACgBwAAAAAAAFiRAQD4VAAAUAYAAAAAAABekQEA+FQAANAHAAAAAAAAZpEBAPhUAAAACAAAAAAAAHCRAQD4VAAAMAgAAAAAAAB+kQEA+FQAAGAIAAAAAAAAhJEBAPhUAACQCAAAAAAAAI2RAQD4VAAAwAgAAAAAAACVkQEA+FQAAPAIAAAAAAAAnpEBAPhUAAAgCQAAAAAAAKaRAQD4VAAAUAkAAAAAAACrkQEA+FQAAIAJAAAAAAAAr5EBAPhUAACwCQAAAAAAALaRAQD4VAAA4AkAAAAAAAC8kQEA+FQAABAKAAAAAAAAxpEBAChVAABACgAAAAAAAM+RAQD4VAAAgAYAAAAAAADUkQEA+FQAAIAGAAAAAAAA3pEBAPhUAABwCgAAAAAAAOWRAQD4VAAAoAoAAAAAAADykQEA+FQAANAKAAAAAAAAAJIBAPhUAAAACwAAAAAAAA6SAQD4VAAAMAsAAAAAAAAakgEA+FQAAGALAAAAAAAAJ5IBAPhUAACQCwAAAAAAADCSAQD4VAAAwAsAAAAAAAA6kgEA+FQAAPALAAAAAAAAQ5IBAPhUAAAgDAAAAAAAAEuSAQD4VAAAUAwAAAAAAABTkgEA+FQAAIAMAAAAAAAAXJIBAPhUAACwDAAAAAAAAGCSAQD4VAAA4AwAAAAAAABrkgEA+FQAABANAAAAAAAAb5IBAPhUAABADQAAAAAAAHmSAQD4VAAAcA0AAAAAAACCkgEA+FQAAKANAAAAAAAAipIBAPhUAADQDQAAAAAAAJeSAQD4VAAAAA4AAAAAAACjkgEA+FQAADAOAAAAAAAArpIBAPhUAABgDgAAAAAAAL6SAQD4VAAAkA4AAAAAAADMkgEA+FQAAMAOAAAAAAAA25IBAPhUAADwDgAAAAAAAOWSAQD4VAAAIA8AAAAAAADukgEA+FQAAFAPAAAAAAAA+JIBAPhUAACADwAAAAAAAAKTAQD4VAAAsA8AAAAAAAAJkwEA+FQAAOAPAAAAAAAAEJMBAPhUAAAQEAAAAAAAABqTAQBAVQAAAAAAAAAAAAAhkwEAQFUAAAAAAAAAAAAAA5EBAFhVAAAAAAAAAAAAACmTAQBwVQAAQBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWQAAAFoAAAAXAAAABAAAAAIAAAAMAAAAWwAAAFoAAAAXAAAABQAAAAAAAAANAAAAWQAAAFoAAAAXAAAABAAAAAIAAAAMAAAAXAAAAF0AAAAYAAAABgAAAAMAAAAOAAAAXgAAAF8AAAAXAAAABwAAAAAAAAAPAAAAWQAAAFoAAAAXAAAACAAAAAIAAAAMAAAAEAAAABEAAAASAAAAEwAAACuUAQAylAEAAAAAADqUAQA8lAEAdRICAD6UAQAMAAAABAAAAAYAAAACAAAAAwAAAAEAAAAJAAAACAAAAAsAAAAMAAAADQAAAA4AAAAPAAAAEAAAABEAAAASAAAAFQAAABYAAAAXAAAAGAAAABkAAAAaAAAAGwAAABwAAAAfAAAAIAAAACEAAAAiAAAAIwAAACQAAAAlAAAAJgAAACkAAAAqAAAAKwAAACwAAAAtAAAALgAAAC8AAAAwAAAAMwAAADQAAAA1AAAANgAAADcAAAA4AAAAOQAAADoAAAA9AAAAPgAAAD8AAABAAAAAQQAAAEIAAABDAAAARAAAAEcAAABIAAAASQAAAEoAAABLAAAATAAAAE0AAABOAAAAUQAAAFIAAABTAAAAVAAAAFUAAABWAAAAVwAAAFgAAACLlQEAm5UBAKiVAQAAAAAAAAAAAAQAAACtlQEAAAAAAAAAAAC4lQEAm5UBAKiVAQAAAAAAz5UBAAUAAACtlQEAAAAAANeVAQDelQEAm5UBAO6VAQAAAAAAAAAAAAYAAACtlQEAGaYBAAAAAADzlQEAm5UBAO6VAQAAAAAAz5UBAAcAAACtlQEAGaYBANeVAQAKlgEAF5YBAO6VAQAAAAAAAAAAAAoAAAAllgEAGaYBAAAAAAArlgEAF5YBAO6VAQAAAAAA15UBAAsAAAAllgEAGaYBANeVAQA+lgEAF5YBAEyWAQAAAAAAAAAAAAgAAAAllgEAAAAAAAAAAABSlgEAF5YBAEyWAQAAAAAA15UBAAkAAAAllgEAAAAAANeVAQBmlgEAZpYBAAAAAAAAAAAAAAAAAAwAAABulgEAAAAAAAAAAAB4lgEAZpYBABmmAQAAAAAAAAAAAA4AAABulgEAGaYBAAAAAACFlgEAZpYBABmmAQAAAAAAz5UBAA8AAABulgEAGaYBANeVAQCZlgEAZpYBAAAAAAAAAAAAz5UBAA0AAABulgEAAAAAANeVAQCplgEAqZYBAAAAAAAAAAAAAAAAABAAAACtlQEAAAAAAAAAAACzlgEAqZYBABmmAQAAAAAAAAAAABIAAACtlQEAGaYBAAAAAADClgEAqZYBABmmAQAAAAAAz5UBABMAAACtlQEAGaYBANeVAQDYlgEAqZYBAAAAAADplgEAAAAAABQAAACtlQEAAAAAAAAAAADzlgEAqZYBABmmAQDplgEAAAAAABYAAACtlQEAGaYBAAAAAAAJlwEAqZYBABmmAQDplgEAz5UBABcAAACtlQEAGaYBANeVAQAmlwEAqZYBAAAAAADplgEAz5UBABUAAACtlQEAAAAAANeVAQA/lwEAqZYBAAAAAAAAAAAAz5UBABEAAACtlQEAAAAAANeVAQBRlwEAZ5cBABmmAQAAAAAAAAAAABoAAAAllgEAGaYBAAAAAAB8lwEAZ5cBABmmAQAAAAAA15UBABsAAAAllgEAGaYBANeVAQCYlwEAZ5cBAAAAAAAAAAAA15UBABkAAAAllgEAAAAAANeVAQCwlwEAZ5cBAMeXAQAAAAAAAAAAABgAAAAllgEAAAAAAAAAAADNlwEA25cBABmmAQAAAAAAAAAAAB4AAAAllgEAGaYBAAAAAADtlwEA25cBABmmAQAAAAAA15UBAB8AAAAllgEAGaYBANeVAQABmAEA25cBAAAAAAAAAAAA15UBAB0AAAAllgEAAAAAANeVAQARmAEA25cBAMeXAQAAAAAAAAAAABwAAAAllgEAAAAAAAAAAAAgmAEAIJgBAAAAAAAAAAAAAAAAACAAAAAnmAEAAAAAAAAAAAAvmAEAOpgBABmmAQAAAAAAAAAAAAIAAAAllgEAGaYBAAAAAABAmAEAOpgBABmmAQAAAAAA15UBAAMAAAAllgEAGaYBANeVAQBRmAEAOpgBAAAAAAAAAAAA15UBAAEAAAAllgEAAAAAANeVAQAImgEAOpgBAAAAAAAAAAAAAAAAAAAAAAAllgEAAAAAAAAAAABemAEAeJgBAIeYAQAAAAAA15UBACEAAAAllgEAAAAAANeVAQCOmAEAm5gBAAAAAAAAAAAAAAAAACIAAAAnmAEAAAAAAAAAAAAIAAAABAAAAAAAAAAKAAAALQAAABIAAAAAAAAAAAAAAAAAAAAIAAAA/////wAAAAAAAAAALgAAAAAAAAAAAAAAAAAAAAAAAAA3mwEAxgAAAD2bAQDBAAAARJsBAMIAAABKmwEAwAAAAFGbAQCRAwAAV5sBAMUAAABdmwEAwwAAAGSbAQDEAAAAaZsBAJIDAABumwEAxwAAAHWbAQCnAwAAeZsBACEgAACAmwEAlAMAAIabAQDQAAAAipsBAMkAAACRmwEAygAAAJebAQDIAAAAnpsBAJUDAACmmwEAlwMAAKqbAQDLAAAAr5sBAJMDAAC1mwEAzQAAALybAQDOAAAAwpsBAMwAAADJmwEAmQMAAM6bAQDPAAAA05sBAJoDAADZmwEAmwMAAOCbAQCcAwAA45sBANEAAADqmwEAnQMAAO2bAQBSAQAA85sBANMAAAD6mwEA1AAAAACcAQDSAAAAB5wBAKkDAAANnAEAnwMAABWcAQDYAAAAHJwBANUAAAAjnAEA1gAAACicAQCmAwAALJwBAKADAAAvnAEAMyAAADWcAQCoAwAAOZwBAKEDAAA9nAEAYAEAAEScAQCjAwAASpwBAN4AAABQnAEApAMAAFScAQCYAwAAWpwBANoAAABhnAEA2wAAAGecAQDZAAAAbpwBAKUDAAB2nAEA3AAAAHucAQCeAwAAfpwBAN0AAACFnAEAeAEAAIqcAQCWAwAAj5wBAOEAAACWnAEA4gAAAJycAQC0AAAAopwBAOYAAAConAEA4AAAAK+cAQA1IQAAt5wBALEDAAC9nAEAJgAAAMGcAQAnIgAAxZwBACAiAADJnAEA5QAAAM+cAQBIIgAA1ZwBAOMAAADcnAEA5AAAAOGcAQAeIAAA55wBALIDAADsnAEApgAAAPOcAQAiIAAA+JwBACkiAAD8nAEA5wAAAAOdAQC4AAAACZ0BAKIAAAAOnQEAxwMAABKdAQDGAgAAF50BAGMmAAAdnQEARSIAACKdAQCpAAAAJ50BALUhAAAtnQEAKiIAADGdAQCkAAAAOJ0BANMhAAA9nQEAICAAAESdAQCTIQAASZ0BALAAAABNnQEAtAMAAFOdAQBmJgAAWZ0BAPcAAABgnQEA6QAAAGedAQDqAAAAbZ0BAOgAAAB0nQEABSIAAHqdAQADIAAAf50BAAIgAACEnQEAtQMAAIydAQBhIgAAkp0BALcDAACWnQEA8AAAAJqdAQDrAAAAn50BAKwgAACknQEAAyIAAKqdAQCSAQAAr50BAAAiAAC2nQEAvQAAAL2dAQC8AAAAxJ0BAL4AAADLnQEARCAAANGdAQCzAwAA150BAGUiAADanQEAPgAAAN2dAQDUIQAA4p0BAJQhAADnnQEAZSYAAO6dAQAmIAAA9Z0BAO0AAAD8nQEA7gAAAAKeAQChAAAACJ4BAOwAAAAPngEAESEAABWeAQAeIgAAG54BACsiAAAfngEAuQMAACSeAQC/AAAAK54BAAgiAAAwngEA7wAAADWeAQC6AwAAO54BANAhAABAngEAuwMAAEeeAQApIwAATJ4BAKsAAABSngEAkCEAAFeeAQAIIwAAXZ4BABwgAABjngEAZCIAAGaeAQAKIwAAbZ4BABciAAB0ngEAyiUAAHieAQAOIAAAfJ4BADkgAACDngEAGCAAAImeAQA8AAAAjJ4BAK8AAACRngEAFCAAAJeeAQC1AAAAnZ4BALcAAAA8pwEAEiIAAKSeAQC8AwAAp54BAAciAACtngEAoAAAALKeAQATIAAAuJ4BAGAiAAC7ngEACyIAAL6eAQCsAAAAwp4BAAkiAADIngEAhCIAAM2eAQDxAAAA1J4BAL0DAADXngEA8wAAAN6eAQD0AAAA5J4BAFMBAADqngEA8gAAAPGeAQA+IAAA954BAMkDAAD9ngEAvwMAAAWfAQCVIgAAC58BACgiAAAOnwEAqgAAABOfAQC6AAAAGJ8BAPgAAAAfnwEA9QAAACafAQCXIgAALZ8BAPYAAAAynwEAtgAAADefAQACIgAAPJ8BADAgAABDnwEApSIAAEifAQDGAwAATJ8BAMADAABPnwEA1gMAAFOfAQCxAAAAWp8BAKMAAABgnwEAMiAAAGafAQAPIgAAa58BAB0iAABwnwEAyAMAAHSfAQAiAAAAeZ8BANIhAAB+nwEAGiIAAISfAQAqIwAAiZ8BALsAAACPnwEAkiEAAJSfAQAJIwAAmp8BAB0gAACgnwEAHCEAAKWfAQCuAAAAqZ8BAAsjAACwnwEAwQMAALSfAQAPIAAAuJ8BADogAAC/nwEAGSAAAMWfAQAaIAAAy58BAGEBAADSnwEAxSIAANefAQCnAAAA3J8BAK0AAADgnwEAwwMAAOafAQDCAwAA7Z8BADwiAADxnwEAYCYAAPifAQCCIgAA/J8BAIYiAAABoAEAESIAAAWgAQCDIgAACaABALkAAAAOoAEAsgAAABOgAQCzAAAAGKABAIciAAAdoAEA3wAAACOgAQDEAwAAJ6ABADQiAAAuoAEAuAMAADSgAQDRAwAAPaABAAkgAABEoAEA/gAAAEqgAQDcAgAAUKABANcAAABWoAEAIiEAAFygAQDRIQAAYaABAPoAAABooAEAkSEAAG2gAQD7AAAAc6ABAPkAAAB6oAEAqAAAAH6gAQDSAwAAhKABAMUDAACMoAEA/AAAAJGgAQAYIQAAmKABAL4DAACboAEA/QAAAKKgAQClAAAApqABAP8AAACroAEAtgMAALCgAQANIAAAtKABAAwgAAAHAAAACAAAAAEBAAAIAAAACAAAAAAAAAAAAAAALwAAABMAAAAAAAAAAAAAAAAAAAAIAAAAEAAAAAAAAAAAAAAAMAAAABQAAAAAAAAAAAAAAAAAAAD8pgEACQAAAP6mAQAKAAAAA6cBAAoAAAALpwEACwAAABGnAQALAAAAGqcBAAwAAAAdpwEADAAAACOnAQANAAAAKKcBAA0AAAAwpwEADgAAADWnAQAOAAAAPKcBAA8AAABCpwEADwAAAE6nAQAQAAAAYAAAADEAAAAyAAAAFAAAADMAAABhAAAANAAAABUAAAA1AAAACAAAAAQAAAD/////AAAAAAAAAAAVAAAAAAAAAAAAAAAAAAAAmagBAFVdyX/Jf/8ApKgBALst1L6u1P8Ar6gBABR3/f3Ahv8AuqgBAFVdyX/Jf/8AxagBALst1L6u1P8A0KgBABR3/f3Ahv8A26gBACpm////mf8A5qgBAFVdyX/Jf/8A8agBALst1L6u1P8A/KgBABR3/f3Ahv8AB6kBACpm////mf8AEqkBAJetsDhssP8AHakBAFVdyX/Jf/8AKKkBALst1L6u1P8AM6kBABR3/f3Ahv8APqkBACpm////mf8ASakBAJetsDhssP8AVKkBAOj88PACf/8AX6kBAFVdyX/Jf/8AaqkBALst1L6u1P8AdakBABR3/f3Ahv8AgKkBACpm////mf8Ai6kBAJetsDhssP8AlqkBAOj88PACf/8AoakBABHgv79bF/8ArKkBAFVdyX/Jf/8At6kBALst1L6u1P8AwqkBABR3/f3Ahv8AzakBACpm////mf8A2KkBAJetsDhssP8A46kBAOj88PACf/8A7qkBABHgv79bF/8A+akBAAAAZmZmZv8ABKoBAJMZ997r9/8ADqoBAI5L4Z7K4f8AGKoBAJG8vTGCvf8AIqoBAJ8Q/+/z//8ALKoBAI8u573X5/8ANqoBAI9/1muu1v8AQKoBAJPQtSFxtf8ASqoBAJ8Q/+/z//8AVKoBAI8u573X5/8AXqoBAI9/1muu1v8AaKoBAJG8vTGCvf8AcqoBAJXxnAhRnP8AfKoBAJ8Q/+/z//8AhqoBAJQr78bb7/8AkKoBAI5L4Z7K4f8AmqoBAI9/1muu1v8ApKoBAJG8vTGCvf8ArqoBAJXxnAhRnP8AuKoBAJ8Q/+/z//8AwqoBAJQr78bb7/8AzKoBAI5L4Z7K4f8A1qoBAI9/1muu1v8A4KoBAJCpxkKSxv8A6qoBAJPQtSFxtf8A9KoBAJfxlAhFlP8A/qoBAJQI//f7//8ACKsBAJMZ997r9/8AEqsBAJQr78bb7/8AHKsBAI5L4Z7K4f8AJqsBAI9/1muu1v8AMKsBAJCpxkKSxv8AOqsBAJPQtSFxtf8ARKsBAJfxlAhFlP8ATqsBAJQI//f7//8AWKsBAJMZ997r9/8AYqsBAJQr78bb7/8AbKsBAI5L4Z7K4f8AdqsBAI9/1muu1v8AgKsBAJCpxkKSxv8AiqsBAJPQtSFxtf8AlKsBAJXxnAhRnP8AnqsBAJjrawgwa/8AqKsBABfvVFQwBf8AsqsBAHf/PAA8MP8AvasBABfsjIxRCv8Ax6sBABjCv7+BLf8A0asBAB1w39/Cff8A26sBAB409vbow/8A5asBAHkm6sfq5f8A76sBAHhfzYDNwf8A+asBAHyllzWXj/8AA6wBAHz8ZgFmXv8ADawBABfvVFQwBf8AF6wBAHz8ZgFmXv8AIqwBAHf/PAA8MP8ALawBABfsjIxRCv8AN6wBABjCv7+BLf8AQawBAB1w39/Cff8AS6wBAB409vbow/8AVawBAAAA9fX19f8AX6wBAHkm6sfq5f8AaawBAHhfzYDNwf8Ac6wBAHyllzWXj/8AfawBAByH2NizZf8AhqwBAAAA9fX19f8Aj6wBAHt/tFq0rP8AmKwBABXXpqZhGv8AoawBAB1w39/Cff8AqqwBAHhfzYDNwf8As6wBAHn9hQGFcf8AvKwBABXXpqZhGv8AxawBAB1w39/Cff8AzqwBAAAA9fX19f8A16wBAHhfzYDNwf8A4KwBAHn9hQGFcf8A6awBABfsjIxRCv8A8qwBAByH2NizZf8A+6wBAB409vbow/8ABK0BAHkm6sfq5f8ADa0BAHt/tFq0rP8AFq0BAHz8ZgFmXv8AH60BABfsjIxRCv8AKK0BAByH2NizZf8AMa0BAB409vbow/8AOq0BAAAA9fX19f8AQ60BAHkm6sfq5f8ATK0BAHt/tFq0rP8AVa0BAHz8ZgFmXv8AXq0BABfsjIxRCv8AZ60BABjCv7+BLf8AcK0BAB1w39/Cff8Aea0BAB409vbow/8Agq0BAHkm6sfq5f8Ai60BAHhfzYDNwf8AlK0BAHyllzWXj/8Ana0BAHz8ZgFmXv8Apq0BABfsjIxRCv8Ar60BABjCv7+BLf8AuK0BAB1w39/Cff8Awa0BAB409vbow/8Ayq0BAAAA9fX19f8A060BAHkm6sfq5f8A3K0BAHhfzYDNwf8A5a0BAHyllzWXj/8A7q0BAHz8ZgFmXv8A960BAIcU+eX1+f8AAK4BAHVK2JnYyf8ACa4BAGe5oiyiX/8AEq4BAIgO++34+/8AG64BAH824rLi4v8AJK4BAHF4wmbCpP8ALa4BAGK+iyOLRf8ANq4BAIgO++34+/8AP64BAH824rLi4v8ASK4BAHF4wmbCpP8AUa4BAGe5oiyiX/8AWq4BAGb/bQBtLP8AY64BAIgO++34+/8AbK4BAHci7Mzs5v8Ada4BAHVK2JnYyf8Afq4BAHF4wmbCpP8Ah64BAGe5oiyiX/8AkK4BAGb/bQBtLP8Ama4BAIgO++34+/8Aoq4BAHci7Mzs5v8Aq64BAHVK2JnYyf8AtK4BAHF4wmbCpP8Ava4BAGmfrkGudv8Axq4BAGK+iyOLRf8Az64BAGb/WABYJP8A2K4BAIYG/ff8/f8A4a4BAIcU+eX1+f8A6q4BAHci7Mzs5v8A864BAHVK2JnYyf8A/K4BAHF4wmbCpP8ABa8BAGmfrkGudv8ADq8BAGK+iyOLRf8AF68BAGb/WABYJP8AIK8BAIYG/ff8/f8AKa8BAIcU+eX1+f8AMq8BAHci7Mzs5v8AO68BAHVK2JnYyf8ARK8BAHF4wmbCpP8ATa8BAGmfrkGudv8AVq8BAGK+iyOLRf8AX68BAGb/bQBtLP8AaK8BAGX/RABEG/8Aca8BAJAU9ODs9P8Aeq8BAJRG2p682v8Ag68BAMR7p4hWp/8AjK8BAIgO++34+/8Ala8BAJI147PN4/8Anq8BAKJKxoyWxv8Ap68BAMqVnYhBnf8AsK8BAIgO++34+/8Aua8BAJI147PN4/8Awq8BAKJKxoyWxv8Ay68BAMR7p4hWp/8A1K8BANbhgYEPfP8A3a8BAIgO++34+/8A5q8BAJQr5r/T5v8A768BAJRG2p682v8A+K8BAKJKxoyWxv8AAbABAMR7p4hWp/8ACrABANbhgYEPfP8AE7ABAIgO++34+/8AHLABAJQr5r/T5v8AJbABAJRG2p682v8ALrABAKJKxoyWxv8AN7ABAL5ksYxrsf8AQLABAMqVnYhBnf8ASbABANX8bm4Ba/8AUrABAIYG/ff8/f8AW7ABAJAU9ODs9P8AZLABAJQr5r/T5v8AbbABAJRG2p682v8AdrABAKJKxoyWxv8Af7ABAL5ksYxrsf8AiLABAMqVnYhBnf8AkbABANX8bm4Ba/8AmrABAIYG/ff8/f8Ao7ABAJAU9ODs9P8ArLABAJQr5r/T5v8AtbABAJRG2p682v8AvrABAKJKxoyWxv8Ax7ABAL5ksYxrsf8A0LABAMqVnYhBnf8A2bABANbhgYEPfP8A4rABANX/TU0AS/8A67ABAHLTnhued/8A9bABABL82dlfAv8A/7ABAK1fs3Vws/8ACbEBAHLTnhued/8AE7EBABL82dlfAv8AHbEBAK1fs3Vws/8AJ7EBAOnR5+cpiv8AMbEBAHLTnhued/8AO7EBABL82dlfAv8ARbEBAK1fs3Vws/8AT7EBAOnR5+cpiv8AWbEBAD7QpmamHv8AY7EBAHLTnhued/8AbbEBABL82dlfAv8Ad7EBAK1fs3Vws/8AgbEBAOnR5+cpiv8Ai7EBAD7QpmamHv8AlbEBAB/85uarAv8An7EBAHLTnhued/8AqbEBABL82dlfAv8As7EBAK1fs3Vws/8AvbEBAOnR5+cpiv8Ax7EBAD7QpmamHv8A0bEBAB/85uarAv8A27EBABvSpqZ2Hf8A5bEBAHLTnhued/8A77EBABL82dlfAv8A+bEBAK1fs3Vws/8AA7IBAOnR5+cpiv8ADbIBAD7QpmamHv8AF7IBAB/85uarAv8AIbIBABvSpqZ2Hf8AK7IBAAAAZmZmZv8ANbIBAEwZ8+Dz2/8APrIBAF893ajdtf8AR7IBAIyqykOiyv8AULIBAEER+fD56P8AWbIBAFcu5LrkvP8AYrIBAHtlzHvMxP8Aa7IBAI3FviuMvv8AdLIBAEER+fD56P8AfbIBAFcu5LrkvP8AhrIBAHtlzHvMxP8Aj7IBAIyqykOiyv8AmLIBAJHzrAhorP8AobIBAEER+fD56P8AqrIBAE0p68zrxf8As7IBAF893ajdtf8AvLIBAHtlzHvMxP8AxbIBAIyqykOiyv8AzrIBAJHzrAhorP8A17IBAEER+fD56P8A4LIBAE0p68zrxf8A6bIBAF893ajdtf8A8rIBAHtlzHvMxP8A+7IBAImg006z0/8ABLMBAI3FviuMvv8ADbMBAJPynghYnv8AFrMBADwM/Pf88P8AH7MBAEwZ8+Dz2/8AKLMBAE0p68zrxf8AMbMBAF893ajdtf8AOrMBAHtlzHvMxP8AQ7MBAImg006z0/8ATLMBAI3FviuMvv8AVbMBAJPynghYnv8AXrMBADwM/Pf88P8AZ7MBAEwZ8+Dz2/8AcLMBAE0p68zrxf8AebMBAF893ajdtf8AgrMBAHtlzHvMxP8Ai7MBAImg006z0/8AlLMBAI3FviuMvv8AnbMBAJHzrAhorP8AprMBAJbvgQhAgf8Ar7MBAEoV9eX14P8AurMBAFBI2aHZm/8AxbMBAGKyozGjVP8A0LMBAEkP+O346f8A27MBAE425Lrks/8A5rMBAFZoxHTEdv8A8bMBAGK+iyOLRf8A/LMBAEkP+O346f8AB7QBAE425Lrks/8AErQBAFZoxHTEdv8AHbQBAGKyozGjVP8AKLQBAGb/bQBtLP8AM7QBAEkP+O346f8APrQBAE0s6cfpwP8ASbQBAFBI2aHZm/8AVLQBAFZoxHTEdv8AX7QBAGKyozGjVP8AarQBAGb/bQBtLP8AdbQBAEkP+O346f8AgLQBAE0s6cfpwP8Ai7QBAFBI2aHZm/8AlrQBAFZoxHTEdv8AobQBAGCeq0GrXf8ArLQBAGK+iyOLRf8At7QBAGz/WgBaMv8AwrQBAEgH/Pf89f8AzbQBAEoV9eX14P8A2LQBAE0s6cfpwP8A47QBAFBI2aHZm/8A7rQBAFZoxHTEdv8A+bQBAGCeq0GrXf8ABLUBAGK+iyOLRf8AD7UBAGz/WgBaMv8AGrUBAEgH/Pf89f8AJbUBAEoV9eX14P8AMLUBAE0s6cfpwP8AO7UBAFBI2aHZm/8ARrUBAFZoxHTEdv8AUbUBAGCeq0GrXf8AXLUBAGK+iyOLRf8AZ7UBAGb/bQBtLP8AcrUBAGX/RABEG/8AfbUBAAAA8PDw8P8Ah7UBAAAAvb29vf8AkbUBAAAAY2NjY/8Am7UBAAAA9/f39/8ApbUBAAAAzMzMzP8Ar7UBAAAAlpaWlv8AubUBAAAAUlJSUv8Aw7UBAAAA9/f39/8AzbUBAAAAzMzMzP8A17UBAAAAlpaWlv8A4bUBAAAAY2NjY/8A67UBAAAAJSUlJf8A9bUBAAAA9/f39/8A/7UBAAAA2dnZ2f8ACbYBAAAAvb29vf8AE7YBAAAAlpaWlv8AHbYBAAAAY2NjY/8AJ7YBAAAAJSUlJf8AMbYBAAAA9/f39/8AO7YBAAAA2dnZ2f8ARbYBAAAAvb29vf8AT7YBAAAAlpaWlv8AWbYBAAAAc3Nzc/8AY7YBAAAAUlJSUv8AbbYBAAAAJSUlJf8Ad7YBAAAA//////8AgbYBAAAA8PDw8P8Ai7YBAAAA2dnZ2f8AlbYBAAAAvb29vf8An7YBAAAAlpaWlv8AqbYBAAAAc3Nzc/8As7YBAAAAUlJSUv8AvbYBAAAAJSUlJf8Ax7YBAAAA//////8A0bYBAAAA8PDw8P8A27YBAAAA2dnZ2f8A5bYBAAAAvb29vf8A77YBAAAAlpaWlv8A+bYBAAAAc3Nzc/8AA7cBAAAAUlJSUv8ADbcBAAAAJSUlJf8AF7cBAAAAAAAAAP8AIbcBABUw/v7mzv8ALbcBABOT/f2ua/8AObcBAA7w5uZVDf8ARbcBABMg/v7t3v8AUbcBABR4/f2+hf8AXbcBABHC/f2NPP8AabcBAA392dlHAf8AdbcBABMg/v7t3v8AgbcBABR4/f2+hf8AjbcBABHC/f2NPP8AmbcBAA7w5uZVDf8ApbcBAA36pqY2A/8AsbcBABMg/v7t3v8AvbcBABVb/f3Qov8AybcBABOT/f2ua/8A1bcBABHC/f2NPP8A4bcBAA7w5uZVDf8A7bcBAA36pqY2A/8A+bcBABMg/v7t3v8ABbgBABVb/f3Qov8AEbgBABOT/f2ua/8AHbgBABHC/f2NPP8AKbgBABDq8fFpE/8ANbgBAA392dlIAf8AQbgBAAz3jIwtBP8ATbgBABUU///16/8AWbgBABUw/v7mzv8AZbgBABVb/f3Qov8AcbgBABOT/f2ua/8AfbgBABHC/f2NPP8AibgBABDq8fFpE/8AlbgBAA392dlIAf8AobgBAAz3jIwtBP8ArbgBABUU///16/8AubgBABUw/v7mzv8AxbgBABVb/f3Qov8A0bgBABOT/f2ua/8A3bgBABHC/f2NPP8A6bgBABDq8fFpE/8A9bgBAA392dlIAf8AAbkBAA36pqY2A/8ADbkBAAz2f38nBP8AGbkBABk2/v7oyP8AIrkBABN5/f27hP8AK7kBAAXF4+NKM/8ANLkBABol/v7w2f8APbkBABhz/f3Miv8ARrkBAA2k/PyNWf8AT7kBAAPa19cwH/8AWLkBABol/v7w2f8AYbkBABhz/f3Miv8AarkBAA2k/PyNWf8Ac7kBAAXF4+NKM/8AfLkBAAD/s7MAAP8AhbkBABol/v7w2f8AjrkBABhf/f3Unv8Al7kBABN5/f27hP8AoLkBAA2k/PyNWf8AqbkBAAXF4+NKM/8AsrkBAAD/s7MAAP8Au7kBABol/v7w2f8AxLkBABhf/f3Unv8AzbkBABN5/f27hP8A1rkBAA2k/PyNWf8A37kBAAey7+9lSP8A6LkBAAPa19cwH/8A8bkBAAD/mZkAAP8A+rkBABgS///37P8AA7oBABk2/v7oyP8ADLoBABhf/f3Unv8AFboBABN5/f27hP8AHroBAA2k/PyNWf8AJ7oBAAey7+9lSP8AMLoBAAPa19cwH/8AOboBAAD/mZkAAP8AQroBABgS///37P8AS7oBABk2/v7oyP8AVLoBABhf/f3Unv8AXboBABN5/f27hP8AZroBAA2k/PyNWf8Ab7oBAAey7+9lSP8AeLoBAAPa19cwH/8AgboBAAD/s7MAAP8AiroBAAD/f38AAP8Ak7oBAI5E46bO4/8An7oBAL6Zmmo9mv8ArLoBAJDTtB94tP8AuLoBAEFh37Lfiv8AxLoBAFK4oDOgLP8A0LoBAABj+/uamf8A3LoBAP7h4+MaHP8A6LoBABeP/f2/b/8A9LoBABX///9/AP8AALsBAMYq1sqy1v8ADLsBAI5E46bO4/8AGLsBAL6Zmmo9mv8AJbsBACpm////mf8AMrsBAJDTtB94tP8APrsBAEFh37Lfiv8ASrsBAFK4oDOgLP8AVrsBAABj+/uamf8AYrsBAP7h4+MaHP8AbrsBABeP/f2/b/8AersBABX///9/AP8AhrsBAMYq1sqy1v8AkrsBAI5E46bO4/8AnrsBAL6Zmmo9mv8Aq7sBACpm////mf8AuLsBAA/FsbFZKP8AxbsBAJDTtB94tP8A0bsBAEFh37Lfiv8A3bsBAFK4oDOgLP8A6bsBAABj+/uamf8A9bsBAP7h4+MaHP8AAbwBABeP/f2/b/8ADbwBABX///9/AP8AGbwBAMYq1sqy1v8AJbwBAI5E46bO4/8AMLwBAJDTtB94tP8AO7wBAEFh37Lfiv8ARrwBAI5E46bO4/8AUbwBAJDTtB94tP8AXLwBAEFh37Lfiv8AZ7wBAFK4oDOgLP8AcrwBAI5E46bO4/8AfbwBAJDTtB94tP8AiLwBAEFh37Lfiv8Ak7wBAFK4oDOgLP8AnrwBAABj+/uamf8AqbwBAI5E46bO4/8AtLwBAJDTtB94tP8Av7wBAEFh37Lfiv8AyrwBAFK4oDOgLP8A1bwBAABj+/uamf8A4LwBAP7h4+MaHP8A67wBAI5E46bO4/8A9rwBAJDTtB94tP8AAb0BAEFh37Lfiv8ADL0BAFK4oDOgLP8AF70BAABj+/uamf8AIr0BAP7h4+MaHP8ALb0BABeP/f2/b/8AOL0BAI5E46bO4/8AQ70BAJDTtB94tP8ATr0BAEFh37Lfiv8AWb0BAFK4oDOgLP8AZL0BAABj+/uamf8Ab70BAP7h4+MaHP8Aer0BABeP/f2/b/8Ahb0BABX///9/AP8AkL0BAI5E46bO4/8Am70BAJDTtB94tP8Apr0BAEFh37Lfiv8Asb0BAFK4oDOgLP8AvL0BAABj+/uamf8Ax70BAP7h4+MaHP8A0r0BABeP/f2/b/8A3b0BABX///9/AP8A6L0BAMYq1sqy1v8A870BAANO+/u0rv8A/70BAJI147PN4/8AC74BAE0p68zrxf8AF74BAANO+/u0rv8AI74BAJI147PN4/8AL74BAE0p68zrxf8AO74BAMob5N7L5P8AR74BAANO+/u0rv8AU74BAJI147PN4/8AX74BAE0p68zrxf8Aa74BAMob5N7L5P8Ad74BABhY/v7Zpv8Ag74BAANO+/u0rv8Aj74BAJI147PN4/8Am74BAE0p68zrxf8Ap74BAMob5N7L5P8As74BABhY/v7Zpv8Av74BACoy////zP8Ay74BAANO+/u0rv8A174BAJI147PN4/8A474BAE0p68zrxf8A774BAMob5N7L5P8A+74BABhY/v7Zpv8AB78BACoy////zP8AE78BABws5eXYvf8AH78BAANO+/u0rv8AK78BAJI147PN4/8AN78BAE0p68zrxf8AQ78BAMob5N7L5P8AT78BABhY/v7Zpv8AW78BACoy////zP8AZ78BABws5eXYvf8Ac78BAOkj/f3a7P8Af78BAANO+/u0rv8Ai78BAJI147PN4/8Al78BAE0p68zrxf8Ao78BAMob5N7L5P8Ar78BABhY/v7Zpv8Au78BACoy////zP8Ax78BABws5eXYvf8A078BAOkj/f3a7P8A378BAAAA8vLy8v8A678BAGw14rPizf8A978BABFR/f3NrP8AA8ABAJsf6MvV6P8AD8ABAGw14rPizf8AG8ABABFR/f3NrP8AJ8ABAJsf6MvV6P8AM8ABAOQr9PTK5P8AP8ABAGw14rPizf8AS8ABABFR/f3NrP8AV8ABAJsf6MvV6P8AY8ABAOQr9PTK5P8Ab8ABADgt9eb1yf8Ae8ABAGw14rPizf8Ah8ABABFR/f3NrP8Ak8ABAJsf6MvV6P8An8ABAOQr9PTK5P8Aq8ABADgt9eb1yf8At8ABACNR///yrv8Aw8ABAGw14rPizf8Az8ABABFR/f3NrP8A28ABAJsf6MvV6P8A58ABAOQr9PTK5P8A88ABADgt9eb1yf8A/8ABACNR///yrv8AC8EBABkn8fHizP8AF8EBAGw14rPizf8AI8EBABFR/f3NrP8AL8EBAJsf6MvV6P8AO8EBAOQr9PTK5P8AR8EBADgt9eb1yf8AU8EBACNR///yrv8AX8EBABkn8fHizP8Aa8EBAAAAzMzMzP8Ad8EBAOb9jo4BUv8AgcEBAE2/ZCdkGf8AjMEBAObcxcUbff8AlsEBAOh23t53rv8AoMEBAOU+8fG22v8AqsEBAOkd/f3g7/8AtMEBADsm9eb10P8A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it4BADqb2KbYVP8Ak94BACLQ///ZL/8AnN4BABla5eXElP8Apd4BAHJ4wmbCpf8Art4BAAub/PyNYv8At94BAJxNy42gy/8AwN4BAORm5+eKw/8Ayd4BADqb2KbYVP8A0t4BACLQ///ZL/8A294BABla5eXElP8A5N4BAAAAs7Ozs/8A7d4BAHhU043Tx/8A994BANNSvbyAvf8AAt8BACpM////s/8ADN8BAK8l2r662v8AFt8BAASL+/uAcv8AIN8BAJBk04Cx0/8AKt8BABac/f20Yv8ANN8BADqG3rPeaf8APt8BAOkv/PzN5f8ASN8BAAAA2dnZ2f8AUt8BAHhU043Tx/8AXN8BANNSvbyAvf8AZ98BAE0p68zrxf8Act8BACpM////s/8AfN8BAK8l2r662v8Aht8BAASL+/uAcv8AkN8BAJBk04Cx0/8Amt8BABac/f20Yv8ApN8BADqG3rPeaf8Art8BAOkv/PzN5f8AuN8BAAAA2dnZ2f8Awt8BAHhU043Tx/8AzN8BANNSvbyAvf8A198BAE0p68zrxf8A4t8BACWQ///tb/8A7d8BACpM////s/8A998BAK8l2r662v8AAeABAASL+/uAcv8AC+ABAJBk04Cx0/8AFeABABac/f20Yv8AH+ABADqG3rPeaf8AKeABAOkv/PzN5f8AM+ABAAAA2dnZ2f8APeABAHhU043Tx/8ARuABACpM////s/8AT+ABAK8l2r662v8AWOABAHhU043Tx/8AYeABACpM////s/8AauABAK8l2r662v8Ac+ABAASL+/uAcv8AfOABAHhU043Tx/8AheABACpM////s/8AjuABAK8l2r662v8Al+ABAASL+/uAcv8AoOABAJBk04Cx0/8AqeABAHhU043Tx/8AsuABACpM////s/8Au+ABAK8l2r662v8AxOABAASL+/uAcv8AzeABAJBk04Cx0/8A1uABABac/f20Yv8A3+ABAHhU043Tx/8A6OABACpM////s/8A8eABAK8l2r662v8A+uABAASL+/uAcv8AA+EBAJBk04Cx0/8ADOEBABac/f20Yv8AFeEBADqG3rPeaf8AHuEBAHhU043Tx/8AJ+EBACpM////s/8AMOEBAK8l2r662v8AOeEBAASL+/uAcv8AQuEBAJBk04Cx0/8AS+EBABac/f20Yv8AVOEBADqG3rPeaf8AXeEBAOkv/PzN5f8AZuEBAHhU043Tx/8Ab+EBACpM////s/8AeOEBAK8l2r662v8AgeEBAASL+/uAcv8AiuEBAJBk04Cx0/8Ak+EBABac/f20Yv8AnOEBADqG3rPeaf8ApeEBAOkv/PzN5f8AruEBAAAA2dnZ2f8At+EBAO39np4BQv8AxeEBALGCol5Pov8A1OEBAPq01dU+T/8A4uEBAAq49PRtQ/8A8OEBABSd/f2uYf8A/uEBAB9z/v7gi/8ADOIBADFg9eb1mP8AGuIBAE9B3avdpP8AKOIBAHJ4wmbCpf8ANuIBAI+7vTKIvf8AROIBAO39np4BQv8AUuIBAI+7vTKIvf8AYeIBALGCol5Pov8AcOIBAPq01dU+T/8AfuIBAAq49PRtQ/8AjOIBABSd/f2uYf8AmuIBAB9z/v7gi/8AqOIBACpA////v/8AtuIBADFg9eb1mP8AxOIBAE9B3avdpP8A0uIBAHJ4wmbCpf8A4OIBAA2k/PyNWf8A7eIBACpA////v/8A+uIBAFFN1ZnVlP8AB+MBAP7h19cZHP8AFOMBABSd/f2uYf8AIeMBAE9B3avdpP8ALuMBAI/EuiuDuv8AO+MBAP7h19cZHP8ASOMBABSd/f2uYf8AVeMBACpA////v/8AYuMBAE9B3avdpP8Ab+MBAI/EuiuDuv8AfOMBAPq01dU+T/8AieMBAA2k/PyNWf8AluMBAB9z/v7gi/8Ao+MBADFg9eb1mP8AsOMBAFFN1ZnVlP8AveMBAI+7vTKIvf8AyuMBAPq01dU+T/8A1+MBAA2k/PyNWf8A5OMBAB9z/v7gi/8A8eMBACpA////v/8A/uMBADFg9eb1mP8AC+QBAFFN1ZnVlP8AGOQBAI+7vTKIvf8AJeQBAPq01dU+T/8AMuQBAAq49PRtQ/8AP+QBABSd/f2uYf8ATOQBAB9z/v7gi/8AWeQBADFg9eb1mP8AZuQBAE9B3avdpP8Ac+QBAHJ4wmbCpf8AgOQBAI+7vTKIvf8AjeQBAPq01dU+T/8AmuQBAAq49PRtQ/8Ap+QBABSd/f2uYf8AtOQBAB9z/v7gi/8AweQBACpA////v/8AzuQBADFg9eb1mP8A2+QBAE9B3avdpP8A6OQBAHJ4wmbCpf8A9eQBAI+7vTKIvf8AAuUBAJMP//D4//8AEeUBABgj+vrr1/8AI+UBAH///wD///8ALeUBAHGA/3//1P8APeUBAH8P//D///8ASOUBACoa9fX13P8AU+UBABc6///kxP8AX+UBAAAAAAAAAP8AauUBABkx///rzf8AfuUBAKr//wAA//8AiOUBAMDO4oor4v8AmOUBAAC+paUqKv8Ao+UBABdj3t64h/8AsuUBAIBnoF+eoP8AweUBAD///3//AP8A0eUBABHa0tJpHv8A4OUBAAuv//9/UP8A6+UBAJqT7WSV7f8A/+UBACEi///43P8ADeYBAPbn3NwUPP8AGuYBAH///wD///8AJOYBAKr/iwAAi/8AMuYBAH//iwCLi/8AQOYBAB7vuLiGC/8AU+YBAAAAqampqf8AYeYBAFX/ZABkAP8AcOYBAAAAqampqf8AfuYBACduvb23a/8AjeYBANT/i4sAi/8AnuYBADqOa1VrL/8AsuYBABf///+MAP8AwuYBAMbAzJkyzP8A0uYBAAD/i4sAAP8A3+YBAAp56emWev8A7+YBAFU9vI+8j/8AAecBAK+Pi0g9i/8AFOcBAH9nTy9PT/8AJ+cBAH9nTy9PT/8AOucBAID/0QDO0f8ATecBAMf/05QA0/8AXecBAOjr//8Uk/8Aa+cBAIr//wC///8AfOcBAAAAaWlpaf8AiecBAAAAaWlpaf8AlucBAJTh/x6Q//8ApucBAADOsrIiIv8AtecBABwP///68P8AxucBAFXAiyKLIv8A1+cBANT///8A//8A5OcBAAAA3Nzc3P8A8+cBAKoH//j4//8AA+gBACP////XAP8ADegBAB7Z2tqlIP8AHOgBAAAAgICAgP8AJugBAFX/gACAAP8AMegBADvQ/63/L/8AQugBAAAAgICAgP8ATOgBAFUP//D/8P8AWugBAOmW//9ptP8AZ+gBAACMzc1cXP8AdugBAML/gksAgv8AgugBACoP////8P8AjegBACZq8PDmjP8AmOgBAKoU+ubm+v8ApugBAPAP///w9f8AuegBAED//Hz8AP8AyOgBACYx///6zf8A2ugBAIk/5q3Y5v8A6egBAAB38PCAgP8A+egBAH8f/+D///8ACOkBACoo+vr60v8AIukBAAAA09PT0/8AMekBAFVk7pDukP8AQekBAAAA09PT0/8AUOkBAPhJ//+2wf8AX+kBAAyE//+gev8A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VAACAOqR//9utP8AXQACAOuN7u5qp/8AZgACAOyHzc1gkP8AbwACAOqUi4s6Yv8AeAACAACMzc1cXP8AggACAACU//9qav8AjQACAACU7u5jY/8AmAACAACVzc1VVf8AowACAACUi4s6Ov8ArgACAML/gksAgv8AtQACACoA/////gAAuwACACoP////8P8AwQACACoP////8P8AyAACACoP7u7u4P8AzwACACoOzc3Nwf8A1gACACoOi4uLg/8A3QACACZq8PDmjP8A4wACACdw///2j/8A6gACACdw7u7mhf8A8QACACdvzc3Gc/8A+AACACdvi4uGTv8A/wACAKoU+ubm+v8ACAECAPAP///w9f8AFgECAPAP///w9f8AJQECAO8P7u7g5f8ANAECAPAOzc3Bxf8AQwECAO8Oi4uDhv8AUgECAED//Hz8AP8AXAECACYx///6zf8AaQECACYx///6zf8AdwECACUy7u7pv/8AhQECACYxzc3Jpf8AkwECACcxi4uJcP8AoQECAIk/5q3Y5v8AqwECAIpA/7/v//8AtgECAIpA7rLf7v8AwQECAIo/zZrAzf8AzAECAIlAi2iDi/8A1wECAAB38PCAgP8A4gECAH8f/+D///8A7AECAH8f/+D///8A9wECAH8f7tHu7v8AAgICAH8fzbTNzf8ADQICAH8fi3qLi/8AGAICACNz7u7dgv8AJwICACN0///si/8ANwICACNz7u7cgv8ARwICACNzzc2+cP8AVwICACNzi4uBTP8AZwICACoo+vr60v8AfAICAAAA09PT0/8AhgICAAAA09PT0/8AkAICAPhJ//+2wf8AmgICAPlR//+uuf8ApQICAPhR7u6irf8AsAICAPlQzc2Mlf8AuwICAPlQi4tfZf8AxgICAAyE//+gev8A0gICAAyE//+gev8A3wICAAuE7u6Vcv8A7AICAAyFzc2BYv8A+QICAAyFi4tXQv8ABgMCAH3RsiCyqv8AFAMCAI91+ofO+v8AIQMCAI9P/7Di//8ALwMCAI9P7qTT7v8APQMCAI5PzY22zf8ASwMCAI9Oi2B7i/8AWQMCAK+P/4Rw//8AaAMCAJQ4mXeImf8AdwMCAJQ4mXeImf8AhgMCAJc03rDE3v8AlQMCAJc1/8rh//8ApQMCAJc17rzS7v8AtQMCAJc1zaK1zf8A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HBwcHBwcFhwcHBwcHBwcHBwWHBocHBYcHBwcHBYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWHBYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYcFhYWFhYWFhYAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP//////////////////////////////////////////AAAAAAAAAAT+//+H/v//BwAAAAAAAAAA//9/////f//////////zf/79//////9///////////8P4P////8x/P///wAAAAAAAAD//////////////wEA+AMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEDX///7/////39/VP3/DwD+3////////////t//////AwD///////+fGf///88/AwAAAAAAAP7///9/Av7///9/AAAAAAAAAAAA////BwcAAAAAAP7//wf+BwAAAAD+//////////98/38vAGAAAADg////////IwAAAP8DAAAA4J/5///9xQMAAACwAwADAOCH+f///W0DAAAAXgAAHADgr/v///3tIwAAAAABAAAA4J/5///9zSMAAACwAwAAAODHPdYYx78DAAAAAAAAAADg3/3///3vAwAAAAADAAAA4N/9///97wMAAABAAwAAAODf/f///f8DAAAAAAMAAAAAAAAAAAAAAAAAAAAAAAAA/v////9/DQA/AAAAAAAAAJYl8P6ubA0gHwAAAAAAAAAAAAAAAAAAAP/+////AwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/////z8A/////38A7doHAAAAAFABUDGCq2IsAAAAAEAAyYD1BwAAAAAIAQL/////////////////////////D///////////////A///Pz//////Pz//qv///z/////////fX9wfzw//H9wfAAAAAEBMAAAAAAAAAAAAAAcAAAAAAAAAAAAAAAAAAACAAAAA/gMAAP7///////////8fAP7/////////////B+D/////HwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA//////////////////////////8/AAAAAAAAAAAAAAD//////////////////////////w8AAAAAAAAAAAAAAAAAAAAAYP8H/v//h/7//wcAAAAAAACAAP//f////3//////AAAAAAAAAP//////////////AQD4AwADAAAAAAD//////////z8AAAADAAAAwNf///v/////f39U/f8PAP7f///////////+3/////97AP///////58Z////zz8DAAAAAAAA/v///38C/v///38A/v/7//+7FgD///8HBwAAAAAA/v//B///BwD/A////////////3z/f+///z3/A+7////////z/z8e/8//AADun/n///3F0585gLDP/wMA5If5///9bdOHOQBewP8fAO6v+////e3zvzsAAMH/AADun/n///3N8485wLDD/wAA7Mc91hjHv8PHPYAAgP8AAO7f/f///e/D3z1gAMP/AADs3/3///3vw989YEDD/wAA7N/9///9/8PPPYAAw/8AAAAAAAAAAAAAAAAAAAAAAAD+/////3//B/9//wMAAAAAliXw/q5s/ztfP/8DAAAAAAAAAAP/A6DC//7///8D/v/fD7/+/z/+AgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/HwIAAACgAAAA/v8+AP7///////////8fZv7/////////////dxkAAAAaAAAAGwAAABwAAAAdAAAAHgAAAB8AAAAoAAAAKQAAACAAAAAqAAAADAAAABkAAAAhAAAABgAAAAcAAAABAAAAAQAAAAAAAAAAAAAAABUKAAAVAAAAAAAAAAAAAAAAAAAAAAAAFRAMExweAw0fICEiIxsaERkZGRkZGRkZGRkWEgIOCw8cGBgYGBgYFhYWFhYWFhYWFhYWFhYWFhYWFhYUHAQcFhwYGBgYGBgWFhYWFhYWFhYWFhYWFhYWFhYWFhwkHBwcCAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBgYGBgYGBgYGBgYGBgYGBgcHBwcHAAAAAAAAAAAAAQErAAAALAAAAC0AAAAuAAAALwAAAC0AAAAwAAAAMQAAADIAAAAZAAAAGgAAABsAAAAcAAAAHQAAAB4AAAAfAAAA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ZgBcAFwAXABnAGgAYQBiAGIAYgBiAGIAYgBiAGIAYgBiAGIAYgBiAGIAYgBiAGIAYgBiAGIAYgBiAGIAAABcAFwAXABcAFwAXABcAFwAXABcAFwAXAAAAAoACwAMAA0ADgAKAA8AEAARABIAEwAKABQAFQAVABUAFgAXABUAGAAVABUAGQAVABUAFQAaABUAFQAKABUAFQAVABYAFwAYABUAFQAZABUAFQAVABoAFQAVABUAFQAbAAwADAAkAB4AHgAgACEAIAAhACQAJQAmAC0AMgAvAC4AKgAlACYAKAApADMAKgA0ACsANQA2ADcAPAAyAEcAPQAiAEUAIgA/AEAARgAzADQASAA1ADYANwAvAEkAKgBHAEoARQBMAFwAPABGAFwAPQBNAEgATgBPAFIASQBBAFAAUQBKAEwAUwBUADEAVQBWAFcATQBOAFgATwBSAFkAUABRAFoAWwBTAEQAVABVAFYAVwBLAEQALABYACwAWQA4ACwAWgBbAB0AHQAdAB0AHQAdAB0AHwAfAB8AHwAfAB8AHwAjACMAIwAjACMAIwAjACcAXAAnACcAJwAnACcAMAAwADkAHAA5ADkAOQA5ADkAOgBcADoAXAA6ADoAOgA7AFwAOwA7ADsAOwA7AD4APgBcAD4APgA
