Eosin Platform is an umbrella for open-source tools that reduce the friction in biological data work: viewing, annotating, analyzing, and integrating data across heterogeneous vendors and formats. Our software is an ops-forward approach to addressing pain points for all things biology, microbiology, bioinformatics, pathology, radiology, pharmacology, and medicine in general.

The organization includes three pillar projects:

---

## **🔬 Eosin — Modern WSI & microscopy infrastructure**

Rust + SvelteKit stack for high-performance whole-slide imaging:

* Human Factors-aware UX design
* Cloud-native slide tiling and streaming
* GPU/WebGPU acceleration
* Fast pathology/microbiology viewer
* Annotation, overlays, and future analysis hooks
* Kubernetes-ready deployments

Eosin exists because researchers and students deserve tooling as good as the data they work with.

---

## **🧬 Cyto — A unified system for biological entities**

A reproducible, vendor-agnostic registry for genes, transcripts, proteins, variants, slides, sequencing runs, structures, ontologies, radiographs, and more.

Cyto provides:

* A stable URI grammar (`cyto://...`)
* Vendor integration tests for data sources
* A path toward clean, normalized schemas
* Provenance for both canonical and user-published artifacts

The goal is simple: **make biological data predictable.** 

---

## **🧪 Lysis — Analysis & workflow orchestration**

A lightweight orchestration layer (in early development) that connects Cyto-normalized data to ML workflows:

* Automatic training/inference triggers
* Docker- and Kubernetes-native execution
* Artifact publishing back into Cyto
* Reproducible pipelines without glue code

This forms the basis for a collaborative ecosystem where data upload can immediately lead to analysis, modeling, and insight.

---

## **🧭 Philosophy**

We keep a few principles:

* **Open by default** — research deserves transparent infrastructure.
* **Permissive licensing** — to foster the creation of composable systems.
* **Ops-first** — ML and bioinformatics should run cleanly on clusters and clouds.
* **Schema matters** — clean data shapes enable automation and collaboration.
* **Students welcome** — early domain experts are capable of meaningful contribution.

---

## **📂 Repositories**

We maintain:

* Core infrastructure (Eosin, Cyto, Lysis)
* Vendor integration tests ([`cyto-vendor-examples`](https://github.com/eosin-platform/cyto-vendor-examples))
* Public datasets, manifests, and specifications
* Supporting Rust and Svelte projects

See the pinned repositories for entry points.

---

## **📝 Blog Posts**

- [Eosin I: Origins](https://thavlik.dev/blog/2026-02-20/eosin-i-origins)
- [Eosin II: Towards a Unified Standard](https://thavlik.dev/blog/2026-02-21/eosin-ii-towards-a-unified-standard)
- [Eosin III: Ecosystem Holes](https://thavlik.dev/blog/2026-02-22/eosin-iii-ecosystem-holes)
- [Cyto Vendor Examples](https://thavlik.dev/blog/2026-02-23/cyto-vendor-examples)
- [Eosin IV: Emergent Systems](https://thavlik.dev/blog/2026-02-24/eosin-iv-emergent-systems)

## **🤝 Contributing**

We welcome contributors from:

* ML & infrastructure engineers
* Biologists & microbiologists
* Physicians
* Academia and industry
* Students at any stage
