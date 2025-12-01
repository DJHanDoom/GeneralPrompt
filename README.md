<h1><img src="https://github.com/DJHanDoom/GeneralPrompt/blob/main/assets/icon.png" width=55px> # General Prompt</h1>
> 🖥️ Desktop **Live Demo:** https://djhandoom.github.io/GeneralPrompt/
<a href="https://djhandoom.github.io/GeneralPrompt/"> <img src="https://github.com/DJHanDoom/GeneralPrompt/blob/main/bgBIG.png" width=800px></a>
</br> 
**General Prompt** is a powerful, local-first tool designed to generate structured, high-quality prompts for AI agents. It provides a specialized interface for configuring agent personas, context, and task details to ensure precise and robust AI outputs.

* **⚡ Local-First Architecture:** Compiles prompts locally within your browser, ensuring privacy and speed without unnecessary API calls for the assembly phase.
* **🧠 Automated Context Mapping:** Uses AI to scan your project and generate a structural JSON mind map (Pages, Tabs, Functions, UI Elements).
* **TB Smart Templating & Shortcuts:** Map project-specific terms to keyboard shortcuts for rapid dynamic expansion.
* **🎛️ Visual Prompt Composition:** Interactive dropdowns and visual selection of project components to populate prompts instantly.
* **✨ AI Refinement:** Integrated options to automatically optimize prompts for brevity or detail (Concise vs. Verbose) using AI.
* **💾 Project & Prompt Management:** Save, export, and manage multiple project configurations and prompt libraries.

Since both DESKTOP and MOBILE versions are built as single-file HTML applications, no installation or build process is required.
Just access: https://djhandoom.github.io/GeneralPrompt (desktop)
or, to run locally:
1.  **Download** the repository.
2.  **Open** `General Prompt DESKTOPv4.1.html` or `genPrompMOBILEv4.9.html` in your preferred web browser.
3.  **Start Generating**: Configure your agent, add context, and describe your task to generate optimized prompts.

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

**GeneralPrompt** is a streamlined, single-page HTML application designed to professionalize and accelerate the prompt engineering process. 

By leveraging the **Gemini API** for initial project mapping and a robust **Local Interface** for prompt construction, the tool enables developers to create highly detailed, context-aware prompts without repetitive manual input.

---

## 🛠️ Workflow

### 1. Installation & Setup
* Access the interface via the [GeneralPrompt GitHub Repository](https://github.com/DJHanDoom/GeneralPrompt).
* Click the **"Install"** button within the tool to generate a custom "Installation Prompt" tailored for your codebase.

### 2. Project Mind Mapping (Gemini API)
* Copy the generated "Installation Prompt".
* Paste and execute it within your project's IDE AI Assistant (e.g., Gemini Code Assist).
* **Outcome:** The AI analyzes your file structure and generates a comprehensive **JSON Mind Map** covering your project's architecture (files, actions, UI components).

### 3. Data Import & Visualization
* Navigate to the **Data Tab** in GeneralPrompt.
* Import the JSON generated in step 2.
* The tool will visualize your project's architecture, making every component selectable for future prompts.

### 4. Prompt Composition
* **Interactive Selection:** Click on items in the visual map or use dropdowns to insert specific components (e.g., "Login Page", "Submit Action") into your prompt.
* **Context Injection:** Fill in structured fields like "Current Problem," "Desired Solution," and "File References."
* **Local Compilation:** The tool instantly assembles these inputs into a coherent, structured prompt.

### 5. Acceleration via Shortcuts
* **Tag Mapping:** Define custom keywords (e.g., `/auth`) that map to previous prompts or project terms.
* **Dynamic Expansion:** Type your shortcuts in the editor to auto-expand them into full instructions or code references, ensuring consistency across requests.

### 6. AI Refinement (Optional)
* Use the **Refine** feature to let the AI polish your draft.
* Select between **Concise** (token-efficient) or **Detailed** (context-heavy) outputs depending on the complexity of the task.

---

## 📂 Project Structure

- `General Prompt DESKTOPv4.1.html`: The main desktop application.
- `genPrompMOBILEv4.9.html`: The mobile-optimized application.
- `assets/`: Contains icons and other static resources.
- `android/`: (Work in Progress) A Progressive Web App (PWA) version with a modern component-based architecture.

## 🛠️ Technologies

- **HTML5 / CSS3 / JavaScript**: Built with standard web technologies for maximum compatibility and performance.
- **Local Storage**: Uses the browser's local storage for data persistence.
- **No External Dependencies**: Runs entirely offline without needing a backend server.

## 💻 Technical Details

* **Stack:** Single-Page Application (HTML/JS/CSS).
* **Integration:** Gemini API (for initial context analysis).
* **Data Format:** JSON (Project Structure & Mind Maps).
* **Privacy:** Prompt assembly and management are handled locally via JavaScript.

## 🎯 Use Cases

* **Complex Refactoring:** When you need to provide an LLM with specific context about multiple files and functions without manually copy-pasting code.
* **Standardization:** Ensuring all developers on a team use the same structure and terminology when querying AI assistants.
* **Rapid Prototyping:** Quickly iterating on features by referencing UI elements and actions defined in the project map.

---

_Managed and maintained by [DJHanDoom](https://github.com/DJHanDoom)._
