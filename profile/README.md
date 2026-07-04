# CodefyUI

CodefyUI is a visual, node-based deep learning platform for education, experimentation, and workflow-driven model building. It lets users design pipelines in the browser by dragging nodes onto a canvas, connecting data flow, running graphs, and inspecting each step of CNN, RNN, Transformer, reinforcement learning, and data processing workflows.

Our goal is to make machine learning more observable, interactive, and teachable, not just hidden inside source code.

## Repositories

| Repository | Description | Technology / Type |
|---|---|---|
| [CodefyUI](https://github.com/CodefyUI/CodefyUI) | The core CodefyUI project. It provides a browser-based visual node editor with drag-and-drop nodes, type-safe connections, real-time validation, WebSocket execution, Teaching Inspector, example workflows, plugin management, model file management, and a CLI graph runner. It is designed for teaching, demonstrating, and experimenting with deep learning pipelines. | Python, FastAPI, PyTorch, React, TypeScript |
| [CodefyUI-Plugin-Graph-Copilot](https://github.com/CodefyUI/CodefyUI-Plugin-Graph-Copilot) | An AI chat assistant plugin for CodefyUI. It adds a floating chat panel to the editor so users can generate, tune, and improve node graphs with natural language. It supports multiple LLM providers, file attachments, conversation history, and direct canvas edits through validated tool calls. | JavaScript, React plugin |
| [CodefyUI-Plugin-Official](https://github.com/CodefyUI/CodefyUI-Plugin-Official) | The official starter template for CodefyUI plugin packs. It includes a complete example manifest, sample nodes, example workflows, assets, tests, and frontend extension scaffolding so developers can fork it and publish their own plugins. | JavaScript, Python plugin template |
| [CodefyUI-OJ](https://github.com/CodefyUI/CodefyUI-OJ) | An Online Judge system designed to work with CodefyUI. Students build computation graphs locally with CodefyUI, export `graph.json`, and upload it to the judge, where the server executes and grades submissions inside a Docker sandbox. It supports student, teacher, and admin roles, problem management, contests, leaderboards, and hidden tests. | Python, FastAPI, Docker, Online Judge |
| [.github](https://github.com/CodefyUI/.github) | The GitHub organization profile repository for CodefyUI. It maintains the public organization homepage, repository overview, and community entry points. | Organization profile |

## Ecosystem

- **Core platform**: `CodefyUI` handles visual graph editing, execution, inspection, and teaching-oriented visualization.
- **AI collaboration**: `CodefyUI-Plugin-Graph-Copilot` helps users create and edit graphs through conversation.
- **Plugin development**: `CodefyUI-Plugin-Official` provides the foundation for third-party nodes and editor tools.
- **Education and grading**: `CodefyUI-OJ` brings CodefyUI graphs into assignments, practice, and contest evaluation workflows.

## Links

- Documentation: [docs.codefyui.com](https://docs.codefyui.com/)
- Core repository: [github.com/CodefyUI/CodefyUI](https://github.com/CodefyUI/CodefyUI)
- Graph Copilot docs: [codefyui.github.io/CodefyUI-Plugin-Graph-Copilot](https://codefyui.github.io/CodefyUI-Plugin-Graph-Copilot/)