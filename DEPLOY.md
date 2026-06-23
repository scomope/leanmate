# 发布到 GitHub Pages

## 最简单方式：网页上传

1. 打开 GitHub。
2. 点击右上角 `+`，选择 `New repository`。
3. Repository name 填：`leanmate`。
4. 选择 `Public`。
5. 点击 `Create repository`。
6. 点击 `uploading an existing file`。
7. 上传本目录下的全部文件：
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `fitai-icon.svg`
   - `.nojekyll`
   - `README.md`
8. 提交后进入 `Settings` -> `Pages`。
9. Source 选择 `Deploy from a branch`。
10. Branch 选择 `main` 和 `/root`。
11. 保存。

等待几分钟后访问：

```text
https://scomope.github.io/leanmate/
```

## 注意

如果你把仓库名改成其他名字，访问地址中的 `leanmate` 也要改成你的仓库名。
