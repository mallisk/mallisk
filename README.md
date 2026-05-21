# Medical Imaging Workspace: Advanced DICOMweb & Responsive Viewport Integrations

A high-performance, modular medical imaging monorepo demonstrating production-ready workflows using **OHIF v3**, **Cornerstone3D**, **ReactJS**, and **Orthanc PACS**. 

This repository showcases advanced client-side 3D rendering pipelines, asynchronous state management, custom metadata parsing, and standard-compliant DICOMweb communication protocols built to production-grade standards.

---

## 👨‍💻 Developer Profile
* **Name:** Mallikarjuna SK
* **Education:** Master of Technology (M.Tech)
* **Experience:** 5+ Years of Professional Software Engineering
* **Specialization:** Enterprise Medical Imaging Architecture, Frontend Workflows, & Web-Based Diagnostics

---

## 🏗️ Architecture Overview

The project is structured as an enterprise-grade monorepo to isolate core viewing capabilities from extensible layouts, mirroring standard production environments.

```text
├── docker/
│   ├── orthanc.json         # Pre-configured Orthanc PACS with DICOMweb & CORS enabled
│   └── docker-compose.yml   # Multi-container orchestration (PACS + Web Apps)
├── packages/
│   ├── custom-viewer/       # Custom ReactJS + Cornerstone3D implementation (MPR & Volumetric)
│   └── ohif-extension/      # Custom Extension & Hanging Protocol Mode for OHIF v3
├── package.json             # Workspace dependency configurations
└── README.md
