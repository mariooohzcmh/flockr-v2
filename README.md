# flockr-v2

Go CLI that organizes a messy folder by file extension

Built for my own use; public in case it helps someone.

## Highlights

- Skips hidden files and folders by default
- Groups files into folders by extension
- Dry-run prints the plan before moving anything
- Single static binary, no runtime deps

## How to use

```bash
./bin/flockr-v2 ~/Downloads --dry-run
./bin/flockr-v2 ~/Downloads
```

## Getting started

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT. Do whatever you want.
