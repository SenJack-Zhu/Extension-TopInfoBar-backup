本项目基于 [SillyTavern/Extension-TopInfoBar](https://github.com/SillyTavern/Extension-TopInfoBar) 修改，
原项目遵循 [AGPL-3.0](https://github.com/SillyTavern/Extension-TopInfoBar/blob/main/LICENSE) 许可证。
修改了顶部状态栏布局为垂直居中并压缩宽度
# Chat Top Info Bar
## 修改说明

对顶部状态栏样式进行了以下调整：

- **垂直居中**：将 `align-items` 从 `baseline` 改为 `center`，图标和文字在状态栏中垂直居中对齐
- **压缩高度**：将高度从 `var(--bottomFormBlockSize)` 改为固定 `35px`，并新增 `min-height: 35px`，状态栏更紧凑
- **单行显示**：将 `flex-wrap` 从 `wrap` 改为 `nowrap`，所有按钮在一行内显示，不会换行
- **防止溢出**：新增 `overflow: hidden`，防止内部元素意外溢出破坏边缘圆角

Adds a top bar to the chat window with shortcuts to quick actions (left to right):

- Open a sidebar with a chats list
- Open chat file manager
- View chat file name and switch chats
- Search in the chat
- Create new chat
- Rename current chat file
- Delete current chat
- Close current chat

## How to install

Use this URL with the extension installer: `https://github.com/SillyTavern/Extension-TopInfoBar`

## License

AGPLv3
