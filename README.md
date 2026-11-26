# Data Storytelling

**A practical, evidence-based guide to finding meaningful insights and communicating data clearly.**

This repository contains two complete language editions of the same version 2.0 skill. Choose the language you want to work in and install that edition on its own. The README and repository overview are primarily in English; a Spanish quick start is included below.

## Choose an edition

| Edition | Skill folder | Skill ID | Language |
|---|---|---|---|
| English | `skills/data-storytelling/` | `data-storytelling` | English |
| Español | `skills/storytelling-con-datos/` | `storytelling-con-datos` | Español |

Each folder contains its own `SKILL.md`, `references/`, `CHANGELOG.md`, and language-specific README. Both editions are complete Agent Skills packages; their instructions and references are not mixed.

## What the skill does

The skill helps an agent identify which findings matter, connect evidence to a clear narrative, adapt the message to its audience, and communicate data in a way that supports understanding and informed decisions. It scales the workflow to the request and distinguishes evidence from interpretation and recommendation.

The two editions share the same version 2.0 scope. The English edition is for people who prefer to work with the skill in English; the Spanish edition preserves the Spanish-language final version. Each edition includes the methodological core, its complementary material, 17 reference modules, and source traceability.

## Install one edition

Install the folder for the language you want. Keep its `SKILL.md` and `references/` directory together.

### Project installation

From the root of the project where you want to use the skill, copy one or both folders:

**Codex or OpenCode**

```bash
mkdir -p .agents/skills
cp -R /path/to/data-storytelling/skills/data-storytelling .agents/skills/data-storytelling
# Or install the Spanish edition:
cp -R /path/to/data-storytelling/skills/storytelling-con-datos .agents/skills/storytelling-con-datos
```

**Claude Code**

```bash
mkdir -p .claude/skills
cp -R /path/to/data-storytelling/skills/data-storytelling .claude/skills/data-storytelling
# Or install the Spanish edition:
cp -R /path/to/data-storytelling/skills/storytelling-con-datos .claude/skills/storytelling-con-datos
```

Replace `/path/to/data-storytelling` with the location where you cloned or extracted this repository. On Windows, use PowerShell:

```powershell
New-Item -ItemType Directory -Force .agents\skills | Out-Null
Copy-Item .\skills\data-storytelling -Destination .\.agents\skills -Recurse
```

Use `.claude\skills` instead of `.agents\skills` for a project-level Claude Code installation. To install both languages, copy both skill folders. OpenCode discovers skills in both `.agents/skills/` and `.claude/skills/`.

### Personal installation

Use the personal skill directory for your agent: Codex `~/.agents/skills/`, Claude Code `~/.claude/skills/`, or OpenCode `~/.config/opencode/skills/`. Copy the selected skill folder into that directory. If it does not appear, reload or restart the agent as its documentation recommends.

## Invoke a skill

- **Codex:** `$data-storytelling` or `$storytelling-con-datos`
- **Claude Code:** `/data-storytelling` or `/storytelling-con-datos`
- **OpenCode:** `@data-storytelling` or `@storytelling-con-datos`

You can install either edition by itself or install both. Their skill IDs are distinct, so they can coexist.

## Sources and attribution

The English and Spanish packages document their sources and page locators in their own `references/17-sources-and-traceability.md` and `references/17-fuentes-y-trazabilidad.md` files. Those files distinguish concepts attributed to their sources from original operational adaptations. Neither edition contains full book transcripts or original figures, and this repository is not an official product of the authors or publishers.

The v2.0 packages are consolidated reconstructions; the original v1.0 ZIP was not available during consolidation, so byte-for-byte preservation of each v1 file is not claimed.

## Compatibility and license

Both editions use the open `SKILL.md` format and include their supporting references. Install locations follow the documented conventions for Codex, Claude Code, OpenCode, and Agent Skills-compatible tools. Runtime behavior has not been tested across every agent version or configuration.

No reuse license is declared in this repository. Agree on licensing terms before offering reuse or accepting public contributions.

## Platform documentation

- [Agent Skills specification](https://agentskills.io/specification)
- [Codex skills](https://learn.chatgpt.com/docs/build-skills)
- [Claude Code skills](https://code.claude.com/docs/en/skills)
- [OpenCode skills](https://opencode.ai/docs/skills/)
- [GitHub README guidance](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

---

## Inicio rápido en español

Este repositorio reúne dos ediciones completas de la skill 2.0: `skills/data-storytelling/` en inglés y `skills/storytelling-con-datos/` en español. Elige una y conserva su carpeta `references/` junto a `SKILL.md`.

- Para **Codex u OpenCode**, copia la carpeta elegida a `.agents/skills/` en tu proyecto.
- Para **Claude Code**, cópiala a `.claude/skills/`.
- Para uso personal, usa la carpeta de skills global de tu agente. OpenCode también reconoce `.agents/skills/` y `.claude/skills/`.
- Invocación en español: `$storytelling-con-datos` en Codex, `/storytelling-con-datos` en Claude Code y `@storytelling-con-datos` en OpenCode.

Las instrucciones completas de instalación están arriba. Cada edición conserva sus propias referencias y trazabilidad bibliográfica.
