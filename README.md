# LeanMate AI减脂教练

一个可直接部署到 GitHub Pages 的 AI 减脂教练 MVP 原型。

## 功能

- 今日目标看板
- BMI / BMR / TDEE 计算
- 食材库存管理
- AI 三餐计划模拟
- 运动计划与打卡
- 心情日记
- AI 教练聊天模拟
- PWA 配置，可添加到手机主屏幕

## GitHub Pages 发布方式

1. 在 GitHub 新建一个空仓库，例如 `leanmate`.
2. 上传本目录中的所有文件到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`.
4. Source 选择 `Deploy from a branch`.
5. Branch 选择 `main`，目录选择 `/root`.
6. 保存后等待 1 到 3 分钟。

发布成功后，访问地址通常是：

```text
https://你的GitHub用户名.github.io/仓库名/
```

如果仓库名是 `leanmate`，用户名是 `scomope`，地址通常是：

```text
https://scomope.github.io/leanmate/
```

## 本地预览

```bash
python3 -m http.server 8765
```

然后打开：

```text
http://127.0.0.1:8765/
```
