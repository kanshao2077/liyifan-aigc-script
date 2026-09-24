# 李一帆 AIGC 教学口播 Skill

把已确认的选题和核心观点，写成完整口播、逐段素材方案与制作清单。重点是影视原理、案例对比和可执行教学，不是工具新闻改写或“一键成片”宣传。

这是根据用户提供的29篇有效口播样本整理的内容生产工作流。仓库名称描述其目标使用场景，不代表李一帆本人或其公司已审核、发布或背书本项目。

## 输入与输出

输入：选题方向、大概内容或核心观点，以及可选的案例、产品资料、Prompt、数据和媒体。

输出固定为四部分：

1. 3—5个标题，标出最推荐标题。
2. 一篇完整、可录制的口播，原则上不少于3分钟，不靠废话凑时长。
3. 逐段素材表：对应口播、画面设计、素材、屏幕文字、获取方式。
4. 素材总清单：实测、录屏、AI生成、搜索下载、后期制作、已有与待补充。

选题默认已获人工认可，不重复评审；适合与选题阶段的确认流程衔接，但不依赖其他Skill。

## 使用

将仓库中的整个 `liyifan-aigc-script/` 文件夹安装到运行环境的Skill目录。Codex默认目录为 `~/.codex/skills/`；如果同名Skill已经存在，先备份并比较差异，不要直接覆盖定制内容。其他支持SKILL.md的工具按各自加载方式使用。

安装后输入：

```text
使用 $liyifan-aigc-script

选题：同样5个AI镜头，怎么剪完还是像Demo？
核心观点：重点讲信息顺序、剪辑节奏和情绪推进，不讲炫技转场。
已有资料：附上镜头描述、参考素材或工具资料；没有则说明暂无。
```

该Skill本身不包含模型接口或媒体生成服务。查询当前产品事实需要运行环境具备检索能力；实际生成、录制、剪辑及授权另行处理。

## 完整示例

| 方向 | 输入 | 输出 |
| --- | --- | --- |
| 运镜知识 | [运镜动机](liyifan-aigc-script/examples/example-input.md) | [完整口播与素材方案](liyifan-aigc-script/examples/example-output.md) |
| 声音设计 | [声音五层](liyifan-aigc-script/examples/sound-input.md) | [完整口播与素材方案](liyifan-aigc-script/examples/sound-output.md) |
| 商业制作 | [无模特产品视频](liyifan-aigc-script/examples/commerce-input.md) | [完整口播与素材方案](liyifan-aigc-script/examples/commerce-output.md) |

示例是原创教学演练，不是李一帆已发布作品，也不代表已经生成了对应媒体或取得实测效果。

## 文件导航

- [SKILL.md](liyifan-aigc-script/SKILL.md)：运行入口、流程、输出规范。
- [风格指纹](liyifan-aigc-script/references/style-fingerprint.md)：人设、教学机制、节奏及分析边界。
- [教学结构](liyifan-aigc-script/references/teaching-patterns.md)：六类基于样本的教学路线。
- [语言习惯](liyifan-aigc-script/references/language-patterns.md)：稳定表达、条件表达与偶发梗。
- [开头与结尾](liyifan-aigc-script/references/openings-and-endings.md)：开场、转场、复盘与收尾。
- [制作规则](liyifan-aigc-script/references/production-rules.md)：事实核验、时长、提示词及素材交接。
- [样本分析](liyifan-aigc-script/references/sample-analysis.md)：29篇样本的结构分析与索引。
- [测试记录](liyifan-aigc-script/references/test-report.md)：三题输出审阅、修正和未验证边界。
- [界面配置](liyifan-aigc-script/agents/openai.yaml)：显示名称与默认调用提示。

## 验证与边界

已完成三题写稿测试、逐段素材对应检查和Skill格式校验；未测试真实视频生成、本人试读、广告转化或平台传播效果。没有现成媒体时，方案会区分待制作与待验证，不编造“我已实测”的结果。

历史样本只有文字稿，没有成片时间码或完播数据。模型功能、价格和操作界面需要在实际使用时重新核实。

发布包不包含原始口播稿、账户凭据、私人附件或本机绝对路径。分析中保留必要的短语及结构描述。第三方名称、IP表达和素材不因本仓库公开而自动获得使用授权；本版本未附加开源许可证。
