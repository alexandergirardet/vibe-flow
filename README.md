# Vibe Marketing Operations System
> GitHub-native content creation powered by AI, strategic workflows, and automated distribution

## Overview

This repository contains a complete vibe marketing operations system that combines strategic content planning with AI-powered execution. The system transforms content ideation into a seamless production pipeline using GitHub as the single source of truth.

**Core Philosophy:** Vibe marketing is the systematic practice of packaging the same fact-rich story in multiple emotional wrappers to match the audience's cultural and psychological state.

## Key Features

- **🎯 Strategic Workflows**: Interactive guides for content strategy, competitor analysis, and viral ideation
- **🤖 AI-Powered Generation**: Claude/ChatGPT integration with brand voice consistency
- **⚡ Automated Pipeline**: Airtable → N8N → GitHub → Multi-platform publishing
- **📊 Performance Tracking**: Real-time analytics and emotional resonance metrics
- **🔄 Collaborative Review**: Pull request-based content review and approval process
- **📈 Scalable System**: From manual workflows to full automation

## Repository Structure

```
marketing/
├── workflows/                    # Interactive strategy workflows
│   ├── seo/                     # SEO research and content strategy
│   ├── content/                 # Viral content ideation workflows
│   ├── research/                # Competitor intelligence workflows
│   ├── social/                  # Social media strategy workflows
│   ├── email/                   # Email marketing workflows
│   └── analytics/               # Performance analysis workflows
├── strategy/                     # Living strategy documents
│   ├── blog/                    # Blog-specific strategy files
│   ├── tone_of_voice.md         # Writing guidelines
│   ├── brand_analysis.md        # Brand positioning
│   └── market_research.md       # Audience insights
├── content/                      # Content pipeline
│   ├── blog-posts/              # Blog content pipeline
│   │   ├── drafts/              # Auto-generated from Airtable
│   │   ├── review/              # In review process
│   │   ├── approved/            # Ready for publishing
│   │   └── published/           # Live blog content
│   ├── case-studies/            # Case study collection
│   ├── newsletters/             # Newsletter archives
│   └── social-content/          # Social media content
├── templates/                    # Reusable content templates
├── automation/                   # Workflow automation
│   ├── n8n-workflows/           # N8N workflow exports
│   └── airtable-schemas/        # Database structures
├── assets/                       # Images, media files
├── .development/                 # Development documentation
│   └── github-content-strategy.md  # Complete implementation guide
└── .cursorrules                 # AI assistant configuration
```

## Content Workflow Architecture

### **Phase 1: Strategic Content Generation**
```
Workflows (using /strategy/ data) → Content Ideas → Airtable MCP → Content Calendar
```

### **Phase 2: Content Production Pipeline**
```
Airtable → N8N Trigger → Auto-Draft Creation → GitHub PR → Review/Edit → Merge → Publishing
```

### **Phase 3: Distribution & Analytics**
```
Published Content → N8N Multi-Platform Distribution → Performance Tracking → Strategy Refinement
```

## Quick Start Guide

### **1. Strategic Foundation Setup**
```bash
# 1. Configure your brand strategy
edit strategy/tone_of_voice.md
edit strategy/brand_analysis.md
edit strategy/market_research.md

# 2. Run your first workflow
open workflows/seo/content-strategy-research.md
# Follow the 7-step process to generate content ideas
```

### **2. Content Pipeline Setup**
```bash
# 1. Set up Airtable workspace (see automation/airtable-schemas/)
# 2. Configure N8N workflows (see automation/n8n-workflows/)
# 3. Set up GitHub Actions for automation
# 4. Test the full pipeline with one piece of content
```

### **3. Team Collaboration**
```bash
# 1. Content ideas automatically create GitHub branches
# 2. Team reviews content via pull requests
# 3. Approved content automatically publishes across platforms
# 4. Performance data feeds back into strategy refinement
```

## Interactive Workflows

The `/workflows/` directory contains step-by-step guides for strategic content creation:

- **[SEO Content Strategy](workflows/seo/content-strategy-research.md)**: 7-step process for comprehensive SEO research
- **[Viral Content Ideation](workflows/content/viral-content-ideation.md)**: 6-step emotional mapping for viral content
- **[Competitor Intelligence](workflows/research/competitor-intelligence.md)**: 5-step competitive analysis workflow

Each workflow includes:
- ⏱️ Time estimates and tool requirements
- 🎯 Specific AI prompts and MCP commands
- 📋 Expected deliverables and templates
- 🔗 Integration points with Airtable and N8N

## Automation Integration

### **Airtable Content Calendar**
- Strategic content planning and scheduling
- Performance tracking and analytics
- Team collaboration and task management
- Integration with GitHub via N8N workflows

### **N8N Workflow Engine**
- Automated draft creation from Airtable
- Multi-platform content distribution
- Performance data collection
- GitHub status synchronization

### **GitHub Actions**
- Automated file organization by status labels
- Content pipeline management
- Publishing triggers and webhooks
- Performance monitoring and alerts

## Development & Customization

See **[Complete Implementation Guide](.development/github-content-strategy.md)** for:

- 📋 Detailed technical implementation
- 🛠️ GitHub Actions and N8N workflow templates
- 📊 Airtable schema and field configurations
- 🚀 4-phase implementation roadmap
- 📈 Success metrics and performance tracking
- ⚠️ Risk mitigation strategies

## Getting Started

1. **Strategic Setup** (30 mins)
   - Update `/strategy/` files with your brand information
   - Configure `.cursorrules` for your specific needs
   - Review and customize content templates

2. **First Workflow** (45 mins)
   - Run `/workflows/seo/content-strategy-research.md`
   - Generate 10+ content ideas using AI and MCP tools
   - Upload results to Airtable content calendar

3. **Automation Setup** (2-3 hours)
   - Configure Airtable workspace and fields
   - Set up N8N workflows for GitHub integration
   - Test automated draft creation and PR process

4. **Team Training** (1 hour)
   - Train team on GitHub PR review process
   - Set up automated publishing and distribution
   - Configure performance tracking and analytics

## Success Metrics

**Efficiency Gains:**
- ⚡ 80% reduction in manual content processes
- 🚀 3x increase in content production volume
- ⏱️ <48 hours from idea to published content

**Quality Improvements:**
- 📝 Consistent brand voice across all content
- 🔍 Built-in SEO optimization and validation
- 📊 Data-driven content strategy refinement

**Collaboration Benefits:**
- 🤝 Streamlined team review and approval process
- 🔄 Version control and rollback capabilities
- 📈 Performance attribution to content decisions

## Support & Documentation

- **[Complete Strategy Guide](.development/github-content-strategy.md)**: Technical implementation details
- **[Workflow Library](workflows/README.md)**: Interactive strategy workflows
- **[Template Collection](templates/README.md)**: Reusable content templates
- **[Automation Setup](automation/README.md)**: N8N and Airtable configuration

---

*This system represents the evolution of content marketing from manual processes to AI-powered, strategically-driven, automated workflows that scale with your business growth.* 