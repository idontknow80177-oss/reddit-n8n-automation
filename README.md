# Reddit n8n Automation

An individual developer project exploring Reddit Data API integration with n8n for keyword-based discussion discovery, AI-assisted analysis, and structured reporting.

## Project Status

**In Development**

The project is currently in the planning and setup stage. Reddit API access has been requested and is subject to approval. API integration and workflow testing will begin once the required access is available.

## Project Overview

The goal is to build an external workflow automation system using n8n that helps users discover relevant public Reddit discussions and organize permitted information for research and learning.

The workflow is intended to connect Reddit's authorized API access with automation, AI-based text analysis, and Google Sheets reporting.

## Planned Features

### 1. Keyword-Based Search
- Accept user-defined keywords and topics.
- Retrieve relevant public posts through authorized API access, where permitted.
- Preserve links to original Reddit discussions.

### 2. Discussion Categorization
- Organize relevant posts by topic.
- Identify recurring questions and common discussion themes.
- Generate AI-assisted summaries of permitted content.

### 3. Google Sheets Reporting
- Store permitted post information in a structured format.
- Include fields such as keyword, subreddit, post title, post URL, publication timestamp, topic category, and summary, where available and permitted.
- Allow users to review the original discussions and verify generated insights.

### 4. Scheduled Monitoring
- Explore scheduled checks for new relevant discussions, subject to API permissions and rate limits.
- Avoid unnecessary repeated requests.

## Planned Workflow Architecture

User Keywords → n8n Workflow → Authorized Reddit API Request → Data Validation and Filtering → AI-Assisted Analysis → Google Sheets

This architecture is a proposed design and has not yet been implemented or tested end to end.

## Technology Stack

- **n8n:** Workflow automation and orchestration
- **Reddit Data API:** Authorized access to permitted Reddit data
- **JavaScript:** Data transformation and validation
- **AI Model:** Text categorization and summarization, subject to applicable policies
- **Google Sheets:** Structured reporting and review

## Responsible Data Use

The project is intended to comply with Reddit's applicable Developer Terms, Data API Terms, access permissions, and rate limits.

The planned workflow will not automatically publish posts or comments, send unsolicited messages, vote, manipulate engagement, bypass access restrictions, or access private or restricted content without authorization.

API credentials and tokens will be stored outside the public repository. Data collection, AI processing, storage, and retention will be limited to permitted purposes and applicable requirements.

## Current Limitations

- Reddit API access is pending approval.
- The Reddit integration has not yet been implemented.
- The planned features and workflow architecture are not yet verified.
- Actual functionality will depend on the access and permissions granted by Reddit.

## Purpose

This project is an individual learning and development initiative focused on practical API integration, workflow automation, and responsible analysis of public online discussions.

**Repository:** https://github.com/idontknow80177-oss/reddit-n8n-automation

