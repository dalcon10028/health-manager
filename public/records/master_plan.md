# 4-Week Master Workout Plan

This master plan is designed for gradual improvement in muscle mass and overall fitness, based on the user's profile. The agent should reference this plan to provide daily coaching.

**Frequency**: 3 gym sessions and 2 optional running sessions per week.
**Principle**: Progressive overload. Aim to increase weight or reps weekly when the target reps are achieved comfortably.

---

## Workout Schedule (4 Weeks, 12 Sessions)

| Session | Day | Exercise | Target_Sets | Target_Reps | Rest_sec |
| :--- | :--- | :--- | :---: | :---: | :---: |
| **Week 1-4** | | | | | |
| 1 | Day 1 (e.g., Monday) | 스쿼트 (Squat) | 4 | 5-8 | 90 |
| 1 | Day 1 (e.g., Monday) | 벤치프레스 (Bench Press) | 3 | 8-10 | 60 |
| 1 | Day 1 (e.g., Monday) | 덤벨 로우 (Dumbbell Row) | 3 | 8-10 | 60 |
| 1 | Day 1 (e.g., Monday) | 레그 프레스 (Leg Press) | 3 | 10-12 | 60 |
| 1 | Day 1 (e.g., Monday) | 플랭크 (Plank) | 3 | 60초 | 45 |
| | | | | | |
| 2 | Day 2 (e.g., Wednesday) | 데드리프트 (Deadlift) | 3 | 5 | 120 |
| 2 | Day 2 (e.g., Wednesday) | 오버헤드 프레스 (Overhead Press) | 3 | 8-10 | 60 |
| 2 | Day 2 (e.g., Wednesday) | 랫풀다운 (Lat Pulldown) | 3 | 8-10 | 60 |
| 2 | Day 2 (e.g., Wednesday) | 덤벨 런지 (Dumbbell Lunge) | 3 | 10-12 | 60 |
| 2 | Day 2 (e.g., Wednesday) | 레그 레이즈 (Leg Raise) | 3 | 15-20 | 45 |
| | | | | | |
| 3 | Day 3 (e.g., Friday) | 바벨 로우 (Barbell Row) | 4 | 5-8 | 90 |
| 3 | Day 3 (e.g., Friday) | 인클라인 덤벨 프레스 (Incline Dumbbell Press) | 3 | 8-10 | 60 |
| 3 | Day 3 (e.g., Friday) | 레그 컬 (Leg Curl) | 3 | 10-12 | 60 |
| 3 | Day 3 (e.g., Friday) | 사이드 래터럴 레이즈 (Side Lateral Raise) | 3 | 12-15 | 45 |
| 3 | Day 3 (e.g., Friday) | 바이시클 크런치 (Bicycle Crunch) | 3 | 20-25 | 45 |
| | | | | | |
| **...** | **...** | **(Repeat for 4 weeks, focusing on progressive overload)** | **...** | **...** | **...** |

---

## Optional Cardio Sessions

These can be performed in the evenings on non-gym days.

| Session Type | Day | Details | Duration |
| :--- | :--- | :--- | :--- |
| **Steady-State Cardio** | e.g., Tuesday | 가벼운 달리기 (Zone 2: 대화 가능한 속도) | 30-40분 |
| **Interval Cardio** | e.g., Thursday | 5분 웜업, (2분 빠르게 + 2분 천천히) x 5회, 5분 쿨다운 | 25-30분 |

---
### Notes for the Agent
- **Progressive Overload**: When providing guidance for the next session, check the user's last performance in `records/workouts.csv`. If the user successfully completed the target reps, suggest a small weight increase (e.g., +2.5kg) for the next session.
- **Flexibility**: The user has 2-3 gym days. The plan is based on 3 days, but if the user can only make it twice, suggest combining the most important compound lifts from two of the sessions.
- **Sleep**: Always consider the user's sleep pattern. If the user reports poor sleep, recommend maintaining the weight from the last session instead of increasing it, or slightly reducing the total volume.
