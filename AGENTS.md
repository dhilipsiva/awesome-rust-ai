# Repository Guidelines

## Project Structure & Module Organization
- `docs/`: curated Markdown overviews of Rust-based AI tools (`chatgpt.md`, `gemini.md`). Add new use cases as separate files or sections rather than expanding an existing one excessively.
- `flake.nix`: Nix dev shell definition for a consistent Rust toolchain (rustc, cargo, clippy, rustfmt). Update inputs sparingly and keep it reproducible.
- Root: project metadata (license). Keep new assets minimal; prefer links over embedding binaries.

## Build, Test, and Development Commands
- `nix develop` (or `nix-shell`): enter the dev environment with Rust tools preinstalled.
- `cargo fmt --check`: ensure Rust snippets in examples stay formatted (only when you add Rust code).
- `cargo clippy -- -D warnings`: lint Rust examples for correctness (optional but preferred when code changes are significant).
- `rg "<term>" docs`: fast search through existing content to avoid duplication and keep terminology consistent.

## Coding Style & Naming Conventions
- Markdown: use `#`/`##` headings, short paragraphs, and bullet lists for scans. Prefer reference-style links when citing sources; keep URLs stable.
- Examples: when adding Rust code, favor idiomatic async Rust and include minimal, runnable snippets. Use `snake_case` for functions/variables and `CamelCase` for types.
- Tone: concise, factual, and tool-focused—avoid marketing language. Clearly state what a tool is, how it’s built, and where it fits.

## Testing Guidelines
- No automated tests exist; for new Rust samples, compile locally (`cargo check`) if you add a `Cargo.toml` for examples. For Markdown, proofread links and run a quick preview to catch formatting issues.

## Commit & Pull Request Guidelines
- Commits: use clear, present-tense messages (`Add vector DB section`, `Update Nix inputs`). Group related doc edits together.
- PRs: include a brief summary of scope, list new/updated files (e.g., `docs/new-tool.md`), and note any new commands or setup steps. Link to sources for new claims when possible.

## Security & Configuration Tips
- Do not commit API keys or model credentials; prefer documenting required env vars instead. If a tool needs secrets, describe setup steps rather than embedding values.
- Large assets or diagrams should be linked, not stored in-repo, to keep the repository lean.
