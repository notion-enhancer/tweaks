# Remove rounded edges of page icons in sidebar.md

**last tested/working:** Oct 28, 2021

**author(s):** [@GitMoleo](https://github.com/GitMoleo)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/q9NmYpt.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/VgOq9Gb.png"></td>
 </tr>
</table>

## css

```css
/* ========== REMOVE ROUNDED EDGES OF PAGE ICONS IN SIDEBAR ========== */
img[style*="display: block; object-fit: cover; border-radius: 3px; width: 17.76px; height: 17.76px; transition: opacity 100ms ease-out 0s;"] {
  border-radius: 0px !important;
}
```
