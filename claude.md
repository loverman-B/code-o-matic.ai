# Code-O-Matic Web Platform

## Overview
Code-O-Matic is a collection of innovative projects hosted on a unified landing page at **code-o-matic.ai**. This document outlines the structure, setup, and guidelines for maintaining the Code-O-Matic ecosystem.

## Projects

### 1. ACONTENT
- **Description**: Advanced content management and automation system
- **Purpose**: Streamline content workflows and enhance productivity
- **Repository**: Private GitHub repo
- **Access**: loverman-B + authorized collaborators

### 2. Social Media Bot
- **Description**: Intelligent automation for social media management
- **Purpose**: Content scheduling, analytics tracking, multi-platform coordination
- **Repository**: Private GitHub repo
- **Access**: loverman-B + authorized collaborators

### 3. Web Platform
- **Description**: Modern web application and infrastructure
- **Purpose**: Foundation of the Code-O-Matic ecosystem
- **Repository**: Public (code-o-matic.ai)
- **Access**: Public (landing page only)

## Infrastructure

### Domain & Hosting
- **Domain**: code-o-matic.ai
- **Registrar**: name.com
- **Hosting**: GitHub Pages
- **DNS Configuration**:
  - A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  - CNAME: www → loverman-b.github.io

### Repository Structure
```
code-o-matic.ai/ (Public GitHub Repo)
├── index.html          # Landing page
├── claude.md           # This file
└── README.md           # (optional)

# Private Repositories (separate repos)
- ACONTENT             # Private repo
- SOCIAL-MEDIA-BOT     # Private repo
```

## Development Guidelines

### Landing Page
- Single-page responsive design
- Modern, professional appearance
- Introduces all projects
- Mobile-optimized
- Links to private project repos (for authorized users)

### Collaborator Access
To add collaborators to private repos:
1. Go to repo Settings → Collaborators
2. Add GitHub username
3. Set appropriate permission level (Read/Write/Admin)

### Deployment
- All changes to landing page auto-deploy via GitHub Pages
- Push to `main` branch triggers automatic deployment
- DNS propagation may take a few minutes for new domain changes

## Future Enhancements
- [ ] Add project detail pages
- [ ] Create documentation site
- [ ] Set up analytics tracking
- [ ] Add team member profiles
- [ ] Implement authentication for private content preview

## Contact
- **Email**: b.m.belskis@gmail.com
- **GitHub**: [@loverman-B](https://github.com/loverman-B)
