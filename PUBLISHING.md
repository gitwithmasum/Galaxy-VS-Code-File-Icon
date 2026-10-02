# Publishing Masum Galaxy // File Icons

## Local package check

On Windows PowerShell:

```powershell
npm.cmd install
npx.cmd vsce package
```

Confirm the generated VSIX installs cleanly before publishing.

## Marketplace publishing

The repository includes `.github/workflows/publish.yml` for trusted publishing with OIDC.

Before the first automated publish:

1. Create or open the **gitwithmasum** publisher in Visual Studio Marketplace.
2. Configure a trusted publishing policy for this GitHub repository and its publish workflow.
3. Make sure the policy matches `gitwithmasum/Galaxy-VS-Code-File-Icon`.
4. Push a version tag such as `v1.3.2`, or run the workflow manually.

The workflow uses:

```text
npx @vscode/vsce publish --oidc
```

No long-lived Marketplace token needs to be stored in the repository.

## Branding assets included

The Marketplace-ready branding set is now part of the repository:

```text
images/icon.png
images/marketplace-hero.png
images/explorer-preview.png
```

`package.json` uses `images/icon.png` as the extension icon, and the README displays both the hero banner and Explorer preview.

The branding assets use PNG format for sharper Marketplace and README rendering.
