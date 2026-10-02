# Masum Galaxy // File Icons

A futuristic, galaxy-inspired **VS Code File Icon Theme** by **Masum Billah**.

The pack is designed to match the **Masum Galaxy** ecosystem: dark space surfaces, cyan/violet neon energy, compact glowing details, and clear technology-specific accent colors.

## Current release — 1.3.0

Version **1.3.0** expands the pack beyond normal web development into **full-stack, database, AI/ML and DevOps** workflows.

New coverage includes **Prisma, PostgreSQL, MongoDB, Firebase, Jupyter Notebook, TensorFlow, PyTorch, ML model artifacts, Vercel, Netlify, Kubernetes and CI/CD workflow files**.

Special Galaxy folder icons now cover:

```text
src
app
pages
components
routes
services
lib
config
database / db / migrations
prisma
models
ml / ai / notebooks
assets / images
public / static
themes
icons
tests / __tests__
api
utils / helpers
hooks
styles / css
workflows
.vscode
node_modules
supabase
.github
```

Model-file mappings include `.pt`, `.pth`, `.onnx`, `.pkl`, `.pickle`, `.joblib`, `.h5` and `.tflite`.

## Install locally

Update the repository and package the extension:

```powershell
cd "D:\OneDrive\Web Development\Galaxy-VS-Code-File-Icon"
git pull
npm.cmd install
npx.cmd vsce package
```

Install the generated VSIX:

```powershell
code --install-extension .\masum-galaxy-file-icons-1.3.0.vsix --force
```

Then reload VS Code and activate:

```text
Ctrl + Shift + P
→ Preferences: File Icon Theme
→ Masum Galaxy // File Icons
```

If the old icons remain visible, run:

```text
Developer: Reload Window
```

## Visual direction

- dark navy / black surfaces
- cyan-to-violet neon outlines
- strong technology-specific accent colors
- recognizable shapes at small Explorer sizes
- subtle Galaxy styling without making the sidebar visually noisy

## Repository

https://github.com/gitwithmasum/Galaxy-VS-Code-File-Icon

## License

MIT
