# Contributing to NexusAI Tools

Thank you for your interest in contributing!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/nexusai-manager.git`
3. Install dependencies: `npm install`
4. Create a branch: `git checkout -b feature/your-feature`
5. Make your changes
6. Run tests: `npm run test`
7. Commit: `git commit -m "feat: add your feature"`
8. Push: `git push origin feature/your-feature`
9. Open a Pull Request

## Development Setup

```bash
npm install
npm run dev
```

## Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation
- `refactor:` — Code refactoring
- `test:` — Tests
- `chore:` — Maintenance

## Code Style

- TypeScript for frontend
- Rust for backend (Tauri)
- Follow existing patterns in the codebase
- Run `npm run lint` before committing

## Pull Request Process

1. Update documentation if needed
2. Add tests for new features
3. Ensure CI passes
4. Request review from maintainers
