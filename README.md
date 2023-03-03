# json-editor

> A JSON schema based editor for JSON document. It provides a tree view to present the structure of JSON document, user could manipulate the JSON from context menu. It also has a text view to present the content of JSON document, user may edit JSON within.
> Develop with Vue.js 2.
> Please reference the [project website](https://json-editor.tangramjs.com) fro detail.

## Features
#### Tree View of JSON document
The structure of JSON document, could expend or collapse at any level.
#### Context Menu
Right-click on the element in tree view could bring out the context menu for that element, and perform actions specific for that element.
#### Text View of JSON document
A text view to display content of schema. User could also edit the document directly in text view.
#### Schema validation
The JSON document would validate with current selected schema after every update.
#### Undo/Redo
Undo and Redo could keep track of every update of JSON document.
#### Copy JSON document to clipboard
Copy JSON document to system clipboard.
#### Download JSON document to file
Download JSON document as a json file.
#### Load JSON document from file
Load JSON document from a json schema file.

## Install
``` bash
git clone https://github.com/tangram-js/json-editor.git
```
## Build

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
## Live demo
Live demo of source code: [https://tangram-js.github.io/json-editor/](https://tangram-js.github.io/json-editor/)
