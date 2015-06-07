### iPython-Notebook-Theme
Personal theme that I use for iPython notebooks

![Notebook Design Screenshot](http://i.imgur.com/U7eRiTB.png "Notebook Design")

### Installation instructions
https://github.com/nsonnad/base16-ipython-notebook

### CSS Code
```CSS
/*
Author: Neil Panchal
http://neil.engineer

PALETTE

YELLOW      = #D9AA00
ORANGE      = #CF5804
RED         = #D43132
MAGENTA     = #C74483
VIOLET      = #975DDE
BLUE        = #2B88D9
CYAN        = #00A397
GREEN       = #688A0A

BACKGROUND  = #F8F8F8
DARK GRAY   = #383838
MID GRAY    = #d8d8d8
LIGHT GRAY  = #828282

*/

/* GLOBALS */

html {
    font-size: 16px !important;
}

body {
    background-color: #FFF !important;
    color: #828282;
    font-weight: 1rem;
    font-family: 'Source Sans Pro', "Helvetica Neue", Helvetica, Arial, sans-serif;
}

body .notebook-app {
    background-color: #FFF !important;
}

#header {
    box-shadow: none !important;
}

#notebook {
    padding-top: 0px;
}

#notebook-container {
    box-shadow: none;
    -webkit-box-shadow: none;
    padding: 10px;
}

div.cell.selected {
    border: 1px dashed #CCCCCC;
}

.edit_mode div.cell.selected {
    border: 1px dashed #828282;
}

div.output_wrapper {
    margin-top: 8px;
}

a {
    color: #383838;
}

code,
kbd,
pre,
samp {
    font-family: 'Menlo', monospace !important;
    font-size: 0.75rem !important;
}

h1 {
    font-size: 1.5rem !important;
    font-weight: 300 !important;
    color: #828282 !important;
    letter-spacing: 3px !important;
    text-transform: uppercase !important;
    /*border-bottom: 1px dashed #000000 !important;*/
}

h2 {
    font-size: 1rem !important;
    font-weight: 500 !important;
    color: #828282 !important;
    letter-spacing: 3px !important;
    text-transform: none !important;
}

h3 {
    font-size: 1rem !important;
    font-weight: 300 !important;
    font-style: italic !important;
    display: block !important;
}

h4,
h5,
h6 {
    font-size: 1rem !important;
    font-weight: 500 !important;
    display: block !important;
}

.prompt {
    font-family: 'Menlo', monospace !important;
    font-size: 0.75rem;
    text-align: right;
    line-height: 1.21429rem;
}

/* INTRO PAGE */

.toolbar_info,
.list-container {
    color: #828282;
}
/* NOTEBOOK */

div#header-container {
    display: none !important;
}

div#notebook {
    border-top: none;
    font-size: 1rem;
}

div.input_prompt {
    color: #C74483;
}

.code_cell div.input_prompt:after,
div.output_prompt:after {
    content: '\25b6';
}

div.output_prompt {
    color: #2B88D9;
}

div.input_area {
    border-radius: 0px;
    border: 1px solid #d8d8d8;
}

div.output_area pre {
    font-weight: normal;
    color: #828282;
}

div.output_subarea {
    font-weight: normal;
    color: #828282;
}

.rendered_html pre,
.rendered_html code {
    color: #828282;
}

.rendered_html table,
.rendered_html th,
.rendered_html tr,
.rendered_html td {
    border: 1px #828282 solid;
    font-size: 0.75rem;
    font-family: 'Menlo', monospace;
}

.rendered_html th,
.rendered_html tr,
.rendered_html td {
    padding: 5px 10px;
}

.rendered_html th {
    font-weight: normal;
    background: #f8f8f8;
}

div.output_html {
    font-weight: 1rem;
    font-family: 'Source Sans Pro', "Helvetica Neue", Helvetica, Arial, sans-serif;
}

table.dataframe tr {
    border: 1px #CCCCCC;
}

div.cell.selected {
    border-radius: 0px;
}

div.cell.edit_mode {
    border-radius: 0px;
    border: thin solid #CF5804;
}

div.text_cell_render,
div.output_html {
    color: #828282;
}

span.ansiblack {
    color: #828282;
}

span.ansiblue {
    color: #00A397;
}

span.ansigray {
    color: #d8d8d8;
}

span.ansigreen {
    color: #688A0A;
}

span.ansipurple {
    color: #975DDE;
}

span.ansired {
    color: #D43132;
}

span.ansiyellow {
    color: #D9AA00;
}

div.output_stderr {
    background-color: #D43132;
}

div.output_stderr pre {
    color: #e8e8e8;
}

.cm-s-ipython.CodeMirror {
    background: #F8F8F8;
    color: #828282;
}

.cm-s-ipython div.CodeMirror-selected {
    background: #e8e8e8 !important;
}

.cm-s-ipython .CodeMirror-gutters {
    background: #F8F8F8;
    border-right: 0px;
}

.cm-s-ipython .CodeMirror-linenumber {
    color: #b8b8b8;
}

.cm-s-ipython .CodeMirror-cursor {
    border-left: 1px solid #585858 !important;
}

.cm-s-ipython span.cm-comment {
    color: #828282;
}

.cm-s-ipython span.cm-atom {
    color: #C74483;
}

.cm-s-ipython span.cm-number {
    color: #C74483;
}

.cm-s-ipython span.cm-property,
.cm-s-ipython span.cm-attribute {
    color: #688A0A;
}

.cm-s-ipython span.cm-keyword {
    font-weight: normal;
    color: #D43132;
}

.cm-s-ipython span.cm-string {
    color: #D9AA00;
}

.cm-s-ipython span.cm-operator {
    color: #828282;
    font-weight: normal;
}

.cm-s-ipython span.cm-builtin {
    color: #2B88D9;
}

.cm-s-ipython span.cm-variable {
    color: #00A397;
}

.cm-s-ipython span.cm-variable-2 {
    color: #2B88D9;
}

.cm-s-ipython span.cm-def {
    color: #00A397;
}

.cm-s-ipython span.cm-error {
    background: #FFBDBD;
    color: #D43132;
}

.cm-s-ipython span.cm-bracket {
    color: #828282;
}

.cm-s-ipython span.cm-tag {
    color: #D43132;
}

.cm-s-ipython span.cm-link {
    color: #975DDE;
}

.cm-s-ipython .CodeMirror-matchingbracket {
    text-decoration: underline;
    color: #828282 !important;
}

```
