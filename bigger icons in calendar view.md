# Bigger icons in calendar view

**last tested/working:** Nov 6, 2020 3:46 PM

**author(s):** [@fabiosangregorio](https://github.com/fabiosangregorio)

_before tweak_

![before tweak](https://cdn.discordapp.com/attachments/767863068617080902/774259408817487882/unknown.png)

_after tweak_

![after tweak](https://cdn.discordapp.com/attachments/767863068617080902/774259527054786580/unknown.png)

## css

```css
/* ========== BIGGER ICONS IN CALENDAR VIEW ========== */
.notion-calendar-view .notion-record-icon {
  width: 16px !important;
  height: 16px !important;
  margin-top: 0 !important;
}
.notion-calendar-view .notion-record-icon * {
  width: 100% !important;
  height: 100% !important;
}
```
