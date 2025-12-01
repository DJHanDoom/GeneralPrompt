<h1><img src="https://github.com/DJHanDoom/GeneralPrompt/blob/main/assets/icon.png" width=55px> # General Prompt</h1>
> 🖥️ Desktop **Live Demo:** https://djhandoom.github.io/GeneralPrompt/
<img src="https://github.com/DJHanDoom/GeneralPrompt/blob/main/bgBIG.png" width=800px>
> 
**General Prompt** is a powerful, local-first tool designed to generate structured, high-quality prompts for AI agents. It provides a specialized interface for configuring agent personas, context, and task details to ensure precise and robust AI outputs.

This repository contains two main versions of the tool:
- **Desktop Version**: A full-featured IDE-like experience. > https://github.com/DJHanDoom/GeneralPrompt/blob/main/General%20Prompt%20DESKTOPv4.1.html
- **Mobile Version**: A responsive, touch-optimized interface for on-the-go prompt generation. > https://github.com/DJHanDoom/GeneralPrompt/blob/main/genPrompMOBILEv4.9.html

## 🖥️ Desktop Version
**File:** `General Prompt DESKTOPv4.1.html`

The Desktop version offers a comprehensive workspace modeled after modern IDEs (like VS Code).

### Key Features
- **Sidebar Navigation**: Quick access to Generator, Library, Data, and About tabs.
- **Agent Configuration**:
  - **Persona Selection**: Choose from predefined personas (e.g., Senior React Engineer, UI/UX Designer).
  - **Fine-Tuning Sliders**: Adjust Creativity vs. Precision, Concise vs. Detailed, and Quick vs. Robust.
- **Context Management**:
  - **Tagging System**: Easily add context tags for Page, Tab, Action, and Tool.
  - **Glossary**: Define domain-specific terms (Data, UI, Verbs) that are automatically explained to the AI.
- **Task Definition**: Dedicated fields for "Current Situation" and "Ideal Situation" with support for file targeting and task types (Bugfix, Feature, Refactor).
- **Library**: Save and organize your best prompts for reuse.
- **Local Storage**: Your state is automatically saved locally, so you never lose your work.

## 📱 Mobile Version
**File:** `genPrompMOBILEv4.9.html`

The Mobile version retains the core power of the Desktop version but is reimagined for smaller screens and touch interaction.

### Key Features
- **Responsive Layout**: A fluid design that adapts to your device's screen size.
- **Collapsible Sidebar**: Maximizes screen real estate for the editor while keeping tools accessible.
- **Touch-Optimized Controls**: Larger touch targets for buttons and toggles.
- **Split View**: Adjustable split view for comparing Original vs. Refined prompts.
- **Mobile Toolbar**: A streamlined toolbar for quick actions.
- **Insert Mode**: Toggle to insert items directly at the cursor position.

## 🚀 Getting Started

Since both versions are built as single-file HTML applications, no installation or build process is required.

1.  **Download** the repository.
2.  **Open** `General Prompt DESKTOPv4.1.html` or `genPrompMOBILEv4.9.html` in your preferred web browser.
3.  **Start Generating**: Configure your agent, add context, and describe your task to generate optimized prompts.

## 📂 Project Structure

- `General Prompt DESKTOPv4.1.html`: The main desktop application.
- `genPrompMOBILEv4.9.html`: The mobile-optimized application.
- `assets/`: Contains icons and other static resources.
- `android/`: (Work in Progress) A Progressive Web App (PWA) version with a modern component-based architecture.

## 🛠️ Technologies

- **HTML5 / CSS3 / JavaScript**: Built with standard web technologies for maximum compatibility and performance.
- **Local Storage**: Uses the browser's local storage for data persistence.
- **No External Dependencies**: Runs entirely offline without needing a backend server.
