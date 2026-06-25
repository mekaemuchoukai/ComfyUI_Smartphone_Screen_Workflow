# ComfyUI_Smartphone_Screen_Workflow
ComfyUI execution environment for Google Colab(Free)

## Features 
  - SDXL + ControlNet 
  - Anime Lineart
  - Smartphone screen compositing
  - Background preserved
    
## Required Models 
  - Animagine XL
  - mistoLine_rank256.safetensors 

## Usage 
  If you already have ComfyUI installed

    Simply import the provided JSON workflow file into your existing ComfyUI environment.

  If you do not have ComfyUI installed
    1. Open notebook.ipynb in Google Colab
    2. Set the runtime to "T4 GPU" with Python 3, then choose "Run all".
    3. Open localtunnel URL
    4. Import the JSON workflow file into ComfyUI
    
  This notebook will automatically install ComfyUI and all required dependencies, 
  providing a minimal environment capable of running the included workflow on Google Colab.

  After importing the workflow, 
  upload either Smartphone_imageA.png or Smartphone_imageB.png to the "Smartphone Image" node.

## Changelog
  v1.1 (2026-06-22)
  - Added a threshold setting to Color to Mask.
  - Added the following custom node:
    - ComfyUI-RMBG
  - Added JSON workflow files.
