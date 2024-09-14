## **說明:**
stable-diffusion-webui-directml v1.6.1版本備份+venv懶人包

目前最新版本下載地址為 https://github.com/lshqqytiger/stable-diffusion-webui-amdgpu

以下是其他使用者早期fork分叉版本

1\.6.1  https://github.com/mastermach50/stable-diffusion-webui-directml

1\.6    https://github.com/Dalethium/stable-diffusion-webui-directml

1\.7.0  https://github.com/ternite/stable-diffusion-webui-directml

使用方法 git完後或是下載zip解壓縮包後再下載 venv懶人包解壓縮到 stable-diffusion-webui-directml\venv 即可使用

venv.zip download : https://huggingface.co/datasets/pluseen/stable-diffusion-webui-directml-1.6.1/resolve/main/venv.zip

webui-user.bat  推薦參數rx5500xt下可畫960x540  set COMMANDLINE_ARGS=--opt-sub-quad-attention  --lowvram  --medvram  --disable-nan-check 

----------------------------------------
User interface 設定
sd_vae   CLIP_stop_at_last_layers

https://github.com/dtlnor/stable-diffusion-webui-localization-zh_CN #自訂中文

https://github.com/picobyte/stable-diffusion-webui-wd14-tagger

https://github.com/Mikubill/sd-webui-controlnet

https://github.com/fkunn1326/openpose-editor

https://github.com/Mikubill/sd-webui-controlnet

https://github.com/picobyte/stable-diffusion-webui-wd14-tagger

https://github.com/jexom/sd-webui-depth-lib

反向
git clone https://huggingface.co/embed/negative /stable-diffusion-webui-directml/embeddings/negative


controlnet
inpaint 局部重繪
canny 硬邊緣
Lineart 線搞上色
