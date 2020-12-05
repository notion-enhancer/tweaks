# Hide new page button

**last tested/working:** Dec 5, 2020

**author(s):** [@admiraldus](https://github.com/admiraldus)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/ghJsn6f.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/SXnATRd.png"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE NEW PAGE BUTTON ========== */
.notion-sidebar > :nth-child(7) {
  display: none !important;
}
```
