# 案例 04：絲綢飄帶新中式插畫（模板型提示詞） | Case 04: Silk Ribbon New-Chinese Illustration (Template Prompt)

![效果圖 / Result](image.png)

模板型提示詞：先在開頭定好主色、遠景、紋樣、生物、人物與詩句，再把變量填進正文的方括號位置。本例填的是閩南海洋絲路主題：靛藍＋赤陶紅、紅磚古厝與媽祖廟、海鷗與漁家女。

A template-style prompt: define palette, backdrop, motifs, creature, figure and a poetic line up front, then fill those variables into the bracketed slots in the body. This example uses a Minnan / Maritime Silk Road theme: indigo + terracotta, red-brick houses and a Mazu temple, seagulls and a fisher girl.

## 完整提示詞 / Full Prompt

```
主色=靛蓝+赤陶红 | 远景=红砖古厝+妈祖庙剪影
纹样=闽南剪瓷雕纹样(海浪纹/牡丹/龙凤)
生物=海鸥 | 人物=渔家女+帆船(非骑马，改海丝意象)
诗意="海上丝路千帆过、妈祖庇佑渡重洋"
辅助色=靛蓝+赤陶+月白+鎏金 | 飘带比喻=海浪翻涌的绸缎/渔网银光

[画幅比例]竖版/横版，新中式东方美学极简插画，[地域文化符号]与现代国潮视觉融合，东方古典[主题关键词]意境海报。


画面以高饱和[主色调]、[主色]渐变背景为主，上半部与[留白方位]保留大面积纯净留白，下方是一片[地面色调]色、空旷地面，远处仅有若隐若现的淡[远景色]水墨[远景元素]和轻雾，空间安静辽阔。


画面[方位]垂落一组巨大、轻盈、飘逸的透明丝绸与薄纱，丝带从画面顶部延伸而下，在空中形成优雅的S形曲线和多层交叠的旋转结构。纱幔材质晶莹剔透，具有琉璃、欧根纱、珍珠薄膜般的半透明质感，边缘柔软发光，表面出现淡[辅助色1]、[辅助色2]、[辅助色3]、[辅助色4]、虹彩色的细腻折射，高光通透，层次丰富，像被风吹动的[意象比喻]。


部分丝带内部镶嵌精美的[地域文化纹样类型]，包括[纹样元素1]、[纹样元素2]、[纹样元素3]、[纹样元素4]、鎏金描边和复古矿物色纹饰。纹样以[主纹样色1]、[主纹样色2]、[主纹样色3]、鎏金、米黄为主，与透明纱幔相互穿插，既有古典装饰性，又具有现代高级时尚质感。


数只[飞鸟/生物类型]围绕丝带上下穿梭飞翔，采用简洁细腻的工笔插画造型，[羽毛/体色特征]、[腹部/辅助色特征]、[喙部/局部特征]，[尾部/形态特征]，飞行动势各不相同，有的迎风上扬，有的向下俯冲，有的沿丝带盘旋，形成富有节奏感的视觉引导。


画面[方位]靠近地平线的位置，安排一个极小比例的[人物身份]骑着/乘坐[交通工具]缓慢前行。人物戴[头饰]，穿[服饰色彩][服饰类型]，[交通工具]配有少量[配饰色彩1]、[配饰色彩2]鞍具，人物与[交通工具]造型简洁精致，带有传统工笔画与现代扁平插画结合的感觉。[交通工具]下方留有柔和细长的灰色投影，强调寂静旅途和辽阔空间。


整体构图[构图方向描述]，巨大飘带与微小[人物]形成强烈尺度对比，大面积负空间，画面具有"[诗意主题句]"的诗意叙事。高饱和但不刺眼，色彩清透，[主色]、[辅色1]、[辅色2]、鎏金形成鲜明对比。


精致东方装饰画，国风艺术海报，[文化元素]，[主题]幻想，工笔线描，矿物颜料质感，轻微岩彩颗粒，柔和光晕，细腻描金，高级平面设计，干净背景，画面无文字，无边框，高完成度。
```

## 適用模型 / Recommended Models

適用於中文語義理解強的插畫模型：即夢、GPT Image（Image2）、Midjourney（建議加 `--ar 3:4` 或 `--ar 16:9` 切換豎／橫版）。

Best on illustration models with strong Chinese-language understanding: Jimeng, GPT Image (Image2), Midjourney (add `--ar 3:4` or `--ar 16:9` for portrait/landscape).

## 修改說明 / How to Adapt

- 用法：先改開頭的變量表（主色、遠景、紋樣、生物、人物、詩句），再把正文所有 `[方括號]` 逐一替換成對應值，不要留下空括號。
- 換地域主題：例如換成江南水鄉——主色改月白＋黛青，遠景改小橋流水，生物改白鷺，人物改撐油紙傘的女子，紋樣改蘇繡花鳥。
- 尺度對比是畫面靈魂：保留「巨大飄帶＋極小人物」與大面積留白的句子，不要刪。

- How to use: edit the variable list at the top (palette, backdrop, motifs, creature, figure, poetic line) first, then replace every `[bracketed slot]` in the body — leave no empty brackets.
- Change the regional theme: e.g. a Jiangnan water town — moon-white + dark teal palette, bridges and canals as backdrop, egrets, a woman with an oil-paper umbrella, Suzhou-embroidery motifs.
- The scale contrast is the soul of the image: keep the "giant ribbons + tiny figure" and generous negative-space lines intact.

---
更多同類提示詞 / More prompts like this: [AIOAE 免費 AI 圖片提示詞庫](https://aioae.us/prompts)
