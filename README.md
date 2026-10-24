# Generic Medicine Saver
An ASI:One agent that shows cheaper generic alternatives
to branded medicines in India.

## What it does
- User asks in ASI:One (no login)
- Agent shows salt, brand vs generic price, savings
- 'book' creates a unique code for a partner store
- Store redeems the code (sale recorded)

## Run
python -m venv venv && venv\Scripts\activate
pip install uagents
python medicine_saver_agent_v2.py

## Test prompts
1. Augmentin 625 ka sasta option
2. book
3. redeem MS-XXXX

## Note
Demo uses sample/curated data. Not medical advice.
