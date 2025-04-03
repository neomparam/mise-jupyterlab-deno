# mise-jupyterlab-deno

🚀 A minimal template for running Deno inside JupyterLab, managed with mise.

This template sets up JupyterLab and the Deno kernel using mise and a mise.toml configuration — no global installs, no clutter.

## 📦 Features
- 🧪 Run Deno in JupyterLab notebooks
- 📁 Minimal and reproducible setup
- 🛠 Managed entirely with mise.toml
- 💻 Supports TypeScript & JavaScript via Deno

## 🛠 Requirements
- mise installed (curl https://mise.run | bash)

## ⚙️ Setup
```sh
git clone https://github.com/your-username/mise-jupyterlab-deno.git
cd mise-jupyterlab-deno

mise trust
mise run setup

mise run lab
```

## 🧪 Usage
1. In JupyterLab, click “Notebook” → “Deno” to create a new notebook.
2. Write TypeScript or JavaScript.
3. Run and enjoy Deno-powered notebooks!

## 📄 License

MIT