# 术语对照表（中英 + 内部缩写）

| 中文 | 英文 / 缩写 | 含义 |
|---|---|---|
| 文生视频 | T2V (Text-to-Video) | 仅文本生成视频 |
| 图生视频 | I2V (Image-to-Video) | 首帧/尾帧图生成视频 |
| 参考生视频 | R2V (Reference-to-Video) | 用图/视频/音频做参考生成视频 |
| 视频生成视频 | V2V (Video-to-Video) | 视频编辑/延长 |
| 参考 | Reference | 任务类型：从素材提元素生成全新视频 |
| 编辑 | Edit | 任务类型：在原视频上加/删/改 |
| 延长 | Extend | 任务类型：续写或前补 |
| 组合 | Combo | 参考一个素材 + 编辑另一个素材 |
| 轨道补齐 | Track Completion | 多段视频拼接 + 过渡（最多 3 段、≤15s） |
| 主体 | Subject | 视频中的人 / 道具 / 场景 |
| 景别 | Shot Size | 特写/近景/中景/全景/远景/大远景 |
| 运镜 | Camera Movement | 推/拉/摇/移/跟拍/环绕等 |
| 景深虚化 | Bokeh / Shallow DoF | 浅景深，背景虚化 |
| 一镜到底 | One Shot / Long Take | 长镜头，无切镜 |
| 正反打 | Shot/Reverse Shot | 对话切镜 |
| 希区柯克变焦 | Dolly Zoom | 推 + 反向变焦，背景拉伸 |
| 迈克尔贝环绕 | Michael Bay 360 | 高速 360 度环绕 |
| 库布里克凝视 | Kubrick Stare | 对称构图 + 抬眼凝视 |
| 昆汀快速变焦 | Crash Zoom | 极快推镜 |
| FPV 穿越机视角 | FPV Drone | 第一人称穿越机 |
| 主观镜头 | POV (Point of View) | 角色"我"看出去的视角，画面中需有肢体锚点 |
| 一镜连续 POV | Orb | 单镜连续不切镜的第一人称动作戏，"相机就是角色的眼睛" |
| 肢体锚点 | Body Anchor | POV 画面中可见的"我"的身体局部（手/脚/方向盘等），缺它则漂回第三人称 |
| 子弹时间 | Bullet Time | 慢动作 + 高速环绕 |
| 荷兰角 | Dutch Angle | 倾斜镜头 |
| 抽离式后拉 | Pull-Out Shot | 持续后拉 |
| 白模视频 | White Model / Untextured | 仅保留几何与动作的白色 3D 视频 |
| 暗水印 | Watermark | 不可见水印（V-5 闪烁原因） |
| 抽卡 | 多次重抽 | 同 prompt 多次生成挑选 |
| ID 漂移 | ID Drift | 人物面部与参考图不一致 |
| 双胞胎 | Twin Effect | 同画面出现复制人物 |
| 胡言乱语 | Mumbling | 台词错乱、增添、重复 |

## 风格关键词常用对照

| 中文 | 英文 |
|---|---|
| 2D 日漫 | Japanese 2D anime |
| 3D 国漫 CG 仙侠 | Chinese 3D CG xianxia |
| 皮克斯 3D 动画 | Pixar 3D animation |
| 新海诚清新治愈 | Makoto Shinkai healing style |
| 粘土动画 | Clay animation |
| 毛毡动画 | Felt animation |
| 水墨风格 | Chinese ink wash |
| 赛博朋克 | Cyberpunk |
| 巴洛克 | Baroque |
| 电影级渲染 | Cinematic rendering |
| 超写实 | Photorealistic |
| 胶片颗粒感 | Film grain |
