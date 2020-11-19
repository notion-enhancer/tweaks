# Remove "Type '/' for commands"

**last tested/working:** Nov 19, 2020

**author(s):** [@Adambl4](https://github.com/Adambl4)

> Remove "Type '/' for commands"

_before tweak_

![before tweak](https://user-images.githubusercontent.com/18431607/99712639-67ddc880-2ab4-11eb-8f34-a77455829c34.png)

_after tweak_

![after tweak](https://user-images.githubusercontent.com/18431607/99712658-6dd3a980-2ab4-11eb-8654-d05585c50ca3.png)

## css

```css
/* ========== REMOVE TYPE FOR COMMANDS ========== */
[contenteditable]:empty:before {
  display: none !important;
}
```
