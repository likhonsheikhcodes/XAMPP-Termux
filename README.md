# 🚀 XAMPP for Termux

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeBr8B8nBG3QP5UIoWaS7xNXhXHrKAkmLsZA&s" alt="XAMPP Termux Logo" width="200"/>
  
  [![Version](https://img.shields.io/badge/version-2.1.0-blue.svg)](https://github.com/likhonsheikhcodes/XAMPP-Termux)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
  [![Stars](https://img.shields.io/github/stars/likhonsheikhcodes/XAMPP-Termux?style=social)](https://github.com/likhonsheikhcodes/XAMPP-Termux/stargazers)
  
  *A modern, feature-rich XAMPP development environment for Termux*
  
  [Documentation](https://xampp-termux.vercel.app) | [Installation](#-installation) | [Features](#-features) | [Contributing](#-contributing)
</div>

## 🌟 Features

- 📱 Modern CLI interface with intuitive controls
- 🔄 Real-time service monitoring and management
- 🛠️ Automated dependency installation
- 📊 Comprehensive logging system
- 🔒 Built-in SSL support
- 💾 Automated backup functionality
- 🎨 Virtual hosts management
- 📈 Performance optimization tools

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/likhonsheikhcodes/XAMPP-Termux

# Navigate to directory
cd XAMPP-Termux

# Make executable
chmod +x xampp

# Install (optional)
cp xampp $PREFIX/bin/
```

## 📦 Components

| Component | Version | Port |
|-----------|---------|------|
| PHP       | Latest  | 8080 |
| MySQL     | Latest  | 3306 |
| Apache    | Latest  | 8081 |
| Nginx     | Latest  | 8082 |
| phpMyAdmin| Latest  | 8083 |

## 💻 Usage

### Interactive Mode
```bash
xampp
```

### Command Line
```bash
xampp start    # Start all services
xampp stop     # Stop all services
xampp status   # Check service status
xampp backup   # Create backup
xampp logs     # View logs
```

## 🔧 Configuration

Default directories:
```
/share/xampp/          # XAMPP home
├── www/              # Web root
├── backups/          # Backup storage
├── conf/             # Configurations
│   ├── php/
│   ├── mysql/
│   ├── apache/
│   └── nginx/
└── logs/             # Log files
```


## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Likhon Sheikh**
- GitHub: [@likhonsheikhcodes](https://github.com/likhonsheikhcodes)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- All contributors and users
- Termux development team
- Open source community
