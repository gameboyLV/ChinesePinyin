# ChinesePinyin
Convert Chinese character to pinyin

MySql中文转拼音，达梦中文转拼音，支持UTF-8字符集的2万余个汉字

```
select fn_pinyins('上海自来水来自海上')
-- output: SHZLSLZHS
```

```
select fn_pinyinf('上海自来水来自海上')
-- output: shanghaizilaishuilaizihaishang