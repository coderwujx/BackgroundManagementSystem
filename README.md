# BackgroundManagementSystem

Vite 中使用 Vue 3 进行开发。

## 推荐插件

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## TS 中. vue 导入的类型支持

TypeScript 默认无法处理. vue 导入的类型信息，因此我们将 tsc CLI 替换为 vue-tsc 以进行类型检查。在编辑器中，我们需要 TypeScript Vue 插件[TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)来使 TypeScript 语言服务知道.vue 类型。

如果您觉得独立的 TypeScript 插件不够快，Volar 还实现了性能更高的接管模式。您可以通过以下步骤启用它：

1. 禁用内置 TypeScript 扩展
   1. 运行扩展：从 VSCode 的命令面板显示内置扩展
   2. 查找 TypeScript 和 JavaScript 语言功能，右键单击并选择禁用（工作区）
2. 通过从命令面板运行“开发人员：重新加载窗口”来重新加载 VSCode 窗口。

## 自定义配置

[Vite Configuration Reference](https://vitejs.dev/config/).

## 项目下载依赖

```sh
npm install
```

### 编译和热重载开发

```sh
npm run dev
```

### 类型检查，编译和缩小生产

```sh
npm run build
```
