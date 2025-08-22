# GitHub Copilot Instructions

A comprehensive guide of best practices, coding rules, and workflow automation for AI-assisted front-end development with GitHub Copilot. Focuses on React, Clean Code principles, accessibility (a11y), and more. Reference implementation for modern front-end projects.

> **Optimized for WebStorm and JetBrains IDEs**

## 📋 What's Included

This repository contains carefully curated GitHub Copilot instructions to enhance AI-assisted development:

### Core Configuration Files
- **Main Instructions** (`copilot-instructions.md`) - Generic workflow automation template to customize per project
- **Git Commit Guidelines** (`git-commit-instructions.md`) - JetBrains IDE-optimized commit conventions template
- **Reusable Prompts** (`prompts/`) - Template prompts for common development tasks

### Core Quality Instructions
- **Accessibility (a11y)** - WCAG 2.2 + French RGAA compliance
- **Performance Optimization** - Frontend, backend, and database best practices
- **Object Calisthenics** - Clean code and OOP principles

### AI Interaction Instructions  
- **Follow-up Questions** - 97% confidence threshold system
- **Meta Instructions** - Self-improving instruction handling
- **Beast Mode** - Autonomous problem-solving agent behavior

### Technology-Specific Instructions
- **React** - Modern React development patterns
- **Vitest** - Testing best practices with accessibility focus

## 🛠 How It Works

The repository is structured with multiple layers of configuration:

### Main Configuration
- `copilot-instructions.md` - Orchestrates the entire instruction system and defines workflow rules
- `git-commit-instructions.md` - Provides commit message standards optimized for JetBrains IDEs

### Instruction Files
Instructions are automatically applied based on file patterns:
- `**` - All files
- `*.ts`, `*.tsx` - TypeScript/React files
- `**/*.test.*` - Test files

Each instruction file includes pattern matching and specific guidelines optimized for JetBrains IDEs.

### Prompt Templates
The `prompts/` directory contains reusable prompt templates for common tasks:
- `open_pull_request.prompt.md` - Standardized pull request creation workflow

> **Note for JetBrains IDEs:** Currently, JetBrains IDEs do not support native prompt execution in Copilot Chat (feature is [in development](https://github.com/microsoft/copilot-intellij-feedback/issues/379)). To use prompts, run this command in Copilot Agent mode:
> 
> ```
> Read the file .github/prompts/open_pull_request.prompt.md and execute only the instructions it contains.
> ```

## 🚀 Getting Started

1. **Clone or fork** this repository
2. **Copy** `.github/` folder to your project
3. **Customize** instructions for your specific needs
4. **Enable** GitHub Copilot in WebStorm/JetBrains IDE

## 📚 Instruction Sources

This collection builds upon excellent work from the community:

- **Core Instructions**: [awesome-copilot](https://github.com/github/awesome-copilot)
  - `a11y.instructions.md`
  - `performance-optimization.instructions.md` 
  - `object-calisthenics.instructions.md`

- **Enhanced Instructions**: [SebastienDegodez/copilot-instructions](https://github.com/SebastienDegodez/copilot-instructions)
  - `follow-up-question.instructions.md`
  - `meta-instructions.instructions.md`

- **Custom Adaptations**: 
  - `beastmode.instructions.md` - Adapted from [awesome-copilot](https://github.com/github/awesome-copilot) chatmode for JetBrains
  - `react.instructions.md` - Custom React development guidelines
  - `vitest.instructions.md` - Testing with accessibility focus

## 🎯 Key Features

- **97% Confidence System** - AI asks clarifying questions before acting
- **JetBrains Optimized** - Instructions adapted for WebStorm and other JetBrains IDEs  
- **Accessibility First** - WCAG 2.2 + French RGAA compliance built-in
- **Performance Focused** - Optimization guidelines for all stack layers
- **React Specialized** - Modern React patterns and best practices

## 🤝 Contributing

Feel free to:
- Add new instruction files following the `.instructions.md` pattern
- Improve existing instructions with real-world feedback
- Share your JetBrains-specific optimizations

## 📄 License

MIT License - Adapt these instructions for your own development environment.
