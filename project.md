# HeyHazel Project Setup (Dementia Care Scheduler Prototype)

## Memory Bank
- Rapid prototyping using React + Capacitor
- VSCode extensions: ES7+ React/Redux/React-Native snippets; Prettier; ESLint; Auto Rename Tag; Bracket Pair Colorizer; GitLens; Path Intellisense; Tailwind CSS IntelliSense; npm Intellisense; Debugger for Chrome; Capacitor Tools; React Developer Tools
- VSCode settings: formatOnSave; defaultFormatter; eslint.autoFixOnSave; emmet.includeLanguages; file associations for JSX/TSX
- Project structure: src/components, hooks, pages, services, utils, App.jsx, main.jsx; public/assets; capacitor.config.json; package.json
- Core dependencies: react, react-dom, @capacitor/core, @capacitor/cli, @capacitor/android, @capacitor/ios, @capacitor-community/react-hooks, vite, @vitejs/plugin-react, eslint, prettier
- Capacitor workflow: npx cap init; npx cap add android; npm run build; npx cap sync; npx cap open android
- Live reload: npm run dev -- --host; npx cap run android --livereload --external
- Key features: Storage API; Local Notifications; Device control APIs; Text-to-Speech

## Essential VSCode Extensions
- ES7+ React/Redux/React-Native snippets
- Prettier - Code formatter
- ESLint
- Auto Rename Tag
- Bracket Pair Colorizer
- GitLens
- Path Intellisense
- Tailwind CSS IntelliSense
- npm Intellisense
- Debugger for Chrome
- Capacitor Tools
- React Developer Tools

## VSCode Settings (settings.json)
```json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "eslint.autoFixOnSave": true,
  "emmet.includeLanguages": { "javascript": "javascriptreact" },
  "files.associations": { "*.jsx": "javascriptreact", "*.tsx": "typescriptreact" }
}
```

## Dependencies and Scripts
```bash
npm install react react-dom @capacitor/core @capacitor/cli @capacitor/android @capacitor/ios @capacitor-community/react-hooks
npm install -D vite @vitejs/plugin-react eslint prettier
```

## Capacitor Initialization and Workflow
```bash
npx cap init
npx cap add android
npm run build
npx cap sync
npx cap open android
```

## Live Reload Setup
```bash
npm run dev -- --host
npx cap run android --livereload --external
```

## MCP Server (Context7)
- Already configured: `get-library-docs`, `resolve-library-id`

## Key Features for Scheduler App
- Data persistence: Capacitor Storage API
- Reminders: Capacitor Local Notifications
- Device control: Custom Capacitor plugins
- Voice reminders: Capacitor Text-to-Speech