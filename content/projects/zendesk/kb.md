---
title: 'Zendesk Knowledge Base Portfolio'
date: 2026-01-18
draft: false
slug: zendesk-kb-portfolio
description: "Complete legal tech knowledge base: 6 articles, automation workflows, and analytics framework built in Zendesk"
summary: "Knowledge base for legal practice management with content templates, macros, triggers, and analytics tracking"
cover: "/images/main-dashboard-zendesk.png"
featured: false
tags:
  - technical-writing
  - zendesk
  - knowledge-management
categories:
  - portfolio
demo: "https://sarah-amalia.zendesk.com/hc/"
tech_stack:
  - Zendesk Guide
  - Zendesk Support
  - Zendesk Explore
  - Loom
status: "completed"
lightbox:
  enabled: true
justified_gallery:
  enabled: true
---
*Note: Live demo available during trial period. Screenshots provided below for reference.*

# Screenshots
## Macro
![Macro Settings](images/macro-settings-zendesk.png "Macro Settings Sample")
![Macros list Zendesk](images/macros-list-zendesk.png "Macro Creation List")

## Triggers
![triggers configuration](/images/trigger-config.png "triggers configuration sample")
![triggers list](/images/triggers-list.png "triggers list")

## Others
{{< masonry columns=2 gutter=2 >}}
![Article sample](/images/article-sample-1-zendesk.png)
![/images/zendesk-main-dashboard.png](/images/main-dashboard-zendesk.png)
![all articles list](images/all-articles-zendesk.png)
![analytics dashboard](images/analytics-zendesk.png "Photo by - Sarah Amalia")
{{< /masonry >}}
---
## Video Tutorial Sample
<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.loom.com/embed/0bbf00ec13a64c67bcf03e0725742b22" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

# Project Overview

Built a complete knowledge base in Zendesk, demonstrating technical writing and knowledge management skills for legal practice management software.

---

# Features

### Content Management
- 6 published articles across 4 legal tech categories
- 3 reusable templates with consistent structure
- Label taxonomy and permission controls
- Version control with change documentation

### Automation
- 3 macros for standardized responses
- 2 triggers for intelligent routing
- Keyword-based auto-tagging

### Analytics & Quality
- Zendesk Explore configured for performance monitoring
- Article voting for user feedback
- Content audit system with priority tracking
- Systematic update workflow

### Customisation
- Branded help center appearance
- Custom article templates
- Metadata and visibility configuration
---

# Technologies Used

**Platform:**
- Zendesk Guide for knowledge base content management
- Zendesk Support for macros, triggers, and automations
- Zendesk Explore for analytics and reporting

**Tools:**
- Loom for video tutorial creation and hosting
- Markdown for article formatting

---

# Architecture

#### System Overview
```mermaid
graph TB
    subgraph Content["Content Layer"]
        KB[Knowledge Base]
        KB --> CAT1[Practice Management]
        KB --> CAT2[Client Onboarding]
        KB --> CAT3[Case Management]
        KB --> CAT4[Legal Accounting]
        
        CAT1 --> ART[6 Published Articles]
        CAT1 --> TMPL[3 Templates]
    end
    
    subgraph Auto["Automation Layer"]
        TRIG[2 Triggers<br/>Auto-tagging]
        MAC[3 Macros<br/>Standardized Responses]
    end
    
    subgraph QC["Quality Control Layer"]
        EXP[Zendesk Explore<br/>Analytics]
        AUDIT[Audit Spreadsheet<br/>Tracking]
        VC[Version Control<br/>Change Logs]
    end
    
    Content --> Auto
    Auto --> QC
    QC -.feedback loop.-> Content
```

#### Trigger Workflow
```mermaid
flowchart LR
    A[New Ticket] --> B{Check Keywords}
    
    B -->|password, login,<br/>access, reset| C[Trigger 1:<br/>Auto-tag Login Issue]
    C --> C1[Add tags:<br/>login_issue<br/>password_related]
    
    B -->|onboarding, client,<br/>setup, new matter| D[Trigger 2:<br/>Auto-tag Onboarding]
    D --> D1[Add tags:<br/>auto_response<br/>onboarding]
    D --> D2[Set status:<br/>Pending]
    
    C1 --> E[Ticket Tagged<br/>& Ready]
    D2 --> E
```

#### Macro Workflow
```mermaid
flowchart TB
    A[Agent Reviews Ticket] --> B{Choose Action}
    
    B --> C[Macro 1:<br/>Password Reset]
    B --> D[Macro 2:<br/>Onboarding Welcome]
    B --> E[Macro 3:<br/>Escalate to Tier 2]
    
    C --> C1[Send reset instructions<br/>+ Add tags<br/>+ Set status Pending]
    D --> D1[Send welcome message<br/>+ Add tags<br/>+ Set status Pending]
    E --> E1[Create internal note<br/>+ Set priority High<br/>+ Add escalated tag]
    
    C1 --> F[Response Sent]
    D1 --> F
    E1 --> F
```

#### Content Lifecycle
```mermaid
stateDiagram-v2
    [*] --> Draft
    Draft --> Review: Submit for review
    Review --> Draft: Needs changes
    Review --> Published: Approved
    Published --> Monitor: Track performance
    Monitor --> Update: Low helpfulness<br/>(<70%)
    Update --> Published: Changes documented
    Published --> Archive: Outdated
    Archive --> [*]
```

#### Quality Control Workflow
```mermaid
flowchart TB
    A[Article Published] --> B[Collect Feedback]
    B --> C[User Voting]
    B --> D[Zendesk Explore<br/>Analytics]
    
    C --> E{Helpfulness<br/><70%?}
    D --> E
    
    E -->|Yes| F[Add to Audit<br/>Spreadsheet]
    E -->|No| G[Monitor Only]
    
    F --> H[Prioritize Update]
    H --> I[Update Article]
    I --> J[Document Changes<br/>in Version Log]
    J --> A
```

