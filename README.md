# Scoop Artifacts

This repository automates the process of downloading GitHub Actions artifacts and re-uploading them as GitHub Releases.

## Why?

The idea originated from my experience with Bitwarden. Bitwarden's desktop app is released monthly (aside from occasional hotfixes), and I often wanted to use the latest features without waiting for the next official release. This repository was created to fetch the GitHub Actions build artifacts and publish them as releases, making them accessible for Scoop installations.

## Why Not Use the REST API?

I initially considered downloading artifacts directly using GitHub’s REST API. However, it requires a fine-grained personal access token to access workflow artifacts, which isn’t ideal for distributing Scoop apps publicly. This repository avoids that limitation by automating the process and publishing downloadable URLs through GitHub Releases.
