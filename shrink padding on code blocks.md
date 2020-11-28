# Shrink padding on code blocks

> Shrinks the padding on the new code blocks design, making the language select floating over the code.

**last tested/working:** Nov 28, 2020

**author(s):** [@fabiosangregorio](https://github.com/fabiosangregorio)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/YkZU9pZ.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/wHtmvJO.png"></td>
 </tr>
</table>

## css

```css
/* ========== SHRINK PADDING ON CODE BLOCKS ========== */
.notion-code-block.line-numbers > div {
  padding-top: 14px !important;
  padding-bottom: 14px !important;
}
.notion-code-block:not(.line-numbers) .line-numbers + div + div, #code-line-numbers {
  top: 14px !important;
}

.notion-code-block.line-numbers + div + div {
  background: var(--theme--code-background);
  box-shadow: 5px 2px 8px 4px var(--theme--code-background);
}
```