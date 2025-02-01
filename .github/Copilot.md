# Copilot Instructions for Contributors �

## Overview
This repository converts **Bubble.io** apps into **React + Electron** with **GraphQL/REST backends**.

## Folder Structure
- `src/` → React UI  
- `server/` → Backend (GraphQL/REST)  
- `.github/workflows/` → GitHub Actions for auto-builds  
- `dist/` → Packaged builds (`.exe`, `.dmg`, `.zip`)  

## Contributor Guide
1. **New UI Feature?** Edit `src/App.js` & `src/components/`.  
2. **Backend Change?** Modify `server/graphql/` or `server/api/`.  
3. **Need to Auto-Build?** Push changes to `main`.  
4. **Debug Electron?** Run `npm start` in development mode.

## Copilot Prompts
**For new components**:  
> "Generate a new React component for file selection in Electron."

**For GraphQL API updates**:  
> "Modify GraphQL schema to support authentication."
