# n8n Workflows

A collection of production-ready [n8n](https://n8n.io) automation workflows.

## Workflows

| Workflow | Description |
|----------|-------------|
| [BoilDocs](./boildocs/) | Turn technical documentation into concise, structured, and actionable developer notes via an LLM |

---

## Getting Started

1. **Import a workflow** — open n8n, go to *Workflows → Import from file*, and select the `.json` file from the workflow folder.
2. **Configure credentials** — each workflow's `README.md` lists the services and credentials it requires.
3. **Activate** — toggle the workflow on and test with the provided instructions.

## Structure

```
n8n-workflows/
└── boildocs/                       # BoilDocs workflow
    ├── BoilDocs - Documentation Summarizer.json
    ├── README.md
    └── screenshot.png
```

## Contributing

Pull requests are welcome! When adding a workflow, please include:

- The exported `.json` file
- A `README.md` describing what it does, required credentials, inputs, and outputs
- A `screenshot.png` showing the workflow canvas

## License

MIT
