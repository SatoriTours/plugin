# Satori App 的配置插件

Satori App 的配置插件

## 使用

1. 编辑对应的模板.
2. 到 Satori APP 的设置页面里面找到 “插件地址”， 填写这些配置的根路径。例如这个仓库就填写 https://raw.githubusercontent.com/SatoriTours/plugin/refs/heads/main.
3. 关掉 APP，然后重新打开，就会在背后自动更新对应的配置了.

## 文件解释

1. 默认用于归类的标签: [common_tags](https://github.com/SatoriTours/plugin/blob/main/common_tags).
2. 长的文章的渲染模板 [long_summary_result](https://github.com/SatoriTours/plugin/blob/main/long_summary_result)
3. 长文章的 AI Role 提示词 [long_summary_role](https://github.com/SatoriTours/plugin/blob/main/long_summary_role)
4. 短文章的 AI Role 提示词 [short_summary_role](https://github.com/SatoriTours/plugin/blob/main/short_summary_role)
5. 一句话总结标题的 AI 提示词 [summarize_oneline_prompt](https://github.com/SatoriTours/plugin/blob/main/summarize_oneline_prompt)
6. 一句话总结标题的 AI Role 提示词 [summarize_oneline_role](https://github.com/SatoriTours/plugin/blob/main/summarize_oneline_role)
7. 翻译中文的 AI 提示词 [translate_prompt](https://github.com/SatoriTours/plugin/blob/main/translate_prompt)
8. 翻译中文的 AI Role 提示词 [translate_role](https://github.com/SatoriTours/plugin/blob/main/translate_role)

##  注意事项

1. **长文章** 是指内容超过 300 个字符的算长文章.
2. 模板里面的变量名不能改变，而且{{变量}}不能留空格，例如，不能写成 {{ 变量 }}.
3. APP 里面填写的模板地址，需要返回的是文本内容，而不能是html.
