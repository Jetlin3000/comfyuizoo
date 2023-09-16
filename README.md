# ComfyUI 简体中文版 【Zho】


使用教程/详解视频：
- [【ComfyUI系统性教程来啦！简体中文版整合包+全新升级云部署！预装超多模块组一键启动！内置超全标准工作流！Stable Diffusion | Ai+建筑】](https://www.bilibili.com/video/BV14r4y1d7r8/?share_source=copy_web&vd_source=aa2245cc0c4c36a0387a65937847fd3c)

- [【简体中文版ComfyUI来啦！我把界面&常用模块&管理器&风格插件都汉化了！Stable Diffusion  | Ai+建筑】](https://www.bilibili.com/video/BV1ym4y1W71m/?share_source=copy_web&vd_source=aa2245cc0c4c36a0387a65937847fd3c)

## 更新日志：

20230916
- 近期谷歌Colab禁止了免费层运行SD，所以专门做了Kaggle平台的免费云部署，每周30小时免费冲浪时间，项目详见：[Kaggle ComfyUI云部署1.0](https://www.kaggle.com/matuma3965/kaggle-xl1-0nl-comfy-1-zho)、[Kaggle ComfyUI云部署1.0临时空间版](https://www.kaggle.com/matuma3965/kaggletp-xl1-0nl-comfy-1-zho)

20230909
- 编写了ComfyUI选择器Selector + 综合输入CoInput模块组（双语版），代码详见：[ComfyUI-Selector-CoInput-Multilingual](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Selector-CoInput-Multilingual.git)

20230816
- 简体中文版整合包正式上线，预装超多模块组（简版5个，标准版25个），下载地址：https://pan.baidu.com/s/11znfR-gm0ieHHEVpOzVhCQ?pwd=e5cu 
提取码：e5cu
- 中文云部署全新升级，新增模组下载器，详见：[ComfyUI 云部署1.0](https://colab.research.google.com/drive/1TxdWQyN71v56TyMr6AFUv0PZ_jjMUExb?usp=sharing)

20230815
- 编写了一个常用参考网站的主菜单按钮，代码详见：[常用艺术库 按钮 双语版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-SDXL_Art_Library-Button)

20230814
- 完成ComfyUI Overlay（Layout）节点汉化，代码详见：[ComfyUI 排版模块 简体中文版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Layout-Zh-Chinese/tree/main)


20230806 
- 完成ComfyUI 20+常用节点汉化，代码详见：[ComfyUI 常用节点 简体中文版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/blob/master/custom_nodes/Zho_Main_Nodes_Chinese.py)

   
  <details>
    <summary>节点列表</summary>


     1.采样器_Zho

     2.高级采样器_Zho
  
     3.主模型加载器_Zho
  
     4.VAE加载器_Zho
  
     5.Lora加载器_Zho
  
     6.ControlNet加载器_Zho
  
     7.GLIGEN加载器_Zho
  
     8.提示词_Zho
  
     9.CLIP跳过层_Zho
  
     10.GLIGEN区域设定_Zho
  
     11.ControlNet_Zho
  
     12.初始潜空间_Zho
  
     13.VAE解码器_Zho
  
     14.VAE编码器_Zho
  
     15.VAE编码器_重绘_Zho
  
     16.批次选择_Zho
  
     17.批次复制_Zho
  
     18.潜空间放大_Zho
  
     19.潜空间放大_比例_Zho
  
     20.图像保存_Zho
  
     21.图像预览_Zho
  
     22.图像加载_Zho
  
     23.图像放大_Zho
  
     24.图像放大_比例_Zho
  
     25.图像反转_Zho

  </details>

20230804 
- 完成ComfyUI Styler汉化，代码详见：[ComfyUI Styler 简体中文版](https://github.com/ZHO-ZHO-ZHO/sdxl_prompt_styler-Zh-Chinese)


20230803 
- 完成ComfyUI界面汉化，并新增ZHO主题配色 ，代码详见：[ComfyUI 简体中文版界面](https://github.com/ZHO-ZHO-ZHO/ComfyUI-UI-Zh-Chinese.git)
- 完成ComfyUI Manager汉化 ，代码详见：[ComfyUI Manager 简体中文版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Manager-Zh-Chinese.git)


--------
声明：我并不是ComfyUI的作者，我只是对界面做了汉化 + 常用节点汉化 + 新增了一个主题配色，原作者在[ComfyUI](https://github.com/comfyanonymous/ComfyUI)

--------
## 使用方法：
本地部署

- 简体中文版整合包正式上线，预装超多模块组（简版5个，标准版25个），下载地址：https://pan.baidu.com/s/11znfR-gm0ieHHEVpOzVhCQ?pwd=e5cu 
提取码：e5cu

- 未部署过的小伙伴：
先下载ComfyUI作者的[整合包](https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu118_or_cpu.7z)，然后再把web和custom nodes文件夹下载到本地，覆盖掉原来的web和custom nodes文件夹即可（自己安装的其他模块也放到新的custom nodes文件夹里），运行之后就可看到中文简体版的界面。

- 已部署的小伙伴：
只需把web和custom nodes文件夹下载到本地，覆盖掉原来的web和custom nodes文件夹即可（自己安装的其他模块也放到新的custom nodes文件夹里）。

- 需要中文版Manager的小伙伴，移步[ComfyUI Manager 简体中文版](https://github.com/ZHO-ZHO-ZHO/ComfyUI-Manager-Zh-Chinese.git)

- 需要中文版Styler的小伙伴，移步[ComfyUI Styler 简体中文版](https://github.com/ZHO-ZHO-ZHO/sdxl_prompt_styler-Zh-Chinese)

Google Colab 云部署：
- 我制作的[ComfyUI 云部署1.0](https://colab.research.google.com/drive/1TxdWQyN71v56TyMr6AFUv0PZ_jjMUExb?usp=sharing)：已载入简体中文版界面、简体中文版常用节点、简体中文版Manager、简体中文版Styler，同时也支持最新SDXL1.0模型，并且提供了支持中文输入的[【SDXL系列标准工作流 -Zho-】](https://drive.google.com/drive/folders/1Jxw2IFvb8_pExowWo6DkaYiUgrTpMZvp?usp=sharing)

- 有自己colab云部署的小伙伴，只需git安装此库即可

--------
## 中文版工作流：
基础文生图工作流：[Zho_文生图](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/blob/master/Zho%E6%B1%89%E5%8C%96_%E9%BB%98%E8%AE%A4%E5%B7%A5%E4%BD%9C%E6%B5%81.json)



--------
## 下载：

整合包百度网盘下载：

链接：https://pan.baidu.com/s/11znfR-gm0ieHHEVpOzVhCQ?pwd=e5cu 
提取码：e5cu


汉化包百度网盘下载：

链接：https://pan.baidu.com/s/1wck3rvUkzO5GS8mduR6wfQ?pwd=pc1o 
提取码：pc1o

直接下载：

web已修复与原始图片加载冲突的问题、汉化默认工作流

[web.zip](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/files/12311746/web.zip)

[custom_nodes.zip](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/files/12288332/custom_nodes.zip)

[ComfyUI-Manager-Zh-Chinese-main.zip](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/files/12288331/ComfyUI-Manager-Zh-Chinese-main.zip)

[sdxl_prompt_styler-Zh-Chinese-main.zip](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/files/12288329/sdxl_prompt_styler-Zh-Chinese-main.zip)



--------
## 20+常用节点 简体中文版：
![image](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/87a1d659-fbce-4918-8578-82a6413dd9ca)

![image](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/f3b3357d-4f88-4646-a733-a6617a39bad0)


--------
## 简体中文操作面板 + ZHO配色主题：

![Dingtalk_20230803173143](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/8c4b11d4-c698-4da8-93fd-f384e749dadc)![Dingtalk_20230803173317](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/5f1c1026-9039-49b6-bc73-71a7b1e4e3c9)

![Dingtalk_20230803173252](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/2bbc031f-da5d-4e3d-a0c9-6ddffa8593e0)





![Dingtalk_20230803173631](https://github.com/ZHO-ZHO-ZHO/ComfyUI-ZHO-Chinese/assets/140084057/61e06dc7-515b-4d02-8647-3e6c422f1a6a)





------------------------------------------------------------





ComfyUI
=======
A powerful and modular stable diffusion GUI and backend.
-----------
![ComfyUI Screenshot](comfyui_screenshot.png)

This ui will let you design and execute advanced stable diffusion pipelines using a graph/nodes/flowchart based interface. For some workflow examples and see what ComfyUI can do you can check out:
### [ComfyUI Examples](https://comfyanonymous.github.io/ComfyUI_examples/)

### [Installing ComfyUI](#installing)

## Features
- Nodes/graph/flowchart interface to experiment and create complex Stable Diffusion workflows without needing to code anything.
- Fully supports SD1.x, SD2.x and SDXL
- Asynchronous Queue system
- Many optimizations: Only re-executes the parts of the workflow that changes between executions.
- Command line option: ```--lowvram``` to make it work on GPUs with less than 3GB vram (enabled automatically on GPUs with low vram)
- Works even if you don't have a GPU with: ```--cpu``` (slow)
- Can load ckpt, safetensors and diffusers models/checkpoints. Standalone VAEs and CLIP models.
- Embeddings/Textual inversion
- [Loras (regular, locon and loha)](https://comfyanonymous.github.io/ComfyUI_examples/lora/)
- [Hypernetworks](https://comfyanonymous.github.io/ComfyUI_examples/hypernetworks/)
- Loading full workflows (with seeds) from generated PNG files.
- Saving/Loading workflows as Json files.
- Nodes interface can be used to create complex workflows like one for [Hires fix](https://comfyanonymous.github.io/ComfyUI_examples/2_pass_txt2img/) or much more advanced ones.
- [Area Composition](https://comfyanonymous.github.io/ComfyUI_examples/area_composition/)
- [Inpainting](https://comfyanonymous.github.io/ComfyUI_examples/inpaint/) with both regular and inpainting models.
- [ControlNet and T2I-Adapter](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
- [Upscale Models (ESRGAN, ESRGAN variants, SwinIR, Swin2SR, etc...)](https://comfyanonymous.github.io/ComfyUI_examples/upscale_models/)
- [unCLIP Models](https://comfyanonymous.github.io/ComfyUI_examples/unclip/)
- [GLIGEN](https://comfyanonymous.github.io/ComfyUI_examples/gligen/)
- [Model Merging](https://comfyanonymous.github.io/ComfyUI_examples/model_merging/)
- Latent previews with [TAESD](#how-to-show-high-quality-previews)
- Starts up very fast.
- Works fully offline: will never download anything.
- [Config file](extra_model_paths.yaml.example) to set the search paths for models.

Workflow examples can be found on the [Examples page](https://comfyanonymous.github.io/ComfyUI_examples/)

## Shortcuts

| Keybind                   | Explanation                                                                                                        |
|---------------------------|--------------------------------------------------------------------------------------------------------------------|
| Ctrl + Enter              | Queue up current graph for generation                                                                              |
| Ctrl + Shift + Enter      | Queue up current graph as first for generation                                                                     |
| Ctrl + S                  | Save workflow                                                                                                      |
| Ctrl + O                  | Load workflow                                                                                                      |
| Ctrl + A                  | Select all nodes                                                                                                   |
| Ctrl + M                  | Mute/unmute selected nodes                                                                                         |
| Delete/Backspace          | Delete selected nodes                                                                                              |
| Ctrl + Delete/Backspace   | Delete the current graph                                                                                           |
| Space                     | Move the canvas around when held and moving the cursor                                                             |
| Ctrl/Shift + Click        | Add clicked node to selection                                                                                      |
| Ctrl + C/Ctrl + V         | Copy and paste selected nodes (without maintaining connections to outputs of unselected nodes)                     |
| Ctrl + C/Ctrl + Shift + V | Copy and paste selected nodes (maintaining connections from outputs of unselected nodes to inputs of pasted nodes) |
| Shift + Drag              | Move multiple selected nodes at the same time                                                                      |
| Ctrl + D                  | Load default graph                                                                                                 |
| Q                         | Toggle visibility of the queue                                                                                     |
| H                         | Toggle visibility of history                                                                                       |
| R                         | Refresh graph                                                                                                      |
| Double-Click LMB          | Open node quick search palette                                                                                     |

Ctrl can also be replaced with Cmd instead for macOS users

# Installing

## Windows

There is a portable standalone build for Windows that should work for running on Nvidia GPUs or for running on your CPU only on the [releases page](https://github.com/comfyanonymous/ComfyUI/releases).

### [Direct link to download](https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu118_or_cpu.7z)

Simply download, extract with [7-Zip](https://7-zip.org) and run. Make sure you put your Stable Diffusion checkpoints/models (the huge ckpt/safetensors files) in: ComfyUI\models\checkpoints

#### How do I share models between another UI and ComfyUI?

See the [Config file](extra_model_paths.yaml.example) to set the search paths for models. In the standalone windows build you can find this file in the ComfyUI directory. Rename this file to extra_model_paths.yaml and edit it with your favorite text editor.

## Colab Notebook

To run it on colab or paperspace you can use my [Colab Notebook](notebooks/comfyui_colab.ipynb) here: [Link to open with google colab](https://colab.research.google.com/github/comfyanonymous/ComfyUI/blob/master/notebooks/comfyui_colab.ipynb)

## Manual Install (Windows, Linux)

Git clone this repo.

Put your SD checkpoints (the huge ckpt/safetensors files) in: models/checkpoints

Put your VAE in: models/vae

### AMD GPUs (Linux only)
AMD users can install rocm and pytorch with pip if you don't have it already installed, this is the command to install the stable version:

```pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/rocm5.4.2```

This is the command to install the nightly with ROCm 5.6 that supports the 7000 series and might have some performance improvements:
```pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/rocm5.6```

### NVIDIA

Nvidia users should install torch and xformers using this command:

```pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu118 xformers```

#### Troubleshooting

If you get the "Torch not compiled with CUDA enabled" error, uninstall torch with:

```pip uninstall torch```

And install it again with the command above.

### Dependencies

Install the dependencies by opening your terminal inside the ComfyUI folder and:

```pip install -r requirements.txt```

After this you should have everything installed and can proceed to running ComfyUI.

### Others:

#### [Intel Arc](https://github.com/comfyanonymous/ComfyUI/discussions/476)

#### Apple Mac silicon

You can install ComfyUI in Apple Mac silicon (M1 or M2) with any recent macOS version.

1. Install pytorch nightly. For instructions, read the [Accelerated PyTorch training on Mac](https://developer.apple.com/metal/pytorch/) Apple Developer guide (make sure to install the latest pytorch nightly).
1. Follow the [ComfyUI manual installation](#manual-install-windows-linux) instructions for Windows and Linux.
1. Install the ComfyUI [dependencies](#dependencies). If you have another Stable Diffusion UI [you might be able to reuse the dependencies](#i-already-have-another-ui-for-stable-diffusion-installed-do-i-really-have-to-install-all-of-these-dependencies).
1. Launch ComfyUI by running `python main.py --force-fp16`. Note that --force-fp16 will only work if you installed the latest pytorch nightly.

> **Note**: Remember to add your models, VAE, LoRAs etc. to the corresponding Comfy folders, as discussed in [ComfyUI manual installation](#manual-install-windows-linux).

#### DirectML (AMD Cards on Windows)

```pip install torch-directml``` Then you can launch ComfyUI with: ```python main.py --directml```

### I already have another UI for Stable Diffusion installed do I really have to install all of these dependencies?

You don't. If you have another UI installed and working with its own python venv you can use that venv to run ComfyUI. You can open up your favorite terminal and activate it:

```source path_to_other_sd_gui/venv/bin/activate```

or on Windows:

With Powershell: ```"path_to_other_sd_gui\venv\Scripts\Activate.ps1"```

With cmd.exe: ```"path_to_other_sd_gui\venv\Scripts\activate.bat"```

And then you can use that terminal to run ComfyUI without installing any dependencies. Note that the venv folder might be called something else depending on the SD UI.

# Running

```python main.py```

### For AMD cards not officially supported by ROCm

Try running it with this command if you have issues:

For 6700, 6600 and maybe other RDNA2 or older: ```HSA_OVERRIDE_GFX_VERSION=10.3.0 python main.py```

For AMD 7600 and maybe other RDNA3 cards: ```HSA_OVERRIDE_GFX_VERSION=11.0.0 python main.py```

# Notes

Only parts of the graph that have an output with all the correct inputs will be executed.

Only parts of the graph that change from each execution to the next will be executed, if you submit the same graph twice only the first will be executed. If you change the last part of the graph only the part you changed and the part that depends on it will be executed.

Dragging a generated png on the webpage or loading one will give you the full workflow including seeds that were used to create it.

You can use () to change emphasis of a word or phrase like: (good code:1.2) or (bad code:0.8). The default emphasis for () is 1.1. To use () characters in your actual prompt escape them like \\( or \\).

You can use {day|night}, for wildcard/dynamic prompts. With this syntax "{wild|card|test}" will be randomly replaced by either "wild", "card" or "test" by the frontend every time you queue the prompt. To use {} characters in your actual prompt escape them like: \\{ or \\}.

Dynamic prompts also support C-style comments, like `// comment` or `/* comment */`.

To use a textual inversion concepts/embeddings in a text prompt put them in the models/embeddings directory and use them in the CLIPTextEncode node like this (you can omit the .pt extension):

```embedding:embedding_filename.pt```


## How to increase generation speed?

Make sure you use the regular loaders/Load Checkpoint node to load checkpoints. It will auto pick the right settings depending on your GPU.

You can set this command line setting to disable the upcasting to fp32 in some cross attention operations which will increase your speed. Note that this will very likely give you black images on SD2.x models. If you use xformers this option does not do anything.

```--dont-upcast-attention```

## How to show high-quality previews?

Use ```--preview-method auto``` to enable previews.

The default installation includes a fast latent preview method that's low-resolution. To enable higher-quality previews with [TAESD](https://github.com/madebyollin/taesd), download the [taesd_decoder.pth](https://github.com/madebyollin/taesd/raw/main/taesd_decoder.pth) (for SD1.x and SD2.x) and [taesdxl_decoder.pth](https://github.com/madebyollin/taesd/raw/main/taesdxl_decoder.pth) (for SDXL) models and place them in the `models/vae_approx` folder. Once they're installed, restart ComfyUI to enable high-quality previews.

## Support and dev channel

[Matrix space: #comfyui_space:matrix.org](https://app.element.io/#/room/%23comfyui_space%3Amatrix.org) (it's like discord but open source).

# QA

### Why did you make this?

I wanted to learn how Stable Diffusion worked in detail. I also wanted something clean and powerful that would let me experiment with SD without restrictions.

### Who is this for?

This is for anyone that wants to make complex workflows with SD or that wants to learn more how SD works. The interface follows closely how SD works and the code should be much more simple to understand than other SD UIs.
