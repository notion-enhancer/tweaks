# Sticky table/list row

note: this will make the first row stick to the top of the screen when scrolling down. to stick a specific row replace `:nth-child(2)` with `[data-block-id="ROW_BLOCK_ID_HERE"]`. does not apply to inline databases.

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

![after tweak](https://i.imgur.com/Ur3N6ER.png)

## css

```css
/* ========== STICKY TABLE/LIST ROW ========== */
.notion-collection_view_page-block
  .notion-page-block.notion-collection-item:nth-child(2) {
  background: var(--theme--main);
  z-index: 10;
  position: sticky;
  top: 0;
}
.notion-table-view
  .notion-collection_view_page-block
  .notion-page-block.notion-collection-item:nth-child(2) {
  top: 32px;
}
```