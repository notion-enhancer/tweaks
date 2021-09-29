# Smaller page icons

> Removes unused space on top of pages and makes the page icon smaller (similar to database page icons).

**last tested/working:** Sept 20, 2021

**author(s):** [@CloudHill](https://github.com/CloudHill) [@Amadeus](https://github.com/l782993610)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://cdn.discordapp.com/attachments/767863068617080902/774277441501790229/unknown.png"></td>
    <td><img alt="after tweak" src="https://cdn.discordapp.com/attachments/767863068617080902/774277459377913866/unknown.png"></td>
 </tr>
</table>

## css

```css
/* ========== SMALLER PAGE ICONS ========== */

/* Place icon relative to the title container */
.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) {
    padding-top: 30px;
    position: relative;
}

/* Set icon size */
.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) > :first-child .notion-record-icon[aria-disabled="false"] {
    width: 38px !important;
    height: 38px !important;
}

.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) > :first-child .notion-record-icon[aria-disabled="false"] * {
    width: 100% !important;
    height: 100% !important;
}

/* Icon placement */
.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) > :first-child .notion-record-icon[aria-disabled="false"] {
    margin-top: 8px !important;
    margin-right: 8px !important;
    float: left;
}

.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) > :first-child .notion-page-controls {
  position:absolute !important;
  top: -5px;
}

/* Emoji icon */
.notion-scroller[style*="display: flex; flex-direction: column"] > :nth-child(2) > :first-child:not([style *= "display: flex"]) > :first-child .notion-record-icon [style*="font-size: 78px"] {
    font-size: 38px !important;
}


/* Remove space on top of the page when no icon or cover is set  */
.notion-page-controls[style*="margin-top: 80px"] {
    margin-top: 8px !important;
}

.notion-page-controls[style*="margin-top: 32px"] {
    margin-top: 8px !important;
}
```