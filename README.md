# Threat Intelligence Platform 

This is a personal project where I am devolpmenting a open source threat intelligence dashboard. The goal is to collect public threat data like IPs, hashes, and domains, and then match it against log files.

---

## What it Does
- Pulls IOCs (Indicators of Compromise) from open sources like ALienVault adn MalwareBazaar
- Stores that data in a local SQLite database
- Lets users upload a .txt log files
- Matches log content agaisnt known IOCs and shows results in a web UI

---

## Tech Stack
- **Backend**: Python, FastAPI, SQLAlchemy
- **Frontend**: Streamlit (simple and clean UI)
- **Database**: SQLite (easy to swap out later if needed)
- **Tools**: GitHub, Render (for backend), Streamlit Cloud (for frontend)

---

## Project Structure 
- backend/ # FastAPI backend
- frontend/ # Streamlit UI
- data/ # Raw IOC feed dumps
- logs/ # Uploaded log files
- utils/ # Helper scripts (e.g., for parsing)
- tests/ # Unit tests


---

## Why I’m Building This
I wanted a project that would help me:
- Get better at handling real-world, messy data
- Practice working with APIs and logs
- Build something that connects cybersecurity and development
- Deploy something full-stack from scratch

---

## Status
🟡 Work in progress. I’m building this over 2 weeks, adding features daily.  
Check the [Issues](https://github.com/Avikandadi/threat-intel-platform/issues) tab to see what’s planned next.

---

##  License
MIT License – free to use, fork, or build on.




