<p align="center">
  <img src="bg.jpg" width="100%" style="transform: translateY(-100px);"position: relative; top: -100px;">
</p>

Welcome to the profile of a Research Software Engineer bridging high-performance systems engineering and interactive visual computing. Specializing in real-time computer vision pipelines, spatial engines and browser-based scientific visualization tools that translate complex telemetry and affective data into intuitive visual interfaces.

# 🔬 Featured Projects & Ecosystems

Exploring key architectures and scientific utilities currently under development:

## 👁️ Visual Computing & Affective Technologies

- **[Wasm Point Cloud Engine 🌐 Live Demo](https://point-cloud.pages.dev/)** ☄︎ A high-performance 3D point cloud rendering and spatial downsampling web application. Powered by a C++20 backend compiled to WebAssembly (WASM) with non-destructive filtering, integrated into an Angular frontend via Signals and Three.js<br/>
  | C++20, WebAssembly, Angular, Three.js → 💻 [Source Code](https://github.com/wixhub/WasmPointCloud)

- **[Med Vision Inspector 🌐 Live Demo](https://vision-inspector.pages.dev/)** ☄︎ An interactive scientific web application for the inspection, processing and visual explanation of biomedical imaging data using Grad-CAM attention mapping<br/>
  | Python, PyTorch, FastAPI, Computer Vision, XAI → 💻 [Source Code](https://github.com/wixhub/web-vision-inspector)

- **[Micro Expression Engine 🌐 Live Demo](https://facs-engine.pages.dev/)** ☄︎ A high-performance, real-time facial telemetry and micro-expression analysis web application. The core detection engine is written in C++20, compiled to WebAssembly (WASM) via Emscripten and Ninja, and integrated into a modern Angular frontend using Signals and reactive components<br/>
  | C++20, WebAssembly, Angular → 💻 [Source Code](https://github.com/wixhub/facs)

- **[Affective Synchronization 🌐 Live Demo](https://affective-sync.pages.dev/)** ☄︎ A client-side neural network application utilizing computer vision to extract facial blendshapes frame-by-frame and synchronize affective data with an interactive timeline<br/>
  | Angular, TypeScript, MediaPipe, ECharts → 💻 [Source Code](https://github.com/wixhub/AffectiveSync)

## 🌍 EcoEngine & Spatial Telemetry Ecosystem

- **EcoEngine Core** ☄︎ High-performance Java Spring Boot core service providing RESTful APIs, secure metadata ingestion pipelines and database management for ecological research 🌐 [Metadata Harvester](https://metadata-harvester.pages.dev) <br/>
  | Java, Spring Boot, PostgreSQL, Docker → 💻 [Source Code](https://github.com/wixhub/ecoengine)

- **Eco-Proxy (Cloudflare Worker)** ☄︎ Secure Cloudflare Worker acting as a CORS proxy for the Movebank API and an AI agent gateway <br/>
  | TypeScript, Cloudflare Workers, Groq AI → 💻 [Source Code](https://github.com/wixhub/ecoproxy)

- **Ecosystem Frontend Suite** ☄︎ Unified Angular monorepo housing all scientific applications and micro-frontends, including web apps 🌐 [Specification Builder](https://eco-spec.pages.dev), [Metadata Harvester](https://metadata-harvester.pages.dev), [Dataset Explorer](https://movebank-explorer.pages.dev), [Telemetry Animator](https://spatial-temporal.pages.dev), [Sensor Streams](https://sensor-streams.pages.dev), [Spatial Visualizer](https://bio-stream.pages.dev) and [Tracking Curation](https://data-curation.pages.dev) <br/>
  | Angular, Signals, TypeScript, NX Monorepo → 💻 [Source Code](https://github.com/wixhub/ecosystem)

🌐 Live Demos:

- **Specification Builder** ⚗️ Professional specification wizard for configuring hierarchical Movebank telemetry parameters and generating structured JSON schemas, featuring real-time data volume calculations processed in a background Web Worker thread <br/>
  | Angular, Signals, Web Workers, TypeScript, NX Monorepo → 🌐 [Live Demo](https://eco-spec.pages.dev)

- **Metadata Harvester** ☄︎ Responsive frontend application for the metadata ingestion pipeline and REST gateway. Communicates with the EcoEngine backend and is housed within the unified ecosystem workspace <br/>
  | Angular, TypeScript, NX Monorepo → 🌐 [Live Demo](https://metadata-harvester.pages.dev)

- **Dataset Explorer** ☄︎ Responsive frontend prototype for research data repositories, built for the MoveRDM ecosystem and communicating with the Workers and Groq AI backends <br/>
  | Angular, TypeScript, NX Monorepo → 🌐 [Live Demo](https://movebank-explorer.pages.dev)

- **Telemetry Animator** ☄︎ High-performance scientific web application for interactive playback and visualization of animal migration telemetry over geographical map layers, incorporating timeline controls and speed scaling, communicating with the Workers backends <br/>
  | Angular, Leaflet, TypeScript, NX Monorepo → 🌐 [Live Demo](https://spatial-temporal.pages.dev)

- **Sensor Streams** ☄︎ The scientific dashboard designed to visualize multi-dimensional sensor streams, combining GPS tracking with accelerometer and environmental data through synchronized time-series charts, communicating with the Workers backends <br/>
  | Angular, ChartJS, TypeScript, NX Monorepo → 🌐 [Live Demo](https://sensor-streams.pages.dev)

- **Spatial Visualizer** ☄︎ Spatial rendering engine for migratory animal tracking data, communicating with the Workers backends <br/>
  | Angular, Leaflet, TypeScript, NX Monorepo → 🌐 [Live Demo](https://bio-stream.pages.dev)

- **Tracking Curation** ☄︎ Interactive web utility for researchers working with animal tracking data, leveraging browser-based Dexie storage for offline-first data management <br/>
  | Angular, Dexie, Leaflet, TypeScript, NX Monorepo → 🌐 [Live Demo](https://data-curation.pages.dev)

### 🧘 Applied Wellness Tools

- **[Bilateral Stimulation 🌐 Live Demo](https://bilateral-stimulation.pages.dev)** (_EMDR_) A visual tool designed to help process stress and reduce emotional intensity.

- **[Breathe & Focus 🌐 Live Demo](https://breathe-circle.pages.dev)** (_Visual Calm_) Guided visualization exercises designed to lower heart rate and reduce cortisol levels through rhythmic pattern observation.

- **[Soundscape Mixer 🌐 Live Demo](https://sonosphere.pages.dev)** (_Audio Therapy_) Personalize your auditory environment with layered binaural beats and nature sounds to improve concentration and mood.

- **[The Thought Shredder 🌐 Live Demo](https://thought-shredder.pages.dev)** (_Cognitive Defusion_) Type out intrusive or anxious thoughts and visually destroy them to create psychological distance and reduce their emotional impact.

- **[5-4-3-2-1 Grounding 🌐 Live Demo](https://grounding.pages.dev)** (_Anxiety Relief_) An interactive step-by-step guide to bring your focus back to the physical present during moments of high anxiety or panic.

- **[Interactive Emotion Wheel 🌐 Live Demo](https://emotion-chart.pages.dev)** (_Self-Reflection_) Navigate through core feelings to accurately identify and verbalize your current emotional state for better nervous system regulation.

---

## ⚡ Core Tech Stack & Infrastructure

- **Frontend & Architecture**: Angular, TypeScript, RxJS, Leaflet (GIS)

- **Backend & APIs**: C++, Java, Spring Boot, REST APIs, Workers (Serverless), Groq AI

- **Databases & Storage**:
  - Relational DBs (PostgreSQL, MySQL) for dynamic cloud-native data management
  - NoSQL (MongoDB) for flexible telemetry schemas and unstructured scientific datasets

- **DevOps & Domain**: Docker, Git, CI/CD Pipelines, spatial data pipelines and scientific instrumentation.
