# Stable Diffusion Quick Start Guide

## Install and set up

- **Use a [free site](https://stable-diffusion-art.com/free-ai-image-generator-sites/)** if you want to play around and generate a few images.
    
<aside>
    
📄 **Free sites**
Many of these sites have paid options for extra functionalities. This option is suitable for users who are looking for an image generation service so that they don’t need to install any software.

**Pros**
     ✅No setup.

     ✅Easy to use.

**Cons**

     ❎Limited functionality.

❎Cost more than other options.

**This is for you if**

👉You don’t want to deal with troubleshooting software.
👉You are ok with limited functionality.
👉You don’t mind paying a bit more for some features.

</aside>
    
- You need to use **AUTOMATIC1111** (A1111) GUI if you want to follow my tutorials and get the most out of Stable Diffusion.  This is suitable for advanced users or who aspire to be one. There are three options for using A1111:
    
<aside>
📄  **Google Colab**
This is what I use. 
📜[**Setup guide**](https://stable-diffusion-art.com/automatic1111-colab/).
🔗Open **[Google Colab Notebook](https://colab.research.google.com/github/sagiodev/stablediffusion_webui/blob/master/StableDiffusionUI_ngrok_sagiodev.ipynb)**
**Pros**

     ✅You don’t need to maintain your A1111 (it will have problems from time to time)

✅Don’t use up your computer resources (models can be big)

✅Cost effective if you account for hardware cost.

✅Free for light usage.

**Cons**

❎Cost money to use regularly. (I use $10-$20 per month)

❎Slower startup time.

**This is for you if**

👉You want the most advanced features.
👉You don’t have the proper hardware or don’t want to use it.
👉You are tech-savvy enough to deal with model files.
👉You don’t mind paying a modest fee to use regularly.

</aside>
    
<aside>
📄 **Windows PC**
You need a discrete NVIDIA graphic card with at least 4GB VRAM.

See the [**install guide**](https://stable-diffusion-art.com/install-windows/).

**Pros**

✅Free

**Cons**

❎Can take up a lot of your disk space.

❎Not cheap if you decide to buy a good GPU card for it.

**This is for you if**

👉You want the most advanced features.
👉You have the proper hardware on your PC and don’t mind using it for SD.
👉You are tech-savvy enough to install and maintain software on your PC.
👉You want a completely free solution.

</aside>

<aside>
📄 **Mac**
You need M1 or M2.

See the [install guide](https://stable-diffusion-art.com/install-mac/).

**Pros**

✅Free

**Cons**

✅Slower than PC

✅Some features are not available

**This is for you if**

👉You want the most advanced features but ok with some features being not available.
👉You have the right hardware on your PC and don’t mind using it for SD.
👉You are tech-savvy enough to install and maintain software on your PC.
👉You want a completely free solution.
👉You don’t mind image generation is a bit slow on Mac.

</aside>
    

## Text-to-image Basics

Text-to-image is the most basic usage of Stable Diffusion. It is a model trained to turn text descriptions into images. For example, a text prompt, “a photo of an astronaut riding a horse on the moon” will produce an image just like that.

However, it could be challenging to generate precisely the image you want. We need to learn particular keywords it was trained on to entice it to give you what you want.

### Three tips for building a good prompt

**💡TIP 1: Be as detailed and as specific when describing a subject**

<aside>
❌ A woman sitting

</aside>

<aside>
✔️ A beautiful woman with blue eyes and blonde hair sitting outside in a restaurant

</aside>

**💡TIP 2: Use names of artists and websites to modify the style**

<aside>
❌ digital art

</aside>

<aside>
✔️ digital art, artstation, artgerm, alphonse mucha

</aside>

**💡TIP 3: Add lighting terms to make it more interesting**

- cinematic lighting
- studio lighting
- sunlight

Extra Tip: Always generate a few images with the same prompt to understand what the prompt can do!

<aside>
⭐ Check out [Stable Diffusion prompt builder](https://andrewongai.gumroad.com/l/stable_diffusion_prompt_generator) for a complete step-by-step system.

</aside>

## Fix Detects with Inpainting

It is uncommon to get a good image in one shot. You can use inpainting to fix defects. This is to ask Stable Diffusion to regenerate part of the image. See [Inpainting Basics](https://stable-diffusion-art.com/inpainting_basics/) to get an overview. See

## Additional Resources

- [Absolute beginner's guide](https://stable-diffusion-art.com/beginners-guide/) - read this if you know nothing about Stable Diffusion.
- [Prompt guide](https://stable-diffusion-art.com/prompt-guide/) - this article introduce you to the basic of building a prompt.
- [Common problems in AI images and how to fix them](https://stable-diffusion-art.com/common-problems-in-ai-images-and-how-to-fix-them/) - Issues you may see and their solutions.
- [How to use img2img](https://stable-diffusion-art.com/how-to-use-img2img-to-turn-an-amateur-drawing-to-professional-with-stable-diffusion-image-to-image/) to gain extra control of your images.
