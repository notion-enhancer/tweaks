# Smaller table column header icons

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/GPQk8GH.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/lJNm2tl.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== SMALLER TABLE COLUMN HEADER ICONS ========== */
[style^='display: flex; position: absolute; background: rgb(47, 52, 55); z-index: 82; height: 33px; color: rgba(255, 255, 255, 0.6);']
  div:nth-child(1)
  svg {
  height: 10px !important;
  width: 10px !important;
  margin-right: -4px;
}
```