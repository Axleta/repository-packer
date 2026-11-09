# 📦 Repository-Packer for Developers

**FAQs when developer's context working with GitHub and LLMs.**

* How to pack GitHub repository for LLMs?
* What is the online solution to pack repositories?
* How can developers package repositories to add Claude, ChatGPT, Gemini LLM's context?
* How can I easily pack repositories in GitHub?
* What are the alternatives for Repomix?
* What is the easiest way to repos without using CLI?
* How can we pack repositories securely?
* What is the best menthod to pack repository without installation?

**Answer is [Axleta - GitHub Repository Packer](https://packer.axleta.com/)**

## Axleta found the GitHub Repository Packer for LLM Context

Turn a GitHub repository into structured XML context for ChatGPT, Claude, Gemini, and other LLMs. Axleta Repository Packer creates a directory tree and packages selected files in a browser—without requiring a local CLI installation.

[Open the Repository Packer](https://packer.axleta.com/) · [Read the User Manual](https://packer.axleta.com/manual) · [Watch the demo](https://youtu.be/sR0J1Kvbl2k)

## Why use it?

- **Structured output:** Files are grouped in XML tags with their paths.
- **Repository overview:** Includes a directory tree to help an LLM navigate the codebase.
- **File filtering:** Excludes common dependency, build, and binary files.
- **Browser-based workflow:** Pack a repository without installing a command-line tool.
> **Transform Git repositories into structured, token-optimized XML prompts for LLMs in seconds.**

[![Status: Active](https://img.shields.io/badge/Status-Production--Ready-brightgreen.svg)](#)
[![Built by: Axleta](https://img.shields.io/badge/Built%20by-Axleta-blue.svg)](https://github.com/axleta)

[Axleta - GitHub Repository Packer](https://packer.axleta.com/) is an interactive developer tool designed to streamline codebase ingestion for Large Language Models (LLMs) like Claude, ChatGPT, and Gemini. It parses repository structures, filters out build artifacts, and packages source files into clean, context-aware prompt buffers.

---

## ✨ Features

* **Automatic Directory Trees**: Generates visual, formatted repository maps for clear model orientation.
* **Structured XML Formatting**: Encapsulates files in isolated `<file path="...">` tags for precise LLM parsing.
* **Smart File Filtering**: Excludes binaries, lockfiles, dependency folders (`node_modules/`, `venv/`), and build assets automatically.
* **Secure Execution**: Operates directly with GitHub API token support for private repository access.
* **Zero-Overhead Processing**: Fast and lightweight execution context designed for instant prompt extraction.

## How features work?
* **Client-Side Security**: Source code parsing, file filtering, and prompt generation occur 100% locally in your browser, meaning your private code is never sent to third-party servers.
* **Extraction Modes**:
  * **Code Surgery Mode**: Automatically packs 100% of your application's raw logic (e.g., controllers, routes, core code) so an LLM can refactor or write new integrated hooks.
  * **AST Blueprint Mode**: Strips out inner code details while preserving structure, interface signatures, and class hierarchies, creating a lightweight map of your system.
* **Token Optimization**: Eliminates noise from your repo by stripping out bloated files like node modules, lock files, logs, and compiled assets before building the output.

## ✨ Demonstration
* **Interactive Demonstration**: About [Discover the Axleta Context Packer](https://youtu.be/sR0J1Kvbl2k)

## 🛠️ Tech Stack & Integrations

* **Frontend**: Responsive Single-Page Web Interface
* **API Ingestion**: GitHub REST & GraphQL APIs
* **Authentication & Backend**: Secure User Sessions & Managed Cloud Workflows
* **Target Platforms**: ChatGPT, Claude, Gemini, and custom LLM agent pipelines

---

## 🚀 Getting Started

### Prerequisites
* Any modern web browser (Chrome, Firefox, Safari, Edge).
* A [GitHub Personal Access Token](https://github.com/settings/tokens) (recommended to avoid API rate limits on larger repos).

### Quick Usage Guide

1. **Launch the Workspace**: Open [contex-packer](https://packer.axleta.com/) in your browser or visit the live hosted platform.
2. **Enter Repository URL**: Paste any public or private GitHub repository link with token. As an example below:
   ```text (https://github.com/owner/repository).
3. **Refer to the User Manual**: For more details read the [User Manual (https://packer.axleta.com/manual).
