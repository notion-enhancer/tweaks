# Bigger icons in calendar view

Created: Nov 6, 2020 3:46 PM
Creator(s): sancyo
Discord Message URL: https://ptb.discord.com/channels/748161877045149706/767863068617080902/774259357889200159
Release: Nov 6, 2020 7:10 AM

## *Before*

![https://cdn.discordapp.com/attachments/767863068617080902/774259408817487882/unknown.png](https://cdn.discordapp.com/attachments/767863068617080902/774259408817487882/unknown.png)

## *After*

![https://cdn.discordapp.com/attachments/767863068617080902/774259527054786580/unknown.png](https://cdn.discordapp.com/attachments/767863068617080902/774259527054786580/unknown.png)

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