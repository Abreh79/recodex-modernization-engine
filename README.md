# RECODEX // Enterprise Legacy Modernization Studio

RECODEX is an AI-powered Enterprise Legacy Modernization Studio designed to transpile legacy mainframe routines (COBOL-85, Fortran) into production-ready Go microservices, Python FastAPI applications, and Java Spring Boot services with 100% mathematical logic parity.

![RECODEX Architecture](https://img.shields.io/badge/AST%20Engine-Armed-00f2fe?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)

---

## Key Features
- **3-Panel Interactive Studio**:
  - **Panel 1 (Legacy Source Editor)**: Preloaded COBOL-85 routines (`LOAN-INTEREST-CALC`, `PAYROLL-DEDUCT-BATCH`, `GL-POSTING-JOURNAL`) with live line numbers and custom editor capabilities.
  - **Panel 2 (Forensic AST & Deconstruction Terminal)**: Live 4-stage streaming terminal output parsing copybooks, graphing execution paths, compiling target ASTs, and generating test vectors.
  - **Panel 3 (Modern Target & Parity Verification)**: Idiomatic target code generation, automated unit test suites, and high-level Executive Summaries.
- **Polyglot Target Synthesis**: Instant transpilation to Go, Python (FastAPI/Pydantic), and Java (Spring Boot).
- **Full-Stack .ZIP Container Exporter**: One-click export of production packages containing `service.*`, `parity_test.*`, `AUDIT_EXECUTIVE_SUMMARY.md`, `Dockerfile`, and `README.md`.
- **AI Core with Fallback Engine**: Integrated with Gemini API for deep qualitative refactoring and backed by an offline local AST deconstruction parser.

---

## Quickstart

### Prerequisites
- Python 3.10+
- Dependencies: `fastapi`, `uvicorn`, `requests`, `pydantic`

### Installation & Run
```bash
# Clone the repository
git clone https://github.com/Abreh79/recodex-modernization-engine.git
cd recodex-modernization-engine

# Install dependencies
pip install fastapi uvicorn requests pydantic

# Set optional Gemini API key
export GEMINI_API_KEY="your-api-key-here"

# Start the studio
python3 app.py
```

Open your browser at `http://localhost:8080`.

---

## License
MIT License
