# cyp-pkg-com-google-chrome

Google Chrome 浏览器的 cyp 包仓库。

## 触发构建

在 GitHub Actions 页面手动触发 `Build Chrome Package`，输入版本号如 `138.0.7204.100`。

## 输出

每个架构生成独立的 `.cyp` 文件，发布到 GitHub Release：

- `chrome-{version}-macosarm64.cyp`
- `chrome-{version}-macosintel.cyp`
- `chrome-{version}-linux64.cyp`
- `chrome-{version}-win64.cyp`

## 安装

```bash
cyp install com.google.chrome
```
