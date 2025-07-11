<div align="center">
  <img src="static/img/logo-old.svg" alt="GPUL Logo" width="250"/>
</div>

# GPUL Main Site

![GitHub License](https://img.shields.io/github/license/gpul-org/web) ![pnpm](https://img.shields.io/badge/pnpm-%3E%3D10.0.0-blue.svg) ![Node.js](https://img.shields.io/badge/node-%3E%3D22.0.0-green.svg)

Official website of GPUL (Grupo de Programadores y Usuarios de Linux). Built with Docusaurus.

## 🚀 Getting Started

### 📋 Prerequisites

- [Node.js](https://nodejs.org/) (version 22.0 or higher)
- [pnpm](https://pnpm.io/) (version 10.0 or higher)
- Git

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/gpul/web.git gpul-web
cd gpul-web
```

2. Install dependencies:

```bash
pnpm install
```

3. Start the development server:

```bash
pnpm start
```

The site will be available at `http://localhost:3000`.

## 📁 Project Structure

```plaintext
gpul-web/
├── docs/                # Documentation files
├── blog/                # Blog posts
├── src/                 # Source files
│   ├── components/      # React components
│   ├── css/             # Custom CSS
│   └── pages/           # Additional pages
├── static/              # Static assets
└── docusaurus.config.js # Docusaurus configuration
```

## 🤝 Contributing

We welcome all contributions! Whether you're fixing bugs, improving documentation, or adding new features, your help is appreciated.

### Quick Start

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/amazing-feature`)
3. Make your changes following our [Conventional Commits](https://www.conventionalcommits.org/) format
4. Push to the branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

All changes will be reviewed by a member of the current GPUL board before being merged.

For more detailed information, please read our [Contributing Guide](CONTRIBUTING.md).

### Code Quality and Pre-Commit Hooks

To help maintain code quality and consistent formatting, this project includes pre-commit hooks that run [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/) on staged files before a commit is made. The same linting and formatting is being run on CI.

These hooks are **completely optional** (opt-in) to give developers flexibility in their workflow, however, we encourage its use, to avoid having to re-do commits to pass CI.

### How It Works

- **ESLint**: Checks for potential bugs and enforces code style rules. If any errors are found, **the commit will be aborted**, and you will need to fix the errors manually before trying to commit again.
- **Prettier**: Automatically formats your code to ensure a consistent style across the entire codebase.

### How to Enable the Hooks

If you wish to enable the pre-commit hooks on your local machine, follow this simple step.

1.  Navigate to the root directory of the project in your terminal.
2.  Create the opt-in file by running the following command:

    ```bash
    touch .opt-in-hooks
    ```

That's it! The hooks will now run automatically every time you make a commit. The `.opt-in-hooks` file is listed in our `.gitignore`, so it won't be added to the repository.

If you decide you no longer want the hooks to run, simply delete the `.opt-in-hooks` file.

## 📄 License

This project is licensed under the GPL v3 License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

For any questions or suggestions, please contact the GPUL team through our official channels.

---

<div align="center">
  <sub>Built with ❤️ by GPUL</sub>
</div>
