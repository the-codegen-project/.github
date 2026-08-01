<div align="center">

<h1>⚡️Code-Forge⚡️</h1>

**Simplify Your Implementation in Any Language — Effortlessly**

[![License](https://img.shields.io/github/license/the-codegen-project/cli)](https://github.com/the-codegen-project/cli/blob/master/LICENSE)
[![Npm latest version](https://img.shields.io/npm/v/@the-codegen-project/cli)](https://www.npmjs.com/package/@the-codegen-project/cli)
![NPM Downloads](https://img.shields.io/npm/dw/%40the-codegen-project%2Fcli)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/the-codegen-project/cli/.github%2Fworkflows%2Fruntime-testing.yml?label=runtime%20testing)
![GitHub last commit](https://img.shields.io/github/last-commit/the-codegen-project/cli)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.x64.pkg?label=MacOS)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.arm64.pkg?label=MacOS)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.x86.exe?label=Win)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.x64.exe?label=Win)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.tar.gz?label=Linux)
![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/the-codegen-project/cli/codegen.deb?label=Linux)
![homebrew downloads](https://img.shields.io/homebrew/installs/dm/codegen?label=Brew%20(SOON))
![Chocolatey Downloads](https://img.shields.io/chocolatey/dt/codegen?label=Chocolatey%20(SOON))
</div>

---

## Stop spending time writing the wrong code


Unleash the power of automation and spend more time on what truly matters — **your business logic**!

> Ready to get started? Install the CLI now and transform your development workflow.


Modern development is fast-paced—and repetitive boilerplate shouldn’t slow you down. The Codegen Project CLI transforms your well defined APIs (AsyncAPI, OpenAPI) into production-ready code. Whether you're generating payload models, protocol functions, crafting custom generators, or automating your entire codebase setup, our CLI is your secret weapon.

---

## 🚀 Why Use Codegen CLI?

- **Effortless Code Generation:** Convert AsyncAPI, Protobuf, RAML, or OpenAPI schemas into fully functional code in minutes.
- **Customizable Output:** Tailor the generated code to your project's exact needs with flexible configuration.
- **Protocol Agnostic:** Supports MQTT, Kafka, AMQP, NATS, and more—future-proofing your development regardless of protocols you use.
- **Continuous Integration:** Regenerate code on-the-fly as your API specifications evolve, seamlessly integrating into your CI/CD pipelines.
- **Multi-Language Ready:** Starting with TypeScript, with plans to support more languages soon.

---

## 🔧 Core Features

- **Instant Payload Generation:** Automatically generate payload models, parameters, headers, messages, and even testing functions.
- **Custom Generator Creation:** Easily build your own generators directly from the configuration file.
- **Seamless Integration:** Plug Codegen CLI into any project—be it a Next.js app or an enterprise-grade microservices architecture.
- **Live Regeneration:** Keep your codebase in sync by regenerating output whenever the input changes.

---

## 📥 Installation

Install the CLI globally or as a development dependency using your favorite package manager:

### Using NPM
```bash
npm install --save-dev @the-codegen-project/cli
```
### Using Yarn

```
yarn add @the-codegen-project/cli
```

### Using Pnpm
```
pnpm add @the-codegen-project/cli
```
### Manually
Or download a prebuilt package directly:

```
curl -OL https://github.com/the-codegen-project/cli/releases/latest/download/codegen.x64.pkg
sudo installer -pkg codegen.x64.pkg -target /
```
For more installation options, [check our documentation](https://the-codegen-project.org/docs/getting-started#install).

---

## ⚙️ Getting Started

### 1. Initialize Your Project:
```
codegen init
```

This creates a configuration file where you can specify your input document, target language, and generators.

### 2. Generate Code:
```
codegen generate
```
Watch as your models, payloads, and more being generated!

### 3. Customize & Integrate
Tweak the configuration to tailor the output exactly to your needs and integrate the generated code into your project seamlessly.

---

## 📚 Documentation & Community

Dive deeper into all features, use cases, and best practices on our [website](https://the-codegen-project.org/) and [docs](https://the-codegen-project.org/docs/).

---

## 📄 License

[The Codegen Project CLI is licensed under the Apache-2.0 License](https://github.com/the-codegen-project/cli/blob/main/LICENSE).
