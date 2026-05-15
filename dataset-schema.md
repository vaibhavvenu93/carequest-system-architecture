# Dataset Schema

CareQuest can generate structured datasets from learner simulations.

## Core Dataset Objects

### 1. Learner

```json
{
  "learner_id": "CQ-001",
  "role_path": "ABAT/RBT Learner",
  "goal": "Certification readiness",
  "current_level": "Behavioral Apprentice"
}
{
  "scenario_id": "SC-001",
  "title": "Transition Refusal",
  "difficulty": "Beginner",
  "domain": "Autism Support",
  "competencies_tested": ["empathy", "safety", "communication", "reinforcement"]
}
{
  "response_id": "RS-001",
  "learner_id": "CQ-001",
  "scenario_id": "SC-001",
  "response_text": "I would stay calm and observe the trigger..."
}
{
  "evaluation_id": "EV-001",
  "response_id": "RS-001",
  "scores": {
    "empathy": 85,
    "safety": 80,
    "observation": 75,
    "reinforcement": 88,
    "communication": 82
  },
  "overall_score": 82,
  "recommended_next_mission": "Transition Planning Basics"
}
