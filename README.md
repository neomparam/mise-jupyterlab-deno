# mise-jupyterlab-deno

🚀 A template for running [Deno](https://deno.land) inside [JupyterLab](https://jupyter.org), managed with [mise](https://mise.jdx.dev).

Quickly scaffold your own Deno-powered JupyterLab environment using this template and [`degit`](https://github.com/Rich-Harris/degit).

---


## 📦 Features

- 🧪 Run Deno in JupyterLab notebooks
- 🛠 Environment managed via `mise.toml`
- ✨ Minimal and reproducible setup
- 💻 Supports TypeScript & JavaScript via Deno kernel

---

## 🛠 Requirements

- [mise](https://mise.jdx.dev) (`curl https://mise.run | bash`)
- [Node.js](https://nodejs.org/) (for using `npx degit`)

---

## ⚙️ Quick Start

```bash
pnpm dlx degit neomparam/mise-jupyterlab-deno
cd mise-jupyterlab-deno

mise trust
mise run setup

mise run lab
```

---

## 📓 Usage

1. In JupyterLab, click “Notebook” → “Deno” to create a new notebook.
2. Write TypeScript or JavaScript.
3. Run and enjoy Deno-powered notebooks!

---

## 📄 License

MIT