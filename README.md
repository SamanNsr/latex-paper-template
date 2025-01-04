# LaTeX Paper Template

This repository provides a template for writing academic papers in LaTeX. Follow these steps to get started:

## Prerequisites

### 1. Install MiKTeX

- Download and install [MiKTeX](https://miktex.org/download).
- **For macOS and Linux users**: Ensure the path to MiKTeX is added to your system's PATH environment variable. Refer to [this link](https://miktex.org/howto/modify-path).

### 2. Install LaTeX Workshop Extension

- Install the **LaTeX Workshop** extension for Visual Studio Code (VSCode).

### 3. Configure a Formatter

There are two options for formatting your LaTeX code:

#### Option 1: Prettier

1. Install the Prettier extension from VSCode's extension marketplace.
2. Download and install [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/).
3. Install dependencies by running the following command in the terminal:
   ```bash
   yarn install
   ```

#### Option 2: tex-fmt

1. Install **tex-fmt** from the [GitHub repository](https://github.com/WGUNDERWOOD/tex-fmt) and follow the instructions provided there.
2. Update your VSCode settings to use tex-fmt as the default formatter by modifying the `.vscode/settings.json` file:
   ```json
   {
     "latex-workshop.formatting.latex": "tex-fmt"
     // "editor.defaultFormatter": "esbenp.prettier-vscode"
   }
   ```

### Final Step

Once the above steps are completed, you're all set to use this template for your LaTeX projects!
