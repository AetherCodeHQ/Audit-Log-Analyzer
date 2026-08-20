# Audit Log Analyzer

![CI](https://github.com/Qyroxen/Audit-Log-Analyzer/actions/workflows/ci.yml/badge.svg)
![CodeQL](https://github.com/Qyroxen/Audit-Log-Analyzer/actions/workflows/codeql.yml/badge.svg)
![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Stars](https://img.shields.io/github/stars/Qyroxen/Audit-Log-Analyzer?style=social)
![Issues](https://img.shields.io/github/issues/Qyroxen/Audit-Log-Analyzer)
![PRs](https://img.shields.io/github/issues-pr/Qyroxen/Audit-Log-Analyzer)

> A production-ready CLI tool built with Go

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/Audit-Log-Analyzer?style=social)](https://github.com/Qyroxen/Audit-Log-Analyzer/stargazers)

## What is it?

Audit Log Analyzer is a production-ready CLI tool built with Go. It provides powerful functionality with a beautiful terminal interface.

## Features

- Fast and efficient (written in Go)
- Beautiful CLI with colored output
- Comprehensive documentation
- GitHub Actions CI/CD
- CodeQL security analysis
- Dependabot for dependency updates
- MIT Licensed
- Fully offline - zero cloud dependency

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/Audit-Log-Analyzer.git
cd Audit-Log-Analyzer
go build -o auditloganalyzer .

# Run
./auditloganalyzer --help
```

## CLI Usage

```bash
# Basic usage
./auditloganalyzer

# With flags
./auditloganalyzer --verbose --output json

# Get help
./auditloganalyzer --help
```

## Examples

```bash
# Example 1
./auditloganalyzer example1

# Example 2
./auditloganalyzer example2 --flag value
```

## Development

```bash
# Run tests
go test ./...

# Build
go build -o auditloganalyzer .

# Lint
golangci-lint run

# Security scan
codeql analyze
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Security

For security vulnerabilities, please see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/Audit-Log-Analyzer/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/Audit-Log-Analyzer?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/Audit-Log-Analyzer/forks">
    <img src="https://img.shields.io/github/forks/Qyroxen/Audit-Log-Analyzer?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/Audit-Log-Analyzer/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/Audit-Log-Analyzer" alt="Issues">
  </a>
  <a href="https://github.com/Qyroxen/Audit-Log-Analyzer/pulls">
    <img src="https://img.shields.io/github/issues-pr/Qyroxen/Audit-Log-Analyzer" alt="Pull Requests">
  </a>
</p>
