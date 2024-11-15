# Aaron's VSCode Extension Pack

Welcome to the **Aaron's VSCode Extension Pack**! This extension pack includes all the essential Visual Studio Code extensions I use for consistent development practices.
This repository levarages the [Yeoman Code Generator NPM package](https://www.npmjs.com/package/generator-code) to create an easy-to-use extensions package manager

## Table of Contents
- [Installation](#installation)
- [Manual Installation](#manual-installation)
- [Contributing](#contributing)
- [FAQs](#faqs)

## Installation

To quickly set up your VSCode environment with my extension pack, follow these steps:

1. **Download the `.vsix` File**:
   - Go to the [Releases](https://github.com/aaronchenghs/aarons_vscode_extensions/tree/main/Releases) folder of this repository.
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
   - Go to the Repository: [(https://github.com/aaronchenghs/aarons_vscode_extensions](https://github.com/aaronchenghs/aarons_vscode_extensions) and click on **Fork** to create your own copy.

2. **Clone Your Fork**:
```bash
git clone [HTTPS to your fork]
cd aarons_vscode_extensions(or your fork name)
```

3. **Intall Dependencies***
```bash
npm install
```

4. **Make Your Changes**:
   - Run the extension locally to ensure your changes work as expected:
 ```bash
   vsce package
   code --install-extension path/to/your-extension-pack.vsix
```

OR if you have the extension ids for the extensions you want to add readily available:
 1. Navigate to package.json
 2. Find the 'extensionPack' region
 3. Append the id to this list
 4. Run ```vsce package```

After doing either of the above, you should now have a new .vsix file in the root directory.
Create a new folder in the Releases module found in the root corresponding to your new version, and place the .vsix file in there.

6. Commit Your Changes:
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
