# CSE Concept Laboratory

**Interactive Case Studies — Making Computer Science Concepts Intuitive**

🔗 **Live site:** [vicharanashala.github.io/cse-concept-laboratory](https://vicharanashala.github.io/cse-concept-laboratory/)

A project under **Vicharanashala Lab for Education Design**, Indian Institute of Technology Ropar (IIT Ropar).

---

## About

Abstract Computer Science ideas are hard to hold onto when the first encounter is a definition, a diagram, and a piece of terminology. This project takes a different approach: rather than telling students what a concept *is*, each case study places them inside a relatable situation where they watch a problem unfold, make their own decisions, and arrive at the underlying idea on their own. The formal name for the concept only shows up afterward, once the student already has something real to attach it to.

> **Show the problem first. Let the concept earn its name.**

## What We're Building

A library of story-based, visual learning templates. Each one follows the same learning journey:

1. **Think About the Problem**
2. **The Story**
3. **Play the Game**
4. **Reflection**
5. **Key Learning**
6. **Exercise**

This approach is designed to carry across many areas of Computer Science, including:

- Computer Networks
- Operating Systems
- Algorithms & Data Structures
- Databases
- Distributed Systems
- Artificial Intelligence
- ...and other abstract CS concepts

## Teaching Philosophy

- **Start with the problem** — not the definition. Every case study opens with a situation a student can step into, so the problem is felt before it's named.
- **Let the idea come first** — the concept name is held back until students have already experienced what it describes.
- **Show it happening** — students watch a process play out step by step, rather than just reading about it.
- **Help them discover, not memorize** — the goal is a connection students make for themselves.

## Case Studies

Explore the live case studies here: [vicharanashala.github.io/cse-concept-laboratory](https://vicharanashala.github.io/cse-concept-laboratory/#case-studies)

| # | Case Study | Status |
|---|------------|--------|
| 01 | Trapped Door | ✅ Available |
| 02 | Photo Day Lineup | ✅ Available |
| 03 | Fake Coin | ✅ Available |
| 04 | Birthday Gift | ✅ Available |
| 05 | The Griddle | ✅ Available |
| 06 | Missing Homework | ✅ Available |
| 07 | Nuts-and-Bolts | 🚧 Coming soon |
| 08 | Operation Padlock | 🚧 Coming soon |
| 09 | Junction Street | 🚧 Coming soon |
| 10 | The Blindfolded Archer | 🚧 Coming soon |

## Repository Structure

```
cse-concept-laboratory/
├── assets/                   # Images and logos
├── case_studies/             # Individual interactive case studies
├── case-study-template.html  # Starter template for new case studies
├── contribute.html           # Contribution guide
├── get-in-touch.html         # Contact page
└── index.html                # Landing page
```


## Contributing

Got an idea for making a tricky CS concept click? Students and contributors are welcome to design and build their own case study for this library. See [`contribute.html`](https://vicharanashala.github.io/cse-concept-laboratory/contribute.html) on the live site for details on how to get started, and use [`case-study-template.html`](./case-study-template.html) as a starting point for a new case study.

### 📋 PR Acceptance Criteria

**Please read this before raising any pull request.** Pull requests must follow the template exactly and meet our quality standards to be considered for merging.

- PRs must follow the template exactly.
- Only quality PRs will be merged.
- Please allow a minimum of two weeks for review and merging.

### How to Raise a PR
 
1. **Fork the repository** and clone it locally.
 
2. **Create a new branch** for your case study or fix (e.g. `case-study/your-topic-name`).
 
3. **Use the starter template** — build your case study from [`case-study-template.html`](https://github.com/vicharanashala/cse-concept-laboratory/blob/master/case-study-template.html) and place it inside `case_studies/your_case_study_name/`. Each case study should remain self-contained within its own folder.
 
4. **Follow the learning journey structure** — Think About the Problem → The Story → Play the Game → Reflection → Key Learning → Exercise — and keep to our [teaching philosophy](https://github.com/vicharanashala/cse-concept-laboratory#teaching-philosophy).
 
5. **Test locally** — open your case study file in a browser and confirm that it renders correctly and that all links and assets work.
 
6. **Add your case study to the main index if required** — make sure the case study is correctly linked from the repository's global `index.html`.
 
7. **Fill out the PR template exactly** as provided when you open the pull request. Incomplete or modified PR templates will not be reviewed.
 
8. **Submit your PR** against the `master` branch with a clear title and description explaining what the case study teaches and why.
 
9. **PR acceptance criteria**:
   - The case study must follow the provided case-study template and learning journey structure.
   - The PR template must be completed exactly as provided.
   - Only quality contributions that meet the project's standards will be merged.
   - Please allow a **minimum of two weeks** for review and merging.
   - You may be asked to make revisions before the PR is accepted.
 
10. **Be patient during review** — maintainers will review the contribution and may request changes before acceptance.

## Get in Touch

Have questions, feedback, or ideas? Visit the [Get in Touch](https://github.com/vicharanashala/cse-concept-laboratory/issues/new/choose) page on the live site.

## License

© 2026 Vicharanashala Lab for Education Design, IIT Ropar — All Rights Reserved.
