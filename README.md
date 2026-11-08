# Reginald Alfret V — Portfolio (Django Stack)

Parallel Django implementation of the obsidian personal resume portfolio, maintaining full fidelity with the production Next.js 14 version at [reginaldalfret.tech](https://reginaldalfret.tech).

## Tech Stack
- **Framework**: [Django](https://www.djangoproject.com/) (v6.1.3)
- **Runtime**: Python 3.13.17 (64-bit)
- **Frontend Architecture**: Django Server-Side Rendered (SSR) Templates + Tailwind CSS
- **Styling**: Obsidian liquid-glass theme with `#050505` backdrop and ambient lighting
- **Asset Handling**: Embedded PDF visual viewer + print trigger + static PDF downloads

## Featured Sections
- **⚡ Open-Source Contributions**: 30 verified merged PRs across Apple, Google, Microsoft, Meta, AWS, NVIDIA, NASA, Netflix, Stripe, Intel, etc.
- **💼 Professional Experience**: Software Developer at DailyGurus, Data Science Intern at Data Patterns.
- **🚀 Key Projects**: 301 Super AI Agents (1st HackIndia 2026), TOR-UNVEIL (1st TN Police Hackathon 2025), AI Crop Recommendation Engine (1st Blaze a Trail 2.0).
- **🛠️ Technical Skills & Education**: B.Tech AI & Data Science (CGPA 8.2), certifications, and technical domains.

## Quick Start

```bash
# Create and activate virtual environment
python -m venv .venv
.\.venv\Scripts\activate   # On Windows
# source .venv/bin/activate # On Linux/macOS

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start local development server
python manage.py runserver 8001
```
Open [http://localhost:8001](http://localhost:8001) to view in browser.
