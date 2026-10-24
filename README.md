# Awesome-AI-Mobile-Camera-Filter-App

## Top AI Mobile Camera & Filter App Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on On-Device AI Filters, Computational Photography & Self-Hosted Camera Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Mobile Camera & Filter Apps**. These tools apply machine learning to smartphone photography—recognizing scenes, enhancing portraits, applying artistic styles, and simulating film looks—ranging from consumer apps with subscription tiers to open-source camera applications that keep processing entirely on-device.



**Examples** include Adobe Photoshop Camera, Prisma, VSCO, Snapseed, Retrica, B612, SNOW, FaceApp, BeautyPlus, and LutinLens (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding subscription fees, and controlling the image processing pipeline. The open-source mobile camera landscape is sparse compared to desktop, but **LutinLens** (AI-driven camera with GPU-accelerated LUT rendering) and **Magic Mirror** (local AI face swap) demonstrate what's possible when processing stays on-device, while **ImageToolbox** provides a comprehensive open-source image editing toolkit for Android.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Adobe Photoshop Camera](https://www.adobe.com/products/photoshop-camera.html)** | AI-powered camera app using Adobe Sensei for scene recognition and real-time lens effects. | **Free** (no paid tier reported in current sources) . | **Fully free**: 100+ lens effects, auto-tone, portrait controls, content-aware recommendations . |

| **[Prisma](https://prisma-ai.com/)** | Neural network art filter app transforming photos into painting-style images. | **Free** with in-app purchases. **Premium** subscriptions: Weekly €1.99, Monthly €5.49–€7.99, Yearly €19.99–€39.99, Unlimited €29.99 . | **Free tier**: Basic filters. **3-day free trial** for Premium before subscription . |

| **[VSCO](https://vsco.co/)** | Photography app with presets, advanced editing, and community features. | **Free Starter** tier. **Pro** and **One** paid memberships for advanced features . | **Starter (free)**: 1 saved Recipe, basic editing, 50 live presets in VSCO Capture, 10 GB gallery storage, 100 one-time AI credits, basic site . |

| **[Snapseed](https://snapseed.online/)** | Google's professional photo editor with 30+ tools and film simulations. | **Free** (no subscriptions, no ads, no watermarks) . | **Fully free**: All 30+ pro tools, RAW support, batch editing, smart masking, film filters, camera with real-time effects . |

| **[Retrica](https://retrica.me/)** | Digicam filter camera recreating Y2K CCD and 2000s point-and-shoot looks. | **Free** with **Retrica Pro** subscription: Weekly $5.99, Monthly $12.99, Yearly $59.99 . | **Free**: 260+ of 388 presets, watermark-free saves, photo/video capture . |

| **[B612](https://b612.com/)** | All-in-one camera and video editor with real-time filters, AR makeup, and beauty tools. | **Free** with in-app purchases (pricing not specified in search results). | **Free**: Real-time filters, AR effects, Smart Beauty, custom filter creation, basic editing tools . |

| **[SNOW](https://snow.me/)** | Camera app with AI profile, beauty effects, and AR filters used by 200M+ people. | **SNOW VIP**: **$6.99/month** (regional pricing varies; €7.99/month, €44.99/year in EU) . | **Free**: Core camera functionality without VIP subscription . |

| **[FaceApp](https://faceapp.com/)** | AI face editor for transformations, aging, gender swap, and enhancement. | **Free** with **FaceApp PRO** in-app purchases (regional pricing varies widely) . | **Free**: All features available for creating and sharing on social media . |

| **[BeautyPlus](https://www.beautyplus.com/)** | AI photo enhancer with beauty retouching, object removal, and image generation. | **Free** with **Pro** and **Max** paid tiers (monthly credits system) . | **Free**: Basic AI features with limitations, watermarked exports . |

| **[Afterlight](https://afterlight.co/)** | Film-inspired photo editor with 300+ filters, textures, and advanced tools. | **Free** with **PRO**: **$3.99/month** or **$23.99/year** (7-day free trial) . | **Free**: Basic editing tools. PRO unlocks 300+ filters, textures, advanced tools, and all frames . |



## Open-Source GitHub Projects



- **[LutinLens](https://github.com/KirisameLonnet/LutinLens)** [![GitHub Stars](https://img.shields.io/github/stars/KirisameLonnet/LutinLens?style=social&color=white)](https://github.com/KirisameLonnet/LutinLens/stargazers)  

  **The AI-driven camera with GPU-accelerated LUT rendering.** Built with **Flutter** for cross-platform UI, optimized for Android with iOS support . **Core innovation**: GPU-accelerated GLSL shaders for YUV-to-ARGB conversion and trilinear interpolation, supporting **.cube LUT files** at ~30fps on Snapdragon 8 Gen 2 . **AI features**: multi-agent composition analysis via NVIDIA NeMo Agent Toolkit + MCP protocol, providing real-time framing suggestions and LUT recommendations based on scene recognition (powered by Qwen models via Alibaba Cloud) . **Caveat**: requires a backend server (LutinServer) for AI features; the camera core works without it. Best for developers wanting a technically ambitious, AI-assisted camera with real-time LUT rendering on Android.



- **[Magic Mirror](https://github.com/keggin-CHN/Magic-Mirror)** [![GitHub Stars](https://img.shields.io/github/stars/keggin-CHN/Magic-Mirror?style=social&color=white)](https://github.com/keggin-CHN/Magic-Mirror/stargazers)  

  **The local AI face swap app.** Cross-platform (Windows, macOS, Linux, Web, Android) with **all processing done locally—no image uploads to third-party services** . **Features**: single/multi-face swapping, video face swap with audio preservation, multi-face source binding, GPU acceleration (CUDA/DirectML), Web mode with JWT authentication, and multi-language support . **Tech stack**: Node.js frontend, Python inference backend, Rust Tauri desktop shell, Android with MediaCodec . **Not a camera filter app per se**—it's a face-swapping tool—but relevant for on-device AI image manipulation. Best for developers wanting a privacy-first, local face-swap implementation to study or extend.



- **[ImageToolbox](https://github.com/T8RIN/ImageToolbox)** [![GitHub Stars](https://img.shields.io/github/stars/T8RIN/ImageToolbox?style=social&color=white)](https://github.com/T8RIN/ImageToolbox/tree/3.8.0)  

  **The comprehensive open-source image editing toolkit for Android.** Version 3.8.0 includes an extensive filter library: **200+ filters and effects** including color matrix operations, dithering algorithms (Floyd-Steinberg, Atkinson, Burkes, Stucki, Sierra variants), blur effects (Gaussian, bilateral, motion, radial, zoom), glitch effects, distortion filters, and film simulations . **Not AI-powered** in the ML sense—it's a traditional image processing toolkit—but it's the most complete open-source Android image editor available. Best for Android users wanting a free, powerful, open-source alternative to subscription-based editors without AI dependencies.



### Additional Strong Open-Source Options



- **LibreCamera** — The open-source camera core that LutinLens is built upon. Best for developers wanting a clean Android camera foundation without AI features.

- **OpenCamera** — The long-standing open-source Android camera app with manual controls, RAW support, and no ads. Best for users wanting a traditional, privacy-respecting camera without AI gimmicks.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Free tiers vary dramatically**: Snapseed is genuinely free with no strings attached ; Adobe Photoshop Camera is also fully free ; VSCO and Retrica offer usable free tiers with optional subscriptions ; FaceApp and BeautyPlus gate features behind PRO/max tiers with credit systems .

- **"AI" claims require scrutiny**: Some apps use genuine ML (Prisma's neural style transfer, Adobe Sensei, LutinLens's composition analysis) while others apply traditional filters labeled as AI. Verify whether the intelligence is real or marketing.

- **Open-source mobile camera apps are rare**: LutinLens and Magic Mirror are technically impressive but niche projects, not mature consumer alternatives. ImageToolbox is comprehensive but not AI-powered. Expect to use commercial apps for polished AI camera experiences.

- **Privacy matters with face-based apps**: FaceApp and similar tools process biometric data. Open-source alternatives like Magic Mirror explicitly keep processing local—verify privacy policies before uploading personal photos to any service.



---



**Made for mobile photographers, developers building camera apps, and privacy-conscious users wanting on-device AI image processing.**  

Let's make AI mobile camera and filter apps more open, privacy-respecting, and on-device.
