# Markdown Editor webcomponent
----

Experiment project with polymer
Markdown editor with preview (inspired by ghost blog platform)

## Instalation

With bower

```shell
bower install markdown-editor
```

## Usage 

In your head include component and platform.js
```html
<head>
	<script src="bower_components/platform/platform.js"></script>
	<link rel="import" href="bower_components/markdown-editor/markdown-editor.html" />
</head>
```

Then use components
```html
<markdown-editor id="editor">
# Title

```
var editorValue = document.getElementById('editor').value;
```
</markdown-editor>
```