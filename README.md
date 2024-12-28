# Recap

> Content Management, Reforged in Rust

Recap is a modern Content Management System built with Rust and WebAssembly, inspired by Decap CMS. It combines Rust's performance and safety with WebAssembly's portability to create a powerful, efficient, and developer-friendly CMS.

## 🚀 Features

- **Rust Core**: High-performance backend leveraging Rust's safety and concurrency
- **WebAssembly**: Browser-native performance with WASM compilation
- **Git-Based**: Version control built into your content workflow
- **Modern UI**: Sleek admin interface with real-time preview
- **Developer First**: API-driven architecture with extensive plugin system
- **Media Management**: Built-in asset optimization and management
- **Type Safe**: Strong type system throughout the entire stack

## 🛠️ Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
- [Node.js](https://nodejs.org/) (for development)

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/recap
cd recap

# Build the WASM package
wasm-pack build

# Start the development server
cd www
npm install
npm start
```

## 🏗️ Project Structure

```
/crates
  /core         - Core CMS functionality
  /git          - Git integration
  /markdown     - Markdown processing
  /admin-ui     - Admin interface
/examples       - Usage examples
/tests         - Integration tests
/www           - Web frontend
```

## 📦 Modules

### Core (Rust)
- Git Authentication
- File Management (Markdown/YAML/JSON)
- WASM/JS Bridge
- Git Persistence Layer

### Frontend (WASM/JS)
- Admin Interface
- Content Editor
- Real-time Preview
- Media Manager

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add: Amazing Feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and development process.

## 🎯 Roadmap

### Phase 1: Foundation
- [ ] Core Rust implementation
- [ ] Git authentication system
- [ ] Basic content editor
- [ ] Admin interface

### Phase 2: Enhancement
- [ ] Plugin system
- [ ] Advanced UI customization
- [ ] Multiple database support
- [ ] GraphQL API

### Phase 3: Scale
- [ ] Custom workflows
- [ ] Internationalization
- [ ] Advanced permissions
- [ ] CDN integration

## 🔒 Security

Security is a top priority. If you discover a security vulnerability, please open an issue using our security issue template.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [Decap CMS](https://decapcms.org/) for inspiration
- [Rust](https://www.rust-lang.org/) community
- [WebAssembly](https://webassembly.org/) community

## 📞 Contact

- Website: [recap.dev](https://recap.dev) _(coming soon)_
- Twitter: [@recapcms](https://twitter.com/recapcms) _(coming soon)_
- Email: [contact@recap.dev](mailto:contact@recap.dev) _(coming soon)_

## ⭐ Support

If you find Recap useful, please consider giving it a star on GitHub! Your support helps make the project better.