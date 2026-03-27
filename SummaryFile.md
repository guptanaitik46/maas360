# Internship Projects H1-2026


## Project: CE React Migration  

### Mentors : Anoop, Suresh  
### Interns : Naitik, Mansi  

---

### Project Description  
The Cloud Extender (CE) migration project focuses on transitioning the existing CE module from its legacy architecture into a standalone, modern application.  

Currently, the CE view is tightly coupled with the monolithic MaaS360 system, which creates performance bottlenecks and makes the UI difficult to maintain.  

We are rebuilding this module using **React.js** and the **IBM Carbon Design System** to ensure a faster, more responsive, and visually consistent user experience.  

---

### Justification  
The shift to a React-based architecture is necessary to solve several critical issues:

- **Performance Gains:** The current legacy setup suffers from high latency and slow DOM rendering due to heavy browser overhead.  
- **Independent Scalability:** Decoupling the CE logic allows us to deploy updates and scale features without impacting the entire MaaS360 portal.  
- **Resource Management:** Moving to a separate app eliminates resource contention from background processes, preventing unexpected routing conflicts and page redirects.  
- **Development Velocity:** A modern framework simplifies debugging and accelerates the development lifecycle for feature updates.  

---

### Scope  

1. **Modernization:** Transitioning all legacy UI components to React.js and IBM Carbon Components.  
2. **Decoupling:** Moving CE logic into a standalone application to run independently of the main monolithic app.  
3. **API Integration:** Mapping and migrating existing Spring/REST APIs to the new React frontend.  
4. **Environment Setup:** Debugging build scripts and environment variables to ensure compatibility with the setup.  
5. **UI Fidelity:** Implementing a responsive grid system to ensure full functionality across tablet and mobile browsers.   

---

### Details


**For More Technical Details in this page**: [View more technical details](./CE_React_Migration/CE_React_Migration.md)
