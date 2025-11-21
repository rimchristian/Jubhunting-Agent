# Jubhunting-Agent

### A multi-agent AI system that automates job searching, generates tailored resumes, and prepares interview answers using Claude Sonnet 4.5

# Table of Contents

- Overview
- Features
- Installation
- Usage
- Output Examples
- Cost Analysis
- Roadmap
- License

# Overview
- AI Jobhunting Assistant is a multi-agent system that streamlines the job search process by leveraging Claude Sonnet 4.5 to provide personalized job matches, resume optimization, and interview preparation.

## The Problem
- Job hunting is time-consuming and overwhelming:
1. Searching across multiple job sites daily
2. Tailoring resumes for different roles
3. Preparing for diverse interview questions
4. Tracking applications and opportunities

## The Solution
- A modular AI system with 4 specialized agents that:

1. Searches for relevant opportunities across industries
2. Analyzes your background and identifies strengths
3. Generates tailored resume summaries for different roles
4. Prepares interview Q&As using the STAR method

## Impact

1. 70% time reduction in job search activities
2. 12 job matches per search with relevance scoring
3. 7 resume versions for different role types
4. 10 interview answers ready to practice
5. $0.15-0.20 per complete workflow

# Features
1. Agent 1: Job Market Researcher

- Searches for jobs across 6 industries (Data, Research, Operations, Recruiting, Hospitality, Customer Success)
- Supports both Korean and US markets
- Match scoring (1-10) based on your actual skills
- Priority categorization (High/Medium/Low)
- Optional real-time web search via Serper API
- Bonus: Generates 25+ manual search keywords for LinkedIn, 사람인, Indeed

2. Agent 2: Personal Profiler
- Analyzes your resume to identify top 5 transferable skills
- Extracts 3 quantified achievements
- Evaluates industry versatility
- Provides career pathway recommendations
- Articulates your unique value proposition

3. Agent 3: Resume Strategist
- Creates 7 customized resume summaries
- ATS-optimized with relevant keywords
- Highlights bilingual capabilities
- 3-4 sentences per summary (copy-paste ready)

4. Agent 4: Interview Coach
- Generates 10 interview questions with STAR method answers
- Uses YOUR actual experience in answers
- Provides career narrative guidance
- Addresses career transition concerns
- Suggests smart questions to ask employers

5. Bilingual Support
- English and Korean job search keywords
- Seoul market optimization
- Korean job site integration (사람인, 잡코리아)

# Installation
- Prerequisites
- Python 3.8 or higher
- Anthropic API key (Get one here)
- (Optional) Serper API key (Get free 2,500 searches)

# Quick Start
###  Clone the repository
git clone https://github.com/christian-rim/Jubhunting-Agent.git
cd ai-jobhunting-assistant

### Install dependencies
pip install anthropic
pip install 'crewai[tools]'  # Only if using Serper

### Set up environment variables
export ANTHROPIC_API_KEY="your-key-here"
export SERPER_API_KEY="your-key-here"  # Optional

### Update your resume in the code
### Edit CHRISTIAN_RESUME variable in jobhunting_assistant_FINAL.py

### Run it!
python jobhunting_assistant_FINAL.py

