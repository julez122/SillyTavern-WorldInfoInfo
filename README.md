# SillyTavern - WorldInfo Info

## `custom-features` branch changes

- Fixes mobile bug where the panels hid the floating button, resulting in having to reload SillyTavern again to close it. [⤷](https://github.com/julez122/SillyTavern-WorldInfoInfo/commit/be95a94604260cf25cd3adbfc7811831d38a2af1)
- Changed homepage and author of `manifest.json` to my own fork. [⤷](https://github.com/julez122/SillyTavern-WorldInfoInfo/commit/dc4690220d2e94b6fe86146879054d30b2a11899)

---

Forked from the amazing LenAnderson. Original at https://github.com/LenAnderson/SillyTavern-WorldInfoInfo; this version adds the following features:

Click the book in the lower left corner of the screen to see the list of active entries. 

![list of entries](https://github.com/aikohanasaki/imagehost/blob/main/wii-list.png)

The floating book icon can be dragged to a different location (right-click to enable dragging). To reset its position, use `/wi-position-reset`.
![drag-to-move](https://github.com/aikohanasaki/imagehost/blob/main/wii-dragtomove.png)

On mobile, long-press the floating book icon to open its settings. On desktop, right-click it.

Tap anywhere on the screen to close the active-entry list and floating settings menu, including inside either window or on the book icon. Tapping a settings option applies its change before closing the menu. Scrolling the entry list or dragging the icon keeps the windows open.

🆕 `/wi-report` shows you what keywords triggered which entry during which round of recursion.

![Popup showing /wi-report](https://github.com/aikohanasaki/imagehost/blob/main/worldinfo.png)

Visibility and privacy

- Entries from hidden lorebooks are omitted from /wi-report for non-admin users.
- All counts in the report (summary and per-loop) reflect only visible entries.

![hidden lorebook](https://github.com/aikohanasaki/imagehost/blob/main/wii-listwithhide.png)

![report omits hidden books](https://github.com/aikohanasaki/imagehost/blob/main/wii-hiddenreport.png)

## License

This project is licensed under the GNU Affero General Public License v3.0. See [LICENSE](./LICENSE).
