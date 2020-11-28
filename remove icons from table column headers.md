# Remove icons from table column headers

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/vuq6zpg.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/eKLWvD3.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== REMOVE ICONS FROM TABLE COLUMN HEADERS ========== */
.notion-table-view-header-cell [style^='margin-right: 6px;'] {
  display: none !important;
}
```