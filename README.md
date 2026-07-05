# LaraFlow

Modern visual integration and automation platform.

Build workflows visually using nodes, connections and real-time execution.

---

# Features

- Visual flow editor
- Drag and drop interface
- Real-time execution
- Payload inspector
- Debug tools
- Flow versioning
- Custom nodes
- Shared resources
- AI-ready architecture

---

# Preview

![Editor](./../../public/img/laraflow.png)

---

# Getting Started

## Create a Project

```bash
laraflow new my-project
```

Generated structure:

```txt
my-project/
├── .laraflow/
├── src/
│   ├── main/
│   └── shared/
│       └── global.json
```

---

# Running a Project

```bash
laraflow start
```

Or open the project directly from the desktop application.

---

# Project Structure

| Folder | Description |
|---|---|
| `.laraflow` | Internal engine metadata |
| `src/main` | Main flows |
| `src/shared` | Shared resources |
| `global.json` | Global variables/configuration |

---

# Example Flow

```txt
Flow
      ↓
HTTP Request
      ↓
Transform
      ↓
Logger
```

---

# Architecture

LaraFlow uses:

- Embedded Laravel runtime
- Embedded PHP runtime
- Vue-based visual editor
- Graph execution engine
- Real-time event system

---

# Philosophy

LaraFlow is designed to hide infrastructure complexity and let developers focus only on workflow logic.

No PHP setup.
No Laravel setup.
No server configuration.

Just create flows.

---

# Roadmap

- [ ] Marketplace
- [ ] Plugin SDK
- [ ] Cloud sync
- [ ] Team collaboration
- [ ] AI flow generation
- [ ] Git integration
- [ ] Distributed execution
- [ ] Multi-runtime support

---

# License

MIT
