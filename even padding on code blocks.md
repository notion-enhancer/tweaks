# Even padding on code blocks

**last tested/working:** Nov 18, 2020

**author(s):** [@fabiosangregorio](https://github.com/fabiosangregorio)

> Top and bottom paddings are different with respect to left and right in code blocks. This tweak reduces the top and bottom padding to match the left and right ones.

_before tweak_

![before tweak](https://cdn.discordapp.com/attachments/767863068617080902/773140995093037086/unknown.png)

_after tweak_

![after tweak](https://cdn.discordapp.com/attachments/767863068617080902/773141156783587358/unknown.png)

## css

```css
/* ========== EVEN PADDING ON CODE BLOCKS ========== */
.notion-code-block.line-numbers > div {
  padding-top: 43px !important;
  padding-bottom: 14px !important;
}
.notion-code-block:not(.line-numbers) .line-numbers + div + div {
    top: 13px !important;
}
```