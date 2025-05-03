# CKC-5W1H Framework

This repository contains the implementation scripts and sample phishing case data for the paper:

**"Enhancing Digital Forensics with Cyber Kill Chain and 5W1H: A Case Study on Phishing Attacks"**  
by Erika Ramadhani, Universitas Islam Indonesia.

## Overview

The CKC-5W1H framework is a digital forensic automation tool that integrates:
- **Cyber Kill Chain (CKC)** for structured attack stage analysis
- **5W1H** (Who, What, When, Where, Why, How) for contextual forensic insights

It is developed to support investigations of phishing attacks by automating the identification and extraction of digital artifacts across all CKC phases.

## System Architecture

- **Frontend**: HTML5 + PHP (used for user authentication and access control)
- **Backend**: Python Flask framework
- **Database**: MariaDB (stores metadata and analysis results)
- **Server**: Debian OS
- **Output**: JSON file containing 5W+1H results from digital evidence extraction

## Repository Structure

- `src/` – Flask backend code and APIs
- `data/` – Sample anonymized phishing case artifacts in JSON format
- `docs/` – Documentation, architecture diagrams, and sample outputs

## Getting Started

To run the tool locally:

```bash
# Navigate to source directory
cd src

# Install dependencies (example)
pip install flask pymysql

# Run the app
python app.py
```

Ensure MariaDB is running and the database is configured.

## Output

The tool outputs structured JSON files summarizing the extracted 5W+1H information from each digital artifact, categorized by CKC phase.

Example:
```json
{
  "who": "Unknown",
  "what": "WhatsApp number scraping",
  "when": "2025-02-14T09:00:00Z",
  "where": "Public social media profiles",
  "why": "Credential collection",
  "how": "Scraping tool"
}
```

## License

This project is licensed under the PUSFID UII.

## Citation

> Ramadhani, E., Raharjo, T. (2025). Enhancing Digital Forensics with Cyber Kill Chain and 5W1H: A Case Study on Phishing Attacks. IJoICT.

## Contact

For inquiries, contact: erika@uii.ac.id
