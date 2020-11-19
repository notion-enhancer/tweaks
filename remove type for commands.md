# Remove "Type '/' for commands"

**last tested/working:** Nov 19, 2020

**author(s):** [@Adambl4](https://github.com/Adambl4)

> Remove "Type '/' for commands"

_before tweak_

![before tweak]()

_after tweak_

![after tweak]()

## css

```css
/* ========== REMOVE TYPE FOR COMMANDS ========== */
[contenteditable]:empty:before {
  display: none !important;
}
```