# Contributing

Thanks for stopping by! This is a hobby studio, so contributions are
welcome but never expected. There is no formal review process.

## If you spot a bug or have an idea

Open an issue. A short description (and how to reproduce, if relevant)
is plenty.

## If you want to send a change

- Fork and branch off `main`.
- Keep it focused — one thing per PR is easier on everyone.
- Match the style of whatever file you're editing.

Don't worry about commit-message conventions or perfect changelogs —
I'm not running release engineering here. A "fixed thing" commit is
totally fine.

## Building the Go projects

```bash
go mod download
go build ./...
go test ./...
```

Each repo's README has anything project-specific.

Have fun. 🙂