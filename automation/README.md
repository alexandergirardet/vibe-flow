# Marketing Automation System

This folder contains N8N workflows and Airtable schemas that automate the content creation and distribution process using vibe marketing principles.

## System Overview

The automation system follows this flow:
1. **Content Ideas** → Added to Airtable content calendar
2. **Research Phase** → N8N workflow researches topic and audience
3. **Content Generation** → AI creates content using strategy docs and templates
4. **Review Process** → Content pushed to GitHub as pull request
5. **Distribution** → Published content automatically shared across platforms

## Core Components

### N8N Workflows
- `content-research-workflow.json` - Market research and trend analysis
- `blog-post-generation-workflow.json` - Full blog post creation pipeline
- `social-content-workflow.json` - Social media content generation
- `content-distribution-workflow.json` - Multi-platform publishing
- `performance-tracking-workflow.json` - Analytics and optimization

### Airtable Schemas
- `content-calendar-schema.json` - Content planning and scheduling
- `research-database-schema.json` - Market insights and competitor tracking
- `performance-metrics-schema.json` - Content performance tracking
- `client-projects-schema.json` - Project management and deliverables

## Setup Requirements

### N8N Configuration
**Required Credentials:**
- OpenAI API key (GPT-4/Claude integration)
- Airtable API key and base IDs
- GitHub personal access token
- Social platform API keys (LinkedIn, Twitter)
- Analytics APIs (Google Analytics, social platform insights)

**Self-Hosted Requirements:**
- N8N instance (Docker recommended)
- Webhook endpoints for trigger automation
- Scheduled execution for research workflows

### Airtable Setup
**Base Structure:**
- Content Calendar (primary planning base)
- Research Database (market intelligence)
- Performance Tracking (analytics)
- Strategy Documents (living brand guidelines)

## Workflow Details

### 1. Content Research Workflow
**Trigger:** New record in Airtable "Content Calendar"
**Process:**
- Extract topic and target audience from Airtable
- Research latest market trends and competitor content
- Analyze audience sentiment and platform preferences
- Generate emotional angle recommendations
- Update Airtable with research findings

**Output:** Research brief with strategic recommendations

### 2. Blog Post Generation Workflow
**Trigger:** Research workflow completion + manual approval
**Process:**
- Load brand strategy documents from GitHub
- Apply appropriate content template based on topic type
- Generate content using AI with vibe marketing principles
- Create structured markdown with proper frontmatter
- Generate multiple emotional angle variations

**Output:** Draft blog post committed to GitHub branch

### 3. Social Content Workflow
**Trigger:** Published blog post or standalone social campaign
**Process:**
- Extract key insights from blog content
- Generate platform-specific adaptations (LinkedIn/Twitter)
- Create thread structures and carousel content
- Schedule optimal posting times based on audience data
- Generate engagement-driving questions and CTAs

**Output:** Social content calendar with scheduled posts

### 4. Content Distribution Workflow
**Trigger:** Content approval and merge to main branch
**Process:**
- Detect new content in GitHub main branch
- Extract content and metadata for distribution
- Publish to connected platforms with platform-specific formatting
- Send newsletter updates to subscriber segments
- Create social media posts with appropriate hashtags

**Output:** Multi-platform content distribution

### 5. Performance Tracking Workflow
**Trigger:** Scheduled daily/weekly execution
**Process:**
- Collect analytics from all connected platforms
- Calculate engagement rates and conversion metrics
- Compare performance against historical baselines
- Identify top-performing content patterns
- Generate optimization recommendations

**Output:** Performance dashboard updates in Airtable

## Integration Points

### GitHub Integration
**Purpose:** Version-controlled content creation and collaboration
**Functionality:**
- Automated content commits to feature branches
- Pull request creation for content review
- Merge triggers for content distribution
- Version tracking for performance correlation

### AI Service Integration
**Purpose:** Intelligent content generation following brand guidelines
**Models Used:**
- **GPT-4**: Long-form content generation and strategic analysis
- **Claude**: Research synthesis and framework development
- **Specialized Models**: Platform-specific optimization

### Social Platform APIs
**Purpose:** Automated content distribution and performance tracking
**Platforms:**
- **LinkedIn**: Professional content and company updates
- **Twitter**: Thread distribution and engagement tracking
- **Newsletter Platforms**: Subscriber communication
- **Analytics Platforms**: Performance measurement

## Customization Guide

### Adapting for Your Brand
1. **Update Strategy Documents**: Modify templates with your brand voice
2. **Configure Emotional Angles**: Define your primary emotional wrappers
3. **Set Content Categories**: Customize for your service offerings
4. **Adjust Posting Schedules**: Optimize for your audience timezone
5. **Define Success Metrics**: Set KPIs that align with business goals

### Workflow Customization
**Research Workflow:**
- Add industry-specific data sources
- Configure competitor monitoring lists
- Set content gap analysis parameters

**Generation Workflow:**
- Customize AI prompts for your voice
- Add approval checkpoints if needed
- Configure quality scoring criteria

**Distribution Workflow:**
- Set platform-specific formatting rules
- Configure audience segmentation
- Add compliance checks for regulated industries

## Performance Optimization

### Content Quality Monitoring
- **Automated Quality Scores**: Based on vibe marketing principles
- **Engagement Prediction**: Using historical performance data
- **Brand Consistency Checks**: Automated voice and tone validation

### Process Efficiency Metrics
- **Time to Publish**: From idea to live content
- **Review Cycle Time**: Content approval workflows
- **Distribution Reach**: Multi-platform publishing effectiveness
- **ROI Tracking**: Content investment vs. business outcomes

## Troubleshooting

### Common Issues
**API Rate Limits:**
- Implement request queuing and retry logic
- Use multiple API keys for high-volume operations
- Monitor usage across all connected services

**Content Quality Issues:**
- Review AI prompt configurations
- Check strategy document updates
- Validate template effectiveness

**Integration Failures:**
- Verify API credentials and permissions
- Check webhook endpoint availability
- Monitor N8N execution logs

### Monitoring and Alerts
- **Workflow Failure Notifications**: Slack/email alerts for broken processes
- **Content Quality Alerts**: Flag content below quality thresholds
- **Performance Anomalies**: Identify unusual engagement patterns

## Scaling Considerations

### Growing Content Volume
- **Batch Processing**: Handle multiple content pieces simultaneously
- **Resource Allocation**: Scale N8N workers for increased load
- **API Optimization**: Implement caching and request optimization

### Team Collaboration
- **Role-Based Access**: Configure Airtable and GitHub permissions
- **Approval Workflows**: Add team review processes
- **Handoff Protocols**: Define clear responsibility boundaries

### Advanced Features
- **A/B Testing**: Automated emotional angle testing
- **Predictive Analytics**: Content performance forecasting
- **Dynamic Personalization**: Audience-specific content variations

---

## Getting Started

1. **Setup N8N Instance**: Deploy and configure with required credentials
2. **Import Workflows**: Load provided JSON files into N8N
3. **Configure Airtable**: Create bases using provided schemas
4. **Test Integration**: Run sample content through complete pipeline
5. **Customize Settings**: Adapt workflows for your specific needs

See individual workflow README files for detailed setup instructions. 