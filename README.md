# SA_AI_EDUCATION

Repository containing research data and documentation about AI integration in Software Architecture education.

## Research Data

### data.md
Original survey data collected from 57 undergraduate Software Engineering students (27 from Class A, 30 from Class U) between November 3-9, 2025. Contains responses to three research questions in markdown table format:
- RQ1: AI Integration in Architecture
- RQ2: Architectural Modeling and Communication  
- RQ3: Learning and Practical Application


## 🕸️ Thematic Networks

Visual representations of thematic analysis results using Mermaid diagrams, showing research questions, codes, and their frequencies:

### rq1-network.md
**AI Integration in Cloud Architectures** - 6 themes with evidence examples:
- C1: Technical challenges, security, quality and cost (40/57 = 70.2%)
- C2: Positive perception and pedagogical value (32/57 = 56.1%)
- C3: Data, analysis and real-time decision-making (29/57 = 50.9%)
- C4: Automation, productivity and optimization (27/57 = 47.4%)
- C5: Modularity, scalability and decoupling (26/57 = 45.6%)
- C6: Architectural styles (23/57 = 40.4%)

Each theme includes bold-highlighted quotes from student responses correlating with quantitative frequencies.

### rq2-network.md
**Architectural Modeling and Communication** - 6 themes with evidence examples:
- C1: Understanding, visualization and clarity (48/57 = 84.2%)
- C2: Documentation, organization and standardization (46/57 = 80.7%)
- C3: Levels of abstraction / C4 Model (39/57 = 68.4%)
- C4: Flows, interactions and behavior / UML (36/57 = 63.2%)
- C5: Architectural decisions and justifications (35/57 = 61.4%)
- C6: Communication and alignment between stakeholders (28/57 = 49.1%)

Includes supporting quotes demonstrating how arc42, C4 Model, and UML facilitated learning.

### rq3-network.md
**Learning and Curricular Gaps** - 6 themes with evidence examples:
- C1: AI, cloud computing and modern architectures (54/57 = 94.7%)
- C2: Architectural understanding and systemic thinking (48/57 = 84.2%)
- C3: Practical learning and iteration (44/57 = 77.2%)
- C4: Architectural and systemic vision (43/57 = 75.4%)
- C5: Practical application in real scenarios (38/57 = 66.7%)
- C6: Modeling as a learning tool (15/57 = 26.3%)

Contains identified curricular gaps (MLOps, model drift, AI governance) and student quotes about practical application intentions.

## Analysis Tables

### table-coding-table.md
Complete codebook with definitions and example phrases for all 18 thematic codes (6 per research question). Each code includes:
- Code identifier (C1-C6)
- Theme name
- Definition
- Representative phrases in quotes

### table-course-outline.md
Educational context summary with 6 elements:
- Pedagogical Approach: Project-Based Learning (PBL)
- Core Content: Cloud Solution Architecture
- Styles & Patterns: Microservices, Serverless, BFF, Event-Driven, Clean Architecture
- Modeling: arc42, C4 Model, UML
- Generative AI: GitHub Copilot integration
- Final Delivery: Full-stack cloud application

### table-rq-questions.md
Research question mapping showing:
- RQ codes
- Full research question text
- Associated survey questions

### table-rq1-results.md
Frequency table for RQ1 themes with:
- Theme descriptions
- Count (n) and percentage (%) for each code
- Interpretation of results

### table-rq2-results.md
Frequency table for RQ2 themes with quantitative results and interpretation focusing on how modeling approaches supported learning.

### table-rq3-results.md
Frequency table for RQ3 themes showing dominant patterns in student learning experiences and intended future applications.

### table-rq3-gaps.md
Analysis of curricular gaps identified through low-frequency themes:
- MLOps and operational lifecycle
- Model drift and evolution
- AI governance and compliance

### table-interventions.md
Proposed pedagogical interventions to address identified gaps:
- Expanding AI lifecycle coverage
- Integrating governance discussions
- Strengthening operational practices

## Documentation Structure

All network files (rq1, rq2, rq3) include:
1. **Mermaid diagram** - visual network representation
2. **Interpretation** - thematic analysis summary
3. **Evidence Examples** - bold-highlighted student quotes organized by code
4. **Quantitative alignment** - frequencies matching survey data (n/N=57)

All table files use markdown format with clear headers and consistent structure for academic presentation.

## Research Context

**Study**: Using AI in Cloud Solution Architecture Education  
**Venue**: SBES 2026 Conference  
**Methodology**: Exploratory qualitative study with thematic analysis  
**Sample**: 57 undergraduate students (2 classes)  
**Technologies**: arc42, C4 Model, UML, Azure, GitHub Copilot  
**Architectural Patterns**: Microservices, Serverless, BFF, API Gateway, Event-Driven, Clean Architecture, Vertical Slice

## File Organization

```
├── data.md                      # Raw survey data
├── method-flow.md               # Research methodology diagram
├── rq1-network.md               # AI integration themes + evidence
├── rq2-network.md               # Modeling themes + evidence
├── rq3-network.md               # Learning themes + evidence
├── table-coding-table.md        # Thematic codebook
├── table-course-outline.md      # Educational context
├── table-rq-questions.md        # Research question mapping
├── table-rq1-results.md         # RQ1 frequency analysis
├── table-rq2-results.md         # RQ2 frequency analysis
├── table-rq3-results.md         # RQ3 frequency analysis
├── table-rq3-gaps.md            # Curricular gaps analysis
└── table-interventions.md       # Proposed interventions
```

All files are in English (translated from original Language survey data) and ready for academic publication.