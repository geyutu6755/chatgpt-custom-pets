# ChatGPT 自定义宠物素材包

包含阿尼娅·福杰与汐墨两只动画宠物的可复用素材。仓库只保存素材、静态配置和校验摘要，不包含账号标识、登录凭据、上传链接、用户参考图片或临时日志。

## 文件结构

- `pets/anya-forger/work/spritesheet.png`、`pets/ximo/work/spritesheet.png`：用于 ChatGPT Work「Mini 与虚拟宠物」的 v2 PNG 精灵图。
- `pets/*/desktop/pet.json` 与 `spritesheet.webp`：桌面本地宠物包的配置和贴图。WebP 使用无损编码；透明度与所有可见像素均逐像素核对。
- `pets/*/preview/all-states.gif`：动作帧预览。
- `pets/*/verification.json`：尺寸、帧布局、校验结果及 PNG SHA-256。

## 格式

两张 PNG 均为 1536×2288、透明背景、v2；单格 192×208。前九行帧数为 `[6, 8, 8, 4, 5, 8, 6, 6, 6]`，最后两行为 8 个方向帧。两份 PNG 均通过官方精灵图预检。

## 上传到 ChatGPT Work

在「设置 → Mini 与虚拟宠物 → 创建虚拟宠物」选择对应宠物目录下的 `work/spritesheet.png`，再填写宠物名称与描述。GitHub 仓库只保存素材，不会迁移或关联任何 ChatGPT 账号中的宠物状态。

## 声明

此仓库是个人自定义素材归档，不是 OpenAI 官方项目。阿尼娅为《间谍过家家》角色；角色与作品权利归其权利人所有。
