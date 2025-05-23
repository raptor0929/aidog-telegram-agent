# AIDOG: Hierarchical AI Community Management System

![AIDOG Architecture](../public/aidog-infrastructure.png)

This is a hierarchical AI agent system for community management, with AIDOG as the high-level planner that coordinates specialized agents.

## System Architecture

AIDOG (Advanced Intelligence for Digital Engagement Networks) is a high-level planner that creates, manages, trains, and optimizes specialized community management agents:

1. **Engagement Agent**
   - Monitors social channels (Discord, Telegram, Twitter) for user queries
   - Drafts responses based on project knowledge base
   - Prioritizes engagement based on user influence and question importance

2. **Content Scheduling Agent**
   - Plans optimal timing for announcements and content
   - Coordinates posting schedules across platforms
   - Analyzes engagement patterns to optimize posting times

3. **Sentiment Analysis Agent**
   - Tracks community sentiment in real-time
   - Identifies potential community issues before escalation
   - Provides sentiment reports with actionable insights

4. **Growth Strategy Agent**
   - Analyzes community growth patterns
   - Suggests targeted campaigns for new community segments
   - Recommends incentive structures for participation
   - Performs comprehensive Web3 community metrics analysis

5. **Moderation Agent**
   - Identifies potentially harmful content
   - Flags suspicious users or potential scammers
   - Maintains community guidelines enforcement

6. **AIDOG Training System**
   - Trains agents with community-specific examples
   - Updates agent knowledge based on community feedback
   - Evaluates agent performance and makes improvements
   - Ensures responses align with community values and terminology

## AIDOG's Core Functions

AIDOG performs four core functions across these agents:

1. **Create Agents** - Establishes specialized agents with defined roles
2. **Manage Agents** - Coordinates agent activities and resource allocation
3. **Train Agents** - Improves agent performance through continuous learning
4. **Optimize Agents** - Continuously refines the community management workflow

## Advanced Agent Training System

AIDOG features a sophisticated training system that adapts each agent to the specific community it serves:

- **Community-Specific Knowledge Base**: Maintains structured data about community values, guidelines, common queries, terminology, and restricted topics
- **Agent-Specific Training**: Each agent maintains its own training examples and specialized knowledge
- **Performance Tracking**: Monitors agent accuracy and improvement over time
- **Contextual Learning**: Training examples include the context to help agents understand when to apply different responses

## LLM-Powered Response System

Responses are generated using an advanced Language Model (LLM) approach:

- **Intelligent Query Analysis**: Uses OpenAI API to analyze the intent, sentiment, and context of user queries
- **Contextual Response Generation**: Leverages community-specific knowledge to craft tailored responses
- **Fallback Mechanisms**: Includes graceful degradation to template responses when API is unavailable
- **Continuous Learning**: Improves over time as new training examples are added

## Enhanced Web3 Community Analysis

The system includes an advanced Web3 community analysis function that provides:

- Cross-platform metrics analysis (Discord, Telegram, Twitter)
- Growth rate comparison across different platforms
- Engagement and sentiment correlation analysis
- Retention metrics with actionable insights
- AI-generated recommendations based on community data

This feature demonstrates best practices for building custom functions with the GAME SDK:
- Strong input validation and error handling
- Default parameters for flexible usage
- Comprehensive data processing
- Actionable insights and recommendations

## Getting Started

1. Install dependencies:
   ```sh
   npm install
   ```

2. Configure your environment variables:
   ```sh
   mv .env.example .env
   ```
   Then edit the `.env` file to add your Telegram bot token and OpenAI API key.

3. Start the Aidog Telegram Agent:
   ```sh
   npm run aidog
   ```

You should see the message "🤖 Aidog Telegram Agent - Started" confirming that the agent is running successfully.

## System State

The system maintains a global state with community metrics:
- Community health score
- Engagement metrics
- Growth rate
- Sentiment analysis
- Member counts
- Pending announcements
- Recent issues
- Agent training examples
- Community-specific knowledge base

## Contributing

We welcome contributions to expand AIDOG's capabilities. See the [contribution guide](../../CONTRIBUTION_GUIDE.md) for more information. 