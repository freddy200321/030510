# Catch the Stars — 接星星

一个单文件的前端小游戏（HTML/CSS/JS），可以直接部署到 GitHub Pages。

## 特性
- 桌面 + 移动端支持（键盘与触控）
- 本地保存最高分（localStorage）
- 无依赖，单文件，易于定制

## 使用方法
1. 新建 GitHub 仓库，将 `index.html` 上传到仓库根目录。
2. 在仓库设置 → Pages → 选择 `main` 分支和 `/ (root)`，保存。
3. 访问 `https://<你的用户名>.github.io/<仓库名>/` 即可玩。

## 自定义建议
- 修改配色、图标、物理参数（掉落速度、生成频率）来调整难度。
- 可以把星星替换为你想要的图片（修改 `.star` 样式或将元素替换成 `<img>`）。
- 增加音效：在 `createStar()` 或碰撞处播放短音频。

## 授权
MIT License
