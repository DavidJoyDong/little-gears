解决一个问题：
- macOS 中，如果一个 App 的窗口被最小化（Minimize），那么你需要通过点击 Dock 上的图标来让窗口出现。
- macOS 的窗口切换，是让一个 App 激活（Activated）
  - 判断当前激活的 App：看屏幕左上角显示的是哪个 App 名称
  - 激活的 App 是可以最小化的 Minimize。

有时候，你切换到一个 App，却发现它被最小化了，还需要进一步把窗口弄出来，比较麻烦。

已知瑕疵：
- 使用 “Activate Application Switcher” 时，如果多次按 Tab 键，也会导致最后的命令执行多次，但貌似没有明显影响。