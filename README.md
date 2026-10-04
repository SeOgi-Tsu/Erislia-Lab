# Erislia Lab

**English** | [简体中文](README.zh-CN.md)

Personal ComfyUI workflows, LoRA experiments, and test notes by **梦影Erislia**.

I explore AI image and video generation, including **MiniMax H3**, **Anima**, and **Qwen Image 2.1**. This collection will grow as I try more models and workflows.

[X / Twitter](https://x.com/dream_weebs) · [YouTube](https://www.youtube.com/@%E6%A2%A6%E5%BD%B1Erislia)

## Workflows

| Model / mode | Workflow |
| --- | --- |
| MiniMax H3 · T2V | [Native vs DMAD — text-to-video](minimax-h3/t2v/Minimax%2BH3_Native_vs_DMAD%E6%96%87%E7%94%9F%E8%A7%86%E9%A2%91.json) |
| MiniMax H3 · Ref2V | [Character Replace LoRA](minimax-h3/ref2v/Minimax%2BH3%2BCharacter%2BReplace%20Lora.json) |
| MiniMax H3 · Ref2V | [Keyframe Animation Generation · SEG](minimax-h3/ref2v/H3%2BKeyframe%2BAnimation%2BGeneration%2BSEG.json) |
| Anima | [Anima 2.9B vs Anima base](anima/Anima%2B2.9b%2Bvs%2BAnima%2Bbase.json) |
| Qwen Image 2.1 | [Any-angle image-to-image · 3D-loading version](qwen-image-2.1/Qwen%2BImage2.1%2B%E5%9B%BE%E7%94%9F%E5%9B%BE%E4%BB%BB%E6%84%8F%E8%A7%92%E5%BA%A6%E8%BD%AC%E6%8D%A2%2B%E5%8A%A0%E8%BD%BD3d%E7%89%88.json) |

The `minimax-h3/fl2v/` folder is ready for future uploads.

## Folder structure

```text
minimax-h3/
├── t2v/
├── fl2v/
└── ref2v/
anima/
qwen-image-2.1/
```

JSON files go directly in their model folders. MiniMax H3 is further grouped by generation mode: T2V, FL2V, and Ref2V. Brief usage notes and test observations belong here alongside the workflow links.

## Using a workflow

Download the workflow JSON and drag it into ComfyUI. Prepare the models, LoRAs, custom nodes, and input files referenced by that workflow.

## Adding workflows

Open the matching folder on GitHub and choose **Add file → Upload files**. Use a descriptive filename, then add its link and any useful notes to both language versions of this README.
