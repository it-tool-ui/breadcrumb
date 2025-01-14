# React Breadcrumb UI component

This is a very light UI Breadcrumb component library for ReactJS.
It's using TailwindCSS for styling.

You can also view the demo and get the source code directly for each component without installing this library.

- [Preview and get the code](https://it-tool.app/breadcrumb)

## Installation

```sh
npm install @it-tool-ui/breadcrumb
```

```js
import { Breadcrumb } from "@it-tool-ui/breadcrumb";

<Breadcrumb
  separator="arrow"
  items={[
    { label: "Home", value: "/home" },
    { label: "Music", value: "/music" },
    { label: "Genre", value: "/genre" },
    { label: "Album", value: "/album" },
    { label: "Song", value: "/song" },
  ]}
  itemsBeforeCollapse={1}
  itemsAfterCollapse={2}
  hasCollapse={true}
  disabled={false}
  onClick={handleClick}
/>;
```
