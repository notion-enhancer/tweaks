# Remove "Type '/' for commands"

> Remove "Type '/' for commands"

**last tested/working:** Nov 19, 2020

**author(s):** [@Adambl4](https://github.com/Adambl4)

<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://user-images.githubusercontent.com/18431607/99712639-67ddc880-2ab4-11eb-8f34-a77455829c34.png"></td>
    <td><img alt="after tweak" src="https://user-images.githubusercontent.com/18431607/99712658-6dd3a980-2ab4-11eb-8654-d05585c50ca3.png"></td>
 </tr>
</table>


## css

```css
/* ========== REMOVE TYPE FOR COMMANDS ========== */
[contenteditable]:empty:before {
  display: none !important;
}
```
