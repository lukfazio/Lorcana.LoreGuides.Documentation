# Lorcana.LoreGuides.Documentation
Repository focused on centralizing translated Disney Lorcana documentation.

## Repository Purpose

This repository collects, standardizes, and maintains translated documentation for Disney Lorcana rules and guides. It serves as a reference for players, translators, and contributors who help keep rules content accurate across languages.


## Structure
- **EnUS/**: Official English documentation and source PDFs.
- **PtBr/**: Portuguese (Brazil) translations.
- **Guardrails/**: Guidelines, terminology rules, extraction scripts, and contributor notes.

## Phases

### Phase 01: _Guardrails_
To ensure the entire adaptation process follows consistent rules, "Guardrail" files must be created containing specific instructions for all file processing. Restrictions preventing the translation of specific terms, names, or letter text are examples of such guardrails.

Guardrails List:
- [x] Terms

### Phase 02: _Structure & Base Files_
To better process the information contained in the rules, all official documentation must be converted to Markdown (.md) format.
This format is an industry standard for software documentation and makes it easier for programs and AI agents to process the information.

Doc's List - https://www.disneylorcana.com/en-GB/resources: 
- [ ] Wilds-Unknown_SetReleaseNotes_EN.pdf
- [ ] Winterspell_SetReleaseNotes_EN.pdf
- [ ] Whispers-in-the-Well_ReleaseNotes_English.pdf
- [ ] Fabled_SetReleaseNotes_EN.pdf
- [ ] Whispers-in-the-Well_StarterDeckA_RULES_A.pdf
- [ ] OPPack_Rush_QuickRules_EN.pdf- 
- [X] CRUpdate_2.1.0-EN.pdf
- [ ] Tournament-Rules-6.11.2026_Update-EN.pdf
- [ ] CORE Lore Guide Document.pdf
- [ ] Disney_Lorcana_Play_Correction_Guidelines_052124update.pdf
- [ ] op-diversity-and-inclusion-policy.pdf
- [ ] community-code-en.pdf

### Phase 3: _Automated Translation_
Automatic translation of all documents into Brazilian Portuguese (initially). With the rules and guardrail files, need to feed specific document chapters to an AI agent (ex: Gemini) to handle the bulk of the translation.

Languages List:
- [ ] Brazilian Portuguese
- [ ] Spanish

### Phase 4: _Revision & Adaptation_
Review and necessary adjustments. This is the most manual and least technical part. As the translated articles are released, the work performed by the AI ​​agents requires validation regarding formatting, syntax, and semantics.


## How to Contribute
Contributions are welcome via Issues and Pull Requests. To propose a change, follow these steps:

- **Report an Issue**: Create an Issue describing the problem or suggestion. Include the file path and a brief rationale.
- **Create a Branch**: Fork the repository and create a branch using `docs/short-description` or `fix/short-description`.
- **Make Clear Changes**: Edit only necessary files. For translations, follow terminology rules in [Guardrails/Terms.md](Guardrails/Terms.md).
- **Commit Messages**: Use concise, conventional-style commits, e.g. `docs: fix spacing in EnUS/Comprehensive_Rules/CRUpdate_2.1.0-EN.md`.
- **Open a Pull Request**: Push your branch and open a PR against `main`. In the PR include a summary, files changed, related Issue (if any), and a short checklist (spellcheck, formatting, guardrails compliance).
- **Review & Merge**: Maintainers will review and request changes if needed. After approvals and passing checks, a maintainer will merge the PR.

## Contributor Guidelines
- **Terminology**: Preserve protected English terms when required. For non-translatable terms, add a parenthetical translation as described in [Guardrails/Terms.md](Guardrails/Terms.md).
- **Formatting**: Keep Markdown tidy. Use consistent list indentation and verify numbering mirrors the source when updating rule documents.
- **Local Checks**: Run spellcheck and a markdown linter locally before opening a PR.

## Support
For questions about contributions or content, open an Issue and tag the maintainers. Use Issues for discussion before making large changes.

## License
©Disney Lorcana is intellectual property belonging to the company Ravensbruger. Thats a Community made resource. All rights reserved. For more information about access disneylorcana.com 
