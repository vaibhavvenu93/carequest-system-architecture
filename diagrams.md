# CareQuest Architecture Diagrams

## 1. Learner Lifecycle

```mermaid
flowchart TD

A[Learner Enters Through Training Partner] --> B[Goal Assessment]
B --> C[Baseline Competency Check]
C --> D[Personalized Mission Path]
D --> E[Behavioral Simulations]
E --> F[AI Supervisor Feedback]
F --> G[XP + Level Progression]
G --> H[Certification Readiness Score]
H --> I[Verified Workforce Profile]
I --> J[Placement / Employer Matching]
```

---

## 2. Competency Loop

```mermaid
flowchart TD

A[Scenario Attempt] --> B[Learner Response]
B --> C[AI Evaluation]
C --> D[Competency Scores]
D --> E[Strengths + Gaps]
E --> F[Recommended Mission]
F --> G[Retry / Practice]
G --> A
```

---

## 3. Simulation Pipeline

```mermaid
flowchart TD

A[Case Library] --> B[Scenario Generator]
B --> C[Learner Simulation]
C --> D[Response Capture]
D --> E[AI Supervisor]
E --> F[Scoring Engine]
F --> G[Readiness Engine]
G --> H[Workforce Graph]
```

---

## 4. Training Provider Dashboard Flow

```mermaid
flowchart TD

A[Learner Cohort] --> B[Mission Completion Data]
A --> C[Simulation Data]
A --> D[Readiness Scores]

B --> E[Training Provider Dashboard]
C --> E
D --> E

E --> F[Completion Risk Alerts]
E --> G[Exam Readiness Insights]
E --> H[Placement-Ready Learners]
```

---

## 5. Long-Term Platform Architecture

```mermaid
flowchart TD

A[Training Organizations] --> B[CareQuest Platform]
C[Colleges] --> B
D[Care Providers] --> B

B --> E[Learning Engine]
B --> F[Simulation Engine]
B --> G[AI Supervisor]
B --> H[Competency Engine]
B --> I[Workforce Graph]

I --> J[Certification Readiness]
I --> K[Employer Matching]
I --> L[Global Care Workforce Analytics]
```
