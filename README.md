# react-icons
Icons with link for React, from Simple Icons

[![Checked with Biome](https://img.shields.io/badge/Checked_with-Biome-60a5fa?style=flat&logo=biome)](https://biomejs.dev)

## Install

```bash
npm i @lwe8/react-icons
```

```bash
pnpm i @lwe8/react-icons
```

```bash
yarn add @lwe8/react-icons
```

## Use

```tsx
import ReactIcon  from "@lwe8/react-icons";

export function Home() {
  return (
    <main>
      <ReactIcon
        name="next-js"
        size={36}
        fillColor="#673ab8"
        fillOpacity={0.9}
        title="next-js"
      />
    </main>
  );
}
```

## Options

| Name          | Description                                                         |    Default               |
| ------------- | ------------------------------------------------------------------- | :---------------------:  |
| `name`        | Name of icon                                                        |                          |
| `title`       | Tooltip text for icon                                               |  name of icon            |
| `size`        | Size for icon                                                       |       24                 |
| `fillColor`   | Color for icon                                                      | "currentcolor"           |
| `fillOpacity` | Opacity of icon. 0.1 to 1                                           |      0.7                 |

## Acknowledgments

- All icons are sourced from Simple Icons - https://simpleicons.org/ - https://github.com/simple-icons/simple-icons. License - https://github.com/simple-icons/simple-icons?tab=CC0-1.0-1-ov-file#cc0-10-universal. Legal Disclaimer: https://github.com/simple-icons/simple-icons/blob/develop/DISCLAIMER.md#disclaimer
