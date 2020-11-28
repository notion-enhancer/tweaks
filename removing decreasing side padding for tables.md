# Removing/decreasing side padding for tables


**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/NI1Z73V.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/atdYZ3V.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== REMOVING/DECREASING SIDE PADDING FOR TABLES ========== */
[style^='flex-shrink: 0; flex-grow: 1; width: 100%; max-width: 100%; display: flex; align-items: center; flex-direction: column; font-size: 16px; color: rgba(255, 255, 255, 0.9); padding: 0px 96px 30vh;']
  .notion-table-view,
[class='notion-scroller'] > .notion-table-view {
  padding-left: 35px !important;
  padding-right: 15px !important;
  min-width: 0% !important;
}
[style^='flex-shrink: 0; flex-grow: 1; width: 100%; max-width: 100%; display: flex; align-items: center; flex-direction: column; font-size: 16px; color: rgba(255, 255, 255, 0.9); padding: 0px 96px 30vh;']
  .notion-selectable
  .notion-scroller.horizontal::-webkit-scrollbar-track {
  margin-left: 10px;
  margin-right: 10px;
}
```