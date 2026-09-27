A customer asks why their handover is delayed. The agent resolves customer and unit context through the ontology, retrieves the relevant policy via RAG, calls mock payment / CRM / service APIs, explains the delay, prepares the next action, and waits for human approval before any booking or financial action. All data is synthetic, for a fictional developer.

## Setup

1. Create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```
2. Activate it:
   ```bash
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Copy the example environment file and add your Anthropic API key:
   ```bash
   cp .env.example .env
   ```
   Then set `ANTHROPIC_API_KEY` in `.env`. The `.env` file is git-ignored; never commit it.
