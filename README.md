# ⚡ Electron React TypeScript Template

A pre-configured template for developing Electron applications with React and TypeScript using Electron Forge. This setup provides a well-structured foundation for building cross-platform desktop applications.

## 🚀 Features

- 🎨 **React**: Leverage the power of React for building dynamic user interfaces.
- 🔷 **TypeScript**: Utilize TypeScript for better code maintainability, readability, and static typing.
- 📦 **Webpack**: Optimized bundling and asset management with Webpack.
- 🖥 **Electron**: Pre-configured for cross-platform desktop application development.

## 📖 How to Use

### 🔄 Clone the Repository
```bash
git clone https://github.com/vladislavrupets/electron-react-typescript-template.git
```

### 📦 Install Dependencies
```bash
cd electron-react-typescript-template
npm install
```

### ▶️ Start the Application
```bash
npm start
```

## 📦 App Packaging

### 📌 Package the Application (for Any Platform)
```bash
npm run package
```

## 📝 Notes

1️⃣ **Preload Script**: To bridge Electron and React, use the preload script located at `./src/electron/preload.ts`.

2️⃣ **External Resources**: You can include extra resources (such as configuration files) by placing them in `./src/extraResources/your-extra-file`. Modify `./src/forge.config.ts` if needed:

```javascript
  const config: ForgeConfig = {
    packagerConfig: {
      asar: true,
      extraResource: ["./src/extraResources"],
    },
    ...
```

3️⃣ **Further Reading**:
   - [📚 Electron Documentation](https://electronjs.org/docs)
   - [🛠 Electron Forge Documentation](https://www.electronforge.io/docs)
