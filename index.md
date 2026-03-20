# CE React Migration Project

<p align="left">
  <strong>Team:</strong> Naitik, Mansi <br>
  <strong>Mentors:</strong> Anoop, Prateek, Suresh
</p>

<hr>

## Problem Statement
The existing **Cloud Extender (CE)** view within the IBM MaaS360 application is built on a legacy architecture that has led to several critical performance and usability bottlenecks:

* **High Latency & Loading Times:** Users experience significant delays when accessing CE views, leading to a sub-optimal user experience.
* **Monolithic Interference:** Tight coupling of the Cloud Extender with the monolithic MaaS360 system causes resource contention from background processes, leading to slower frontend performance and occasional routing conflicts.
* **Resource Contention:** Loading all components of the main `device-view` simultaneously with CE leads to heavy browser overhead and slower DOM rendering.
* **Maintenance Complexity:** Debugging specific CE UI issues is difficult within the larger legacy framework, slowing down the development lifecycle for feature updates.

> **Solution:** Migrate the Cloud Extender module to a standalone React-based application using the **Carbon Design System**.

---

## Business Objectives

### 1. Improve User Experience (UX)
* **Goal:** Drastically reduce initial load times and page transitions.
* **Impact:** A seamless, responsive UI that allows IT administrators to manage Cloud Extenders without waiting for global app assets to load.

### 2. Modernize UI Framework
* **Goal:** Transition from legacy views to **React.js** and **IBM Carbon Components**.
* **Impact:** Consistent design language with the rest of the MaaS360 ecosystem and access to modern frontend state management.

### 3. Decoupling & Scalability
* **Goal:** Isolate CE logic into a standalone React app to ensure independent execution and avoid cross-module interference.
* **Impact:** Independent deployment cycles during **DDs** and easier scaling of specific CE features without impacting the entire MaaS360 portal.

---

## Architecture Overview

### High-Level Architecture
* *Status:* **Under Discussion** (Pending mentor review)

### Low-Level Architecture
* **React App:** Transitioning specific CE views into independent React pages.
* **Data Strategy:** Utilizing dummy data/mocking to stabilize the UI layer during the initial phase.
* **Backend APIs:** Systematic mapping of existing **Spring/REST APIs** (In coordination with mentors).
* **E2E Integration:** Defining the integration roadmap and testing strategy.

---

## Key Challenges

| Challenge | Mitigation Strategy |
| :--- | :--- |
| **Build & Environment Config** | Active debugging of build scripts for `ui-policy-management` and `maas-react-app` to ensure ecosystem compatibility. |
| **Carbon Design System Adoption** | Deep-dive analysis of Carbon documentation and grid-system layouts to maintain functional parity with legacy views. |
| **Backend Integration Complexity** | Systematic analysis of existing REST APIs (Phase 8) before initiating frontend-to-backend binding. |

---

## Future Scope

* **Micro-Frontend (MFE) Transition:** Using this migration as a blueprint for a broader transition to MFE architecture within MaaS360.
* **Performance Telemetry:** Implementing real-time monitoring to quantify ROI through "Before vs. After" load-time analytics.
* **Enhanced Responsiveness:** Leveraging Carbon’s responsive grid to ensure a "Mobile First" management experience for administrators.

<hr>

<p align="center">
  <i>IBM MaaS360 - Cloud Extender React Migration 2026</i>
</p>
