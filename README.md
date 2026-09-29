# Awesome-Building-Information-Modeling

## Top Building Information Modeling (BIM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Model Coordination, Common Data Environment & Construction Collaboration*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Building Information Modeling (BIM)**. These tools enable architecture, engineering, and construction (AEC) teams to create, coordinate, and manage intelligent 3D models that carry structured data throughout the building lifecycle, from design through construction to operations.



**Examples** include Autodesk BIM Collaborate, Revizto, Trimble Connect, Dalux, BIM Track, BIMcollab, Catenda Hub, Bricsys 24/7, Novorender, and OpenSpace BIM (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom IFC data management, and transparent model collaboration — ideal for AEC firms, developers, and researchers building vendor-independent BIM solutions. The open-source ecosystem offers production-grade IFC servers, object-based data infrastructure, and browser-based viewers for coordination workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Autodesk BIM Collaborate](https://www.autodesk.com/products/bim-collaborate/overview)**  

  Cloud-based design collaboration and model coordination platform integrated with Autodesk Construction Cloud. Features real-time Revit co-authoring, automated clash detection, design package exchange, change analytics, and connected issues with roundtrip resolution in Revit or Navisworks. Digital twin handover via Tandem integration .



- **[Revizto](https://revizto.com/)**  

  Integrated collaboration platform with 2D/3D review, issue tracking, and offline model access for field teams. Centralizes project data for design-build workflows with automatic issue location and real-time coordination across disciplines. Used on major projects including Copenhagen children's hospital .



- **[Trimble Connect](https://connect.trimble.com/)**  

  Open collaboration tool connecting people to constructible data across design, build, and operate phases. Supports 60+ file formats, live collaboration sessions across Revit/Tekla/browser, and access on desktop, mobile, and mixed-reality devices. Over 10 million users in 185 countries .



- **[Dalux](https://www.dalux.com/)**  

  Construction management software with powerful mobile BIM viewer, QR-code-based plan verification, and CDE capabilities. Features dynamic split view, point-to-point measurements, AI-powered task translations, and field documentation tools. Used by 1.7 million users .



- **[BIM Track](https://bimtrack.co/)**  

  Communication platform for BIM coordination with issue tracking directly inside Revit, Navisworks, Tekla, AutoCAD, and Solibri. OpenBIM-friendly with BCF-based issues and IFC-powered web viewer. Provides transparency and accountability with full issue history and interactive KPIs .



- **[BIMcollab](https://www.bimcollab.com/)**  

  Unified platform combining Model Quality Assurance and Common Data Environment solutions. Coordinates information across BIM phases with model, document, issue, and workflow integration. Supports Autodesk Forma Connection and Revit models in Model WebViewer and BIMcollab Zoom .



- **[Catenda Hub](https://catenda.com/)**  

  Open CDE platform supporting ISO 19650 compliance with unlimited users. Features BCF tracking, document version management, naming conventions, and native IFC support. Open API for integration with existing tools .



- **[Bricsys 24/7](https://www.bricsys.com/247/)**  

  Cloud-based Common Data Environment for project collaboration. Features ISO 19650-compliant folder structures for WIP/Shared/Published/Archived, role-based permissions, metadata forms, workflows, and mobile access. Integrates with LetsBuild Aproplan and Leica .



- **[Novorender](https://novorender.com/)**  

  BIM repository and visualization platform with centralized data management, clash detection, rule validation (IFC/DWG/XML), and AI-assisted rule creation. Features real-time rendering (7-km road model in 2 seconds), offline caching, Power BI export, and integration with JIRA and BIMcollab .



- **[OpenSpace BIM](https://www.openspace.ai/)**  

  Reality capture and BIM comparison platform with 360° site documentation, AI-powered progress tracking, and mobile BIM viewer. Features BIM Compare, Sheet Overlay, Field Notes, thermal imaging integration, and split-view temporal comparison .



## Open-Source GitHub Projects



- **[BIMserver](https://github.com/opensourceBIM/BIMserver)**  

  The original open-source BIM server platform with 800+ GitHub stars, enabling storage and management of construction project data using the open IFC data standard. Model-driven architecture stores IFC data as objects (not files), functioning as an IFC database with versioning, merging, model checking, and multi-user support. buildingSMART certified for IFC 2x3 full and IFC 4 full compliance. AGPL-3.0 licensed with active development .



- **[Speckle](https://github.com/specklesystems/speckle-server)**  

  Open-source data infrastructure for the AEC industry described as "Git & Hub for geometry and BIM data." Object-based platform replacing file-based workflows with a real-time database. Features version control, 3D viewer, GraphQL API, webhooks, and real-time collaboration. Connectors for Revit, Rhino, Grasshopper, AutoCAD, Civil 3D, Excel, Unreal Engine, Unity, QGIS, Blender, ArchiCAD, and Power BI enable interoperability without export/import. Self-hostable via Docker Compose .



- **[BIMsurfer](https://github.com/opensourceBIM/BIMsurfer)**  

  Open-source WebGL viewer for IFC models, MIT licensed and buildingSMART certified for IFC 2x3 coordination view. Lightweight browser-based viewer suitable for embedding in web applications .



- **[Bldrs Share](https://github.com/bldrs-ai/Share)**  

  Browser-based BIM & CAD viewer and collaboration platform supporting IFC 2x3 & 4, STL, OBJ, and STEP (early access). Features drag-and-drop model viewing with no data upload, offline capability, section planes, property editing, CSV data export, real-time link sharing, and multi-user timeline-based versioning in Git. Extensible Apps framework for Digital Twin lifecycle systems.



- **[xeokit-bim-viewer](https://github.com/xeokit/xeokit-bim-viewer)**  

  Open-source IFC, BIM, and point cloud 3D viewer built with the xeokit SDK. Supports double precision global coordinates for AEC & GIS applications. Features combined geometry and metadata in XKT files, split-model loading with manifest.json, and backward compatibility. BSD-licensed with active development.



- **[ifc-lite](https://github.com/LTplus-AG/ifc-lite)**  

  Rust + WASM core for parsing, viewing, querying, editing, and exporting IFC files in the browser with WebGPU rendering. Works with IFC2X3, IFC4/IFC4X3, and IFC5 (IFCX). Features ~260 KB gzipped bundle, 5x faster geometry processing, columnar parsing, SQL queries via DuckDB-WASM, IDS validation, and export to STEP/Parquet/IFC5. **Collab package** adds real-time collaborative BIM editing via CRDT (Yjs) with presence, conflict detection, and secure server bundle.



- **[ConvergeStudio](https://github.com/wieslawsoltes/ConvergeStudio)**  

  Open-source BIM coordination and clash detection tool with browser-based interface. Features model tree navigation, property inspection, section planes, and clash detection with 1 micrometre numerical epsilon. Supports IFC and glTF 2.0/GLB. Distinguishes hard clashes from clearance results, with review statuses attached to stable entity-pair IDs and staleness marking after model edits.



- **[Online 3D Viewer](https://github.com/yhzcake/Online3DViewer)**  

  Free and open-source web solution to visualize and explore 3D models in the browser. Supports import of 3dm, 3ds, 3mf, amf, bim, brep, dae, fbx, fcstd, gltf, ifc, iges, step, stl, obj, off, ply, and wrl formats. Export to 3dm, bim, gltf, obj, off, stl, and ply. Lightweight viewer for quick model inspection.



- **[GomeraX](https://github.com/salpbes/GomeraX)**  

  Experimental IFC viewer with local AI assistant. Features WebGL and experimental WebGPU rendering, IFC to Fragments conversion, hierarchical property inspection, Excel-like property tables, sectioning, measurement tools (length/area/volume), 2D floor plan views, and Level of Detail system for massive models. Automatic model alignment to site coordinates.



### Additional Strong Open-Source Options



- **OpenBIM Collective** — Umbrella organization maintaining BIMserver and related IFC tooling for the openBIM ecosystem.

- **web-ifc** — WebAssembly-based IFC parsing library used by ConvergeStudio, Online 3D Viewer, and other browser-based BIM tools.

- **IFC.js** — Open-source JavaScript library for IFC parsing and viewing in the browser.

- **That Open Company (formerly IFC.js)** — Open-source platform components for BIM web development including Fragments format.



**Frameworks for building custom BIM solutions**: Combine **BIMserver** for server-side IFC data management with versioning and multi-user support . Use **Speckle** as the data infrastructure layer for object-based model sharing across disciplines and tools . For browser-based viewing and coordination, **Bldrs Share** or **xeokit-bim-viewer** provide production-ready viewers. For real-time collaborative editing, **ifc-lite collab** offers CRDT-based concurrent model editing with presence and conflict resolution. For clash detection, **ConvergeStudio** provides browser-based coordination with configurable epsilon and status tracking. Note that true enterprise CDE platforms with document control, transmittals, and workflow automation remain largely commercial territory; open-source stacks provide strong model server, viewer, and collaboration foundations that require integration for full project information management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- BIM collaboration tools must comply with project-specific information management standards (ISO 19650, buildingSMART standards) and contractual requirements.

- Self-hosted open-source solutions require proper infrastructure, IFC data management expertise, and ongoing maintenance. Model federation and clash detection accuracy depend on model quality and coordination discipline.

- The open-source ecosystem provides strong model server, viewer, and real-time collaboration foundations, but full enterprise CDE platforms with document control, transmittals, and workflow automation remain primarily commercial offerings.



---



**Made for architects, engineers, contractors, BIM managers, and AEC technologists.**  

Let's make BIM collaboration more open, transparent, and interoperable.
