# GitBrowse

> A modern, intuitive web interface for searching GitHub repositories and projects, built with [Svelte](https://svelte.dev/) and powered by [`sv`](https://github.com/sveltejs/cli).

## Overview

GitBrowse enables you to quickly search for any public GitHub repository or project and view all relevant details, such as repository status, stars, forks, issues, and contributors. If you want to explore a repository in depth, simply click and you'll be redirected to the repository on GitHub.

## Features

- 🔍 **Repository Search:** Find any public GitHub repository or project by name or keyword
- 📊 **Repository Details:** Instantly view repository status, stars, forks, open issues, main language, and more
- 👥 **Contributors & Activity:** See key contributors and latest activity snapshots
- 🔗 **Direct GitHub Access:** Click any listed repository to be redirected to its GitHub page for in-depth exploration
- 🌟 **Responsive UI:** Fast, accessible, and mobile-friendly interface

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/), [pnpm](https://pnpm.io/), or [yarn](https://yarnpkg.com/)
- [Bun](https://bun.sh/) (optional, for ultra-fast install and run)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/gitbrowse.git
   cd gitbrowse
   ```

2. **Install dependencies:**
    - With **npm**:
      ```bash
      npm install
      ```
    - Or with **pnpm**:
      ```bash
      pnpm install
      ```
    - Or with **yarn**:
      ```bash
      yarn install
      ```
    - Or with **Bun** (optional, ultra-fast):
      ```bash
      bun install
      ```

### Running the Development Server

Start the local development server:

- With **npm**:
  ```bash
  npm run dev
  ```
- Or with **pnpm**:
  ```bash
  pnpm dev
  ```
- Or with **yarn**:
  ```bash
  yarn dev
  ```
- Or with **Bun**:
  ```bash
  bun run dev
  ```

Open your browser to [http://localhost:5173](http://localhost:5173) (or as indicated in your terminal).

### Building for Production

To create a production build:

- With **npm**:
  ```bash
  npm run build
  ```
- Or with **pnpm**:
  ```bash
  pnpm build
  ```
- Or with **yarn**:
  ```bash
  yarn build
  ```
- Or with **Bun**:
  ```bash
  bun run build
  ```

Preview the built app locally:

```bash
npm run preview
# or
pnpm preview
# or
yarn preview
# or
bun run preview
```

> To deploy your app, you may need to install a [SvelteKit adapter](https://svelte.dev/docs/kit/adapters) for your target environment.

## Configuration

GitBrowse uses the public GitHub API. For increased rate limits and private repo access, create a `.env` file and add your [GitHub personal access token](https://github.com/settings/tokens):

```
VITE_GITHUB_TOKEN=your_token_here
```

## Contributing

1. Fork this repository
2. Create a new branch: `git checkout -b feature/my-feature`
3. Make your changes and commit: `git commit -am 'Add new feature'`
4. Push to your branch: `git push origin feature/my-feature`
5. Open a pull request

All contributions are welcome! Please open issues for bugs or feature requests.

## License

Licensed under the [Apache License, Version 2.0](LICENSE).

---

Made with ❤️ using [Svelte](https://svelte.dev/) and [`sv`](https://github.com/sveltejs/cli).