# Contributing to Wrench-Studio projects

Thank you for your interest in contributing! 🎉
Contributions of all sizes are welcome — bug reports, feature ideas,
documentation fixes, and pull requests.

## 🐛 Reporting bugs

1. Search the repository's **Issues** page first to make sure it hasn't
   already been reported.
2. If it's a new bug, open an issue and include:
   - A clear, descriptive title
   - Steps to reproduce
   - Expected vs. actual behavior
   - Your environment (OS, runtime version, relevant config)
   - Logs or screenshots if helpful

## 💡 Requesting features

- Open an issue with the `enhancement` label (or just describe it clearly).
- Explain the **use case**, not just the solution — design discussions are
  easier when the goal is clear.

## 🔀 Submitting a pull request

1. **Fork** the repository and create a new branch:
   ```bash
   git checkout -b feature/short-description
   ```
2. **Make your changes**
   - Keep the scope focused — one PR per concern is easier to review.
   - Match the existing code style and conventions of the repo.
   - Update documentation / README when behavior changes.
   - Add or update tests when reasonable.
3. **Test locally** before pushing — make sure nothing existing breaks.
4. **Write a good commit message** — see the [Conventional Commits](https://www.conventionalcommits.org/)
   style where possible (e.g. `feat: add foo`, `fix: handle nil pointer`).
5. **Open a pull request** against the upstream `main` branch.
   - Describe **what** changed and **why**.
   - Reference any related issue numbers (`Closes #123`).
   - Add screenshots for UI changes.

## 📦 Development setup

Most projects in this organization are written in **Go**, with some
supporting tooling. To work on a Go project:

```bash
# Install Go (recommended): https://go.dev/dl/
go version    # confirm Go is installed

# Clone and build
git clone https://github.com/Wrench-Studio/<repo-name>.git
cd <repo-name>
go mod download
go build ./...
go test ./...
```

For project-specific build instructions, see the README inside that
repository.

## 📜 Code of Conduct

By participating, you are expected to follow our
[`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md). Please read it before
interacting with the community.

## 🔒 Reporting security issues

**Do not** open a public issue for security vulnerabilities. Instead,
follow the process in [`SECURITY.md`](./SECURITY.md).

## ❓ Questions?

Open an issue with the `question` label, or check
[`SUPPORT.md`](./SUPPORT.md) for other ways to get help.