# Masum Galaxy // File Icons

A futuristic, galaxy-inspired **VS Code File Icon Theme** by **Masum Billah**.

The pack is designed to match the **Masum Galaxy** ecosystem: dark space surfaces, cyan/violet neon energy, compact glowing details, and clear technology-specific accent colors.

## Current release — 1.2.0

Version **1.2.0** focuses on making the real VS Code Explorer look much closer to the approved preview. Core icons now use stronger recognizable shapes instead of tiny generic document symbols, so they remain distinct at normal Explorer size.

Dedicated icons are included for HTML, CSS, JavaScript, TypeScript, React, Python, JSON, Markdown, Git, npm, environment files, Next.js, Vite, Tailwind CSS, Node.js, C, C++, Java, SQL, Docker, Supabase, GitHub, YAML, config files, lockfiles, VSIX packages, LICENSE and CHANGELOG files.

Special Galaxy folder icons are included for:

```text
src
components
assets / images
public / static
themes
icons
tests / __tests__
api
utils / helpers
hooks
styles / css
.vscode
node_modules
supabase
.github
```

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
code --install-extension .\masum-galaxy-file-icons-1.2.0.vsix --force
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

The icon system follows the approved **Masum Galaxy // File Icons** preview direction:

- dark navy / black surfaces
- cyan-to-violet neon outlines
- strong technology-specific accent colors
- recognizable shapes at small Explorer sizes
- subtle galaxy styling without making the sidebar visually noisy

## Repository

https://github.com/gitwithmasum/Galaxy-VS-Code-File-Icon

## License

MIT
