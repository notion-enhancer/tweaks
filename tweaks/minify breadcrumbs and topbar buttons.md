# Minify breadcrumbs and topbar buttons

> Removes unused space on top of pages and makes the page icon smaller (similar to database page icons).

**last tested/working:** Nov 19, 2020

**author(s):** [@CloudHill](https://github.com/CloudHill)


<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://cdn.discordapp.com/attachments/767863068617080902/772752921355092008/unknown.png"></td>
    <td><img alt="after tweak" src="https://cdn.discordapp.com/attachments/767863068617080902/772753008458596373/unknown.png"></td>
 </tr>
</table>


## css

```css
/* ========== MINIFY BREADCRUMBS AND TOPBAR BUTTONS ========== */

/* Only apply when window size is <= 600px */
@media (max-width:600px) {
  /* Hide Share, Update, Favorite Buttons */
  .notion-topbar-actions> :not(:last-child) {
    display: none !important;
  }
  /* Remove icon margin */
  .notion-topbar-breadcrumb [role="button"] .notion-record-icon {
    margin-right: 0 !important;
  }
  /* Absolutely position page title */
  .notion-topbar-breadcrumb .notion-selectable:hover {
    z-index: 999;
  }
  .notion-topbar-breadcrumb [role="button"] {
    position: relative;
  }
  .notion-topbar-breadcrumb [role="button"] .notion-record-icon+div {
    background: var(--theme--interactive_hover);
    height: 24px;
    padding: 0 6px;
    border-radius: 3px;
    position: absolute;
    left: 26px;
    display: flex;
    align-items: center;
    pointer-events: none;
  }
  /* Title transition */
  .notion-topbar-breadcrumb [role="button"] .notion-record-icon+div {
    transition: opacity 20ms ease-in, max-width 300ms ease-in !important;
  }
  /* Hide title when not hovered */
  .notion-topbar-breadcrumb [role="button"]:not(:hover) .notion-record-icon+div {
    opacity: 0;
    max-width: 0px !important;
  }
  /* Show title when hovered */
  .notion-topbar-breadcrumb [role="button"]:hover .notion-record-icon+div {
    opacity: 1;
  }
  /* Transition delay when hovered */
  .notion-topbar-breadcrumb [role="button"]:hover .notion-record-icon, .notion-topbar-breadcrumb [role="button"]:hover .notion-record-icon+div {
    transition-delay: 200ms !important;
  }
}
```