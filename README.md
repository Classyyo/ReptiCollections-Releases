# ReptiCollections Releases

Official Android APK releases for **ReptiCollections**.

This repository is used only for downloadable app builds. The application source code lives in the private development repository.

## APK naming

Every GitHub Release should attach the installable APK using the same filename:

`ReptiCollections.apk`

Keeping the asset filename constant gives us one permanent "latest version" download URL:

`https://github.com/Classyyo/ReptiCollections-Releases/releases/latest/download/ReptiCollections.apk`

Each GitHub Release itself should still be versioned, for example:

- `v1.8.0`
- `v1.8.1`
- `v1.9.0`

Suggested release title:

`ReptiCollections v1.8.0`

## Publishing a new APK

1. Build the Android APK from the main ReptiCollections project.
2. Create a new GitHub Release in this repository.
3. Use the app version as the release tag, such as `v1.8.0`.
4. Attach the APK as **ReptiCollections.apk**.
5. Publish the release.

The permanent latest-download URL will then automatically resolve to the APK attached to the newest release.

## Custom domain

A download domain can redirect directly to:

`https://github.com/Classyyo/ReptiCollections-Releases/releases/latest/download/ReptiCollections.apk`

Example:

`download.example.com` → latest ReptiCollections APK

> Important: direct unauthenticated downloads from GitHub Releases require this release repository to be public. If the repository stays private, GitHub requires authentication to access the APK.

## Repository policy

- APK files belong in **GitHub Releases**, not regular Git commits.
- Keep the source-code repository separate and private.
- Use one release per app version.
- Keep the APK asset filename exactly `ReptiCollections.apk` so the permanent download link never changes.
