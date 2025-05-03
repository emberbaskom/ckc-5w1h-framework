# CKC-5W1H Framework

This repository contains the implementation scripts and sample phishing case data for the paper:

**"Enhancing Digital Forensics with Cyber Kill Chain and 5W1H: A Case Study on Phishing Attacks"**  
by Erika Ramadhani, Universitas Islam Indonesia.

## Overview

The CKC-5W1H framework is a web-based tool that automates digital forensic investigations by integrating:
- **Cyber Kill Chain (CKC)**: for mapping attack stages
- **5W1H Questions**: for contextual analysis (Who, What, When, Where, Why, How)

## Repository Structure

- `src/` – Source code for Flask-based implementation and analysis scripts.
- `data/` – Anonymized and simulated artifacts used in phishing case studies.
- `docs/` – Diagrams, sample outputs, and documentation.

## Getting Started

To run the web tool:
```bash
cd src
python app.py
```

Dependencies:
- Python 3.8+
- Flask
- Pandas
- JSON libraries

## License

This project is released under the MIT License.

## Citation

If you use this framework in your research, please cite the original paper:
> Ramadhani, E., Raharjo, T. (2025). Enhancing Digital Forensics with Cyber Kill Chain and 5W1H: A Case Study on Phishing Attacks. IJoICT.

## Contact

For any inquiries, contact: erika@uii.ac.id
