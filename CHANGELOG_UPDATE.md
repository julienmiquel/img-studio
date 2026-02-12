# Changelog Summary

This document summarizes the recent changes from the upstream project that are now present in this repository.
Note: The source code was already largely up-to-date with the upstream `main` branch. This update synchronizes `package-lock.json` and documents the recent features.

## Recent Features (from Upstream)
- **Veo 3 Integration:** Support for Veo 3, including 1080p resolution (default), fast mode, duration settings, and mandatory prompt enhancement.
- **Imagen 4 Integration:** Integration with Imagen 4 and updates to Imagen 3 endpoints.
- **Editing Tools:** Out-of-the-box upscale feature in the Edit tab.
- **Generation:** "More like this" button for generated images.
- **Seed Control:** Seed support for both text-to-video and text-to-image generation.
- **Batch Operations:** Batch delete feature for media management.
- **Prompting:** Image-to-prompt generator feature.

## Enhancements
- **Prompt Engineering:** Enhanced prompting logic for Veo 3 and Imagen.
- **UI/UX:** Separated export and download buttons. Improved labels.
- **Documentation:** Updated README with model access forms.

## Fixes
- **Video Generation:** Fixed video polling logic and Veo 3 parameters.
- **Image Generation:** Fixed image generation model selection.
- **Data Handling:** Fixed Firestore fetch logic and seed logic.
- **UI:** Fixed filter logic, orientation logic, and mask borders.
- **Infrastructure:** Updated Dockerfile.

## Maintenance
- **Dependencies:** Synchronized `package-lock.json` with upstream.
