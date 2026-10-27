# Medical Report Analyzer

A Python-based project for working with medical report text and presenting report-related information through a web interface. The repository contains Python modules, an HTML page, and sample medical-report text files.

> **Disclaimer:** This project is for educational and informational purposes only. It is not a substitute for advice, diagnosis, or treatment from a qualified healthcare professional. Do not use its output as the sole basis for medical decisions.

## Project Contents

| File | Purpose |
|---|---|
| `Agent.py` | Agent-related Python logic |
| `Main.py` | Main Python module |
| `app.py` | Python application module |
| `index.html` | HTML page for the web interface |
| `Medical_Report.txt` | Sample medical-report text |
| `Medical_Report_1.txt` | Additional sample report |
| `Medical_Report_2.txt` | Additional sample report |
| `final_diagnosis.txt` | Text file containing diagnosis-related output or example content |

The repository also contains Python bytecode files generated for specific Python versions.

## Technology Stack

- **Python** — primary application language
- **HTML** — web-page structure

According to GitHub's language breakdown, the repository consists of approximately 75.1% Python and 24.9% HTML.

## Getting Started

### Prerequisites

- Python installed on your system
- Git installed on your system

### Clone the Repository

```bash
git clone https://github.com/maahii-in/Medical-Report-Analyzer.git
cd Medical-Report-Analyzer
```

### Create a Virtual Environment

**Windows:**

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**Linux or macOS:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install Dependencies and Run

Check the Python imports in `app.py`, `Main.py`, and `Agent.py` to identify the required packages and the application's entry point. Install the required dependencies in the activated virtual environment before starting the application.

## How to Explore the Project

1. Review the Python modules to understand the report-processing workflow.
2. Explore the sample report files to understand the expected input format.
3. Review `index.html` to understand the web interface.
4. Test the application with sample data and carefully verify any generated output.

## Responsible Use

Medical reports can contain sensitive personal information. Use synthetic or properly de-identified data during testing, store files securely, and ensure that any processing service is appropriate for the data being handled.

Any medical interpretation or diagnosis-related output must be reviewed by a qualified healthcare professional.

## Future Improvements

- Add a `requirements.txt` file to document Python dependencies.
- Document the exact command for starting the application.
- Add automated tests and example test data.
- Include screenshots or a demonstration of the interface.
- Add input validation and error handling.

## License

No license is visible in the repository screenshot. Add a `LICENSE` file if you intend to distribute the project under an open-source license.
