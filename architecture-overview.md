# Architecture Overview

## User Flow

Learner enters CareQuest through a training provider or certification partner.

The system then moves the learner through:

1. Goal assessment
2. Baseline competency check
3. Personalized mission path
4. Behavioral simulations
5. AI supervisor feedback
6. XP and badge progression
7. Certification readiness score
8. Workforce profile generation

---

## System Flow

```mermaid
flowchart TD

A[Learner Signup] --> B[Goal Assessment]
B --> C[Learning Path Assignment]
C --> D[Mission Engine]
D --> E[Behavioral Simulation]
E --> F[AI Supervisor]
F --> G[Competency Engine]
G --> H[Readiness Score]
H --> I[Workforce Profile]
I --> J[Training Provider Dashboard]
I --> K[Employer Matching Layer]
