# API Security Analysis: JSONPlaceholder

## Project Overview
This project is a non-intrusive security assessment of the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) API — a free, open-source "fake" REST API used by developers for testing and prototyping. The analysis identifies critical vulnerabilities based on the **OWASP API Security Top 10 (2023)** framework.

## Scope
The assessment is strictly limited to the public demo endpoints provided by **JSONPlaceholder**.
- **Allowed:** Testing public endpoints via documentation-based analysis and inspection of headers and response payloads.
- **Constraints:** Restricted to **read-only requests (GET)** and non-intrusive traffic analysis. No data modification, DoS, or brute-force attempts were performed.

## Methodology
The analysis follows a structured approach to identify and categorize risks:
1.  **Reconnaissance:** Reviewing endpoint structures and documentation.
2.  **Traffic Analysis:** Monitoring request/response cycles using Postman to inspect headers and payload structures.
3.  **Vulnerability Mapping:** Comparing observations against OWASP categories (e.g., BOLA, Security Misconfigurations).
4.  **Risk Rating:** Classifying findings by severity (High, Medium, Low) based on impact and likelihood.

## Tools Used
- [Postman](https://www.postman.com/): Primary API client for constructing requests and inspecting responses.
- [OWASP API Security Top 10](https://github.com/OWASP/API-Security): Foundational framework for threat modeling and vulnerability classification.

## Detailed Report
- Full Technical Report: [API Security Risk Analysis Report]()
- Evidence: [Postman Requests]()
