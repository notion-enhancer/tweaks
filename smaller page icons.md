# Smaller page icons

> Removes unused space on top of pages and makes the page icon smaller (similar to database page icons).

**last tested/working:** Nov 19, 2020

**author(s):** [@CloudHill](https://github.com/CloudHill)

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
.notion-scroller[style*="display: flex; flex-direction: column"] > :first-child:not([style*="sticky"]) > :last-child {
    position: relative;
}

/* Set icon size */
.notion-scroller[style*="display: flex; flex-direction: column"] > :first-child:not([style*="sticky"]) .notion-record-icon {
    width: 38px !important;
    height: 38px !important;
}
.notion-scroller[style*="display: flex; flex-direction: column"] > :first-child:not([style*="sticky"]) .notion-record-icon * {
    width: 100% !important;
    height: 100% !important;
}

/* Icon placement */
.notion-scroller[style*="display: flex; flex-direction: column"] > :first-child:not([style*="sticky"]) .notion-record-icon {
    position: absolute !important;
    margin: 0 !important;
    top: 45px;
}

/* Emoji icon */
.notion-scroller[style*="display: flex; flex-direction: column"] > :first-child:not([style*="sticky"]) .notion-record-icon [style*="font-size: 78px"] {
    font-size: 38px !important;
}

/* Push page title to the right */
.notion-record-icon + .notion-page-controls + .notion-page-block {
    margin-left: 52px;
}

/* Remove space on top of the page when no icon or cover is set  */
.notion-page-controls[style*="margin-top: 80px"] {
    margin-top: 8px !important;
}
```