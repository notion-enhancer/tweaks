# Hide discussions 
> Hide discussions (the comment threads at the top of each page)

**last tested/working:** Oct 1, 2020

**author(s):** [@dragonwocky](https://github.com/dragonwocky)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/gOGZsbZ.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/8sXrj4Z.png"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE DISCUSSIONS ========== */
[style*='env(safe-area-inset-left)']:not(.notion-page-content)
  [style*='width: 100%; height: 1px;'],
.notion-page-view-discussion {
  display: none !important;
}
```