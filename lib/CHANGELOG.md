# nextjs-themes

## 3.1.4

### Patch Changes

- 8e0f4c4: Apps not setting moduleResolution to Node16 or NodeNext are failing to build as they don't respect exports field. Fix by adding one level of nexting inside nextjs folder

## 3.1.3

> Complete rewrite but no breaking changes

### Major Changes

- 387587f: Complete rewrite of the library ensuring minimum breaking changes.

### Patch Changes

- 4b10902: Remove next from peer dependency as we no longer depend on next.js specific APIs
- bdbf4d6: Update peer-dependency next.js to 10-15