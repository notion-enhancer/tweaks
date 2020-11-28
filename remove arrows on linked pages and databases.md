# Remove arrows on linked pages and databases

> Removes all the arrow icons from linked databases/pages, resulting in a cleaner look.

**last tested/working:** Nov 9, 2020

**author(s):** [@fabiosangregorio](https://github.com/fabiosangregorio)


<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/jkljRhA.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/hFIyFTC.png"></td>
 </tr>
</table>

## css

```css
/* ========== REMOVE ARROWS ON LINKED DATABASES/PAGES ========== */
svg.alias, .notion-collection_view-block [style="display: flex; align-items: center; margin-right: 6px;"] {
  display: none !important;
}
/* Remove in page mentions */
.notion-page-mention-token [style="width:1em;display:inline-block;vertical-align:-0.15em;margin-right:0.1em"] {
  width: 2px !important;
}
```