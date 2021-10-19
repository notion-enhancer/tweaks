# Hide board view hidden columns

**last tested/working:** Oct 19, 2021

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/Z7a3Dav.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/8pT5Mk7.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE BOARD VIEW HIDDEN COLUMNS ========== */
.notion-board-view > [data-block-id] > :first-child > :last-child,
.notion-board-view > [data-block-id] > :last-child {
  display: none !important;
}
```
