# Table columns below 100px

**not recommended!** this may cause buggy viewing. as it is a per-table-column style, unlike most others here, it must be prepended with the block ID and repeated for each column.

to see how to do this, watch [this video](https://www.youtube.com/watch?v=6V7eqShm_4w).

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/BNkdQfE.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/ajl2rFw.png"></td>
 </tr>
</table>

## css

```css
/* ========== TABLE COLUMNS BELOW 100PX ========== */
[data-block-id^='tableID']
  > [style^='display: flex; position: absolute; background: rgb(47, 52, 55); z-index: 82; height: 33px; color: rgba(255, 255, 255, 0.6);']
  > div:nth-child(1)
  > div:nth-child(COL_NUMBER)
  > div:nth-child(1),
[data-block-id^='tableID']
  > [style^='position: relative; min-width: calc(100% - 192px);']
  > [data-block-id]
  > div:nth-child(COL_NUMBER),
[data-block-id^='tableID'] > div:nth-child(5) > div:nth-child(COL_NUMBER) {
  width: 32px !important;
}
[data-block-id^='tableID']
  [style^='position: absolute; top: 0px; left: 0px; pointer-events: none;']:not(.notion-presence-container) {
  display: none;
}
```