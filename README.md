# Obsidian CSS Snippets

Currently I am using these snippets and [JSDelivr](https://www.jsdelivr.com/github) to create a CDN link for each of my CSS files and then importing these CSS files into my `styles.css` entrypoint file in Obsidian. Like this:

```css
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Dasboard.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Active_Note.css");
@import url("https://cdn.jsdelivr.net/gh/ChristopherHarwell/Obsidian-CSS@main/Callouts.css")
```

This allows me to modularize my Styling and enable/disable styles more easily by just commenting out a link rather than having to deal with the bugs that Obsidian has where CSS styles that are toggled on will toggle off automatically when I don't want them toggled off.
