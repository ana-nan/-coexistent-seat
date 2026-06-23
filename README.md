# 共栖之座 Final Submission

## 打开方式

推荐在本目录启动本地静态服务器：

```bash
python3 -m http.server
```

然后访问：

```text
http://127.0.0.1:8000/
```

也可以直接打开 `index.html` 查看 2D 展览。3D 模型视图会从外部 CDN 加载 viewer，现场无网络时可使用 2D 场景完成展示。

## 目录说明

```text
final-submission/
├─ index.html
├─ assets/
│  └─ renders/
│     ├─ 2d-scenes/
│     └─ 3d/
├─ report/
│  └─ 参数化设计报告-温力成.pdf
└─ docs/
   ├─ poster-outline.md
   ├─ video-script.md
   └─ screenshots/
```

## 核心文件

- `index.html`：期末展示主入口，由 `coexistent-seat-2d.html` 整理而来。
- `assets/renders/2d-scenes/`：12 个叙事场景图。
- `assets/renders/3d/`：Scene 01 和 Scene 06 的 3D 模型文件。
- `report/参数化设计报告-温力成.pdf`：课程报告。
