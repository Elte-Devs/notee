# Tauri Solid

## 🚀 Install

> [!TIP]
> Install [ni](https://github.com/antfu/ni) and choose `pnpm`.
>
> ```bash
> npm i -g @antfu/ni
> ```

### Install `tauri` and `pnpm` globally

```bash
ni -g @tauri-apps/cli@next pnpm
```

If you skip this step, you will need to run the tauri scripts like this: `npx tauri dev` or `nr tauri dev`.

### Install dependencies

```bash
ni
```

## 🥏 Run

- dev (browser): `nr dev`

### Desktop

- dev: `tauri dev`
- build: `tauri build`

### Mobile

- initialize for android/ios: `tauri [android|ios] init` (only once)
- dev: `tauri [android|ios] dev`
- open in android studio/xcode: `tauri [android|ios] open`
- build: `tauri [android|ios] build`
