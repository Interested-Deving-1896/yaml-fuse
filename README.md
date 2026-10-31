# yaml-fuse

[![AI agent ready](https://img.shields.io/badge/AI_agent-ready-2ea44f?style=flat-square)](https://github.com/Interested-Deving-1896/fork-sync-all/blob/main/DOCS/ai-agent-badges.md)
[![Open in Codex](https://img.shields.io/badge/Open_in-Codex-000000?style=flat-square&logo=openai&logoColor=white)](https://chatgpt.com/codex)
[![Open in Claude Code](https://img.shields.io/badge/Open_in-Claude_Code-d97757?style=flat-square&logo=anthropic&logoColor=white)](https://claude.ai/code)
[![Open in GitHub Copilot](https://img.shields.io/badge/Open_in-GitHub_Copilot-181717?style=flat-square&logo=githubcopilot&logoColor=white)](https://github.com/copilot)
[![Open in Cursor](https://img.shields.io/badge/Open_in-Cursor-111111?style=flat-square)](https://cursor.com/agents)
[![Use with Gemini CLI](https://img.shields.io/badge/Use_with-Gemini_CLI-4285f4?style=flat-square&logo=googlegemini&logoColor=white)](https://github.com/google-gemini/gemini-cli)
[![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria)




<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/yaml-fuse.git
cd yaml-fuse
```

## Usage


### Basic Usage

```bash
python yaml-fuse.py <yaml_file> <mount_point> [--mode yaml|json]
```

### Examples

1. Mount a YAML file with default YAML mode:
```bash
python yaml-fuse.py config.yaml /mnt/config
```

2. Mount with JSON output mode:
```bash
python yaml-fuse.py data.yaml /tmp/data --mode json
```

3. Enable debug logging:
```bash
python yaml-fuse.py config.yaml /mnt/config --debug
```

4. Run tests to verify installation:
```bash
# Quick test (no FUSE required)
python3 tests.py --unit

# Full test suite (requires FUSE - for local development)
python3 tests.py --all

# Run specific test types
python3 tests.py --integration  # FUSE integration tests
python3 tests.py --demo         # Demo functionality
```

**Note**: The CI pipeline runs unit tests and demos automatically. Full integration tests with FUSE filesystem mounting are designed for local development and testing.

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/yaml-fuse`](https://github.com/Interested-Deving-1896/yaml-fuse) and mirrored through:

```
Interested-Deving-1896/yaml-fuse  ──►  OpenOS-Project-OSP/yaml-fuse  ──►  OpenOS-Project-Ecosystem-OOC/yaml-fuse
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
| Contributor | Commits |
|---|---|
| [@shlomi-dr](https://github.com/shlomi-dr) | 29 |
| [@Interested-Deving-1896](https://github.com/Interested-Deving-1896) | 15 |
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream influences recorded._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## Accessibility

<!-- AI:start:accessibility -->
No  was found when this README was generated. Check the
[Actions tab](https://github.com/Interested-Deving-1896/yaml-fuse/actions) for repository-specific checks, and document an
accessibility status only when a report or workflow provides evidence for it.




See the [W3C Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/)
for accessibility guidance.
<!-- AI:end:accessibility -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/yaml-fuse/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
