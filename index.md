## CE Settings UI Migration to React

**Mentors:** Anoop, Suresh  
**Interns:** Naitik, Mansi  

---

## Project Description

The Cloud Extender (CE) settings UI migration project focuses on transitioning the existing CE UI from a legacy architecture into a standalone, modern React-based application.

Currently, the CE view is tightly coupled with the monolithic MaaS360 application (device-view), which leads to performance bottlenecks and makes the UI difficult to maintain.

We are rebuilding this module using **React.js** and the **IBM Carbon Design System** to deliver a faster, more responsive, and consistent user experience.

---

## Justification

The shift to a React-based architecture helps address several critical issues:

- **Performance Gains:** Reduces high latency and improves DOM rendering performance.
- **Independent Scalability:** Allows deploying updates without impacting the entire MaaS360 portal.
- **Resource Optimization:** Eliminates interference from background processes and avoids unexpected routing conflicts.
- **Development Velocity:** Simplifies debugging and accelerates feature development.

---

## Scope

1. **Modernization:** Transition all legacy UI components to React.js and IBM Carbon components.  
2. **Decoupling:** Move CE logic into a standalone application to ensure independent execution.  
3. **API Integration:** Map and integrate existing Spring/REST APIs with the React frontend.  
4. **Environment Setup:** Configure build scripts and environment variables for smooth setup.  
5. **UI Fidelity:** Implement responsive layouts for consistent experience across devices.  

---

## Details

For more technical details, refer to:  
[CE Settings UI Migration Documentation](./ce-react-migration/ce-react-migration.md)
