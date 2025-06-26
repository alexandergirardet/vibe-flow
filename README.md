# Content Marketing Operations System
> GitHub-native content creation powered by AI and vibe marketing methodology

## Overview

This repository contains a complete content marketing operations system that combines:
- **Vibe Marketing Framework**: Packaging the same fact-rich story in multiple emotional wrappers
- **AI-Powered Content Generation**: Using Cursor AI with custom prompts and templates
- **Automated Workflows**: N8N automations that create GitHub commits for new content
- **Collaborative Review**: Pull request-based content review and approval process

## Repository Structure

```
marketing-repo/
├── strategy/           # Living strategy documents
├── content/           # All content organized by type
├── templates/         # Reusable content templates
├── automation/        # N8N workflows and Airtable schemas
├── assets/           # Images, media files
└── .cursorrules      # AI assistant configuration
```

## Quick Start

1. **Setup Strategy Foundation**
   - Update files in `strategy/` with your brand analysis
   - Customize `templates/` to match your tone of voice
   - Configure `.cursorrules` for your specific needs

2. **Content Creation Workflow**
   - Add new content ideas to Airtable
   - N8N automatically researches and generates content
   - Review and refine via GitHub pull requests
   - Merge to publish across platforms

3. **Collaboration**
   - Team members can suggest edits via PR comments
   - All content versions are tracked and rollback-able
   - Performance data linked to specific content versions

## Key Features

- **Template-Driven**: Consistent quality using proven frameworks
- **AI-Enhanced**: Cursor AI learns from your best content patterns
- **Collaborative**: GitHub-native review and approval process
- **Automated**: N8N handles research, generation, and publishing
- **Trackable**: Performance metrics tied to content versions

## Getting Started

See individual folder READMEs for detailed setup instructions:
- [Strategy Setup](strategy/README.md)
- [Content Templates](templates/README.md)
- [Automation Workflows](automation/README.md) 