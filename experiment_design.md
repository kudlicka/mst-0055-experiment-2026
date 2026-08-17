# MST 0055 Experiment Design (Fall 2026)

Date: 17 August 2026

## Background

Between 2021 and 2025, GRA 4142 (which MST 0055 replaces) showed a growing disconnect between measured outcomes and observed engagement: the A-share on the take-home exam (24 hours in Spring and Fall 2021, 30 hours thereafter) rose from 39% to 97%, while lecture attendance, in-class communication, and voluntary practice (solving homework problems and problems on Codewars.com) declined. The course is taught with an active-learning format: lecturing segments alternate with in-class exercises that students work on individually and in pairs.

The rise in the A-share is not explained by the course becoming easier — the exam format was unchanged throughout and the difficulty was targeted to be comparable, and the 2022 rise is partly explained by students then having the Fall 2021 exam as a worked example (ChatGPT was released only after that exam). From 2023 onward, however, the distribution kept compressing while every behavioral indicator I can observe moved gradually the other way: lecture attendance declined, the number of questions students asked in class fell, engagement with the in-class exercises weakened, fewer students answered questions I put to the class, and contact outside the classroom — students staying after class, emails, consultations — became steadily rarer, as did voluntary practice, both on homework problems and on Codewars. The trend has been more pronounced in some of my other courses than in GRA 4142, which held up comparatively well; but the direction is the same across all of them. High grades combined with low engagement is not a success story; it indicates that the assessment no longer measures learning. My hypothesis is that generative AI broke the take-home format: grades stopped measuring learning, which in turn made semester effort irrational for many students. When ChatGPT arrived I believed that being explicit about academic integrity, and about why students need these skills, would be sufficient; the data above says it was not, and this experiment is the consequence.

## Intervention (what changes in Fall 2026)

1. **Mandatory attendance** at 75% of lectures (the maximum BI permits), swappable for additional documented practice on Codewars.com (~300 extra points). The swap is there to allow flexibility for students who work alongside their studies or have conflicting schedules.

2. **Codewars requirement:** a minimum score (~300 points) during the semester.

3. **Assessment:** a 5-hour supervised, hands-on school exam (WISEflow with device monitoring) replaces the 30-hour take-home exam. Five hours is shorter than I would have preferred for a practical programming exam; it is the maximum length permitted, and even that required a written justification.

   **What does *not* change is what students are permitted to use.** In the take-home years the use of AI tools was already prohibited, while passive use of online material — documentation, tutorials, reference sites — was and remains allowed. The same rules apply to the supervised exam. The intervention is therefore not a change of policy but a change in *enforceability*: the prohibition that could not be enforced in a 30-hour take-home setting can be enforced under supervision. This matters for interpreting the grade distribution: if grades fall, the explanation cannot be that students lost access to resources they were previously entitled to use.

4. **Delivery structure (context, not an experimental variable).** The course runs twice in the same semester, with the same exam for everyone at the end of the semester:

   - **SH1 (first half, ~36 students):** students of the Master in Business Analytics, for whom the course is mandatory, plus some exchange students. This group continues in the second half of the semester to another course that uses Python.
   - **SH2 (second half, ~9 students):** students taking the course as an elective.

   The course also carries a new code, and the credit weight increases from 6 to 7.5 ECTS. The content is the same as in GRA 4142, and teaching time is nearly unchanged — 45 hours, against 48 hours where I had been granted an exception for additional hours — so the entire increase falls on expected self-study. The work requirements are consistent with that larger expected workload, which means the credit change and the intervention are not fully independent: part of the additional practice I now require is workload the course is formally expected to contain.

5. *(Confounds to acknowledge.)* Beyond the new code and the compressed delivery, the following features of this structure will shape any comparison with the GRA 4142 years, and the analysis below:

   - **Time between teaching and exam differs by group.** SH1 finishes teaching roughly half a semester before the exam; SH2 finishes shortly before it. Forgetting works against SH1, recency in favor of SH2.
   - **SH1 gets additional Python exposure** in its follow-on course between teaching and exam, which works in the opposite direction.
   - **Small numbers.** With roughly 45 students in total, and only ~9 in SH2, every percentage below is coarse — a single student is worth more than two percentage points overall, and more than ten in SH2. Group-level comparisons are therefore reported as observations, not as findings; no statistical test on SH2 alone would be meaningful.
   - **The credit weight has increased.** Students are formally expected to invest more hours than in the GRA 4142 years — whether they actually do is one of the things this experiment is trying to find out — which should in principle improve exam performance. It also means the effect of the work requirements cannot be cleanly separated from the effect of the credit increase.
   - **Exam results are anonymous.** BI's examination results cannot be linked to individual students, so exam performance cannot be broken down by group, nor related to attendance or Codewars data. All exam-level analysis is therefore at the level of the whole cohort.

## Hypotheses — falsifiable predictions

*The numbers below are my predictions, recorded before the semester starts so that the outcome can be compared against them rather than rationalized afterwards. Where no documented baseline exists, this is stated.*

**H1 (work requirements).** I predict that **85–95%** of students still enrolled at the end of their scheduled classes (SH1: mid-semester; SH2: end of semester) qualify for the exam, and that **15–30%** of those who pass the work requirements do so via the Codewars swap rather than attendance. I further predict that attendance settles close to the required minimum rather than well above it — the requirement re-establishes a floor but does not by itself restore a habit of attending beyond what is demanded; average attendance among those taking the attendance route: **75–85%**. *(No reliable attendance baseline exists for GRA 4142 — attendance was not systematically recorded then — so these figures cannot be compared with a documented past number. From Fall 2026 attendance is registered per session in Canvas, which establishes a documented baseline for future course instances.)*

**H2 (practice).** I predict that the Codewars score distribution shows a visible cluster just above the threshold (compliance-shaped rather than enthusiasm-shaped), that the median nonetheless exceeds the threshold by a clear margin, and that activity concentrates in the final weeks rather than spreading evenly across the course. Against the Fall 2025 baseline — where Codewars was recommended, not required, and only three of the students who registered and joined the course group reached the recommended score — even compliance-shaped behavior represents a large increase in practice volume.

**H3 (grades — the critical test).** Under a supervised exam, and under unchanged but now enforceable rules on permitted aids (no AI; passive use of online material allowed), I predict the grade distribution re-spreads: the A-share falls from 96–97% to **40–60%**, grades below B reappear (**10–20%** at C or lower), and the fail rate stays low (**<10%**).

This prediction can fail in two directions, and I will report either. If the A-share stays around 95%, my hypothesis is wrong: the take-home grades were probably honest, and the exams have simply been too easy. If, on the other hand, a large share of students fail — say, more than a quarter — I will treat that as a sign that something is wrong with the exam rather than as confirmation of my hypothesis. The cause could be the time available, tasks that turned out harder than intended, misalignment between the exam and what was actually taught, or the unfamiliar exam setting itself. Which of these it is has to be diagnosed from the answers, question by question — and in that case the exam says little about the AI hypothesis in either direction.

The exam is designed to target the same level of difficulty as in previous years, but this is a design intention, not a verifiable property: a 5-hour supervised exam cannot contain the same tasks as a 30-hour take-home exam, and no measure exists that would establish equivalent difficulty across the two formats. I will publish the exam assignments alongside the results so that others can judge for themselves.

Finally, a group-level comparison is not possible: exam results at BI are anonymous, so I cannot link grades to SH1 or SH2 membership. This is worth recording as a limitation of the experiment rather than a design choice — the two groups differ in exactly the way that would make the comparison interesting (SH1 has a longer gap to the exam but additional Python exposure in its follow-on course; SH2 has recency and no further practice), and with linkable results the comparison would be a natural small study of whether continued use or recency matters more for retention. It is one instance of a general problem I plan to raise through my institutional roles: permanent anonymization of exam results prevents the outcome analysis that evidence-based teaching development requires.

**H4 (satisfaction).** The new requirements may cost some goodwill; I predict an overall score of **at least 4.0** (on a 1–5 scale) in the end-of-term evaluation, at most a modest dip, and I accept that dip as a reasonable price for restoring the effort–outcome link. I further predict that free-text comments will be *divided rather than uniformly negative* — some students explicitly welcoming the structure, others objecting to compulsion. Mid-term and final evaluation surveys will ask students directly how they experience the mandatory attendance and the Codewars requirement.

## Data to collect

- Group membership (SH1/SH2) recorded for every student, so that the *non-exam* metrics below (attendance, Codewars, surveys) can be reported by group as well as overall. Exam results cannot be split this way (see above).
- Attendance: per-session records from Canvas's attendance function, giving per-student attendance rates for the whole semester.
- Codewars: registrations, score distribution, timing (steady practice vs. last-week rush).
- Exam: raw scores (total points per candidate and points per question, recorded at grading time) as well as the overall grade distribution. Results are anonymous and cannot be split by group or linked to attendance/practice data. To be compared against the GRA 4142 A-shares (Spring 2021: 39%; Fall 2021: 58%; Fall 2022: 87%; Fall 2023: 87%; Fall 2024: 96%; Fall 2025: 97%).
- Surveys: standard three-point cycle (pre-course, mid-term and final).
- Informal: office-hours visits, forum activity, students staying after class.

## Analysis and reporting

This document is finalized on 17 August 2026 before the start of teaching the course in Fall 2026 and will not be edited afterwards; anything I need to add later will appear as a separate, dated addendum.

Exam results are expected in January 2027, once the exams are graded. At that point I will compare each metric against its baseline and its prediction, and write up the outcome — including failures and surprises — as a short results report.
