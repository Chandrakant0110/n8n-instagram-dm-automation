# Instagram DM Automation - N8N Workflow

This repository contains a complete Instagram DM automation workflow for N8N, designed to run on Hugging Face Spaces (free hosting).

## Overview

Automated Instagram messaging system that handles:
- **Webhook processing** (GET/POST requests)
- **Comment replies** - Automated responses to Instagram comments
- **Direct messages** - AI-powered DM automation with conversation handling
- **User data management** - Database integration for user profiles and settings
- **CRM updates** - Automatic CRM synchronization
- **Follow status checks** - Conditional messaging based on follow relationships
- **Trigger keywords** - Smart message filtering and routing

## Workflow Diagram

![Workflow Screenshot](screenshot.png)

## Key Features

- Handles Instagram webhook callbacks (GET/POST)
- Processes both comments and direct messages
- Integrates with Instagram Graph API
- Database-driven configuration and user data storage
- Conditional logic for different message types and user states
- Echo message rejection
- Chat history tracking

## Usage

Import the `Full DM Automation (2).json` file into your N8N instance and configure:
- Instagram Graph API credentials
- Database connection settings
- Webhook endpoints

---

*This workflow has been tested and used in production for 6+ months.*
