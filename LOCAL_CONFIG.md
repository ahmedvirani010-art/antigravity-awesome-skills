# Local Skills Configuration

> **Lean Setup**: Only the skills you actually use are active locally.  
> **GitHub**: All 62 skills remain available in the repository for the community.

## 📊 Active Skills (27 + symlinks)

### 🔥 Tier S - Core Development (9 skills)

Essential skills used automatically by the agent:

- `systematic-debugging` - Root cause analysis and structured debugging
- `test-driven-development` - TDD workflow and red-green-refactor
- `writing-skills` - Documentation and markdown expertise
- `doc-coauthoring` - Structured technical documentation workflow
- `planning-with-files` - Implementation plan creation
- `software-architecture` - Quality-focused design principles
- `senior-architect` - Scalable system design and architecture
- `verification-before-completion` - Pre-completion verification workflow
- `git-pushing` - Automated staging and conventional commits

### ⭐ Tier A - Your Projects (12 skills)

Skills actively used for your specific projects:

- `docx-official` (+ symlink `docx`) - Official Anthropic Word manipulation
- `pdf-official` (+ symlink `pdf`) - Official Anthropic PDF manipulation
- `pptx-official` (+ symlink `pptx`) - Official Anthropic PowerPoint manipulation
- `xlsx-official` (+ symlink `xlsx`) - Official Anthropic Excel manipulation
- `react-best-practices` - Vercel's 40+ performance optimization rules
- `web-design-guidelines` - Vercel's 100+ UI/UX audit rules
- `frontend-dev-guidelines` - Modern React/TS development patterns
- `webapp-testing` - Local web application testing with Playwright
- `playwright-skill` - Advanced Playwright automation
- `mcp-builder` - Model Context Protocol server creation
- `notebooklm` - Google NotebookLM integration
- `ui-ux-pro-max` - Advanced design intelligence

### 📢 Marketing & SEO (1 skill)

- `content-creator` - SEO-optimized marketing and brand voice

### 🏢 Corporate (4 skills)

- `brand-guidelines-anthropic` - Official Anthropic brand styling
- `brand-guidelines-community` - Community brand guidelines
- `internal-comms-anthropic` - Official Anthropic communications
- `internal-comms-community` - Community communications

### 📝 Additional (1 skill)

- `writing-plans` - Strategic planning documentation

---

## 🗂️ Directory Structure

```
skills/
├── .disabled/              ← 35 skills (inactive locally, kept for GitHub)
├── .gitignore             ← Prevents committing .disabled to GitHub
├── [27 active skills]     ← Only what you use
└── [4 symlinks]           ← docx, pdf, pptx, xlsx → official versions
```

---

## 🔄 Re-enabling Skills

If you need a disabled skill, simply move it back:

```bash
cd /Users/nicco/Antigravity\ Projects/antigravity-awesome-skills/skills
mv .disabled/SKILL_NAME ./
```

Example:

```bash
mv .disabled/loki-mode ./  # Re-enable Loki Mode
```

---

## 📦 Disabled Skills (35)

Located in `skills/.disabled/`:

### Development Tools

- `backend-dev-guidelines`
- `frontend-design`
- `react-ui-patterns`
- `test-fixing`
- `testing-patterns`
- `receiving-code-review`
- `requesting-code-review`

### Infrastructure

- `linux-shell-scripting`
- `using-git-worktrees`

### Security

- `aws-penetration-testing`
- `ethical-hacking-methodology`
- `pentest-checklist`
- `top-web-vulnerabilities`

### Creative & Design

- `algorithmic-art`
- `canvas-design`
- `claude-d3js-skill`
- `theme-factory`
- `slack-gif-creator`

### Architecture & Planning

- `brainstorming`
- `core-components`
- `skill-creator`
- `skill-developer`

### Workflow & Process

- `executing-plans`
- `file-organizer`
- `finishing-a-development-branch`
- `kaizen`
- `using-superpowers`

### Autonomous

- `loki-mode`
- `dispatching-parallel-agents`
- `subagent-driven-development`

### Product & Business

- `app-store-optimization`
- `product-manager-toolkit`
- `prompt-engineering`

### UI/UX

- `web-artifacts-builder`

---

## 🎯 Benefits of This Configuration

✅ **Faster Agent Response** - Only parses 27 skills instead of 62  
✅ **Cleaner Context** - Less noise when selecting skills  
✅ **GitHub Intact** - All 62 skills available for community  
✅ **Easy Recovery** - Disabled skills can be re-enabled anytime

---

## 🔧 Maintenance

### To Disable More Skills

```bash
cd skills
mv SKILL_NAME .disabled/
```

### To Re-enable Skills

```bash
cd skills
mv .disabled/SKILL_NAME ./
```

### To Reset to Full Configuration

```bash
cd skills
mv .disabled/* ./
rmdir .disabled
rm .gitignore
```

---

**Last Updated**: 2026-01-15  
**Active Skills**: 27 + 4 symlinks = 31 total  
**Disabled Skills**: 35 (temporarily inactive)
