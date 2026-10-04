# Erislia Lab

[English](README.md) | **简体中文**

我是 **梦影Erislia**，这里是我的个人 ComfyUI 工作流库，用来分享 LoRA 测试、工作流和使用记录。

目前主要整理 **MiniMax H3**、**Anima** 和 **Qwen Image 2.1** 相关的图像与视频生成工作流。以后测试其他模型，也会继续补充进来。

[X / Twitter](https://x.com/dream_weebs) · [YouTube](https://www.youtube.com/@%E6%A2%A6%E5%BD%B1Erislia)

## 已上传的工作流

| 模型 / 模式 | 工作流 |
| --- | --- |
| MiniMax H3 · T2V | [Native 与 DMAD 文生视频对比](minimax-h3/t2v/Minimax%2BH3_Native_vs_DMAD%E6%96%87%E7%94%9F%E8%A7%86%E9%A2%91.json) |
| MiniMax H3 · Ref2V | [角色替换 LoRA](minimax-h3/ref2v/Minimax%2BH3%2BCharacter%2BReplace%20Lora.json) |
| MiniMax H3 · Ref2V | [关键帧动画生成 · SEG](minimax-h3/ref2v/H3%2BKeyframe%2BAnimation%2BGeneration%2BSEG.json) |
| Anima | [Anima 2.9B 与 Anima base 对比](anima/Anima%2B2.9b%2Bvs%2BAnima%2Bbase.json) |
| Qwen Image 2.1 | [图生图任意角度转换 · 加载 3D 版](qwen-image-2.1/Qwen%2BImage2.1%2B%E5%9B%BE%E7%94%9F%E5%9B%BE%E4%BB%BB%E6%84%8F%E8%A7%92%E5%BA%A6%E8%BD%AC%E6%8D%A2%2B%E5%8A%A0%E8%BD%BD3d%E7%89%88.json) |

`minimax-h3/fl2v/` 已建好，目前作为待上传的预留目录。

## 目录结构

```text
minimax-h3/
├── t2v/
├── fl2v/
└── ref2v/
anima/
qwen-image-2.1/
```

JSON 直接放在对应的模型目录里；MiniMax H3 再按 T2V、FL2V、Ref2V 分类。简短的使用说明和测试心得集中写在这里，放在对应工作流链接旁边。

## 使用方法

下载工作流 JSON，拖入 ComfyUI。根据工作流中引用的内容，准备对应的模型、LoRA、自定义节点和输入素材。

## 添加工作流

进入 GitHub 上对应的目录，点击 **Add file → Upload files** 上传 JSON。文件名写清用途，再把链接和必要说明同步补充到中英文两版 README 中。
