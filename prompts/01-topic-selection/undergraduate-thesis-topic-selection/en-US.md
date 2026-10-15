# Undergraduate Thesis Topic Selection AI Prompt Handbook

## A Complete Workflow from Major Direction to Final Topic

## I. First Understand: What Problems Must Topic Selection Solve?

A sound thesis topic should answer at least six questions:

1. **What to study?** What is the research object, phenomenon, variable, or text?
2. **Why study it?** Does the question have practical relevance, theoretical value, or disciplinary value?
3. **How far has prior research gone?** What are the main views, methods, and findings in existing work?
4. **What still deserves further study?** Is it a different object, a different context, contested claims, or limits of existing methods?
5. **How will you study it?** Can you obtain materials, samples, data, cases, or primary texts?
6. **Can you finish it yourself?** Do the scope, disciplinary competence, time, and resources match?

When selecting a topic, do not only ask AI to “recommend 20 thesis titles.” That kind of request often yields a set of titles that sound plausible but may lack research value or feasibility.

The right approach is to break topic selection into stages and move forward step by step.

Recommended sequence:

**Clarify your own conditions → Define a research direction → Form problem leads → Search existing research → Identify potential research space → Assess feasibility → Narrow the scope → Define the research question → Finalize the topic.**

The prompts in this handbook can be used separately or in sequence within the same conversation.

# II. Before You Start: Give AI the Necessary Background

The quality of AI responses depends heavily on whether you provide sufficiently concrete information.

Before using the topic-selection prompts below, prepare the following materials.

| Information | What you need to fill in | Why it matters |
| ----------- | ------------------------ | -------------- |
| Major | e.g., Business Administration, Chinese Language and Literature, Computer Science and Technology | Sets the disciplinary boundary of the topic |
| Degree stage | Undergraduate thesis, course paper, etc. | Determines research difficulty and depth |
| Institutional requirements | Word count, deadline, topic restrictions, method requirements | Avoids titles that fail to meet requirements |
| Personal interests | Industries, phenomena, problems, or fields of interest | Strengthens willingness to sustain the research |
| Courses taken | Statistics, management, law, literary theory, etc. | Helps judge whether subject knowledge is adequate |
| Research methods | Survey, interview, case study, textual analysis, experiment, program implementation, etc. | Determines whether the topic can be executed |
| Data resources | Access to firm materials, public data, interviewees, or experimental conditions | Helps judge whether the study can proceed |
| Time budget | Remaining weeks; hours available per week | Controls topic scale |
| Existing foundation | Papers read, coursework, internship or project experience | Helps find more concrete problem leads |
| AI-use rules | Institutional rules on topic selection, search, analysis, etc. | Clarifies the allowed boundary of AI use |

If you do not yet know some items, fill in “uncertain.” Do not invent conditions just to complete the table.

## Prompt 01: Build a Thesis Topic Background Profile

**Applicable stage: First use of AI.**

**Purpose:** Help AI understand who you are, what research conditions you have, and what constraints later suggestions must respect.

Copy the following prompt:

You now need to help me prepare for thesis topic selection based on my real study situation and institutional requirements.

Please note: you must first check the AI-use rules I provide from my institution. Only when those rules allow it may you help generate or compare specific topics. If the rules are unclear, mark them explicitly as “needs confirmation”; do not assume that every use is permitted.

My basic information is as follows:

- Major: [fill in major]
- Degree stage: [e.g., undergraduate thesis]
- Thesis type: [theoretical research, empirical research, case study, design/development, other]
- Basic institutional requirements for the thesis: [fill in]
- Topic requirements from the college or supervisor: [fill in]
- Currently known AI-use rules: [paste the specific rules; if unclear, write “unclear”]
- Fields I am relatively interested in: [fill in; may list more than one]
- Fields I am not interested in or unwilling to study: [fill in]
- Main courses I have taken: [fill in]
- Research methods or tools I am good at: [fill in]
- Research methods or tools I am unfamiliar with: [fill in]
- Materials, data, or research objects I can currently obtain: [fill in]
- Whether I have access to fieldwork channels such as firms, schools, communities, or institutions: [fill in]
- Expected completion time: [fill in]
- Other constraints: [fill in]

Please do not generate a final thesis title yet.

Step 1: Organize my personal research conditions, including disciplinary strengths, interest base, research capacity, data resources, and practical constraints.

Step 2: Distinguish the following:

1. Facts already clarified.
2. Information that remains uncertain.
3. Key constraints that may affect topic selection.
4. Conditions I must confirm myself.

Step 3: Judge which research types I should prioritize, such as literature research, case study, questionnaire survey, interview research, experimental research, data analysis, textual analysis, or design/development.

Step 4: Explain what materials, subject knowledge, and workload each research type requires. Do not recommend a method merely because it is popular.

Step 5: Until there is clear permission to proceed with topic exploration, do not treat speculation as fact.

Please output in clear tables and give the three next questions most worth resolving.

Output principles: do not exaggerate my ability, invent my resources, assume I can obtain any data, or package complex research methods as easy tasks.

**Usage tip:** The point of this prompt is not to get a title immediately, but to build a realistic research-conditions profile. Every later step should rest on this profile.

# III. Stage One: Find a Research Direction That Fits You

For many undergraduates, the difficulty is not that they cannot invent titles, but that they know only the name of their major and not what they can actually study.

For example, Business Administration covers human resources, organizational behavior, marketing, operations management, strategic management, and more. “Studying business management” is still too broad and needs further decomposition.

## Prompt 02: Find Research Directions from Disciplinary Knowledge

**Applicable stage: Unsure what to study.**

Based on my major, help me build a layered map of thesis research directions.

My information is as follows:

- Major: [fill in]
- Research stage: [fill in]
- Courses I am relatively interested in: [fill in]
- Real-world settings I am relatively familiar with: [fill in]
- Materials or research resources I have: [fill in]
- Constraints set by institutional rules: [fill in]

Please complete the analysis in the following steps.

### Step 1: Decompose the disciplinary field

Split my major into several main research directions, and list at least three concrete sub-directions under each.

Do not stop at broad labels such as “education research,” “business management,” or “literary studies.”

### Step 2: Find problems that can be studied

For each sub-direction, propose problem leads from the following angles:

- Phenomena that exist in real life.
- Difficulties encountered in practice.
- Differences across groups.
- Causes of a given phenomenon.
- Changes after a policy or measure is implemented.
- Controversies among existing views.
- Differences across cases.
- Possible boundary conditions or limits of existing research.

The output here should be “problem leads worth investigating,” not merely thesis titles with reworded phrasing.

### Step 3: Match my actual conditions

For each problem lead, annotate:

- Degree of disciplinary fit.
- Knowledge requirements.
- Possible research methods.
- Necessary data or materials.
- Difficulty of obtaining those materials.
- Possible ethical or access issues.
- Suitability as an undergraduate thesis.

### Step 4: Form candidate directions

Prioritize directions that match my interests, disciplinary foundation, and existing resources.

Do not treat “popular,” “easy to pass,” or “lots of online materials” as equivalent to research value.

Finally, provide a research-direction map and select directions worth further examination.

Mark separately “preliminary conjectures based on common sense” and “the research status confirmed by existing literature.” Do not claim that a direction has a research gap before literature has been searched.

## Prompt 03: Infer Topic Directions from Interests

**Applicable stage: Limited understanding of the major; unsure what you like.**

I am currently unsure what I am truly suited to study. For now, do not decide a title for me. Instead, use a series of targeted questions to help me discover possible research interests.

Please ask questions sequentially along the following dimensions:

1. What phenomena do I usually pay attention to on my own?
2. Which courses or disciplinary topics have raised questions for me?
3. Have I noticed any real-world contradiction worth explaining?
4. Have I encountered firms, works, social groups, or technologies worth analyzing?
5. Which questions am I willing to spend several weeks researching materials for?
6. Am I more inclined to explain causes, compare differences, evaluate effects, analyze texts, or design and implement a solution?
7. Am I better at reading, writing, communicating, statistics, programming, experiments, or case analysis?
8. What resource limits can I clearly not overcome?

You may ask three related questions at a time and gradually narrow the scope based on my answers.

After gathering enough information, please output:

- My interest themes.
- The disciplinary problems behind those interests.
- Possible research directions.
- The research object corresponding to each direction.
- Materials needed to further validate each direction.
- Uncertainties that still remain.

Do not infer that I have adequate research capacity merely from my interests; do not package any interest as an academically innovative topic just to please me.

## Prompt 04: Turn Hot Topics into Research Questions

**Applicable stage: You have found a hot field and want to build research around it.**

The field I am following is: [fill in, e.g., the impact of artificial intelligence on enterprise work].

Do not turn this hot topic directly into a thesis title. Instead, decompose it step by step as “macro topic → concrete phenomenon → research object → concrete question → verifiable question.”

Please identify the following types of research entry points:

1. **Object entry:** Are there differences across groups, organizations, or settings that are worth explaining?
2. **Mechanism entry:** Through what process might a phenomenon occur? Can existing theory explain it?
3. **Context entry:** Might an existing conclusion be affected by specific conditions?
4. **Method entry:** Are existing methods suitable for solving the problem? Is another method needed?
5. **Application entry:** What concrete problems in practice remain insufficiently addressed?
6. **Controversy entry:** What disagreements exist among research or practice views, and do they arise from different conditions or evidence?

For each entry point, provide:

- A concrete problem statement.
- A preliminary reason why it is worth investigating.
- Keywords to search.
- Possible research objects.
- Usable evidence or materials.
- Suitable research methods.
- Assumptions that have not yet been verified.

Please pay special attention:

- Popularity is not the same as novelty.
- A new concept is not the same as a new problem.
- Being the first to use a technology in an industry does not by itself constitute academic novelty.
- Without reviewing related research, do not assert that an entry point is “the first study at home or abroad” or “completely unstudied.”

Finally, retain problem leads rather than rushing to finalize a title.

# IV. Stage Two: Turn Broad Themes into Concrete Questions

The most common problem in topic selection is that a title sounds professional but lacks a clear research object, research boundary, and question that must be answered.

For example:

- Broad theme: Artificial intelligence and university students.
- More concrete phenomenon: University students using generative AI to support learning.
- Research-question lead: Do different usage patterns relate to differences in learning engagement?
- Research question that needs verification: With student year, course setting, and usage mode specified, how do existing studies measure this relationship? Are existing conclusions consistent? Can reliable data be obtained?

Note that the last question is only an example. It does not mean the relationship actually exists, still less that a research gap exists there.

## Prompt 05: Break a Broad Theme into Concrete Research Questions

The theme I plan to study further is: [fill in].

Please help me turn this theme into a set of concrete, clear candidate questions with research potential.

Please carry out the following tasks in order.

**Task 1: Define the theme.**

Clarify the core concepts in this theme, possible research objects, settings in which it occurs, and main problems.

If the theme contains vague terms, point out how different interpretations may change the research scope.

**Task 2: Split the questions.**

Around this theme, propose several different types of questions, including at least:

- Descriptive questions: What features does a phenomenon show?
- Comparative questions: What differences exist across groups, periods, or cases?
- Explanatory questions: Which factors may explain a phenomenon?
- Mechanism questions: Through what process might a relationship occur?
- Evaluative questions: What effects has a policy, product, or measure produced?
- Application questions: What unresolved problems exist in concrete practice?

Not every question type fits the current theme; judge applicability according to research conditions.

**Task 3: Check researchability.**

For each candidate question, answer:

1. Can the research object be clearly defined?
2. Can an answerable question be posed, rather than an abstract slogan?
3. Can related theory or prior research be found?
4. Is obtainable evidence available?
5. Does it require models, experiments, or data beyond undergraduate capacity?
6. Are there ethical, privacy, access, or data-compliance risks?

**Task 4: Form a candidate-question list.**

Please output in a table:

| Candidate question | Research object | Key concepts | Evidence needed | Method direction | Main risks |
| ------------------ | --------------- | ------------ | --------------- | ---------------- | ---------- |
|                    |                 |              |                 |                  |            |

Do not treat goal slogans such as “raise the level,” “promote development,” or “improve mechanisms” as already clear research questions.

If a question cannot yet be answered, point out what evidence is missing rather than inventing conclusions for me.

## Prompt 06: Identify the Real Contradiction in a Problem

The phenomenon I am currently focusing on is: [fill in the concrete phenomenon].

Please help me judge whether this phenomenon contains a contradiction, difference, or explanatory difficulty worth studying.

Please analyze from the following angles:

1. Is there a gap between real-world goals and actual performance?
2. Might there be a difference between theoretical expectations and practical performance?
3. Have different studies reported inconsistent results?
4. Might different groups or contexts show different patterns?
5. Might a measure produce different results under different conditions?
6. Has a phenomenon been oversimplified so that internal differences are ignored?

For each possible contradiction, provide:

- An accurate statement of the contradiction.
- The type of evidence that would support the existence of this problem.
- Research that needs to be searched.
- Possible alternative explanations.
- What results would weaken the research value of this problem.
- Whether a concrete research question can be formed.

Strictly distinguish “phenomena I observed,” “findings reported in existing literature,” and “hypotheses proposed for later research.”

Where there is no factual or literature basis, mark the item as pending verification.

## Prompt 07: Judge Whether a Topic Is Too Broad

The topic I am currently considering is: [fill in the title or research direction].

From the completion conditions of an undergraduate thesis, assess whether the research scope is too large.

Please check the following dimensions:

- Whether the research object is too broad.
- Whether multiple independent questions are involved at once.
- Whether too many core variables or theories are included.
- Whether it spans too many regions, industries, groups, or time ranges.
- Whether it requires large amounts of inaccessible data.
- Whether it requires complex technical methods or experiments that are hard to complete.
- Whether it easily becomes a vague essay that introduces the status quo, lists problems, and offers suggestions.

Then propose three narrowing layers in order:

**Layer 1:** Narrow the research object.

**Layer 2:** Limit the concrete setting, time range, case range, or key question.

**Layer 3:** Reduce the research goal to one core question that limited evidence can answer.

For each layer, explain what workload it reduces and what research value it may sacrifice.

Finally, give several title directions for further verification, and make clear which choices depend on material conditions that have not yet been verified.

Do not treat a topic as sufficiently concrete merely by adding “taking X as an example.”

# V. Stage Three: Use Literature Search to Judge Whether a Topic Is Worth Studying

This is a critical step in the whole topic-selection process.

AI can help you generate keywords, build search strategies, organize literature, and summarize possible controversies. But note carefully: **When AI says a field has “relatively little research,” that does not mean the field truly has little research.**

Without actually searching related literature, AI cannot reliably confirm a research gap for you. Author names, paper titles, journals, years, and DOIs it provides may also be wrong.

At this stage, it is best to have AI work from papers, abstracts, search results, or full texts that you have actually found.

## Prompt 08: Generate an Academic Database Search Strategy

My major is: [fill in].

My candidate research direction is: [fill in].

The question I am currently considering is: [fill in].

Please design a search strategy I can execute in academic databases.

### 1. Extract core concepts

Break the question into several core concepts and identify:

- Core concepts and their definitions.
- Common synonyms.
- Distinctions between academic terms and everyday expressions.
- Related theory names.
- Variables, objects, or settings related to the research question.
- Possible English terms and their variant spellings.

### 2. Build a search-term matrix

Please output in the following form:

| Concept category | Chinese keywords | English keywords | Synonyms or related terms | Search purpose |
| ---------------- | ---------------- | ---------------- | ------------------------- | -------------- |
|                  |                  |                  |                           |                |

If a Chinese concept has no unique, stable English equivalent, list possible translations and note what needs to be checked.

### 3. Design combined search strings

Generate separately:

1. A broader preliminary search string.
2. A search string focused on the core question.
3. A search string focused on theory or key variables.
4. A search string focused on a specific group or setting.
5. Search strings for finding existing reviews and systematic reviews.

Make as much use as possible of AND, OR, NOT, phrase searching, and field-search rules supported by databases.

Do not assume that all databases support exactly the same advanced search syntax. Separate general search logic from platform-specific syntax.

### 4. Set screening rules

Suggest appropriate inclusion and exclusion criteria, for example:

- Degree of relevance to the research question.
- Document type.
- Research objects and settings.
- Year range.
- Whether methods are clear.
- Whether there are clear research findings.
- Whether the original text can be obtained.
- Whether it is a high-quality review, theoretical study, or empirical study.

Do not mechanically require that all literature be published in the last five years before understanding the field’s development history.

### 5. Design a search log

Design a literature-search recording template for me, including at least:

- Search date.
- Database name.
- Full search string.
- Number of search results.
- Number screened.
- Reasons for inclusion and exclusion.
- Keywords that need to be added next.

Finally, provide a search plan I can execute and verify myself. Do not pretend you have already searched databases you have not accessed.

## Prompt 09: Turn Existing Literature into a Research Map

**Prerequisite: You have already found a set of real papers in formal databases.**

I will provide real literature materials related to the candidate topic, including title, author, year, abstract, and keywords, and full text when necessary.

My candidate research direction is: [fill in].

Please organize a research map based only on the materials I provide. Do not add unverified papers, authors, findings, or citation information on your own.

Please analyze from the following angles:

1. What questions do these papers study?
2. What theories or conceptual frameworks do they mainly use?
3. What differences exist in research objects, samples, settings, or periods?
4. What common research methods appear?
5. What results do these papers actually report?
6. Are there inconsistent conclusions, limits of research objects, method limits, or different boundary conditions?
7. Which questions have already been discussed fairly fully?
8. Which questions deserve further searching and verification?

Link each judgment to specific papers. If the materials are insufficient for a judgment, write clearly “existing materials are insufficient to judge.”

Please output four parts:

**Part 1: Literature classification table.**

| Paper ID | Research question | Theory or concepts | Object and method | Core findings | Limits |
| -------- | ----------------- | ------------------ | ----------------- | ------------- | ------ |
|          |                   |                    |                   |               |        |

**Part 2: Research-theme map.**

Explain which research themes the existing literature can be grouped into, and list the paper IDs supporting each theme.

**Part 3: Research disagreements and potential shortcomings.**

Clearly distinguish limits that authors themselves acknowledge in the original texts, differences observable across studies, and unverified conjectures based only on the current materials.

**Part 4: Further search suggestions.**

For each possible research space, list:

- What literature needs to be sought further.
- What keywords are recommended.
- What facts still need to be verified.
- What results might overturn the current judgment.

Do not directly declare “no research at home or abroad,” “fills an academic gap,” or “is pioneering.”

## Prompt 10: Judge Whether There Is Genuine Research Space

The candidate title I am examining is: [fill in].

Below are the literature materials or literature-analysis results I have collected so far:

[Paste real search results, literature lists, or the research map prepared earlier]

Please help me judge whether this title has research space that can be argued for.

Pay special attention: research space does not mean that no one has studied it at all. Valuable research may come from verifying existing conclusions, testing applicability in different contexts, explaining inconsistent results, refining conceptual definitions, improving methods, or analyzing real-world problems in depth.

Please check in order:

1. Has existing research already directly answered my core question?
2. Are there verifiable differences in conclusions across existing studies?
3. Is there a sufficient reason for changes in research object, time, or setting, rather than merely changing a region or school?
4. Are there problems in theoretical explanation or measurement?
5. Can enough evidence be obtained to advance the research?
6. Compared with existing literature, what specifically does the proposed question add?
7. Is that addition worth the corresponding research cost?

Please output in the following table:

| Potential research space | Literature evidence | Current support level | What evidence is still missing | Value for an undergraduate thesis |
| ------------------------ | ------------------- | --------------------- | ------------------------------ | --------------------------------- |
|                          |                     |                       |                                |                                   |

For each research space, use descriptions such as “has preliminary support,” “insufficient evidence,” or “existing materials do not support it.” Do not pretend to have complete coverage of the entire field.

Finally, give conclusions on:

- Whether it is currently worth continuing to consider this title.
- The three types of literature most in need of supplementation.
- Which claims cannot yet be written into a proposal.
- Which additional search results would affect the final decision.

## Prompt 11: Assess Whether Literature Is Enough to Support an Undergraduate Thesis

The topic I am considering is: [fill in].

The literature I have collected so far is as follows:

- Number of Chinese-language papers: [fill in]
- Number of foreign-language papers: [fill in]
- Core-journal papers or important studies: [fill in]
- Related reviews: [fill in]
- Number of full texts actually obtainable: [fill in]
- Literature directly related to the concrete research question: [fill in]
- Main publication years of the literature: [fill in]

Do not judge whether materials are adequate solely by the total number of papers.

Please focus on assessing:

1. Whether the literature directly addresses the research question.
2. Whether there is a necessary theoretical foundation.
3. Whether the main research progress on the question can be understood.
4. Whether there is enough material to compare different views and methods.
5. Whether there is too much duplicated, low-relevance, or unverifiable literature.
6. Whether key classic studies, authoritative standards, or recent advances need to be added.
7. Whether I can obtain the primary materials or full texts needed for analysis.

Distinguish “insufficient literature quantity” from “an unreasonable coverage structure of relevant literature.”

Finally, give a clear conclusion: continue the research, supplement the search and then judge, or recommend changing direction. All conclusions must be based on the materials I provide; do not invent literature counts or the research status.

# VI. Stage Four: Systematically Assess Whether Candidate Topics Are Feasible

At this step, you should not only ask “Is this title good?” You should break the judgment into a set of verifiable indicators.

Whether a title suits an undergraduate thesis is not only a matter of research value; it also depends on whether it can be finished within limited time.

## Prompt 12: Comprehensive Feasibility Scoring for Thesis Topics

Using undergraduate thesis advising standards, assess the following candidate title.

Candidate title: [fill in]

Supplementary information:

- Major and research stage: [fill in]
- Expected thesis length: [fill in]
- Remaining time: [fill in]
- Existing related literature: [fill in]
- Obtainable data and materials: [fill in]
- Planned methods: [fill in]
- Personal capacity and tool foundation: [fill in]
- Institutional and college requirements: [fill in]

Please use the following scoring framework.

| Evaluation dimension | Weight | Key checks |
| -------------------- | ------ | ---------- |
| Disciplinary fit | 15% | Whether it falls within the major’s training scope |
| Research value | 15% | Whether it is worth analyzing and explaining |
| Literature foundation | 15% | Whether there is a reliable related-research base |
| Data and material accessibility | 15% | Whether necessary evidence can be obtained |
| Methodological operability | 10% | Whether required methods are mastered or can reasonably be learned |
| Reasonableness of research scope | 10% | Whether research boundaries can be clearly limited |
| Potential novelty space | 10% | Whether there is a testable incremental contribution |
| Time and resource match | 5% | Whether it can be finished within the required time |
| Ethics and compliance | 5% | Whether there are unresolvable compliance barriers |

Score each dimension from 1 to 5.

The calculation is:

**Overall score = for each dimension, (score ÷ 5 × corresponding weight), then sum all dimensions.**

The total is out of 100.

Please strictly apply the following rules:

1. Do not freely give high scores on dimensions without supporting evidence.
2. Unconfirmed data accessibility should be marked “pending verification,” with uncertainty in the score explained.
3. When there are unresolvable barriers in ethics, privacy, access, or institutional rules, do not recommend starting the research even if the total score is high.
4. The score for potential novelty space reflects only the current judgment and cannot replace literature verification.
5. Use the same standards when scoring different titles.

Please output each dimension’s score, scoring rationale, evidence basis, and items pending verification.

Finally, give a recommendation: continue, continue after revision, judge after adding evidence, or temporarily abandon.

Do not score every candidate title highly just to appear professional.

## Prompt 13: Compare Multiple Candidate Titles

I currently have the following candidate directions:

1. [Direction 1]
2. [Direction 2]
3. [Direction 3]
4. [Direction 4]
5. [Direction 5]

My personal conditions are as follows: [Paste the background profile organized in Step 1].

Do not directly pick the title that sounds most impressive.

Please compare each direction uniformly by the following standards:

- Disciplinary relevance.
- Actual research value.
- Related literature that can be retrieved.
- Actual accessibility of data or materials.
- Difficulty of research methods.
- Whether the research scope is easy to control.
- Whether potential novelty space can be verified.
- Completion time and resource cost.
- Main failure risks.
- Whether a reasonable fallback exists if the research fails.

Use the same scoring rules for each title, and for each explain separately:

1. The strongest reasons for further investigation.
2. The factors most likely to make the research fail.
3. Conditions that must be verified before investing a large amount of time.
4. Where the title needs revision.
5. Which personal conditions might change the current evaluation.

Provide an evidence-based comparison rather than making the decision for me. If a direction seems valuable but key materials cannot be obtained, point that out clearly.

## Prompt 14: Reverse-Audit Failure Risks of a Topic

Please act as a strict methods reviewer and reverse-test my candidate title.

Candidate title: [fill in]

Known research conditions: [fill in]

Temporarily assume that this title ultimately cannot be completed successfully, then work backward to possible failure reasons.

Focus on:

- The title is too broad to form a clear research question.
- There is a large volume of literature, but none truly supports the core question.
- Key data cannot be obtained or lack usage rights.
- Research participants are unwilling to take part.
- The research method exceeds my capacity.
- Research results cannot answer the original question.
- Variable definitions are vague or lack reliable measurement.
- The thesis easily degenerates into vague suggestions.
- The topic does not match disciplinary requirements.
- The title depends on premises that have not been verified.
- Institutional rules do not allow the intended AI-assisted approach.

For each risk, explain:

1. Possible reasons the risk would occur.
2. Consequences if it occurs.
3. How to verify it before formally starting the research.
4. Whether a feasible alternative exists.
5. Whether the risk is serious enough that the title should be abandoned.

Finally, provide a “verification checklist that must be completed before formally confirming the topic.”

If there are unresolvable key barriers, clearly recommend pausing or changing the title; do not force a recommendation just to finish the task.

# VII. Stage Five: Converge Candidate Titles into a Final Title

A good topic needs balance between being “concrete” and having “research space.”

If the title is too broad, the research is hard to deepen; if it is too narrow, there may not be enough materials. A complex-sounding title is not the same as a high research level.

## Prompt 15: Multi-Round Convergence of Thesis Titles

My candidate research direction is: [fill in].

Conditions already clarified:

- Research object: [fill in]
- Concrete setting or research scope: [fill in]
- Core research question: [fill in]
- Related theory or concepts: [fill in]
- Obtainable materials or data: [fill in]
- Planned methods: [fill in]
- Expected completion time: [fill in]

Please help me form more precise candidate titles.

### Round 1: Determine necessary information

Judge whether the title needs to include:

- Research object.
- Core question or relationship.
- Research setting.
- Specific case or time range.
- Theoretical perspective.
- Research method.

Not every title must include all of the above. Explain whether each element truly helps define the research scope.

### Round 2: Generate different wording forms

Within institutional rules, propose several different title wordings around the same already-clarified question.

Each wording must correspond to the same real, researchable question. Do not use more professional-sounding language to conceal an unclear research question.

### Round 3: Check title quality

Check one by one:

1. Are there broad, vague, or indefinable words?
2. Are there multiple research goals that are hard to pursue together?
3. Is there conceptual redundancy?
4. Does it imply research conclusions that have not been confirmed?
5. Does it claim to study a causal relationship when the actual method can only provide correlational evidence?
6. Should unnecessary geographic, temporal, or method limits be removed?
7. Does it clearly match my major and thesis requirements?

### Round 4: Explain consistency between title and research content

For each candidate title, explain:

- What research content each key phrase in the title corresponds to.
- The core question expected to be answered.
- Evidence that must actually be collected.
- Preconditions for completing the research.
- Risks that remain in the title.

Present in the form “title wording — research question — evidence needed — research method — main risks.”

Finally, provide recommended revision directions, but do not treat linguistic elegance of the title as the sole judgment criterion.

## Prompt 16: Check Whether Research Objects, Variables, and Concepts Are Clearly Defined

My title is: [fill in].

Please help me judge whether the core concepts in the title are clear, identifiable, and researchable.

For each key concept, check:

1. What common definitions does it have in the relevant discipline?
2. Are there definition differences across theoretical traditions or studies?
3. Which definition do I plan to adopt, and why?
4. Does this concept need to be split into multiple dimensions?
5. Are there observable indicators, textual features, measurement tools, or judgment criteria?
6. Can valid evidence be obtained based on these indicators?
7. Is it easily confused with nearby concepts?

Separate “theoretical definition,” “working definition adopted in this thesis,” and “actual measurement approach.”

If a concept first requires literature search before it can be determined, list it as pending verification.

Do not arbitrarily set standards for concepts that lack a basis, and do not equate a complex theoretical concept with an easily measurable indicator.

# VIII. Stage Six: Turn the Topic into a Clear Research Question

Finalizing a title is not enough.

Even a complete-looking title may have these problems: not knowing what to explain, having no verifiable materials, too many research goals, or a mismatch between method and question.

Therefore, before confirming the topic, ask AI to help check the relationship between the research question and research objectives.

## Prompt 17: Extract Research Questions from the Final Candidate Title

My candidate title is: [fill in].

The research background and related literature materials I currently have are: [fill in or paste real materials].

Please help me turn the candidate title further into clear research questions, but do not generate research conclusions for me that have not been read and verified.

Please complete the following tasks:

1. Summarize the most core question of this study in one sentence.
2. Judge whether this question is descriptive, comparative, explanatory, evaluative, mechanism analysis, textual interpretation, technical implementation, or another type.
3. Decompose the core question into several necessary sub-questions.
4. Explain why each sub-question needs to be answered.
5. Indicate what evidence each sub-question requires.
6. Check whether there is overlapping scope, weak links among sub-questions, or logical leaps.
7. Delete content not directly related to the core question.
8. Check whether these questions fit the workload of an undergraduate thesis.

Please output:

| Level | Research question | Why it needs answering | Evidence needed | Suitable methods |
| ----- | ----------------- | ---------------------- | --------------- | ---------------- |
|       |                   |                        |                 |                  |

Then perform a reverse check: assuming I have completed all sub-questions, would that be enough to answer the core research question?

If not, point out the logical gaps.

Do not add unnecessary research questions merely to form a complete framework.

## Prompt 18: Match Check Between Research Question and Research Method

My core research question is: [fill in].

The candidate research object is: [fill in].

The materials I can obtain include: [fill in].

The method I am currently considering is: [fill in].

Please judge whether my research question and research method match.

Please answer in order:

1. Does this question require description, comparison, explanation, evaluation, prediction, interpretation, or implementation of a technical function?
2. What type of evidence does this question require?
3. Can the materials I can actually obtain support these evidence needs?
4. What questions can the current method answer, and what can it not answer?
5. Is there a simpler but sufficiently effective method?
6. Are there unnecessary statistical models, complex theories, or technical-implementation requirements?
7. If results do not match expectations, can the existing method still answer the research question?

Pay special attention to the boundaries of causal inference.

For example, correlations among variables in a cross-sectional questionnaire usually cannot prove causality from correlation coefficients alone. If the research goal involves causal explanation, clearly state what additional research design, temporal order, or identification conditions are needed.

Finally, output a “research question — evidence — method — conclusion boundary” comparison table.

# IX. Stage Seven: Make AI Strictly Find Faults Instead of Always Affirming

Many students fall into a problem when talking with AI: AI proposes a title, the student agrees, and AI then continues to praise the title as meaningful, innovative, and practically valuable.

That kind of dialogue cannot effectively improve topic selection.

The right approach is to actively ask AI to argue against your plan and require it to state the basis for the rebuttal.

## Prompt 19: Have AI Play a Strict Thesis Reviewer

My candidate title is: [fill in].

My reasons for choosing this title are: [fill in].

Existing literature and research conditions are: [fill in].

Do not assume my judgment is correct, and do not affirm this title just to satisfy me.

Please examine this topic from the following roles:

**Role 1: Disciplinary expert.**

Check whether the research question belongs to the discipline, whether professional concepts are accurate, and whether the topic has a clear academic object.

**Role 2: Literature researcher.**

Check whether my understanding of existing research is biased, and whether I have mistaken an as-yet-unsearched area for a research gap.

**Role 3: Research-methods reviewer.**

Check whether the research question can be answered with existing data and methods.

**Role 4: Practical executor.**

Check whether I can truly complete the research under current time, skill, and resource conditions.

**Role 5: Strict opposing reviewer.**

Seek as many reasons as possible against this topic, including topic duplication, insufficient research significance, vague core concepts, inaccessible materials, and method mismatch.

Please output:

- The three strongest supporting reasons.
- The five strongest opposing reasons.
- The evidence each supporting and opposing reason depends on.
- The most critical current uncertainties.
- What actions can reduce uncertainty.
- Which defects can be revised, and which problems may mean the topic should be abandoned.

Finally, give a conditional judgment:

- Recommend continuing the research.
- Continue after revising the title.
- Judge after adding key evidence.
- Temporarily not recommended.

Do not treat “it may be meaningful in theory” as sufficient supporting evidence.

## Prompt 20: Require AI to Check Its Own Prior Conclusions

Please re-examine all important judgments you previously made about the candidate topic.

Candidate title: [fill in]

Please focus on finding the following problems:

1. Are there academic-value judgments without supporting evidence?
2. Has speculation been written as fact?
3. Has a research gap been claimed without a systematic search basis?
4. Have uncertain references been treated as real literature?
5. Have professional concepts been misused?
6. Have inaccessible materials or samples been recommended?
7. Have time, resource, privacy, or ethical limits been ignored?
8. Have complex research methods beyond undergraduate needs been proposed?
9. Has novelty been overemphasized while completability was neglected?
10. Is there inconsistency between the title and the research question?

Please divide the issues found into:

- Errors that can already be confirmed.
- Problems with a relatively high likelihood.
- Problems that can be judged only through external search or human verification.

Propose a correction for each item.

If a previous recommendation truly does not hold, withdraw it directly and explain why. Do not defend wrong conclusions merely to keep answers consistent.

# X. Discipline-Specific Topic-Selection Prompts

Research logics differ across disciplines. The same topic-selection standards cannot be applied mechanically to every major.

Below are templates that can be used directly by discipline.

## 1. Economics, Finance, Business Administration, Marketing

My disciplinary direction is: [fill in].

The candidate field is: [fill in].

Please help me identify researchable questions in light of the characteristics of economics and management research.

Focus on:

- Concrete phenomena in firms, consumers, organizations, or markets.
- Management problems with clear explanatory value.
- Testable theoretical relationships or reasonable comparative questions.
- Obtainable public data, firm cases, or survey samples.
- Suitable research methods and their applicability conditions.
- Potential value for management or market practice.

Please especially check:

1. Does the title only introduce a phenomenon without a research question?
2. Is correlation directly explained as causation?
3. Is a questionnaire chosen mechanically just because it is easy to distribute?
4. Can the sample represent the intended research object?
5. Can core variables be clearly defined and measured?
6. Are necessary data, identification conditions, or a reasonable comparative basis available?
7. To what range might conclusions apply, and to what range can they not be generalized?

Propose several candidate question directions, and annotate for each the data needed, research difficulty, and main risks.

If the research would require complex econometric models, first assess necessity and feasibility at the undergraduate stage. Do not recommend complex models merely to appear professional.

## 2. Education, Psychology, Sociology

My candidate field is: [fill in].

From the perspective of education, psychology, or social science, help me identify concrete, researchable questions.

Prioritize:

- Behavior or experience of specific groups.
- Differences across educational or social settings.
- Definable psychological, behavioral, or social concepts.
- Problems between theory and practice that can be tested.
- Differences among research findings and their potential explanations.
- Interviews, questionnaires, observation, experiments, or literature research suitable for the undergraduate stage.

Please focus on judging:

1. Is the research object clear?
2. Do key concepts have reliable definitions and measurement tools?
3. Are questionnaire items clearly sourced, and do they need authorization or necessary adaptation and validation?
4. Does the research involve minors, sensitive personal information, or other ethical risks?
5. Is the sample source reliable, and is there obvious sample bias?
6. Are informed consent, privacy protection, and necessary ethics review feasible?
7. Is the research method sufficient to answer the proposed question?

Prioritize research directions that can be completed under real resource conditions. Do not require large samples, multi-round experiments, or complex causal models merely to pursue complexity.

## 3. Law

My disciplinary direction is: [fill in, e.g., civil and commercial law, economic law, intellectual property law].

The candidate question is: [fill in].

Please help me check the topic from the perspective of legal research.

Focus on:

- Whether legal relationships and legal issues are clear.
- Whether there are concrete legal norms, institutions, or controversies.
- Whether related statutes, judicial interpretations, normative documents, and judgments can be obtained.
- Whether differences among judicial views or academic interpretations need analysis.
- Whether methods such as doctrinal interpretation, case analysis, or comparative-law research fit the question.
- Whether the topic remains only legal popularization or a listing of provisions.

Please distinguish:

1. Currently effective legal norms.
2. Historical legal norms.
3. Actual practices in judicial practice.
4. Academic views.
5. Issues that remain contested.

For judgments involving the current legal status, remind me to verify authoritative, up-to-date legal texts and effective dates.

Do not invent statutes, case numbers, or judicial views. For conclusions that can be determined only with the latest regulations, mark them clearly as pending verification.

Based on obtainable norms, cases, and research literature, help me identify directions with clear legal questions and analytical space.

## 4. Chinese Language and Literature, Journalism and Communication, History

My disciplinary direction is: [fill in].

The works, authors, historical phenomena, or communication objects I am interested in are: [fill in].

From the characteristics of humanities and social science research, help me turn interest into concrete questions.

Please first check:

- Whether the research object is clear.
- Whether obtainable, verifiable primary materials exist.
- Whether there are explainable textual features, narrative phenomena, historical problems, or communication mechanisms.
- Whether a suitable theoretical perspective exists.
- Whether argumentation can be formed through close reading, historical-document analysis, discourse analysis, content analysis, or other appropriate methods.
- Whether the object is so large that only overview is possible.
- Whether personal feelings are being treated as research conclusions.

Distinguish novelty of the research object, novelty of the interpretive angle, and novelty of the method. Do not treat merely changing a work, author, or region as innovation.

For literary, communication, or historical research, do not force questionnaires, variables, and statistical models. First judge what evidence and methods the research question fits.

If historical materials are relied on, explain how sources, dates, editions, and reliability need to be verified.

## 5. Computer Science, Software Engineering, Artificial Intelligence

My disciplinary direction is: [fill in].

My technical foundation is: [fill in programming languages, tools, courses, and project experience].

The technical problem I am currently focusing on is: [fill in].

According to undergraduate thesis requirements in computing, help me judge whether this direction can become a clear research or development topic.

Please check:

1. Is there a clear technical problem, rather than merely developing an ordinary application?
2. Can system functions, inputs, outputs, and use scenarios be clearly specified?
3. Can a reasonable baseline or comparison method be established?
4. Are there public datasets, reproducible test environments, or legally obtainable data?
5. Are necessary computing resources, development time, and technical foundation available?
6. Can results be evaluated by accuracy, latency, resource use, usability, maintainability, or other appropriate metrics?
7. Does the expected outcome belong to system implementation, algorithm improvement, experimental comparison, engineering application, or theoretical analysis?

Please distinguish:

- Engineering-implementation workload.
- Research value of the technical solution.
- Reliability of experimental design.
- Whether control groups are reasonable.
- Whether performance evaluation is reproducible.

Do not equate “used AI,” “adopted a new framework,” or “completed a system” directly with academic novelty.

If models need to be compared, explain why these baselines are chosen, what data and evaluation metrics are used, and whether experimental resources are realistically available.

Finally, provide a problem definition, outcome form, verification approach, and risk list.

## 6. Accounting, Auditing

My disciplinary direction is: [fill in].

The candidate research field is: [fill in].

Please assess the topic from the perspective of accounting, auditing, and financial research.

Prioritize checking:

- Whether the accounting or financial problem is clear.
- Whether there is a stable theoretical or normative foundation.
- Whether financial indicators, accounting treatments, or audit procedures have clear definitions.
- Whether evidence can be obtained through public annual reports, financial data, case materials, or other lawful sources.
- Whether internal firm materials or restricted data are required.
- Whether research objects are comparable.
- Whether industry differences, period differences, or institutional-background differences exist.

Distinguish normative analysis, case study, and empirical research.

If it is empirical research, judge whether data sources, sample size, variable definitions, and methods match. If it is a case study, judge whether case materials are sufficient to support explanation rather than merely describing the firm.

Prioritize topics that can form a complete evidence chain with an appropriate research scope.

## 7. Art and Design, Architecture, Industrial Design, Visual Communication

My disciplinary direction is: [fill in].

My research object or design direction is: [fill in].

In light of this major’s characteristics, help me distinguish the thesis research question from the design/creative task.

Please focus on checking:

- Whether there is a clear design problem or theoretical problem.
- Whether design needs, user needs, or use contexts can be explained.
- Whether appropriate reference works, design cases, or normative materials exist.
- Whether there is a reliable evaluation approach.
- Whether field measurement, user research, prototype testing, or professional software is needed.
- Whether design outcomes and thesis analysis are consistent.
- Whether there are copyright, material-source, or user-privacy issues.

Judge by the concrete direction whether case study, design research, user research, experimental testing, materials analysis, or other methods are suitable.

Do not treat “producing a set of works” or “designing a brand” directly as a sufficient research question, and do not force all design research to use quantitative statistical methods.

Finally, distinguish research goals, design goals, evaluation metrics, material requirements, and completion risks.

## 8. Environmental Science, Biology, Food Science, and Laboratory-Based Majors

My disciplinary direction is: [fill in].

The candidate research question is: [fill in].

My experimental conditions and obtainable data are: [fill in].

Please assess this topic according to the characteristics of experimental research.

Focus on checking:

- Whether there is a clear, testable research question.
- Whether required materials, instruments, and experimental conditions are available.
- Whether a long experimental cycle is needed.
- Whether the experimental design has appropriate controls, replication, and quality control.
- Whether hazardous materials, biosafety, animal ethics, or other approvals are involved.
- Whether data can be collected and verified according to prescribed procedures.
- Whether suitable evaluation metrics and statistical methods exist.
- Whether expected conclusions go beyond what the experiment can support.

Distinguish known scientific principles, existing research findings, and questions that still need experimental verification.

For experiments I cannot complete, do not assume that online materials or AI-generated experimental data can replace real experiments.

Prioritize assessing realistically feasible research plans, and clearly indicate experimental conditions that must be resolved before confirming the topic.

# XI. Stage Eight: Form Materials That Can Support Topic Justification

After a title has gone through literature verification and feasibility assessment, you can organize a clear topic-justification package.

The goal here is not to have AI write the proposal for you, but to help you check whether the argument is complete so that you can refine it with real literature and your own judgment.

## Prompt 21: Generate a One-Page Topic-Justification Outline

My candidate title is: [fill in].

My research background and related literature materials are: [paste real materials].

The research conditions I have already clarified are: [fill in].

Based on these materials, please organize a “one-page research-plan outline” for discussing the topic.

Include the following parts:

**I. Candidate title**

Give the current title and point out concepts or scope that are not yet fully clear.

**II. Research background**

List concrete manifestations of the real-world or academic problem. Related facts need real sources and must not rest only on common-sense inference.

**III. Research question**

Use clear, answerable sentences to state what problem this study intends to solve.

**IV. Existing research foundation**

Summarize the main themes, theories, methods, and findings in the real literature I provided.

**V. Potential research value**

Explain what understanding, comparison, explanation, or practical insight is expected to be added. Unverified novelty points should be marked pending verification.

**VI. Research object and scope**

State the research object, time, setting, and scope boundaries.

**VII. Materials and methods**

List needed materials, data sources, and suitable methods, and explain access conditions.

**VIII. Main risks**

Point out main risks regarding data, methods, time, ethics, and academic norms.

**IX. Next steps**

List verification tasks to complete, ordered by priority.

Clearly distinguish content already supported by materials from content that is still only a plan or hypothesis.

Do not invent references, findings, statistics, or novelty points merely to make the outline look complete.

## Prompt 22: Simulate a Supervisor Questioning the Topic

My candidate title is: [fill in].

The topic-justification materials I have prepared are: [paste].

From the perspective of thesis advising, raise concrete and strict questions about the topic.

Please prioritize checking:

1. Why study this question?
2. Which problems has existing literature already solved?
3. How does your research differ from the most relevant existing studies?
4. Why choose this research object?
5. Why choose this method?
6. What materials can you actually obtain?
7. If data cannot be obtained, is there a fallback?
8. Which conclusions may go beyond what the research evidence supports?
9. Is the current title still too broad?
10. How do you show that your research judgments are grounded?

For each question, explain:

- The concrete content of the challenge.
- Which defect of the topic it targets.
- What materials are needed to answer it.
- What evidence might support or overturn the current plan.

Do not presuppose that the current topic is necessarily correct, and do not write a seemingly complete set of answers for me.

Finally, form a topic-discussion checklist for me to prepare before communicating with my supervisor.

## Prompt 23: Revise the Candidate Topic Based on Real Feedback

After discussing with my supervisor, I received the following feedback:

[Paste the actual feedback]

The current candidate title is: [fill in]

The literature, data, and research conditions already in hand are: [fill in]

Please help me accurately understand the feedback and develop a revision plan.

Step 1: Break the feedback into concrete problems, such as overly broad scope, insufficient theoretical foundation, unsuitable research object, inaccessible data, or unclear research value.

Step 2: Distinguish problems that must be solved, problems that can be optimized, and problems that cannot yet be judged.

Step 3: For each item, explain revision directions and how revision would affect research goals, methods, materials, and workload.

Step 4: Check whether the revised title still matches my major, research conditions, and institutional requirements.

Step 5: Propose evidence that needs further verification and items pending confirmation.

Do not rewrite the supervisor’s views into conclusions opposite to their original meaning, and do not ignore substantive problems merely to keep the original title.

Finally, please output:

| Feedback content | Actual problem | Revision plan | Evidence to add | Potential cost |
| ---------------- | -------------- | ------------- | --------------- | -------------- |
|                  |                |               |                 |                |

The focus is to make the revised topic clearer and more feasible, not merely to change the wording of the title.

# XII. Full Use Case: From Broad Interest to a Researchable Question

The following fictional practice scenario shows how to use the prompts in sequence.

**Note: This only demonstrates the reasoning method for topic selection. It does not mean that a confirmed research gap currently exists in this direction, nor that any specific title has passed literature verification.**

Suppose an undergraduate in Business Administration:

- Is interested in short-video platforms and consumer behavior.
- Has basic marketing knowledge.
- Can access some on-campus students.
- Can complete a basic questionnaire survey.
- Has limited time and is not suited to large-scale experiments.
- Has not yet systematically reviewed literature in this direction.

## Step 1: Form a direction from interest

Initial idea:

“I want to study short videos and consumer behavior.”

There is no clear research object, question, or method yet, so this cannot be treated as a mature title.

Use Prompt 02 and Prompt 04 to gradually identify problem leads related to consumer decision-making, content features, information credibility, and purchase intention.

The output at this stage is not a final title, but a checklist of questions pending verification.

## Step 2: Turn the direction into a question

Suppose you further choose “local restaurant-exploration content on short-video platforms.”

This is still too broad, because it may involve content type, information credibility, brand attitude, purchase intention, actual store visits, and more.

After using Prompt 05, the question can be further limited to:

“What is the relationship between consumers’ perceived authenticity of restaurant-exploration content and their intention to visit?”

This is only an example research question. It does not yet show that the relationship actually exists, nor that the question is already novel.

## Step 3: Design a real literature-search plan

Using Prompt 08, design search terms around concepts such as:

- Short-video or social-media content.
- Perceived authenticity or information credibility.
- Consumer decision-making.
- Visit intention or purchase intention.
- Related theories and measurement approaches.

Then execute the search in academic databases you can actually access, and save real literature records.

If you find that existing research already fully covers the same question, continue looking for well-grounded differences, or consider other questions, rather than claiming novelty merely by changing a school or city.

## Step 4: Analyze literature instead of letting AI invent research gaps

Using Prompt 09 and Prompt 10, organize research objects, methods, conclusions, and limits in real papers.

Questions that may need further verification include:

- Do existing studies use the same concepts?
- Are measurement methods consistent across studies?
- Are research findings divergent?
- Is there a reasonable basis for further limiting a population or setting?
- Do I have the conditions to obtain samples and conduct analysis?

Only after search and analysis yield enough evidence can you judge whether the direction is worth continuing.

## Step 5: Assess data and research methods

If you plan to use a questionnaire, check in advance:

- Whether the research object is clear.
- Whether questionnaire content has a reliable source.
- Whether sample recruitment is realistically feasible.
- Whether the target sample can support the intended analysis.
- Whether corresponding permission is needed.
- How to protect respondents’ personal information.
- Whether questionnaire results can answer the research question.

If you can obtain only a convenience sample from a single period, results may support only relationships or differences within that specific sample; do not lightly infer causality or generalize to all consumers.

## Step 6: Assess the final candidate title

Suppose a temporary candidate title is:

“A Study of the Relationship Between Perceived Authenticity of Short-Video Restaurant-Exploration Content and University Students’ Intention to Visit Dining Venues.”

This title is clearer than the original broad direction, but still needs verification of:

- How “perceived authenticity” is defined and measured?
- Whether “university students” needs further scope limitation?
- Whether the research object is all university students, or a obtainable sample?
- Whether related research has already answered the same question?
- Why choose the dining setting?
- Whether questionnaire data are sufficient to support the intended conclusions?

At this point, use Prompt 12, Prompt 14, Prompt 16, and Prompt 18 to complete feasibility, risk, and concept checks.

**The most valuable lesson in this case is that each step reduces uncertainty, rather than each step chasing a prettier title.**

# XIII. Three Easily Overlooked Issues in AI Use

## 1. Do not let AI only give answers; make it show its basis

When AI says “this topic is innovative,” follow up:

“What materials did you use to judge that it is innovative? Please list the actual literature or evidence supporting this judgment. If no search has been done, withdraw the definitive claim and instead state what needs to be verified.”

When AI says “this title is easy to complete,” follow up:

“What concrete conditions does this judgment depend on? If the sample is insufficient, data cannot be obtained, or the experiment fails, can the research still be completed?”

These follow-ups are more valuable than simply asking AI to generate more titles.

## 2. Do not treat richness of academic vocabulary as research quality

The following phrases should not be treated directly as proof of research value:

- Construct a multi-dimensional analytical framework.
- Explore mechanisms of action.
- Build a comprehensive evaluation model.
- Propose optimization pathways.
- Fill existing research gaps.
- Promote high-quality development.

These words may appear in qualified theses, but they have substantive meaning only when the research question, theoretical basis, data, and methods can support them.

For an undergraduate thesis, a clearly scoped question that can be answered with real evidence is usually more suitable than a concept-heavy title that cannot complete its argument.

## 3. Do not treat AI responses as research evidence

AI can help you propose hypotheses, but it cannot automatically turn hypotheses into facts.

For example:

“A certain factor may affect a certain behavior” is only a research idea pending testing.

“Existing research has shown that a certain factor affects a certain behavior” requires real literature as a basis.

“There is still no related research in this field” needs a sufficiently comprehensive, reviewable literature search to support it.

The three must be strictly distinguished.

# XIV. Appendix: The Most Important Operating Principles

1. Clarify research conditions before exploring titles.
2. Form problem leads before writing titles.
3. Search real literature before judging novelty.
4. Verify data and resources before committing to a research plan.
5. Clarify the research question before choosing research methods.
6. Require AI to mark uncertainty; do not accept affirmations without a basis.
7. Break complex research into checkable small tasks.
8. Keep real search records and your own judgment process.
9. Verify sources for any citation, data, research finding, and legal norm.
10. The final topic should meet institutional requirements and be research you can genuinely understand, explain, and complete.

**Final judgment criterion:** You are truly close to a mature thesis topic when you can clearly answer “what I study, why I study it, how far others have gone, what evidence I can obtain, how I plan to answer the question, and whether I can finish on time.”
