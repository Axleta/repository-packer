# 📦 Context-Packer for Developers

> **Transform Git repositories into structured, token-optimized XML prompts for LLMs in seconds.**

[![Status: Active](https://img.shields.io/badge/Status-Production--Ready-brightgreen.svg)](#)
[![Built by: Axleta](https://img.shields.io/badge/Built%20by-Axleta-blue.svg)](https://github.com/axleta)

[Context-Packer](https://packer.axleta.com/) is an interactive developer tool designed to streamline codebase ingestion for Large Language Models (LLMs) like Claude, ChatGPT, and Gemini. It parses repository structures, filters out build artifacts, and packages source files into clean, context-aware prompt buffers.

---

## ✨ Features

* 🌲 **Automatic Directory Trees**: Generates visual, formatted repository maps for clear model orientation.
* 🏷️ **Structured XML Formatting**: Encapsulates files in isolated `<file path="...">` tags for precise LLM parsing.
* ⚡ **Smart File Filtering**: Excludes binaries, lockfiles, dependency folders (`node_modules/`, `venv/`), and build assets automatically.
* 🔐 **Secure Execution**: Operates directly with GitHub API token support for private repository access.
* 🚀 **Zero-Overhead Processing**: Fast and lightweight execution context designed for instant prompt extraction.

---

## 🛠️ Tech Stack & Integrations

* **Frontend**: Responsive Single-Page Web Interface
* **API Ingestion**: GitHub REST & GraphQL APIs
* **Authentication & Backend**: Secure User Sessions & Managed Cloud Workflows
* **Target Platforms**: ChatGPT, Claude, Gemini, and custom LLM agent pipelines

---

## 🚀 Getting Started

### Prerequisites
* Any modern web browser (Chrome, Firefox, Safari, Edge)
* A [GitHub Personal Access Token](https://github.com/settings/tokens) (recommended to avoid API rate limits on larger repos)

### Quick Usage Guide

1. **Launch the Workspace**: Open [contex-packer](https://packer.axleta.com/) in your browser or visit the live hosted platform.
2. **Enter Repository URL**: Paste any public or private GitHub repository link with token. As an example below:
   ```text
   (https://github.com/owner/repository)
3. **Refer to the User Manual**: For more details read the [User Manual](https://packer.axleta.com/manual)
