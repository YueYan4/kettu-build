# Kettu build with chat wallpaper fix

A personal build of [Kettu](https://codeberg.org/cocobo1/Kettu) (BSD-3-Clause, see LICENSE) with one change: theme wallpapers work again on Discord versions that moved the chat screen to `components_native/chat/Messages.tsx` (or the A/B-tested `MessagesFunctional.tsx`).

- Based on Kettu commit `45bc734`
- The change: [wallpaper-fix.patch](wallpaper-fix.patch)

To use: Kettu Settings > Developer > Load from custom URL:

```
https://raw.githubusercontent.com/YueYan4/kettu-build/main/kettu.js
```
