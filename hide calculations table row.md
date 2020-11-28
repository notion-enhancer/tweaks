# Hide calculations table row

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/ajn1BA0.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/iJVdBxA.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE CALCULATIONS TABLE ROW ========== */
.notion-table-view-add-row + div {
  display: none !important;
}
```