# Awesome-AI-Mobile-Camera-Filter-App

## Top AI Mobile Camera & Filter App Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on On-Device AI Filters, Computational Photography & Self-Hosted Camera Pipelines*  

**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Mobile Camera & Filter Apps**. These tools apply machine learning to smartphone photography—recognizing scenes, enhancing portraits, applying artistic styles, and simulating film looks—ranging from consumer apps with subscription tiers to open-source camera applications that keep processing entirely on-device.

**Examples** include Adobe Photoshop Express, Prisma, VSCO, Snapseed, Retrica, B612, SNOW, FaceApp, BeautyPlus, and LutinLens (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosting, avoiding subscription fees, and controlling the image processing pipeline. The open-source mobile camera and filter ecosystem features robust libraries like **GPUImage**, **android-gpuimage**, **CameraView**, and **PhotoEditor**, alongside advanced standalone toolkits like **ImageToolbox**, **Harbeth**, and on-device neural pipelines like **LutinLens** and **Magic Mirror**.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global mobile photo editing and camera filter app sector represents a multi-billion dollar market estimated at approximately $1.5B to $2.5B+ annually, growing at a CAGR of ~8–12% fueled by mobile-first creator culture, computational photography, and on-device generative AI. The industry is **highly fragmented** with low barriers to entry and rapid viral feature replication across hundreds of specialized indie studios and regional leaders (e.g., Meitu, SNOW, VSCO), while mega-cap platform ecosystems (Alphabet/Google, Adobe) coexist with dedicated category players rather than forming a winner-take-all monopoly.

## SaaS/Hosted Platforms

| Product | Company Scale (Revenue / Valuation) | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Snapseed](https://snapseed.online/)** | **Alphabet (Google)**: ~$402.8B revenue (FY2025) / ~$2.2T+ market cap | **Free** ($0/month forever) | **Fully free forever**: All 30+ pro editing tools, RAW DNG support, selective filter brushes, curves, and smart masking with zero subscriptions, ads, or export limits. |
| **[Adobe Photoshop Express](https://www.adobe.com/products/photoshop-express.html)** | **Adobe**: ~$23.8B revenue (FY2025) / ~$200B+ market cap | **Premium**: **$9.99/month** or **$34.99/year** | **Free forever plan**: Core editing tools, basic filters, red-eye removal, and standard collage templates; 3-day or 7-day free trial for Premium. |
| **[SNOW](https://snow.me/)** | **Naver (SNOW Corp)**: ~$9.0B parent revenue (FY2025) / subsidiary | **SNOW VIP**: **$6.99/month** or **$39.99/year** | **Free forever plan**: Standard camera, daily beauty adjustment tools, AR stickers, and manual facial retouching without mandatory watermarks; AI Profile & HD modes locked to VIP. |
| **[BeautyPlus](https://www.beautyplus.com/)** | **Meitu, Inc.**: ~$300M+ revenue (SEHK: 1357) / ~$1.5B+ valuation | **Pro**: **$8.99/month** or **$49.99/year** | **Free forever plan**: Basic retouching tools and standard filters; exports carry BeautyPlus watermark and premium AI generation features require credits. 7-day free trial available for Pro. |
| **[VSCO](https://vsco.co/)** | **Visual Supply Co.**: ~$40M–$50M annual revenue / ~$550M valuation | **Plus**: **$7.99/month** ($29.99/year); **Pro**: **$12.99/month** ($59.99/year) | **Free Starter plan forever**: 1 saved Recipe, standard editing tools, 50 live presets in VSCO Capture, 10 GB gallery storage, 100 one-time AI credits; 7-day free trial for Pro. |
| **[FaceApp](https://faceapp.com/)** | **FaceApp (Wireless Lab)**: ~$50M–$80M annual revenue | **FaceApp PRO**: **$9.99/month** or **$49.99/year** | **Free forever plan**: Basic facial filters, fundamental smile and makeup tools; exported images include FaceApp corner watermark and advanced age/hair styling tools are locked. 3-day free trial offered in select regions. |
| **[Prisma](https://prisma-ai.com/)** | **Prisma Labs**: ~$16M–$20M annual revenue | **Premium**: **$7.99/month** or **$29.99/year** | **Free forever plan**: Daily collection of standard art/neural filters with SD export; 3-day free trial unlocks HD resolution and 500+ full neural style library before billing. |
| **[Retrica](https://retrica.me/)** | **Retrica Inc.**: ~$5.9M venture funding / ~$2M–$5M estimated revenue | **Retrica Pro**: **$5.99/month** or **$59.99/year** | **Free forever plan**: 260+ vintage/CCD presets, photo/video capture, watermark-free exports; Pro unlocks 120+ exclusive digicam effects and premium grain controls. |
| **[Afterlight](https://afterlight.co/)** | **Afterlight Collective**: ~$600K–$1M estimated annual revenue (indie) | **PRO**: **$3.99/month** or **$23.99/year** (or $39.99 lifetime) | **Free forever plan**: Basic exposure/color adjustments and standard filter presets; 7-day free trial unlocks 300+ film filters, light leak overlays, and custom curve tools. |

## Open-Source GitHub Projects

Curated open-source camera apps, computational photography frameworks, and mobile image processing toolkits sorted by GitHub star count (descending).

- **[GPUImage (iOS)](https://github.com/BradLarson/GPUImage)** [![GitHub Stars](https://img.shields.io/github/stars/BradLarson/GPUImage?style=social&color=white)](https://github.com/BradLarson/GPUImage/stargazers)  
  **The benchmark GPU-accelerated camera framework.** An open-source iOS framework for GPU-based image and live video processing using OpenGL ES shaders, providing real-time camera filter pipelines, custom shaders, and color adjustments with maximum throughput.

- **[ImageToolbox](https://github.com/T8RIN/ImageToolbox)** [![GitHub Stars](https://img.shields.io/github/stars/T8RIN/ImageToolbox?style=social&color=white)](https://github.com/T8RIN/ImageToolbox/stargazers)  
  **The comprehensive open-source image editing toolkit for Android.** Built with Jetpack Compose and Kotlin, featuring over 200+ filters and effects, color matrix operations, multiple dithering algorithms (Floyd-Steinberg, Atkinson, Sierra), bilateral/Gaussian blurs, glitch effects, distortion filters, and film simulations.

- **[android-gpuimage](https://github.com/wasabeef/android-gpuimage)** [![GitHub Stars](https://img.shields.io/github/stars/wasabeef/android-gpuimage?style=social&color=white)](https://github.com/wasabeef/android-gpuimage/stargazers)  
  **Android real-time GPU image and camera filter library.** An Android port of Brad Larson's GPUImage based on OpenGL ES 2.0 shaders, offering instant live-camera viewfinder filters, custom GLSL filter chains, and blend modes without CPU bottlenecking.

- **[CameraView](https://github.com/natario1/CameraView)** [![GitHub Stars](https://img.shields.io/github/stars/natario1/CameraView?style=social&color=white)](https://github.com/natario1/CameraView/stargazers)  
  **High-level camera library for Android.** Provides a robust, easy-to-integrate camera engine supporting real-time filter integration, frame processing, gestures, continuous autofocus, HDR, video stabilization, and RAW capture.

- **[PhotoEditor](https://github.com/burhanrashid52/PhotoEditor)** [![GitHub Stars](https://img.shields.io/github/stars/burhanrashid52/PhotoEditor?style=social&color=white)](https://github.com/burhanrashid52/PhotoEditor/stargazers)  
  **A powerful Android photo editing library.** Enables fast integration of image editing capabilities including custom filters, brush drawings, sticker overlays, text additions, and crop transformations for mobile camera apps.

- **[CameraFilter](https://github.com/nekocode/CameraFilter)** [![GitHub Stars](https://img.shields.io/github/stars/nekocode/CameraFilter?style=social&color=white)](https://github.com/nekocode/CameraFilter/stargazers)  
  **Realtime camera filters on Android with OpenGL.** An Android implementation leveraging OpenGL ES shaders to demonstrate live camera feed filtering including edge detection, ascii art, sketch, polygonization, and color mapping effects.

- **[android-gpuimage-plus](https://github.com/wysaid/android-gpuimage-plus)** [![GitHub Stars](https://img.shields.io/github/stars/wysaid/android-gpuimage-plus?style=social&color=white)](https://github.com/wysaid/android-gpuimage-plus/stargazers)  
  **High-performance C++ OpenGL camera filter engine for Android.** Features real-time camera preview rendering, 40+ artistic photo/video filters, facial beauty filters, and custom color lookup table (LUT) support written in native C++.

- **[Harbeth](https://github.com/yangKJ/Harbeth)** [![GitHub Stars](https://img.shields.io/github/stars/yangKJ/Harbeth?style=social&color=white)](https://github.com/yangKJ/Harbeth/stargazers)  
  **High-performance GPU image and camera filter framework based on Apple Metal.** Cross-platform for iOS and macOS, featuring 100+ GPU-accelerated Metal filters, real-time camera video processing, lookup tables (LUTs), MPS support, and visual effects.

- **[Libre Camera](https://github.com/iakdis/librecamera)** [![GitHub Stars](https://img.shields.io/github/stars/iakdis/librecamera?style=social&color=white)](https://github.com/iakdis/librecamera/stargazers)  
  **Privacy-first open-source Android camera app.** Built with Flutter, stripping metadata/EXIF by default, with no trackers, no ads, full manual focus/exposure controls, and local-only processing.

- **[Magic Mirror](https://github.com/keggin-CHN/Magic-Mirror)** [![GitHub Stars](https://img.shields.io/github/stars/keggin-CHN/Magic-Mirror?style=social&color=white)](https://github.com/keggin-CHN/Magic-Mirror/stargazers)  
  **Local AI face swap and manipulation application.** Cross-platform (Windows, macOS, Linux, Web, Android) with all inference executed locally via ONNX Runtime / CUDA / DirectML without external server communication.

- **[LutinLens](https://github.com/KirisameLonnet/LutinLens)** [![GitHub Stars](https://img.shields.io/github/stars/KirisameLonnet/LutinLens?style=social&color=white)](https://github.com/KirisameLonnet/LutinLens/stargazers)  
  **AI-driven camera with GPU-accelerated LUT rendering.** Built with Flutter for Android and iOS, featuring GPU GLSL shaders for 3D .cube LUT color grading at ~30fps alongside LLM/agent-assisted composition suggestions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Free tiers vary dramatically**: Snapseed is genuinely free with no strings attached; Adobe Photoshop Express offers standard free tools with a paid subscription; VSCO and Retrica offer usable free tiers with optional subscriptions; FaceApp and BeautyPlus gate features behind PRO/max tiers with credit systems.
- **"AI" claims require scrutiny**: Some apps use genuine ML (Prisma's neural style transfer, Adobe Sensei, LutinLens's composition analysis) while others apply traditional filters labeled as AI. Verify whether the intelligence is real or marketing.
- **Privacy matters with face-based apps**: FaceApp and similar tools process biometric data. Open-source alternatives like Magic Mirror explicitly keep processing local—verify privacy policies before uploading personal photos to any service.

---

**Made for mobile photographers, developers building camera apps, and privacy-conscious users wanting on-device AI image processing.**  
Let's make AI mobile camera and filter apps more open, privacy-respecting, and on-device.
