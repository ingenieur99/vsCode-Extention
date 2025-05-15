# REST API Client

Simple and intuitive REST API Client built as a Visual Studio Code extension to improve developer productivity with an in-editor interface for sending and testing HTTP/S requests.

[Visual Studio Marketplace](#) • [Repository](#) • [Releases](#)

---

## 📸 Preview

A seamless API testing experience directly in your VS Code environment.

---

## 🚀 Installation

> **Note**: This extension works only on the desktop version of Visual Studio Code (not the web version) and pairs best with a dark theme.

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for `REST API Client`
4. Click Install

---

## 🔐 Security and Privacy

- This extension does **not** collect or store any personal data or API request information externally.
- All request history and favorite collections are stored locally using the [VS Code Global State API](https://code.visualstudio.com/api/references/vscode-api#Memento).

---

## ✨ Features

- Supports 7 HTTP methods: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `HEAD`, `OPTIONS`
- Add custom headers, query parameters, and authorization:
  - Basic Auth
  - Bearer Token
- Add body data in multiple formats:
  - Form Data
  - x-www-form-urlencoded
  - Raw: Text, JavaScript, JSON, HTML
- Generate and copy code snippets in 18+ languages using [Postman-Code-Generators](https://github.com/postmanlabs/postman-code-generators)
- View response data in:
  - Pretty / JSON / HTML / Raw / Text views
- Sidebar for:
  - Request History
  - Favorites
- Display response metadata: Status code, size, time
- HTML preview for response data
- Search bar to filter request history
- Visual UI for marking favorites and deleting history
- Responsive and resizable vertical menu

---

## 💻 Commands

To access the extension UI:

- `Ctrl+Shift+P` (Windows/Linux)
- `Cmd+Shift+P` (macOS)

Then run:  
```plaintext
> Start: New Request
