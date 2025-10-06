# 📚 Academic Research Assistant 🤖

Welcome to **Academic Research Assistant**! This repository provides a collection of markdown files designed to supercharge your academic research workflow with AI-powered tools. Originally adapted from software development workflows, these tools are now optimized for literature reviews, research paper writing, and academic project management.

Stop wrestling with unstructured research processes and start guiding your AI research assistant step-by-step!

## ✨ The Core Idea

Conducting academic research with AI can sometimes feel overwhelming. This workflow aims to bring structure, clarity, and control to the research process by:

1. **Defining Research Scope:** Clearly outlining your research question and objectives with a Research Proposal Document.
2. **Detailed Planning:** Breaking down the research proposal into a granular, actionable task list.
3. **Iterative Research:** Guiding the AI to tackle one research task at a time, allowing you to review and approve each step.

This structured approach helps ensure the AI stays on track, makes it easier to organize literature, and gives you confidence in the research output.

## Workflow: From Research Idea to Completed Paper 💡➡️📄

Here's the step-by-step process using the `.md` files in this repository:

### 1️⃣ Create a Research Proposal Document

First, lay out the blueprint for your research project. A research proposal clarifies what you're studying, why it matters, and how you'll approach it.

You can create a research proposal directly within your AI tool of choice:

1. Ensure you have the `create-research-proposal.md` file from this repository accessible.
2. In your AI tool, initiate proposal creation:

    ```text
    Use @create-research-proposal.md
    Here's the research topic I want to explore: [Describe your research topic in detail]
    ```

### 2️⃣ Generate Your Research Task List from the Proposal

With your research proposal drafted (e.g., `MyResearch-Proposal.md`), the next step is to generate a detailed, step-by-step research plan.

1. Ensure you have `generate-research-tasks.md` accessible.
2. In your AI tool, use the proposal to create research tasks:

    ```text
    Now take @MyResearch-Proposal.md and create tasks using @generate-research-tasks.md
    ```
    *(Note: Replace `@MyResearch-Proposal.md` with the actual filename of the proposal you generated in step 1.)*

### 3️⃣ Examine Your Research Task List

You'll now have a well-structured research task list, often with tasks and sub-tasks, ready for the AI to start working on. This provides a clear roadmap for your research project.

### 4️⃣ Instruct the AI to Work Through Research Tasks (and Mark Completion)

To ensure methodical progress and allow for verification, we'll use `process-research-task-list.md`. This command instructs the AI to focus on one research task at a time and wait for your go-ahead before moving to the next.

1. Create or ensure you have the `process-research-task-list.md` file accessible.
2. In your AI tool, tell the AI to start with the first task (e.g., `1.1`):

    ```text
    Please start on task 1.1 and use @process-research-task-list.md
    ```
    *(Important: You only need to reference `@process-research-task-list.md` for the *first* task. The instructions within it guide the AI for subsequent tasks.)*

The AI will attempt the task and then prompt you to review.

### 5️⃣ Review, Approve, and Progress ✅

As the AI completes each research task, you review the work.

* If the work is satisfactory, simply reply with "yes" (or a similar affirmative) to instruct the AI to mark the task complete and move to the next one.
* If changes are needed, provide feedback to the AI to correct the current task before moving on.

You'll see a satisfying list of completed research milestones grow, providing a clear visual of your research project progressing!

## 🗂️ Files in this Repository

* **`create-research-proposal.md`**: Guides the AI in generating a Research Proposal Document for your academic project.
* **`generate-research-tasks.md`**: Takes a research proposal markdown file as input and helps the AI break it down into a detailed, step-by-step research task list.
* **`process-research-task-list.md`**: Instructs the AI on how to process the generated task list, tackling one research task at a time and waiting for your approval before proceeding. (This file also contains logic for the AI to mark tasks as complete).
* **`conduct-literature-review.md`**: Guides the AI in conducting a comprehensive literature review for a research topic.

## 🌟 Benefits

* **Structured Research:** Enforces a clear process from research question to completed paper.
* **Step-by-Step Verification:** Allows you to review and approve AI-generated research work at each small step, ensuring academic rigor and quality.
* **Manages Research Complexity:** Breaks down large research projects into smaller, digestible tasks for the AI, reducing the chance of it getting lost or generating unstructured, incomplete work.
* **Improved Reliability:** Offers a more dependable approach to leveraging AI for academic research compared to single, large prompts.
* **Clear Progress Tracking:** Provides a visual representation of completed research tasks, making it easy to see how much has been done and what's next.

## 🚀 Coming Soon Workflows

### 🔄 **Data Analysis Pipeline**
- Systematic data processing and analysis workflows

### 🔄 **Experiment Design & Execution**
- Protocol development and experimental task management

### 🔄 **Code Development & Implementation**
- Structured coding tasks and development processes

### 🔄 **Grant Proposal Writing**
- Funding application development and submission

### 🔄 **Thesis/Dissertation Writing**
- Long-form academic writing support

### 🔄 **Conference Presentation Preparation**
- Slide creation and presentation practice workflows

### 🔄 **Systematic Review Process**
- Comprehensive systematic review methodology

### 🔄 **Peer Review Process**
- Manuscript evaluation and feedback workflows

### 🔄 **Research Data Management**
- Data organization, documentation, and sharing protocols

### 🔄 **Research Ethics & Compliance**
- Ethical review preparation and compliance tracking

## Framework Structure

Each workflow follows a consistent three-step pattern:
1. **Planning Phase** - Outline and structure creation
2. **Task Generation** - Breaking down into actionable steps

### 🔄 **Research Project Management**
- Complete research lifecycle tracking and coordination

---

*This framework is designed to scale with additional academic workflows as needed.*

## 🛠️ How to Use

1. **Clone or Download:** Get these `.md` files into your research project or a central location where your AI tool can access them.
   ```bash
   git clone https://github.com/snarktank/ai-dev-tasks.git
   ```
2. **Follow the Workflow:** Systematically use the `.md` files in your AI assistant as described in the workflow above.
3. **Adapt and Iterate:**
    * Feel free to modify the prompts within the `.md` files to better suit your specific research needs or academic style.
    * If the AI struggles with a task, try rephrasing your initial research description or breaking down tasks even further.

## Tool-Specific Instructions

### Cursor

Cursor users can follow the workflow described above, using the `.md` files directly in the Agent chat:

1. Ensure you have the files from this repository accessible
2. In Cursor's Agent chat, reference files with `@` (e.g., `@create-research-proposal.md`)
3. Follow the 5-step workflow as outlined above

### Claude Code

To use these tools with Claude Code:

1. **Copy files to your repo**: Copy the three `.md` files to a subdirectory in your project (e.g., `/academic-research-assistant`)

2. **Reference in CLAUDE.md**: Add these lines to your project's `./CLAUDE.md` file:
   ```
   # Academic Research Assistant
   Use these files when I request structured academic research using research proposals:
   /academic-research-assistant/create-research-proposal.md
   /academic-research-assistant/generate-research-tasks.md
   /academic-research-assistant/process-research-task-list.md
   ```

3. **Create custom commands** (optional): For easier access, create these files in `.claude/commands/`:
   - `.claude/commands/create-research-proposal.md` with content:
     ```
     Please use the structured workflow in /academic-research-assistant/create-research-proposal.md to help me create a research proposal for a new project.
     ```
   - `.claude/commands/generate-research-tasks.md` with content:
     ```
     Please generate research tasks from the proposal using /academic-research-assistant/generate-research-tasks.md
     If not explicitly told which proposal to use, generate a list of proposals and ask the user to select one under `/research` or create a new one using `create-research-proposal.md`:
     - assume it's stored under `/research` and has a filename starting with `[n]-proposal-` (e.g., `0001-proposal-[topic].md`)
     - it should not already have a corresponding task list in `/research` (e.g., `tasks-0001-proposal-[topic].md`)
     - **always** ask the user to confirm the proposal file name before proceeding
     Make sure to provide options in number lists so I can respond easily (if multiple options).
     ```
   - `.claude/commands/process-research-task-list.md` with content:
     ```
     Please process the research task list using /academic-research-assistant/process-research-task-list.md
     ```

   Make sure to restart Claude Code after adding these files (`/exit`).
   Then use commands like `/create-research-proposal` to quickly start the workflow.

### Other Tools

For other AI-powered IDEs or CLIs:

1. Copy the `.md` files to your project
2. Reference them according to your tool's documentation
3. Follow the same workflow principles

## 💡 Tips for Success

* **Be Specific:** The more context and clear instructions you provide (both in your initial research description and any clarifications), the better the AI's output will be.
* **Use a Capable Model:** The free version of Cursor currently uses less capable AI models that often struggle to follow the structured instructions in this workflow. For best results, consider upgrading to the Pro plan to ensure consistent, accurate task execution.
* **Correct File Tagging:** Always ensure you're accurately tagging the proposal filename (e.g., `@MyResearch-Proposal.md`) when generating tasks.
* **Patience and Iteration:** AI is a powerful tool, but it's not magic. Be prepared to guide, correct, and iterate. This workflow is designed to make that iteration process smoother.

## 🤝 Contributing

Got ideas to improve these `.md` files or have new ones that fit this workflow? Contributions are welcome!

Please feel free to:

* Open an issue to discuss changes or suggest new features.
* Submit a pull request with your enhancements.

---

Happy AI-assisted researching!
