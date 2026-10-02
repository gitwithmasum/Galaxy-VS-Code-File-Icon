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
4. Push a version tag such as `v1.3.1`, or run the workflow manually.

The workflow uses:

```text
npx @vscode/vsce publish --oidc
```

No long-lived Marketplace token needs to be stored in the repository.

## Branding assets still required

Before the public Marketplace launch, add PNG assets:

```text
images/icon.png
images/marketplace-hero.png
images/explorer-preview.png
```

Then add the extension icon path to `package.json` and embed the PNG preview images in the README.

Do not use SVG for the Marketplace extension icon or README screenshots.
