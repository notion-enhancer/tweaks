# Hide '+ new' board row

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/Wpsyjez.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/MZDUqEQ.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE '+ NEW' BOARD ROW ========== */
.notion-board-group > div[role='button'][tabindex='0'] {
    display: none !important;
}
```
