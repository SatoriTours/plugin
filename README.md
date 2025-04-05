# Satori App 的配置插件

Satori App 的配置插件，提供了多种模板和 AI 提示词，帮助用户自定义内容生成和翻译。

## 使用

1. 编辑对应的模板文件，确保内容符合需求。
2. 打开 Satori APP 的设置页面，找到 “插件地址” 选项，填写这些配置的根路径。例如，本仓库的地址为：https://raw.githubusercontent.com/SatoriTours/plugin/refs/heads/main。
3. 关闭并重新打开 APP，配置会自动更新。

## 文件解释

1. **AI 模型配置文件**: [ai_models](https://github.com/SatoriTours/plugin/blob/main/ai_models)
    包含了用于生成和翻译的 AI 模型配置，定义了模型的类型、参数以及适用场景。

2. **AI 提示词配置文件**: [ai_prompts](https://github.com/SatoriTours/plugin/blob/main/ai_prompts)
    提供了多种 AI 提示词模板，用于指导模型生成特定内容或执行特定任务。

## 注意事项

1. **长文章** 是指内容超过 300 个字符的内容。
2. 模板中的变量名不能更改，且 `{{变量}}` 中不能有空格。例如，不能写成 `{{ 变量 }}`。
3. APP 中填写的模板地址必须返回纯文本内容，而不能是 HTML 格式。
4. 确保模板文件的内容格式正确，以避免解析错误。
