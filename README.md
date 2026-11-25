# NCM · Next-Concept Modeling

[中文](#中文) · [English](#english)

## 中文

这是一份 20 页的中文交互演示，讲解 NCM 如何从粗到细生成文本。你可以观察自回归模型逐词生成、掩码扩散模型多轮去噪，再跟着一个例子走完 NCM 的文本编码、逐尺度生成和解码过程。

**[在线演示](https://alphazerolan.github.io/ncm-html-slides/)** · [下载离线版（ZIP）](https://github.com/Alphazerolan/ncm-html-slides/archive/refs/heads/main.zip) · [原论文](https://arxiv.org/abs/2610.14162)

解压后，双击 `index.html` 即可离线播放。想直接看 NCM，可以从[第 10 页「逐尺度生成」](https://alphazerolan.github.io/ncm-html-slides/#ncm-generation)开始，或跳到[第 12 页的编码示例](https://alphazerolan.github.io/ncm-html-slides/#ncm-example)。

### 播放操作

| 你想做什么 | 操作 |
| --- | --- |
| 播放一段动画 | 点击画面或按空格。播放中再次点击可暂停，再点继续。每段结束后停在最后一帧，点击开始下一段；本页播完后再点翻页。 |
| 逐步查看 | 滚轮向下或按 → 前进一步，滚轮向上或按 ← 回退一步。 |
| 跳到指定位置 | 用「目录」或页码跳页，用动画菜单跳到本页某一段。 |
| 全屏演示 | 点击底部的「全屏」，按 Esc 退出。 |

### 把它交给 AI 做新演示

把 `index.html` 和你自己的素材一起交给 AI。文件里内嵌了英文 `agent.md`，说明播放器如何分段、回退和跳页。你只需说明每一页要展示什么，以及希望在哪里停下来讲解。例如：

> 读取 HTML 中的 agent.md，用附上的讲义制作三页演示。第二页先展示输入，等我点击，再并排展示两种方法的结果。保留滚轮回退和全屏功能，输出一个可离线播放的 HTML 文件。

**许可范围**　MIT 许可仅适用于原创播放器和可复用的动画模板代码。幻灯片正文、讲稿、示例数据、论文图表、机构标识及其他素材各自适用其原有权利条款。完整许可证随 [index.html](./index.html) 一同提供。

## English

This 20-slide, Chinese-language presentation uses animations to show how NCM generates text from coarse to fine. Watch an autoregressive model generate one token at a time, compare it with masked diffusion over several denoising rounds, then follow one NCM example from text encoding through generation and decoding.

**[Open the presentation](https://alphazerolan.github.io/ncm-html-slides/)** · [Download for offline use (ZIP)](https://github.com/Alphazerolan/ncm-html-slides/archive/refs/heads/main.zip) · [Read the paper](https://arxiv.org/abs/2610.14162)

Unzip the download and open `index.html` in your browser. To go straight to NCM, start with [coarse-to-fine generation on slide 10](https://alphazerolan.github.io/ncm-html-slides/#ncm-generation) or [the worked encoding example on slide 12](https://alphazerolan.github.io/ncm-html-slides/#ncm-example).

### Playback

| To | How |
| --- | --- |
| Play a segment | Click the slide or press Space. Click or press Space again to pause or resume. Each segment holds its final frame. Click to start the next segment, or to advance once the slide is complete. |
| Inspect individual steps | Scroll down or press → to step forward. Scroll up or press ← to step back. |
| Jump to a slide or segment | Open the contents (目录) or enter a page number. Use the animation menu to jump to a segment on the current slide. |
| Present in full screen | Click 全屏 in the bottom toolbar. Press Esc to exit. |

### Make your own presentation with AI

Give your AI assistant `index.html` and your own source material. The file contains an English `agent.md` guide to playback, stepping and navigation. Tell the assistant what each slide should show and where you want to pause for discussion. For example:

> Read the agent.md guide embedded in the HTML. Turn my attached notes into three slides. On slide two, show the input first. Wait for my click, then show the two methods’ results side by side. Keep backward stepping and full-screen mode. Return one HTML file that plays offline.

**License scope.** The MIT license covers only the original presentation player and reusable animation template code. Slide content, speaker notes, example data, paper figures, institutional logos and other assets remain subject to their respective terms. The complete license is embedded in [index.html](./index.html).
