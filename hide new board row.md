# Hide '+ new' board row

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/Wpsyjez.jpg"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/MZDUqEQ.jpg"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE '+ NEW' BOARD ROW ========== */
.notion-board-group
  [style='user-select: none; transition: background 120ms ease-in 0s; cursor: pointer; display: inline-flex; align-items: center; flex-shrink: 0; white-space: nowrap; height: 32px; border-radius: 3px; font-size: 14px; line-height: 1.2; min-width: 0px; padding-left: 6px; padding-right: 8px; color: rgba(255, 255, 255, 0.4); width: 100%;'] {
  display: none !important;
}
```