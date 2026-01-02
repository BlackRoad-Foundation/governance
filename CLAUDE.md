# CLAUDE.md - AI Assistant Guidelines

This document provides guidance for AI assistants working with the BlackRoad-Foundation governance repository.

## Repository Overview

**Purpose:** This repository contains governance documents, policies, and decision-making processes for the BlackRoad-Foundation organization within the BlackRoad ecosystem.

**Repository URL:** https://github.com/BlackRoad-Foundation/governance

**Status:** Initial development phase

## Project Structure

```
governance/
├── README.md          # Project overview and quick start
├── .gitignore         # Standard ignores (node_modules, .env, dist, build, logs)
└── CLAUDE.md          # This file - AI assistant guidelines
```

### Future Expected Structure

As this repository grows, governance documents should follow this structure:

```
governance/
├── policies/          # Organizational policies
├── processes/         # Decision-making and operational processes
├── templates/         # Document templates for proposals, decisions, etc.
├── decisions/         # Archived decisions and their rationale
├── roles/             # Role definitions and responsibilities
└── meetings/          # Meeting notes and agendas
```

## Development Guidelines

### Branch Naming Convention

- Feature branches: `claude/<description>-<session-id>`
- Always push to the designated feature branch
- Never push directly to main without explicit permission

### Commit Messages

Use clear, descriptive commit messages:
- `feat:` for new governance documents or features
- `docs:` for documentation updates
- `fix:` for corrections to existing documents
- `refactor:` for restructuring without content changes

Example: `feat: Add code of conduct policy`

### Document Standards

When creating governance documents:

1. **Use Markdown format** - All documents should be in `.md` format
2. **Include metadata** - Add creation date, author, and status at the top
3. **Be explicit** - Governance documents should be clear and unambiguous
4. **Version control** - Use git history for versioning, not in-document version numbers
5. **Cross-reference** - Link to related documents when applicable

### Document Template

```markdown
# [Document Title]

**Status:** Draft | Under Review | Approved | Superseded
**Created:** YYYY-MM-DD
**Last Updated:** YYYY-MM-DD

## Purpose

[Brief description of what this document covers]

## Scope

[Who and what this document applies to]

## Content

[Main content of the document]

## Related Documents

- [Link to related doc 1]
- [Link to related doc 2]
```

## AI Assistant Instructions

### When Working on This Repository

1. **Read existing documents first** - Understand the current governance structure before making changes
2. **Maintain consistency** - Follow established patterns and conventions
3. **Be precise** - Governance documents require clear, unambiguous language
4. **No over-engineering** - Only create documents that are explicitly requested
5. **Preserve history** - Use git properly; don't delete content without clear justification

### Do's

- Create well-structured, clear governance documents
- Follow the document template for new policies
- Use proper markdown formatting
- Commit with descriptive messages
- Ask for clarification if requirements are ambiguous

### Don'ts

- Don't create policies or processes without explicit request
- Don't modify existing approved documents without authorization
- Don't add unnecessary complexity to simple documents
- Don't use informal language in governance documents
- Don't guess at organizational policies - ask if unsure

### Important Considerations

- **Legal implications** - Governance documents may have legal weight; be careful with language
- **Stakeholder impact** - Changes may affect multiple parties in the organization
- **Audit trail** - All changes should be traceable through git history

## Technical Details

### Environment

- **Platform:** Linux-based development environment
- **Git:** Standard git workflow with remote on GitHub

### File Ignores

The repository ignores:
- `node_modules/` - Node.js dependencies (if tooling is added)
- `.env`, `.env.local` - Environment variables
- `dist/`, `build/` - Build artifacts
- `*.log` - Log files
- `.DS_Store` - macOS metadata

## Organization Context

This repository is part of the **BlackRoad-Foundation** organization within the **BlackRoad ecosystem**. When creating governance documents, consider:

- Alignment with broader ecosystem goals
- Consistency with other BlackRoad-Foundation repositories
- Impact on ecosystem partners and contributors

## Quick Reference

| Task | Action |
|------|--------|
| New policy | Create in `policies/` using template |
| Process documentation | Create in `processes/` |
| Decision record | Create in `decisions/` with rationale |
| Meeting notes | Create in `meetings/` with date prefix |

---

*This document should be updated as the repository evolves and new conventions are established.*
