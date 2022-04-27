# waifu2x-web-video-upscaler
 A python script that takes a folder of images as input, and upscales them using a waifu2x-web endpoint

## Requirements:
1. Python 3.6+
2. selenium
3. chromedriver (same version as your chrome browser)

## Usage
```bash
python3 upscale.py "inputDir" "outputDir" "https://url-to-endpoint"
```
1. `inputDir` is the path to the images you want to upscale
2. `outputDir` is the path to the folder you want to save the upscaled images
3. `https://url-to-endpoint` is the waifu2x-web endpoint you want to use

You will most likely have to refer to https://github.com/nagadomi/waifu2x and set up your own endpoint, as any public endpoints require you to fill out a captcha.