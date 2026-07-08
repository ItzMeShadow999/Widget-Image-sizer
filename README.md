
# W.I.S. — Widget Image Studio

A lightweight, blazing-fast browser utility designed to format, convert, and optimize assets for Discord and social platforms. 


## How to Use & Deployment

Getting started is instant. You can access the application directly online, or spin up a local host if you want it **FULLY OFFLINE** for 100% local performance and privacy.

*   **Live Web Deployment:** Just visit [https://widgetimagestudio.vercel.app/](https://widgetimagestudio.vercel.app/) to use the application immediately.
*   **Go Fully Offline:** Clone the repository and run one of the following commands in your terminal to spin up a local static server:

```bash
# Python Standard Implementation
python3 -m http.server 8080

# Node Standard Loop Implementation
npx serve .

```

---

## The Three Tabs Breakdown

### 1. Widget Framer (W.I.S.gif)

The go-to tool for perfectly fitting your images into platform layouts. It automatically strips headers using custom sizing rules tailored to Discord's UI presentation, adjusts border radius cornering with smooth anti-aliasing, and fully supports frame-by-frame animation processing for GIFs right in your browser.

* **How to Use:**
1. Drag and drop your image or animated `GIF` into the workspace.
2. Adjust the padding, header stripping variables, and dynamic border cornering to match your target platform style.
3. Preview the live animation loop and click **Export/Download** to save your framed asset.



### 2. Multi-Format Image Converter

A powerhouse conversion engine that can input absolutely **ANYTHING** you throw at it. Whether you are dealing with standard web formats, legacy assets, or raw print standards, it instantly transcodes files across a massive format ecosystem—including `PNG`, `JPG`, `WEBP`, `AVIF`, `GIF`, `BMP`, `TIFF`, `TGA`, `PPM`, `ICO`, `CUR`, `SVG`, and native `PDF` compilation. It even features a Raster-to-Vector layer isolation tool to wrap structural binary blocks directly into safe `SVG` vectors.

* **How to Use:**
1. Upload any source file (even rare or legacy formats) into the converter dropzone.
2. Select your desired output format from the configuration dropdown menu.
3. Hit **Convert** to process the file instantly via client-side memory buffers and save the output.



### 3. W.I.S.AE (Widget Image Studio Advanced Editor) — For Nerds!

This is where the magic happens under the hood. The Advanced Editor gives you deep, granular control over asset manipulation using low-level, hardware-accelerated rendering contexts:

* **Matrix Color Manipulation:** Compute real-time pixel modifications across channels, including contrast, brightness, exposure, hue rotation ($0^\circ$ to $360^\circ$), noise variance, sharpening grids, and localized vignette masking.
* **Alpha Hardening Optimization Loop:** Pre-calculates transparency structures against an adjustable opacity baseline to safely prevent standard artifacts across historical rendering formats like static index-color GIFs.
* **ArrayBuffer Stream Compilation:** Implements synchronous file headers natively inside JavaScript arrays to manually generate target formats (e.g., custom structured bit layouts for `BMP` headers, `TGA` offsets, and structural dictionary nodes for `TIFF` files).
* **Canvas Grid Geometry:** Features built-in target layouts mapped to precise platform boundary constraints (Discord Widgets, Avatars, Server Icons; Instagram grids; YouTube Thumbnails).
* **How to Use:**
1. Load your asset into the **W.I.S.AE** console interface.
2. Use the specialized adjustment sliders to map custom matrix filters, or select a pre-configured Canvas Grid layout framework.
3. Fine-tune your alpha channel hardening limits if processing complex transparencies, then execute the compile pipeline to extract your highly-optimized asset code or image.



```

```
