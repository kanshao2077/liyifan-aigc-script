# 教学短视频剪辑执行手册

以下是设计起点，不是每条视频都必须套用的固定招式。先保证案例能证明口播，再选择节奏与声音工具。

## 教学节奏

- 人物出镜负责问题、判断、公式和总结。
- 案例全屏负责让观众先感受结果；重要 A/B 播放时通常暂停口播。
- 时间线、波形、关键帧和参数负责说明“具体改了什么”。
- 每个方法都要尽快回放结果，避免连续讲理论后才一次性给画面。
- 口播从人物切到案例时，可用 L-cut 保留上一句声音；进入下一步前，可用 J-cut 让下一段发动机、换挡或口播先出现，建立预期。

## 积累—打断—释放

这是对情绪曲线的工作命名，不是软件厂商的标准按钮。

### 积累

- 画面从局部、静态或低信息开始，逐步增加动作、景别和速度。
- 声音从底噪/环境声逐层加入 Foley、发动机和音乐。
- 镜头时长可以逐步缩短，但不要第一镜就交出最强远景和满编音乐。

### 打断

- 在高潮前主动减少信息：切到内饰/方向盘近景，收掉 BGM，只留一个可识别的机械声或近乎留白。
- 黑场不是必选。首轮可试 3–8 帧的近乎留白；黑场可先试 4/6/8 帧并按 25/30fps 项目调整。
- 全静音或全黑太久容易像卡顿或视频结束。保留发动机怠速、换挡或一次呼吸式声音锚点通常更稳。

### 释放

- 在音乐段落变化、强拍或 drop 点切最有冲击力的宽景/高速动作。
- BGM、发动机和关键动作可以同点回来，但高潮镜头要留足辨识时间，不要只闪 0.3 秒。
- 前面的积累和打断越清楚，释放越有效；没有预期时只加重音不会自动变成高潮。

## 声音工具

- **J-cut**：下一镜的声音先进入，画面稍后切；适合预告发动机、换挡、下一段口播或 riser。首轮可提前约 0.2–0.6 秒，再按素材调整。
- **L-cut**：画面先切到案例，上一句口播继续；适合“比如这里”“我们实际做一次”。注意统一房间底噪，避免露出剪口。
- **Riser**：终点锁到 impact 或断点，常见首轮长度约 0.6–1.5 秒。不要每个转场都用。
- **Impact/Hit**：瞬态峰值对齐切点；若后面需要留白，控制尾音，避免低频拖尾填满空白。
- **Ducking**：口播区让 BGM 退后，断点再更明显地抽离；以听清口播为准，不把固定 dB 数写成普遍标准。
- 音轨至少区分口播、BGM、环境/发动机、动作 Foley、riser/whoosh、impact，便于分别控制。

## A/B 对比

- 先明确变量。比较完整剪辑节奏时，可以重排镜头、调整时长和声音，但口播要准确称为“重新组织镜头和声音”；比较纯声音时，画面顺序和时长必须完全相同。
- 两版尽量同总时长、同画幅、同字幕条件和相近总响度。B 版不能只因更响而显得更好。
- 先完整播 A，再完整播 B，然后才解释或并排总结。左右分屏不要同时播放两套声音；可先后高亮两侧，竖屏更适合先后全屏播放。
- 先静音检查纯画面的景别、动作和时长变化，再加音乐与音效，防止用燃曲遮住“素材拼盘”。

## 连续性与风险

- AI 汽车素材检查车型、车色、轮毂、方向盘、驾驶员、道路方向、昼夜和光线连续性。
- 动作匹配优先在方向盘转动、换挡、踩油门等动作中段切换；保留切点前后可调余量。
- 品牌名、Logo 和车型不确定时，用“跑车/汽车”或明确标待核对，不凭相似外观写死。
- 完整案例播放时减少花字，避免挡住车身、手部、参数或时间线关键位置。
- 音频硬切前后检查 click、底噪跳变和低频尾巴；需要突然停时也可用极短淡变消除技术噪声。

## 主要参考

- Apple Final Cut Pro：[J/L-cut 与 B-roll](https://support.apple.com/zh-cn/guide/final-cut-pro/ver1632d82c/mac)
- Apple Final Cut Pro：[按歌曲段落、节拍和小节剪辑](https://support.apple.com/en-gb/guide/final-cut-pro/ver65b55a2b7/mac)
- Adobe Premiere：[J-cut 与 L-cut](https://helpx.adobe.com/ie/premiere/desktop/edit-projects/trim-clips/perform-j-cuts-and-l-cuts.html)
- Adobe Premiere：[自动 Ducking](https://helpx.adobe.com/premiere/desktop/add-audio-effects/adjust-volume-and-levels/automatically-duck-audio.html)
- Adobe Premiere：[音频 Crossfade](https://helpx.adobe.com/premiere/desktop/add-audio-effects/apply-audio-transitions/audio-crossfade-transitions.html)
- Adobe Premiere：[Black Video](https://helpx.adobe.com/premiere/desktop/add-video-effects/commonly-used-effects/create-black-video-clips.html)
- Blackmagic Design：[DaVinci Resolve 20 Beginner's Guide](https://documents.blackmagicdesign.com/UserManuals/DaVinci-Resolve-20-Beginners-Guide.pdf)
- Frame.io：[用动态起伏组织剪辑](https://blog.frame.io/2022/03/29/oscars-2022-best-editing-roundtable/)
- Frame.io：[留白需要先建立节奏预期](https://blog.frame.io/2017/05/08/edit-with-silence/)
- Frame.io：[动作中切与空间方向](https://blog.frame.io/2019/01/31/editing-action-scenes/)
