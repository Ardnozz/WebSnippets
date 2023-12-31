# WebSnippets

This is the README for WebSnippet Visual Studio Code extension. The extension should be used only for web developement projects, that have Vue.js included.

## Snippets

Write them as normal part of code and IntelliSence (suggestions) will help you.

### vuefile
```html
<script setup lang="ts">

</script>

<template>

</template>

<style scoped>

</style>
```

### vueprops
```typescript
const props = defineProps({
  msg: String
});
```

### vueemits
```typescript
const emit = defineEmits(['response']);
emit('response', 'text');
```

## Requirements

Visual Studio Code version 1.80.0 (or later) installed.

## Installation

Via VSIX file:

1. Open your Visual Studio Code
2. Go to Activity bar and there select Extension option (shortcut Ctrl+Shift+X)
3. Click on the three dots in the top-right corner
4. Select install from VSIX option.
5. Locate newest VSIX file (located in releases folder)
6. Click on the file and confirm your installation.

## Known Issues

The WebSnippets extension isn't providing settings yet. In the upcoming updates there'll be options for choosing between TypeScript and JavaScript.\
Also the extension doesn't have any icon.

These are the plans for upcoming versions.

## Release Notes

### 0.1.0

* Initial release of WebSnippets

### 0.1.1

* Updated README.md
* Created first release via VSIX file

### 0.1.2

* "vue" snippet renamed to "vuefile"
* Added "vueprops" and "vueemits" snippets

### 0.1.3

* Created VSIX file
* Updated languages in package.json
* Snippets for TypeScript in Vue now works
* Snippets has options of completing via tab positions and default values 

## For more information

* Contact me via Discord - ardno

**Enjoy!**