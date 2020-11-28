# Hide board view 'add a group'


**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/AyyECDj.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/FlmOHnd.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE BOARD VIEW 'ADD A GROUP' ========== */
.notion-board-view > [data-block-id] > div:last-child,
.notion-board-view > [data-block-id] > div:first-child > div:last-child {
  display: none !important;
}
```