# Build Notes

- `npm run build` 实际执行的是 `zotero-plugin build && tsc --noEmit`。
- `zotero-plugin build` 会把插件构建产物输出到 `.scaffold/build`。
- `tsc --noEmit` 只做 TypeScript 类型检查，不会在源码目录生成 `.js` 或 `.d.ts` 编译产物。
