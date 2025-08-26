# AI Engineering Crash Course

🚀 **Master AI Engineering with AI Hero's comprehensive crash course.** This repository contains all the code examples and exercises from our hands-on, practical AI engineering course available on [aihero.dev](https://aihero.dev).

Learn to build production-ready AI applications using the latest tools and techniques, including AI SDK v5 - the incredible TypeScript library that's becoming the standard for AI app development.

## 🎯 What You'll Master

This crash course will take you from AI engineering basics to advanced production patterns:

- **AI SDK v5 Fundamentals** - Understanding the modern AI development toolkit
- **Text Streaming** - Building real-time, responsive AI experiences
- **Tool Calling & Agents** - Creating AI applications that can use external tools and APIs
- **Message Parts** - Working with structured message components and data
- **Model Context Protocol (MCP)** - Integrating with external data sources and tools
- **File & Image Handling** - Processing and working with multimedia content
- **Custom Data Parts** - Building rich, interactive AI experiences with custom data
- **Message Metadata** - Adding context and tracking to your AI conversations

## 🚀 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/en/download) (version 22 or higher)
- [pnpm](https://pnpm.io/) (recommended) or npm/yarn/bun
- API keys for your preferred AI providers:
  - [OpenAI](https://platform.openai.com/api-keys) (GPT-4, GPT-3.5)
  - [Anthropic](https://console.anthropic.com/) (Claude)
  - [Google AI Studio](https://aistudio.google.com/apikey) (Gemini)

### Setup

1. **Clone this repository:**

```bash
git clone https://github.com/ai-hero-dev/ai-engineering-crash-course.git
cd ai-engineering-crash-course
```

2. **Install dependencies:**

```bash
pnpm install
```

3. **Configure your environment:**

```bash
cp .env.example .env
```

4. **Add your API keys to `.env`** and you're ready to start learning!

## 📚 Course Structure

Start by running `pnpm dev`:

```bash
pnpm dev
```

This will allow you to choose between the different course sections.

You can also run `pnpm exercise <exercise-number>` to jump to a specific exercise.

## 📁 Course Modules

```
exercises/
├── 01-basics/                    # AI Engineering fundamentals
│   ├── 01.1-what-is-the-ai-sdk/
│   ├── 01.2-choosing-a-model/
│   ├── 01.3-stream-text-to-terminal/
│   ├── 01.4-ui-message-streams/
│   ├── 01.5-stream-text-to-ui/
│   └── 01.6-system-prompts/
├── 02-agents/                    # Tool calling & agents
├── 03-advanced/                  # Advanced AI engineering patterns
└── 99-reference/                 # Reference implementations
```

## 🛠️ Learning Workflow

Each exercise follows this learning structure:

### `problem/` folder

- **Your coding playground** - Start here!
- Contains `readme.md` with detailed instructions
- Code files with `TODO` comments for you to implement

### `solution/` folder

- **Reference implementation** - Check when you're stuck
- Complete, working code for each exercise
- Great for comparing approaches and learning best practices

### `explainer/` folder

- **Deep dives** - Additional explanations and concepts
- Extended walkthroughs of complex topics
- Perfect for reinforcing your understanding

## 🎥 Complete Course Experience

This repository is the companion to our comprehensive AI engineering crash course on [aihero.dev](https://aihero.dev). The full course includes:

- **Step-by-step video walkthroughs** of every exercise
- **Deep dives** into AI engineering concepts and patterns
- **Best practices** for production AI applications
- **Real-world examples** and use cases

## 🆕 Modern AI Engineering Tools

This crash course covers the latest tools and techniques in AI engineering, including AI SDK v5's groundbreaking features:

- **Enhanced Streaming** - Better real-time experiences
- **Improved Multi-Provider Support** - Seamless switching between AI providers
- **Advanced Memory Patterns** - More sophisticated state management
- **Better Type Safety** - Enhanced TypeScript integration
- **Simplified Agent Creation** - Easier multi-agent workflows
- **Production-Ready Tools** - Built-in testing and monitoring capabilities

## 🤝 Getting Help

1. **Check the solution** - Each exercise has a completed version
2. **Verify your setup** - Ensure API keys and dependencies are correct
3. **Watch the course** - Full explanations available on [aihero.dev](https://aihero.dev)

Ready to become an AI engineering expert? Let's start building the future! 🚀
