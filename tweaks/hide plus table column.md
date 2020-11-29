# Hide '+' table column

**last tested/working:** Nov 29, 2020

**author(s):** [@admiraldus](https://github.com/admiraldus)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://media.discordapp.net/attachments/767863068617080902/782330818920054794/Table__1.png"></td>
    <td><img alt="after tweak" src="https://media.discordapp.net/attachments/767863068617080902/782330828755173436/Table__2.png"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE '+' TABLE COLUMN ========== */
.notion-table-view-add-column {
   display: none !important;
}
.notion-selectable.notion-page-block.notion-collection-item > div:last-child {
   display: none !important;
}
```