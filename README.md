# react-native-share

> Social share, sending simple data to other apps.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-native-share** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

Social share, sending simple data to other apps.

**Topics / Tags:** `approvers-1`

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | React Native |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `@babel/core`
- `@babel/runtime`
- `@commitlint/cli`
- `@commitlint/config-conventional`
- `@react-native-community/eslint-config`
- `@react-native-community/eslint-plugin`
- `@semantic-release/commit-analyzer`
- `@semantic-release/git`
- `@semantic-release/github`
- `@semantic-release/npm`


---

## Repository Structure

```
react-native-share/
├── .circleci
├── .eslintignore
├── .eslintrc
├── .flowconfig
├── .github/
│   ├── ISSUE_TEMPLATE
│   ├── PULL_REQUEST_TEMPLATE.md
│   ├── stale.yml
├── .gitignore
├── .npmignore
├── CHANGELOG.md
├── CODEOWNERS
├── LICENSE
├── README.md
├── RNShare.podspec
├── android/
│   ├── .npmignore
│   ├── build.gradle
│   ├── gradle
│   ├── gradlew
│   ├── gradlew.bat
├── commitlint.config.js
├── components/
│   ├── Button.js
│   ├── Overlay.js
│   ├── Sheet.js
├── example/
│   ├── .eslintrc.js
│   ├── .gitignore
│   ├── .prettierrc.js
│   ├── App.js
│   ├── android
├── index.js
├── ios/
│   ├── .npmignore
│   ├── EmailShare.h
│   ├── EmailShare.m
│   ├── FacebookStories.h
│   ├── FacebookStories.m
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `CHANGELOG.md` | Source file |
| `CODEOWNERS` | Source file |
| `LICENSE` | Source file |
| `README.md` | Source file |
| `RNShare.podspec` | Source file |
| `android/.npmignore` | Source file |
| `android/build.gradle` | Source file |
| `android/gradle/wrapper/gradle-wrapper.jar` | Source file |
| `android/gradle/wrapper/gradle-wrapper.properties` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/react-native-share.git
cd react-native-share
# Follow language-specific setup
```

### Available Scripts

```bash
# start
npm run start   # react-native start

# start:android
npm run start:android   # react-native run-android

# start:ios
npm run start:ios   # react-native run-ios

# lint
npm run lint   # eslint index.js --max-warnings=0

# lint:staged
npm run lint:staged   # lint-staged

# validate
npm run validate   # yarn validate:prettier && yarn validate:lint && yarn validate:flow

# validate:flow
npm run validate:flow   # yarn flow

# validate:lint
npm run validate:lint   # eslint *js components/*.js --max-warnings=0

# validate:prettier
npm run validate:prettier   # prettier --write *.js components/*.js

# ci:publish
npm run ci:publish   # npx semantic-release

```


---

## Running the Application

```bash
npm run start   # react-native start
```

---

## Infrastructure & CI/CD

- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> # react-native-share [![react-native-share](https://circleci.com/gh/react-native-share/react-native-share.svg?style=svg)](https://app.circleci.com/pipelines/github/react-native-share/react-native-share) [![npm version](https://badge.fury.io/js/react-native-share.svg)](http://badge.fury.io/js/react-native-share) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

React Native Share, a simple tool for share message and file to other apps.

# Sponsors

---

If you use this library on

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
