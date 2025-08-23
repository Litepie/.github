# 🚀 Litepie - Modern Laravel Packages for Enterprise Applications

<div align="center">

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

🐛 **Report Bugs** - [GitHub Issues](https://github.com/LavaLite/issues)

💡 **Feature Requests** - [GitHub Discussions](https://github.com/LavaLite/community/discussions)

📖 **Improve Docs** - Help us improve our documentation

💻 **Code Contributions** - Submit pull requests 


[![MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Laravel](https://img.shields.io/badge/Laravel-12%20Ready-red.svg)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.2%2B-blue.svg)](https://php.net)
[![Stars](https://img.shields.io/github/stars/LavaLite?style=social)](https://github.com/LavaLite)

**A comprehensive suite of enterprise-grade Laravel packages for modern, scalable applications.**

*Part of the [Lavalite](https://lavalite.org) ecosystem by [Renfos Technologies](https://renfos.com)*

</div>

---

## 🎯 About Litepie

Litepie is a collection of production-ready Laravel packages developed as part of the **Lavalite** ecosystem by **Renfos Technologies**. These packages provide everything you need to build enterprise-grade web applications with **multi-tenancy**, **security**, and **performance** built-in.

---

## � Available Packages

### 🏢 **Multi-Tenancy & Organization**

| Package | Description | Links |
|---------|-------------|-------|
| **[Tenancy](https://github.com/Litepie/tenancy)** | Complete multi-tenant architecture with isolation, detection, and performance optimization | [![Packagist](https://img.shields.io/packagist/v/litepie/tenancy.svg)](https://packagist.org/packages/litepie/tenancy) |
| **[Organization](https://github.com/Litepie/organization)** | Hierarchical organization management (companies, branches, departments) | [![Packagist](https://img.shields.io/packagist/v/litepie/organization.svg)](https://packagist.org/packages/litepie/organization) |
| **[Roles](https://github.com/Litepie/roles)** | Advanced role-based access control with dynamic permissions | [![Packagist](https://img.shields.io/packagist/v/litepie/roles.svg)](https://packagist.org/packages/litepie/roles) |

### 👥 **User Management**

| Package | Description | Links |
|---------|-------------|-------|
| **[Users](https://github.com/Litepie/users)** | Comprehensive user management with workflows and file handling | [![Packagist](https://img.shields.io/packagist/v/litepie/users.svg)](https://packagist.org/packages/litepie/users) |
| **[Teams](https://github.com/Litepie/teams)** | Team collaboration with role management and permissions | [![Packagist](https://img.shields.io/packagist/v/litepie/teams.svg)](https://packagist.org/packages/litepie/teams) |

### �️ **Data Management**

| Package | Description | Links |
|---------|-------------|-------|
| **[Database](https://github.com/Litepie/database)** | Enhanced Eloquent with search, caching, archiving, and money handling | [![Packagist](https://img.shields.io/packagist/v/litepie/database.svg)](https://packagist.org/packages/litepie/database) |
| **[Masters](https://github.com/Litepie/masters)** | Master data management (countries, currencies, categories) | [![Packagist](https://img.shields.io/packagist/v/litepie/masters.svg)](https://packagist.org/packages/litepie/masters) |
| **[Settings](https://github.com/Litepie/settings)** | Multi-level settings with encryption and audit trails | [![Packagist](https://img.shields.io/packagist/v/litepie/settings.svg)](https://packagist.org/packages/litepie/settings) |

### ⚡ **Business Logic**

| Package | Description | Links |
|---------|-------------|-------|
| **[Actions](https://github.com/Litepie/actions)** | Action pattern with validation, authorization, and sub-action orchestration | [![Packagist](https://img.shields.io/packagist/v/litepie/actions.svg)](https://packagist.org/packages/litepie/actions) |
| **[Flow](https://github.com/Litepie/flow)** | Workflow management with state transitions and visual designer | [![Packagist](https://img.shields.io/packagist/v/litepie/flow.svg)](https://packagist.org/packages/litepie/flow) |
| **[Form](https://github.com/Litepie/form)** | Dynamic form builder with validation and theming | [![Packagist](https://img.shields.io/packagist/v/litepie/form.svg)](https://packagist.org/packages/litepie/form) |

### 🔔 **Communication & Files**

| Package | Description | Links |
|---------|-------------|-------|
| **[Notifications](https://github.com/Litepie/notifications)** | AI-powered notifications with multi-channel support and analytics | [![Packagist](https://img.shields.io/packagist/v/litepie/notifications.svg)](https://packagist.org/packages/litepie/notifications) |
| **[Trans](https://github.com/Litepie/trans)** | Advanced translation management with language negotiation | [![Packagist](https://img.shields.io/packagist/v/litepie/trans.svg)](https://packagist.org/packages/litepie/trans) |
| **[FileHub](https://github.com/Litepie/filehub)** | Secure file management with processing and user tracking | [![Packagist](https://img.shields.io/packagist/v/litepie/filehub.svg)](https://packagist.org/packages/litepie/filehub) |
| **[Logs](https://github.com/Litepie/logs)** | Enhanced logging with filtering, analytics, and monitoring | [![Packagist](https://img.shields.io/packagist/v/litepie/logs.svg)](https://packagist.org/packages/litepie/logs) |

---

## � Quick Installation

### Install Individual Packages
```bash
# Core multi-tenancy
composer require litepie/tenancy

# User management
composer require litepie/users litepie/roles litepie/organization

# Business logic
composer require litepie/actions litepie/flow litepie/notifications

# Data management
composer require litepie/database litepie/masters litepie/settings
```

### System Requirements
- **PHP** 8.2+ (8.3+ recommended)
- **Laravel** 11.x or 12.x
- **MySQL** 8.0+ or **PostgreSQL** 13+
- **Redis** 6.0+ (recommended for caching)

---

## 📚 Resources

- **[Lavalite Documentation](https://docs.lavalite.org)** - Comprehensive guides and API reference
- **[Examples](https://github.com/LavaLite/examples)** - Real-world implementation examples
- **[Community](https://github.com/LavaLite/community/discussions)** - Ask questions and share ideas
- **[Support](mailto:support@lavalite.org)** - Get help with your implementation

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

- � **Report Bugs** - [GitHub Issues](https://github.com/Litepie/issues)
- 💡 **Feature Requests** - [GitHub Discussions](https://github.com/Litepie/community/discussions)
- 📖 **Improve Docs** - Help us improve our documentation
- � **Code Contributions** - Submit pull requests

---

## 📄 License

All Litepie packages are open-sourced software licensed under the **MIT License**.

---

<div align="center">

**Made with ❤️ by [Renfos Technologies](https://renfos.com)**

*Part of the [Lavalite](https://lavalite.org) ecosystem*

[![GitHub](https://img.shields.io/github/followers/LavaLite?style=social)](https://github.com/LavaLite)
[![Twitter](https://img.shields.io/twitter/follow/LavaLite?style=social)](https://twitter.com/LavaLite)

[⭐ Star us on GitHub](https://github.com/LavaLite) • [📖 Read the Docs](https://docs.lavalite.org) • [💬 Join the Community](https://github.com/LavaLite/community)

</div>
