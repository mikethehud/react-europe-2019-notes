# 4 - Gutenberg Editor (Wordpress), Ella van Durpe
- Built with React/Redux (React Native for Mobile)
- Everything is blocks
- Block Markup: HTML; works everywhere, readable BUT: difficult to parse
- Using Comments as delimiters for blocks
- Blocks are parsed into a Redux Store
- Every block is an isolated container
  - Easy to debug
  - Specific block grammar
  - Uses contentEditable on a block basis
- Now supports Placeholders and Templates
  - Predefined, downloadable layouts
- Create your own reusable blocks
- Discoverable blocks within the Editor

## Rich Text Editing
- Used to be TinyMCE, but was too heavy, requirements:
  - Light
  - HTML input/output
  - Native UI (e.g. Touchbar) support
  - Format Boundaries
- ContendEditable
  - Controlled component with custom state
  - Manipulation helpers, e.g.
```
{
  text: 'hello world',
  format: [,,,,,,[B],[B],[B],[B],[B]]
}
```
- Extendable
  - Formatting
  - Autocomplete
  - Text patterns
  - Annotations
  - Content checking

## Future
- React Component made available
- Full site editor with Gutenberg