# 📚 AI-Powered Academic Research Assistant 🤖

Welcome to the **Academic Research Assistant** - a comprehensive framework designed to transform how you conduct academic research with AI. This repository provides structured workflows that break down complex research projects into manageable, verifiable steps, ensuring academic rigor and quality throughout your research journey.

## 🎯 What This Framework Solves

Academic research with AI often leads to:
- **Unstructured outputs** that are hard to organize
- **Overwhelming complexity** when tackling large projects
- **Lack of verification** for AI-generated content
- **Inconsistent quality** across different research phases

This framework addresses these challenges by providing **systematic, step-by-step workflows** that guide AI assistants through the entire research lifecycle.

## 🏗️ Framework Architecture

Each research workflow follows a consistent three-phase pattern:

### Phase 1: Planning & Structuring
- Create comprehensive outlines and proposals
- Define research scope and methodology
- Establish clear objectives and deliverables

### Phase 2: Task Generation & Breakdown
- Convert proposals into actionable task lists
- Create hierarchical task structures with dependencies
- Establish clear success criteria for each task

### Phase 3: Iterative Execution & Verification
- Process tasks one at a time
- Human-in-the-loop review process
- Progress tracking and milestone completion

## 📋 Complete Research Workflow Directory

### 🔍 **Literature Review** (`/literature-review/`)
Comprehensive literature analysis and synthesis:
- **`1.conduct-literature-review.md`** - Systematic approach to literature search and analysis
- **`2.generate-research-tasks.md`** - Break down literature review into manageable tasks
- **`3.process-research-task-list.md`** - Execute literature review tasks systematically

### 📝 **Paper Writing** (`/paper-writing/`)
From outline to completed manuscript:
- **`1.create-paper-outline.md`** - Structure your paper with clear sections
- **`2.generate-paper-writing-tasks.md`** - Convert outline into writing tasks
- **`3.process-paper-writing-task-list.md`** - Write and refine paper sections iteratively

### 🗂️ **Research Project Management** (`/research-project-management/`)
Complete research lifecycle management:
- **`1.create-research-project-plan.md`** - Comprehensive project planning
- **`2.generate-research-project-tasks.md`** - Break down project into executable tasks
- **`3.process-research-project-task-list.md`** - Execute project tasks with oversight

### 📄 **Research Proposal Development** (`/research-proposal/`)
From research idea to formal proposal:
- **`1.create-research-proposal.md`** - Develop structured research proposals
- **`2.generate-research-tasks.md`** - Generate research tasks from proposals
- **`3.process-research-task-list.md`** - Execute research tasks methodically

### 📊 **Data Analysis** (`/data-analysis/`)
Systematic data processing and statistical analysis:
- **`1.define-analysis-plan.md`** - Plan statistical analysis approach
- **`2.generate-analysis-tasks.md`** - Create analysis task list
- **`3.process-analysis-task-list.md`** - Execute analysis tasks step-by-step

### 💾 **Data Management** (`/data-management/`)
Research data organization and documentation:
- **`1.create-data-plan.md`** - Design data management strategy
- **`2.generate-data-tasks.md`** - Generate data handling tasks
- **`3.process-data-task-list.md`** - Process data management tasks systematically

### 🔬 **Experiment Design** (`/experiment-design/`)
Protocol development and experimental validation:
- **`1.create-experiment-protocol.md`** - Create experimental protocols
- **`2.generate-experiment-tasks.md`** - Break down experiments into tasks
- **`3.process-experiment-task-list.md`** - Execute experimental tasks with oversight

### 💰 **Grant Proposals** (`/grant-proposals/`)
Funding application development:
- **`1.create-grant-outline.md`** - Structure grant proposals
- **`2.generate-grant-tasks.md`** - Generate grant writing tasks
- **`3.process-grant-task-list.md`** - Process grant writing tasks methodically

### 👥 **Peer Review** (`/peer-review/`)
Manuscript evaluation and feedback:
- **`1.create-review-plan.md`** - Plan review process
- **`2.generate-review-tasks.md`** - Create review tasks
- **`3.process-review-task-list.md`** - Execute review tasks systematically

### 🎤 **Presentation Preparation** (`/presentation-prep/`)
Conference and seminar presentation development:
- **`1.create-presentation-outline.md`** - Structure presentations
- **`2.generate-presentation-tasks.md`** - Generate presentation preparation tasks
- **`3.process-presentation-task-list.md`** - Process presentation tasks step-by-step

### ⚖️ **Research Ethics** (`/research-ethics/`)
Ethical review preparation and compliance:
- **`1.create-ethics-plan.md`** - Plan ethical considerations
- **`2.generate-ethics-tasks.md`** - Generate ethics-related tasks
- **`3.process-ethics-task-list.md`** - Process ethics compliance tasks

### 📚 **Thesis Writing** (`/thesis-writing/`)
Long-form academic writing support:
- **`1.create-thesis-outline.md`** - Structure thesis/dissertation
- **`2.generate-thesis-tasks.md`** - Generate thesis writing tasks
- **`3.process-thesis-task-list.md`** - Execute thesis writing tasks systematically

## 🚀 Getting Started: The Core Workflow

### Step 1: Define Your Research Scope

Start with a research proposal to establish clear boundaries and objectives:

```text
Use @create-research-proposal.md
Research Topic: [Your detailed research topic description]
```

### Step 2: Generate Actionable Task Lists

Convert your proposal into a detailed, step-by-step research plan:

```text
Now take @MyResearch-Proposal.md and create tasks using @generate-research-tasks.md
```

### Step 3: Execute with Oversight

Begin systematic task execution:

```text
Please start on task 1.1 and use @process-research-task-list.md
```

### Step 4: Review & Progress

For each completed task:
- **Review** the AI's work
- **Approve** with "yes" or provide feedback
- **Track** progress through completed milestones

## 🎯 Key Benefits

### ✅ **Quality Assurance**
- Human verification at every step
- Consistent academic standards
- Error detection and correction

### 📊 **Progress Visibility**
- Clear visual tracking of completed tasks
- Understanding of remaining work
- Confidence in research direction

### 🎪 **Complexity Management**
- Break down large projects into digestible chunks
- Maintain focus on current objectives
- Reduce cognitive overload

### 🔄 **Iterative Improvement**
- Continuous feedback integration
- Adaptive research research approach
- Quality enhancement through iteration

### 🎯 **Goal Alignment**
- Ensure AI stays on track with research objectives
- Maintain alignment with academic standards
- Consistent progress toward research goals

## 🛠️ Implementation Guide

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/snarktank/ai-dev-tasks.git
   ```

2. **Choose your workflow** based on your research phase
3. **Follow the three-phase pattern** for systematic execution

### Tool-Specific Instructions

#### **Cursor**
- Reference files directly in Agent chat using `@` syntax
- Follow the step-by-step workflow
- Provide clear, specific research descriptions

#### **Claude Code**

**Option A: Reference in CLAUDE.md**
```markdown
# Academic Research Assistant
Use these structured workflows for systematic research:
/literature-review/1.conduct-literature-review.md
/paper-writing/1.create-paper-outline.md
/research-project-management/1.create-research-project-plan.md
/research-proposal/1.create-research-proposal.md
```

**Option B: Custom Commands** (Recommended):

Create these files in `.claude/commands/`:

- **`.claude/commands/create-research-proposal.md`**
  ```
  Please use the structured workflow in /academic-research-assistant/create-research-proposal.md to help me create a research proposal for a new project.
  ```

- **`.claude/commands/generate-research-tasks.md`**
  ```
  Please generate research tasks from the proposal using /academic-research-assistant/generate-research-tasks.md
  ```

- **`.claude/commands/process-research-task-list.md`**
  ```
  Please process the research task list using /academic-research-assistant/process-research-task-list.md
  ```

#### **Other AI Tools**
- Copy the relevant `.md` files to your project
- Reference them according to your tool's documentation
- Follow the same workflow principles

## 💡 Best Practices for Success

### 🎯 **Be Specific and Detailed**
- Provide comprehensive research context
- Include relevant background information
- Specify academic standards and requirements

### 🔄 **Iterative Approach**
- Start with small, well-defined tasks
- Build complexity gradually
- Maintain quality through verification

### 🤖 **Model Selection**
- Use capable AI models (Pro plans recommended)
- Ensure consistent performance
- Monitor for quality degradation

### 📁 **File Management**
- Use consistent naming conventions
- Organize files by research phase
- Maintain clear version control

## 🔮 Future Enhancements

### 🎯 **Expanding Research Domains**
- Additional specialized workflows for specific disciplines
- Integration with research databases and tools
- Advanced collaboration features

## 🤝 Contributing & Community

We welcome contributions to enhance and expand this framework:

### 🎯 **How to Contribute**
- **New Workflows:** Propose additional research workflows
- **Improvements:** Enhance existing prompts and workflows
- **Documentation:** Improve guides and examples

### 📬 **Getting Involved**
- **Open Issues:** Discuss improvements or report problems
- **Pull Requests:** Submit enhancements directly
- **Discussion:** Share experiences and best practices

### 🐛 **Reporting Issues**
- Use GitHub Issues for bug reports
- Suggest new features or workflows
- Share successful implementations

## 📚 Additional Resources

### 📖 **Academic Standards**
- Ensure compliance with disciplinary conventions
- Maintain rigorous academic quality
- Follow ethical research practices

---

## 🎉 Ready to Transform Your Research?

This framework represents a paradigm shift in how we approach academic research with AI. By breaking down complex projects into verifiable steps, you gain:\n- **Control** over the research process
- **Confidence** in the quality of AI-generated work
- **Efficiency** through systematic execution
- **Quality** through continuous verification

**Start your structured research journey today!**

---

*Built by researchers, for researchers. This framework scales with your research needs.*

**Happy AI-assisted researching! 🎓✨
