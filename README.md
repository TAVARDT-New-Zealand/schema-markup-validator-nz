# Schema Markup and Structured Data Validator | TAVARDT New Zealand

[![Schema Validator](https://img.shields.io/badge/TAVARDT-Schema.org%20Validator-5b3cf5.svg)](https://tools.tavardt.com/nz/schema-markup-validator/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-New%20Zealand-00C853.svg)](https://ag.tavardt.com/nz/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Independent structured data validator for New Zealand websites, auditing Schema.org markup, semantic tagging, and search engine entity recognition.

Engineered and maintained by the digital integrity and search architecture practice at **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## Semantic Validation Capabilities

* **Comprehensive Markup Parsing**: Ingests and inspects JSON-LD blocks and Microdata attributes embedded in web pages.
* **Entity Model Conformance**: Validates key schema representations including Organization, LocalBusiness, WebSite, Article, Product, and FAQPage.
* **Defect and Omission Identification**: Detects syntax parsing failures, missing required properties, and invalid data structures.
* **Semantic Rating Index**: Objective 0 to 100 metric with actionable technical guidance to achieve rich snippets eligibility.

---

## Installation and Execution

Requires Python 3.8 or higher with standard library.

```bash
git clone https://github.com/TAVARDT-New-Zealand/schema-markup-validator-nz.git
cd schema-markup-validator-nz
python schema_validator.py example.co.nz
```

For JSON format:

```bash
python schema_validator.py example.co.nz --json
```

---

## Online Validation Suite

For web-based testing and real-time schema evaluation:

* **[Official Schema Markup Validator](https://tools.tavardt.com/nz/schema-markup-validator/)**
* **[TAVARDT New Zealand Portal](https://ag.tavardt.com/nz/)**

---

## New Zealand Digital Architecture Advisory

For structured data implementation and technical compliance with NZ Web Standards and W3C Specifications, contact **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
