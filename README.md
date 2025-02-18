# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Project Structure

```
    src/
    ├── components/   (Atomic Design)
    │   ├── atoms/
    │   ├── molecules/
    │   ├── organisms/
    │   ├── templates/
    │   └── pages/
    ├── features/   (Feature-based Structure)
    │   ├── auth/
    │   │   ├── components/
    │   │   ├── hooks/
    │   │   ├── services/
    │   │   ├── types/
    │   │   └── store/
    │   ├── user/
    │   │   ├── components/
    │   │   ├── hooks/
    │   │   ├── services/
    │   │   ├── types/
    │   │   └── store/
    ├── hooks/  (Global hooks)
    ├── services/  (Global services, API calls, etc.)
    ├── store/  (Global state management)
    ├── utils/  (Helper functions)
    ├── config/  (Configurations like DI, environment variables)
    ├── tests/  (Test setup and mock data)
    ├── styles/  (Global styles)
    ├── App.tsx
    ├── index.tsx
```
