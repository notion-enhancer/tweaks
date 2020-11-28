# Centre-align table column headers

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/8ZbIN3c.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/sNCfiqS.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== CENTRE-ALIGN TABLE COLUMN HEADERS ========== */
.notion-table-view-header-cell > div > div {
  margin: 0px auto;
}
```