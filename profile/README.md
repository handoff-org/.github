

### Private research you can prove.

**handoff** builds local-first AI tools for researchers, research engineers, labs, and companies that need privacy, provenance, and reproducibility — not just faster text generation.

Our flagship project is [`handoff`](https://github.com/IParraMartin/handoff): a terminal-native AI research companion that reads literature, runs experiments, writes papers, tracks claims, and helps teams transfer research context without leaking private work.

---

## What we believe

Modern research tools should help people move faster **without making their work less trustworthy**.

That means:

- **Local-first by default** — unpublished ideas, data, drafts, and experiment logs should stay on your machine.
- **Evidence over vibes** — claims should be linked to citations, runs, metrics, and decisions.
- **Reproducibility as a workflow** — every result should have a trail.
- **Research memory that survives** — future-you, collaborators, students, PIs, reviewers, and teams should be able to pick up the work.
- **Terminal-native power** — serious tools should fit into real developer and research workflows.

---

## Flagship project

### [`handoff`](https://github.com/IParraMartin/handoff)

> A local-first AI research companion that lives in your terminal.

`handoff` helps you:

- Search and read research literature
- Ingest papers and maintain local research notes
- Run experiments from a project workspace
- Track runs, metrics, outputs, and decisions
- Draft and edit LaTeX papers
- Sync only the paper folder to Overleaf
- Maintain a claim ledger for supported, weak, and unsupported claims
- Generate handoff packets for future self, collaborators, reviewers, or teams
- Use local models by default through Ollama, llama.cpp, MLX, or self-hosted vLLM

```bash
npm install -g ownhandoff
handoff
```

Linux and macOS installer:

```bash
curl -fsSL https://raw.githubusercontent.com/IParraMartin/handoff/main/install.sh | bash
```

---

## Product pillars

### Read

Find, inspect, summarize, and cite relevant literature while keeping project notes local.

### Run

Create and execute experiments in a structured project workspace with logged outputs and reproducible trails.

### Write

Draft and revise LaTeX papers directly from the terminal, with bibliography support and Overleaf sync boundaries.

### Remember

Maintain a project notebook, claim ledger, run history, and handoff packet so research state is never lost.

---

## Why local-first matters

Research often contains:

- Unpublished ideas
- Private drafts
- Proprietary data
- Sensitive experiments
- Internal reports
- Reviewer responses
- Patent-relevant work
- Company or lab IP

`handoff` is designed so cloud usage is explicit, visible, and optional. The default path is local inference and local files.

---

## Who `handoff` is for

- Graduate students and PhD researchers
- Research engineers
- Independent researchers
- AI and ML labs
- R&D teams
- Privacy-sensitive companies
- Anyone writing papers, running experiments, or maintaining research artifacts

---

## Design principles

```text
private by default
transparent by design
local before cloud
evidence before polish
small tools, strong guarantees
human control, agent assistance
```

---

## Organization roadmap

We are building an ecosystem around private, reproducible research workflows.

Potential repositories:

| Repository | Purpose |
|---|---|
| `handoff` | Main terminal AI research companion |
| `handoff-docs` | Documentation, guides, and examples |
| `handoff-skills` | Reusable research workflows and skill packs |
| `handoff-templates` | Paper, experiment, and project templates |
| `handoff-examples` | Example research workspaces and demos |

---

## Suggested workflows

### Start a project

```bash
handoff
/project new Memory and Attention
```

### Check a claim

```text
/research transformers need positional encodings
```

### Start a paper

```text
Start the paper.
```

### Audit the draft

```text
/audit-paper
/claims
/unsupported
```

### Generate a handoff packet

```text
/handoff --for-me
```

---

## Brand promise

Generic AI tools help you produce more output.

**handoff helps you produce research you can defend.**

---

## Contributing

We welcome thoughtful contributions that improve local-first research workflows, model performance on laptops, terminal UX, reproducibility, privacy, and scientific provenance.

Good contribution areas:

- Local model performance
- Tool-use reliability
- Ink/TUI polish
- Paper and citation workflows
- Experiment provenance
- Claim auditing
- Docs and examples
- Research workflow templates

---

## Links

- Main project: [`IParraMartin/handoff`](https://github.com/IParraMartin/handoff)
- npm package: [`ownhandoff`](https://www.npmjs.com/package/ownhandoff)
- Command: `handoff`

---

<p align="center">
  <strong>Private research you can prove.</strong>
</p>
