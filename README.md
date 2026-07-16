# ModelView

**A high-performance engineering model viewer and collaboration foundation for BIM, mechanical CAD, industrial assemblies, and large 3D projects.**

[Download the latest Windows release](https://github.com/GoodLuckIce/modelView/releases/latest) · [Report an issue or discuss a project](https://github.com/GoodLuckIce/modelView/issues)

ModelView turns native engineering files into a reusable local viewing cache, then keeps model hierarchy, properties, measurement, sectioning, component operations, sharing, and synchronized review connected in one 3D context.

## Why ModelView

- **One workflow for BIM and CAD** — review building models, mechanical assemblies, factory equipment, and general 3D data without rebuilding the workflow for every format.
- **Built for large engineering models** — conversion cache, spatial chunks, LOD, on-demand loading, and GPU scheduling keep the active working set manageable.
- **Engineering context stays attached** — hierarchy, object identity, properties, selection, measurement, sectioning, and component operations remain part of the review experience.
- **Local, private, or online deployment** — keep source models and conversion data on a workstation or controlled company network, or deploy an online conversion and collaboration service.
- **Ready for product integration** — extend the existing foundation with custom UI, review tools, permissions, workflows, APIs, and industry-specific functions.

## Windows Standard Edition

The Windows Standard Edition is free to use and is designed for direct testing with real project models.

1. Open the [latest release](https://github.com/GoodLuckIce/modelView/releases/latest).
2. Download `ModelView.exe` to a writable folder such as `D:\ModelView`.
3. Run `ModelView.exe`.
4. Add a model file or folder and wait for the first local conversion to finish.
5. Reopen the converted model to use the reusable local cache.

No installation package is required. Windows may show a security prompt for a newly downloaded executable; verify the file hash shown on the release page before running it.

## Supported engineering formats

ModelView covers most common engineering model formats. Representative extensions include:

| Category | Formats |
| --- | --- |
| BIM and architecture | RVT, RFA, IFC, NWD, NWC, RVM, SKP, DGN |
| Mechanical CAD and assemblies | STEP, STP, IGES, IGS, JT, CATPart, CATProduct, PRT, ASM, IAM, IPT, SLDASM, SLDPRT, X_T, X_B |
| General 3D | FBX, OBJ, STL, 3DS, 3MF, DAE, glTF, GLB, U3D, VRML, WRL |
| USD and visualization exchange | USD, USDA, USDC, USDZ, 3DXML, PLMXML, PRC, PVZ, PVS |
| Drawings and supporting documents | DWG, DXF, PDF |

Format support can vary with the source application version and the contents of an individual file. The fastest way to validate compatibility is to test the Standard Edition with a representative project model.

## Review and collaboration tools

- Model hierarchy and component properties
- Selection, isolation, visibility control, and object positioning
- Distance, angle, and related measurement workflows
- Section planes and section-based review
- Perspective and orthographic camera modes
- Navigation presets for familiar BIM, CAD, and 3D interaction styles
- Shareable model links, synchronized camera and selection, and multi-user review

## Large-model performance

After the first source-format conversion has completed and a local cache has been generated, models at the 100-million-triangle scale can reopen in under five seconds and enter an interactive view. During browsing and review, the renderer is designed to maintain the target refresh rate through chunking, LOD, on-demand loading, and GPU scheduling.

The five-second figure refers to reopening an already converted model, not the first conversion of an RVT, NWD, STEP, JT, or another native source file. Actual results depend on the model, hardware, resolution, and active working set.

## Data boundary and deployment

Model conversion, cache generation, and viewing can stay on the local Windows workstation. For sensitive engineering data, ModelView can also be deployed inside a controlled company network so source files do not need to be uploaded to a public cloud.

For distributed teams, the same foundation can be deployed as an online service for upload, conversion, viewing, link sharing, and synchronized review.

## International interface

ModelView follows the operating system or browser language on first launch and falls back to English for unsupported locales. The current interface includes:

English · Simplified Chinese · Traditional Chinese · Japanese · Korean · French · German · Spanish · Brazilian Portuguese · Russian

The language can also be changed manually and the choice is remembered.

## Enterprise integration and custom development

ModelView can be adapted for engineering review, asset management, equipment maintenance, digital twins, construction coordination, and other model-based business systems. Project-specific work can include:

- Private or intranet deployment
- Custom UI, review tools, and approval workflows
- Permissions, data interfaces, and internal model formats
- Integration with asset, maintenance, inspection, and digital-twin platforms
- Online conversion, delivery, and collaboration services

Open a GitHub issue with the model type, source application/version, approximate file size, hardware, deployment environment, and the workflow you want to support. Do not upload confidential models or sensitive project data to a public issue.

## Distribution and commercial use

The Windows Standard Edition is free to use. Commercial embedding, white-labeling, redistribution, source access, enterprise deployment, and long-term support require a separate agreement.

This repository is the official international product and release page. The application source code is not distributed here.

