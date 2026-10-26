# Contributing to ALTA

Thank you for helping build user-controlled AI infrastructure. Each repository has its own scope, license, setup instructions, and checks. Read its `README.md`, `AGENTS.md` (if present), and `LICENSE` before contributing.

## Start a change

- For a small fix, open a pull request directly.
- For a new connector, public API change, or cross-repository change, open an issue first so the contract and migration can be discussed.
- Keep pull requests focused. Explain the user problem, design choice, compatibility impact, and how you verified the result.
- Update documentation and tests when behavior or a public contract changes. Run the checks documented by the target repository.

## Data and credentials

Use synthetic fixtures. Never commit personal exports, recordings, transcripts, access tokens, cookies, `.env` files, or customer configuration. Redact logs and screenshots before attaching them to an issue or pull request.

If you discover a vulnerability or exposed credential, follow [SECURITY.md](SECURITY.md) instead of opening a public issue with details.

## Rights and conduct

Only submit work that you have the right to contribute under the target repository's license. Do not copy code, models, data, or assets from another project without checking its license and preserving required notices. Follow our [Code of Conduct](CODE_OF_CONDUCT.md).

Maintainers review contributions as time permits. Opening an issue or pull request does not guarantee acceptance or a response time.
