## 插件提交 / Plugin Submission

### 插件信息

| 字段 | 值 |
|------|-----|
| ID | `your_plugin_id` |
| 显示名称 | 插件名称 |
| 作者 | 作者名 |
| 仓库 | `godotline/plugin-repo-name` |
| 版本 | `v0.1.0` |
| 最低 Godot 版本 | `4.7` |

### 检查清单

- [ ] 插件已发布到 GitHub 仓库并打了对应 tag
- [ ] `plugin_registry.json` 中的 `md5` 与 tag 的 ZIP 包一致（`git archive --format=zip v0.1.0 \| md5sum`）
- [ ] `sub_dir` 和 `dest_path` 路径正确（插件目录为 `addons/xxx`）
- [ ] 下载链接可访问（GitHub + Codeload）
- [ ] 插件已通过 Godot 4.7 编辑器的插件商店安装测试

### 说明

请简要描述插件的功能。