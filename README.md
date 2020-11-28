# tweaks
> a collection of user-submitted css/js tweaks for [notion-enhancer](https://github.com/notion-enhancer/notion-enhancer).

the enhancer comes with some built-in colour themes and layout improvements,
but to get even more control over how the app looks you can use the file picker in the
"custom inserts" module to inject your own javascript or css into it.

to make your own css file to add, make sure that your file manager has "show file extensions" ticked, then
create a text document and make sure the name ends in `.css` (e.g. `notion-tweaks.css`).

this page is a collection of tested visual tweaks users often ask about.
they should all also work in notion's web client, if copied into a customiser
like [stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en).

css below will work for every instance of the element, but if you wish to hide only a specific element
(e.g. the '+ new' table row) it is recommended that you prepend each selector with
`[data-block-id='ID']`.

if you don't know what css is and are interested, check out some youtube videos
or [try a free short course like the one on codecademy](https://www.codecademy.com/learn/learn-css).

**the following tweaks were previously on this page and have since been moved to the**
**more stable and theme-compatible css variable system described in the**
**[developer documentation](DOCUMENTATION.md#variable-theming):**

- colour theming
- custom fonts and font sizes
- wider page preview
- thinner cover image

if you are attempting to customise the web client, the css previously used for these can be found
[in the legacy documentation](https://github.com/notion-enhancer/notion-enhancer/blob/b5043508d91df76f145f0f48c2c63d7dd1c27543/STYLING.md).

## list of tweaks

* [Bigger icons in calendar view](bigger%20icons%20in%20calendar%20view.md)
* [Shrink padding on code blocks](shrink%20padding%20on%20code%20blocks.md)
* [Minify breadcrumbs and topbar buttons](minify%20breadcrumbs%20and%20topbar%20buttons.md)
* [Remove arrows on linked pages and databases](remove%20arrows%20on%20linked%20pages%20and%20databases.md)
* [Smaller page icons](smaller%20page%20icons.md)
* [Remove "Type '/' for commands" hint](remove%20type%20for%20commands.md)
* [Left-align images](left-align%20images.md)
* [Scroll past end of page](scroll%20past%20end%20of%20page.md)
* [Centre-align table column headers](centre-align%20table%20column%20headers.md)
* [Hide backlinks](hide%20backlinks.md)
* [Hide board view 'add a group'](hide%20board%20view%20add%20a%20group.md)
* [Hide board view hidden columns](hide%20board%20view%20hidden%20columns.md)
* [Hide calculations table row](hide%20calculations%20table%20row.md)
* [Hide discussions](hide%20discussions.md)
* [Hide '+ new' board row](hide%20new%20board%20row.md)
* [Hide '+ new' table row](hide%20new%20table%20row.md)
* [Hide the '+ new' gallery button](hide%20the%20new%20gallery%20button.md)
* [Remove icons from table column headers](remove%20icons%20from%20table%20column%20headers.md)
* [Removing/decreasing side padding for boards](removing%20decreasing%20side%20padding%20for%20boards.md)
* [Removing/decreasing side padding for tables](removing%20decreasing%20side%20padding%20for%20tables.md)
* [Smaller table column header icons](smaller%20table%20column%20header%20icons.md)
* [Sticky table/list row](sticky%20table%20list%20row.md)
* [Table columns below 100px](table%20columns%20below%20100px.md)