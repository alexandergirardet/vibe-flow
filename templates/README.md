# Content Templates

This folder contains reusable templates for creating consistent, high-quality content using the vibe marketing methodology. Each template follows Alexander's proven frameworks and voice patterns.

## Available Templates

### Core Content Types
- `blog-post-template.md` - Long-form blog post structure
- `case-study-template.md` - Client success story format
- `social-thread-template.md` - Twitter/LinkedIn thread structure
- `newsletter-template.md` - Email newsletter format

### Specialized Templates
- `framework-post-template.md` - Educational framework content
- `story-post-template.md` - Narrative-driven content
- `data-post-template.md` - Research and insights content

## How to Use Templates

### For Manual Content Creation
1. Copy the appropriate template to `content/[category]/`
2. Rename with proper filename convention (see below)
3. Fill in each section following the guidance provided
4. Reference `strategy/tone_of_voice.md` for style consistency

### For AI-Assisted Content Creation
1. Include template content in your AI prompt
2. Provide specific details for each template section
3. Reference strategy documents for brand alignment
4. Use `.cursorrules` for automatic style consistency

### For N8N Automation
1. Templates are automatically used by N8N workflows
2. Airtable data fills template placeholders
3. AI generates content following template structure
4. Output is automatically formatted and committed to GitHub

## Template Structure

All templates follow this consistent structure:

### Frontmatter
```yaml
---
title: ""
date: ""
author: ""
category: ""
emotional_angle: ""
target_audience: ""
platform: ""
status: "draft"
---
```

### Content Sections
1. **Hook**: Compelling opening that establishes emotional stakes
2. **Framework**: Clear, actionable structure
3. **Evidence**: Data, examples, and proof points
4. **Call-to-Action**: Collaborative engagement

## Filename Conventions

### Blog Posts
`YYYY-MM-DD-descriptive-title.md`
Example: `2024-01-15-vibe-marketing-frameworks.md`

### Case Studies
`case-study-client-name-outcome.md`
Example: `case-study-mediterranean-brand-viral-content.md`

### Social Content
`platform-YYYY-MM-DD-topic.md`
Example: `linkedin-2024-01-15-ai-automation.md`

### Newsletters
`newsletter-YYYY-MM-DD-subject.md`
Example: `newsletter-2024-01-15-weekly-insights.md`

## Customization Guidelines

### Brand Voice Adaptation
- Maintain core vibe marketing principles
- Adapt tone for different audiences and platforms
- Reference `strategy/tone_of_voice.md` for consistency
- Include signature phrases and concepts

### Emotional Mapping
- Define primary emotional angle in frontmatter
- Consider multiple emotional wrappers for same content
- Test different approaches for different audiences
- Track emotional resonance in performance data

### Platform Optimization
- Adapt templates for platform-specific requirements
- Consider algorithmic preferences and user behavior
- Optimize length, format, and engagement style
- Include platform-native elements and features

## Quality Standards

Every template ensures:
- Story-first approach with human moments
- Specific data and timeframes (not vague claims)
- Clear, actionable frameworks
- Vulnerable authority and authentic voice
- Platform-appropriate optimization
- Collaborative rather than prescriptive tone

## Template Maintenance

### Regular Updates
- Review templates monthly for effectiveness
- Update based on performance data and feedback
- Refine emotional mapping based on audience response
- Incorporate new platform features and best practices

### Version Control
- Track template changes in Git history
- Document reasons for template updates
- Maintain backward compatibility when possible
- Test template changes before implementing in automation 