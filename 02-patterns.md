# 02 · Patterns the system can surface

The system is deployed against one person's records — whoever has built it. What follows are templates of the kind of pattern such a system tends to find in practice, stripped of any individual's details.

---

## Pattern one — a sentence that survives decades

**Structural self-descriptions written early in life often persist, nearly unchanged, for many years.**

A person writes, at twenty-five, a short self-diagnosis — three phrases, perhaps, naming the recurring hungers their life is built around. They forget this sentence.

Twelve years later the same person writes, in different words, about the same three hungers.

The system notices, because the keywords drift only a little while the structure stays stable. A single such finding may be the most truthful long-range portrait one can have of oneself.

```mermaid
flowchart LR
    Y1["Year 1<br/>sentence written<br/>(then forgotten)"] -.years of silent operation.-> Y5["Year 5<br/>still running<br/>underneath decisions"] -.-> Y12["Year 12<br/>same structure<br/>rediscovered"]
```

---

## Pattern two — the same feeling, oppositely diagnosed

**A single emotion can be read as symptom at one point and as signal at another.**

Restlessness, in one year's diary, is named as a problem — a leak of attention, a cost of unresolved fear. Six years later the same person calls the same feeling *evidence of standing at the frontier*.

The emotion has not changed; the interpretation has flipped.

The system can lay the two sentences beside each other and produce a map of that change. Growth, here, is legible not as a feeling but as a 180-degree inversion in the interpretive stance.

```mermaid
flowchart LR
    A["<b>Year N</b><br/>restlessness = symptom<br/><i>something wrong</i>"] ==6 years==> B["<b>Year N+6</b><br/>restlessness = signal<br/><i>standing at the frontier</i>"]
```

---

## Pattern three — a belief overturned in writing

**Beliefs one has explicitly refuted sometimes keep running in the background.**

At some point the person writes, with conviction: *"I used to believe X, and I now see X is false for me."* This is a small but real philosophical event.

The system keeps the refutation. Years later it can check: does the refuted belief keep appearing in new behavior?

Most often the answer is partial — the belief is named as false while still operating as true. The system can show the gap.

```mermaid
flowchart LR
    A[belief X<br/>held] --> B[belief X<br/>refuted in writing]
    B -.still running.-> C[belief X<br/>showing up in<br/>new behavior]
    B --> D{gap<br/>between<br/>thought & act}
    C --> D
```

---

## Pattern four — external observation meeting self-image

**A trusted observer's remark, pinned to a date, can be held against the subject's own self-description from other years.**

Teachers, therapists, partners, longtime friends — their sharp remarks tend to be preserved in notes, because the subject was trying to remember them.

The system can retrieve such a remark and place it beside the subject's own self-portrait from a different year. The two frequently disagree.

The contradiction is the data. Neither portrait alone is the whole person; the contradiction is closer.

```mermaid
flowchart TB
    Self["<b>Self-portrait</b><br/>'I am X'"]
    Ext["<b>External observer</b><br/>'You are Y'"]
    Gap["<b>The contradiction is the data</b><br/>closer to truth than<br/>either portrait alone"]
    Self --> Gap
    Ext --> Gap
```

---

## Pattern five — a ceiling that has been exceeded but never erased

**Old self-assessments of personal limits often remain on file after the limit has been surpassed.**

A person writes, in a private note, a sober estimate of their own ceiling — the highest place they realistically expect to reach. Years later reality has quietly walked past this line.

The note, however, is still on file, unrevised.

The system can retrieve it and place it beside current reality. The question it poses is not celebratory; it is practical: *to what extent is this obsolete estimate still directing present decisions?* Old estimates often keep working silently.

```mermaid
flowchart LR
    H["Year N<br/><b>ceiling hypothesis</b><br/>'my limit is X'"] -.still on file.-> Q{still directing<br/>present decisions?}
    R["Year N+5<br/><b>reality</b><br/>quietly past X"] -.contradicts.-> Q
```

---

→ Next: [03 · Contributions to self-reflection](./03-contributions.md)
