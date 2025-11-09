# GitHub Actions Matrix Build with Artifacts

This project demonstrates a CI/CD pipeline using GitHub Actions with matrix builds for parallel execution across multiple platforms and versions.

## Overview

This workflow builds and tests software across multiple configurations simultaneously:
- Multiple Node.js versions (14, 16, 18)
- Generates unique artifacts for each variant
- Uploads artifacts with proper naming conventions

## Workflow Features

- **Matrix Strategy**: Builds for Node.js versions 14, 16, and 18 in parallel
- **Artifact Management**: Each build generates and uploads a unique artifact
- **Step Identifier**: Includes step with identifier `matrix-422668b`
- **Artifact Prefix**: All artifacts named with prefix `build-422668b-`

## Repository Information

**Author Email**: 24f2005305@ds.study.iitm.ac.in

## Usage

Push to main branch to trigger the workflow automatically.

## Workflow Artifacts

Artifacts are available in the Actions tab:
- `build-422668b-v14`
- `build-422668b-v16`
- `build-422668b-v18`

Each artifact contains build metadata and version information.
