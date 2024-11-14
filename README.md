# Aaron's VSCode Extension Pack

Welcome to the **Aaron's VSCode Extension Pack**! This extension pack includes all the essential Visual Studio Code extensions I use for consistent development practices.

## Table of Contents
- [Installation](#installation)
- [Manual Installation](#manual-installation)
- [Contributing](#contributing)
- [FAQs](#faqs)

## Installation

To quickly set up your VSCode environment with our extension pack, follow these steps:

1. **Download the `.vsix` File**:
   - Go to the [Releases]([[[https://github.com/yourusername/your-repo-name/release](https://github.com/aaronchenghs/aarons_vscode_extensions/tree/main/Releases)s](https://github.com/aaronchenghs/aarons_vscode_extensions/tree/main)](https://github.com/aaronchenghs/aarons_vscode_extensions/tree/main/Releases)) folder of this repository.
   - Download the `.vsix` file from the newest release (e.g., `team-standard-pack-0.0.1.vsix`).

2. **Install the Extension Pack**:
   - Open Visual Studio Code.
   - Navigate to the **Extensions** view (`Ctrl+Shift+X` or `Cmd+Shift+X` on macOS).
   - Click on the **...** (ellipsis) at the top-right corner and select **Install from VSIX...**.
   - Locate the downloaded `.vsix` file and install it.

Alternatively, you can use the command line:
```bash
code --install-extension path/to/my-extension-pack.vsix
```

## Contributing

I encourage contributions to improve and expand this VSCode extension pack. Here’s how you can contribute:

### How to Contribute

1. **Fork the Repository**:
   - Go to the [repository][(https://github.com/yourusername/your-repo-name](https://github.com/aaronchenghs/aarons_vscode_extensions)) and click on **Fork** to create your own copy.

2. **Clone Your Fork**:
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/aaronchenghs/aarons_vscode_extensions.git)
   cd aarons_vscode_extensions
   ```

3. **Clone Your Fork**:
   git checkout -b feature/your-feature-name

4. **Make Your Changes**:
   - Run the extension locally to ensure your changes work as expected:
 ```bash
   vsce package
   code --install-extension path/to/your-extension-pack.vsix
```

5. Commit Your Changes:
 ```bash
git add .
git commit -m "Add/update: Brief description of your change"
```

6. Push to Your Branch
 ```bash
git push origin feature/your-feature-name
```

7. Create a Pull Request

Go to the original repository and create a pull request from your branch.
Provide a clear description of what your changes do and why they are necessary.

THank you for your contributions!
