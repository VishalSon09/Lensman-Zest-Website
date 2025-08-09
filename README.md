# Lensman-Zest-Website

### **Branching Strategy**

**Gitflow branching model** to manage parallel development, bug fixes, and releases.

| Branch Type | Purpose                        | Naming Pattern                | Example               |
| ----------- | ------------------------------ | ----------------------------- | --------------------- |
| **main**    | Always production-ready        | `main`                        | `main`                |
| **develop** | Latest development integration | `develop`                     | `develop`             |
| **feature** | New features                   | `feature/<short-description>` | `feature/homepage-ui` |
| **bugfix**  | Fixes for bugs (non-critical)  | `bugfix/<short-description>`  | `bugfix/navbar-hover` |
| **hotfix**  | Urgent production fixes        | `hotfix/<short-description>`  | `hotfix/footer-logo`  |
| **release** | Pre-release prep               | `release/<version>`           | `release/1.0.0`       |
