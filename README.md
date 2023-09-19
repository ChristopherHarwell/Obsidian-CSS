# Obsidian CSS Snippets

Currently I am using these snippets and [JSDelivr](https://www.jsdelivr.com/github) to create a CDN link for each of my CSS files and then importing these CSS files into my `styles.css` entrypoint file in Obsidian. Like this:

```css
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Dasboard.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Active_Note.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Callouts.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Hide_Folders.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Hide_Frontmatter.css");
```

This allows me to modularize my Styling and enable/disable styles more easily by just commenting out a link rather than having to deal with the bugs that Obsidian has where CSS styles that are toggled on will toggle off automatically when I don't want them toggled off.

## DONE:
- [x] [Dasboard.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Dasboard.css)
- [x] [Active_Note.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Active_Note.css)
- [x] [Callouts.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Callouts.css)
- [x] [Hide_Folders.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Hide_Folders.css)
- [x] [Hide_Frontmatter.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Hide_Frontmatter.css)

## TODO:
Use [JSDelivr](https://www.jsdelivr.com/github) to convert the following files to a CDN link and add them to `styles.css` in Obsidian
- [ ] [Highlights.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Highlights.css)
- [ ] [Layouts.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Layouts.css)
- [ ] [MCL_Gallery_Cards.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/MCL_Gallery_Cards.css)
- [ ] [MCL_Multi_Column.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/MCL_Multi_Column.css)
- [ ] [MCL_Wide_Views.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/MCL_Gallery_Views.css)
- [ ] [MCL_Gallery_Cards.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/MCL_Gallery_Cards.css)
- [ ] [Mermaid_Settings.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/Mermaid_Settings.css)
- [ ] [collapsible_side_notes.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/collapsible_side_notes.css)
- [ ] [column_layout.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/column_layout.css)
- [ ] [tabStyles.css](https://github.com/ChristopherHarwell/Obsidian-CSS/blob/main/tabStyles.css)

