# Content Classification Guide for AI Editing Assistant

This guide provides a comprehensive framework for identifying and fixing common content issues. Each classification includes detection patterns, transformation examples, and implementation principles.

## Quick Reference

| Issue Type | Priority | Focus Area |
|------------|----------|------------|
| [Wordiness - Filler Text](#issue-1-wordiness---filler-text) | High | Efficiency |
| [Value Gap - Missing Outcomes](#issue-2-value-gap---missing-outcomes) | High | Persuasion |
| [Engagement Deficit - Weak Language](#issue-3-engagement-deficit---weak-language) | Medium | Impact |
| [Abstract Content - Poor Visualization](#issue-4-abstract-content---poor-visualization) | Medium | Clarity |
| [Inefficiency - Redundant Information](#issue-5-inefficiency---redundant-information) | Medium | Efficiency |
| [Structure Problem - Inconsistent Parallelism](#issue-6-structure-problem---inconsistent-parallelism) | Low | Grammar |
| [Logic Gap - Missing Context](#issue-7-logic-gap---missing-context) | High | Reasoning |
| [Style Weakness - Passive Construction](#issue-8-style-weakness---passive-construction) | Medium | Voice |
| [Conclusion Gap - Missing Takeaways](#issue-9-conclusion-gap---missing-takeaways) | High | Synthesis |
| [Clarity Problem - Vague Language](#issue-10-clarity-problem---vague-language) | High | Precision |

---

## Issue 1: Wordiness - Filler Text

**Classification:** Text efficiency issue where unnecessary words dilute message impact

### Detection Patterns
- Qualifying words (actually, basically, really, very)
- Redundant phrases ("the process of," "in order to")
- Multiple sentences expressing a single idea
- Overexplaining obvious concepts
- Excessive prepositions and connecting phrases

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "The last interaction a customer had before purchasing is likely the thing that motivated the purchase." | "The last interaction likely motivated the purchase." | Removed obvious context ("before purchasing") and redundant phrasing ("the thing that") |
| "In reality, this might not actually be the case at all." | "In reality, this might not be the case." | Removed "actually" which rarely adds value |
| "Payroll basically refers to the process of calculating an employee's pay." | "Payroll is the process of calculating employee pay." | Removed qualifier "basically" and condensed language |

### Transformation Techniques
- Eliminate qualifier words without changing meaning
- Convert multi-sentence structures to single sentences
- Remove phrases that state the obvious
- Eliminate redundant context that readers can infer
- Replace "of the" constructions with possessives
- Delete connector phrases that add no value

---

## Issue 2: Value Gap - Missing Outcomes

**Classification:** Persuasion deficit where content fails to articulate concrete benefits or results

### Detection Patterns
- Generic benefit phrases ("business success," "improve results")
- Content that explains what but not why
- Features described without connecting to benefits
- Absence of metrics or measurable impact
- Instructions without outcome statements

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Not all customer acquisition is good customer acquisition. Knowing what separates them is the first big step to business success." | "Not all customer acquisition is good customer acquisition. Data-driven strategies focused on ROI over revenue win." | Replaced vague "business success" with specific outcome (ROI focus) |
| "Though limited, this attribution model is useful for understanding which marketing activities attract customers." | "Though limited, this attribution model is useful for understanding which marketing activities attract customers. You can use that data to optimize top-of-funnel activities and drive more leads." | Added the specific benefit of how the information can be used |

### Transformation Techniques
- Replace vague outcomes with specific metrics
- Add consequences of inaction
- Connect features to quantifiable benefits
- Transform abstract concepts into tangible advantages
- Add "so you can..." statements that clarify reader gain
- Specify timeframes for expected results

---

## Issue 3: Engagement Deficit - Weak Language

**Classification:** Impact problem where neutral language fails to create emotional connection

### Detection Patterns
- Bland descriptive statements without emotional hooks
- Passive observations instead of direct challenges
- Vague quantifiers (some, many, few) instead of precise numbers
- Generic terminology where specific terms would have more impact
- Lack of contrast or tension in statements

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Imagine attracting 300 profile visitors and none of them click the follow button." | "If 300 people click your profile and 0 follow, something's wrong." | Replaced passive "imagine" with direct statement; used "0" instead of "none" for impact |
| "Too often we think conflict is a bad thing. I know, I'm a recovering conflict avoider." | "Too often, we think conflict is a bad thing. As a recovering conflict avoider, I know it's easier to run than resolve." | Added visual contrast ("run vs. resolve") for emotional impact |

### Transformation Techniques
- Replace passive observations with direct statements
- Use precise numbers instead of vague quantifiers
- Create emotional tension through contrasting concepts
- Add sensory-rich language that evokes feelings
- Transform neutral descriptions into emotionally-charged statements
- Replace bland verbs with power verbs

---

## Issue 4: Abstract Content - Poor Visualization

**Classification:** Cognitive processing issue where readers cannot form mental images

### Detection Patterns
- Abstract concepts without concrete examples
- Theoretical explanations without real-world applications
- Generic descriptions missing sensory details
- Complex processes explained without analogies
- Statistical information without contextual framing

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "At a minimum it costs organizations 2x an employee's salary if they quit. Your top performer just quit. You never saw it coming." | "At a minimum it costs organizations 2x an employee's salary to replace them if they quit. Now imagine your top performer walks away out of nowhere. They're burned out, and you didn't see it coming." | Added scenario details that create a mental image |
| "The more you learn, the more irreplaceable you'll be." | "Learn more today so you're irreplaceable tomorrow." | Created time-based visualization with clear cause and effect |

### Transformation Techniques
- Convert abstract concepts into concrete imagery
- Add sensory details that bring ideas to life
- Create before/after scenarios readers can visualize
- Use metaphors that create mental pictures
- Add progressive timelines (today/tomorrow) to show change
- Transform statistics into relatable examples

---

## Issue 5: Inefficiency - Redundant Information

**Classification:** Content optimization issue where repeated concepts waste reader attention

### Detection Patterns
- Similar ideas stated multiple times with slight rewording
- Multiple sentences making the same fundamental point
- Repeated words in close proximity
- Explaining obvious implications
- Overqualifying statements that are self-evident

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "The key to achieving that is ongoing measurement. You could skip straight to trying new acquisition strategies, but if you can't measure their impact, you won't know what works." | "The key is ongoing measurement and testing to understand which acquisition strategies work." | Combined two sentences making the same point into one concise statement |
| "The roles begin to diverge once you take technical skills into account. Sales engineers have technical skills that allow them to identify patterns that someone without technical expertise may miss." | "The roles begin to diverge once you take technical skills into account. Sales engineers have the industry expertise to identify patterns that an untrained eye may miss." | Removed repetitive use of "technical" and introduced variation |

### Transformation Techniques
- Merge sentences that make the same point
- Replace repeated words with synonyms or pronouns
- Remove explanations of obvious implications
- Combine related concepts into unified statements
- Eliminate unnecessary restatements
- Streamline sequential thoughts into single expressions

---

## Issue 6: Structure Problem - Inconsistent Parallelism

**Classification:** Grammatical issue where similar elements don't follow the same pattern

### Detection Patterns
- Mixed verb forms in a series (run, to swim, and biking)
- Inconsistent grammatical structures in lists
- Mixed noun/verb constructions in headers or bullet points
- Inconsistent sentence structures in parallel ideas
- Shifting between active/passive voice in related statements

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Her writing is neat and I can identify it easily." | "Her writing is neat and identifiable." | Matched both descriptors as adjectives |
| "I like running and to listen to music." | "I like running and listening to music." | Made both verbs use the -ing form |
| "Make sure to answer: 1. Why it matters 2. How will they do it?" | "Make sure to answer: 1. Why it matters 2. How they can do it" | Made both list items statements rather than mixing statement and question |

### Transformation Techniques
- Align grammatical forms in lists (all nouns, all verbs, etc.)
- Match tenses across parallel elements
- Standardize structures in bullet points or numbered lists
- Ensure consistency in paired concepts (either/or, both/and)
- Apply identical patterns to all items in a series
- Convert mixed constructions to single grammatical pattern

---

## Issue 7: Logic Gap - Missing Context

**Classification:** Reasoning issue where connections between ideas aren't clearly established

### Detection Patterns
- Statements of what to do without explaining why
- Claims without supporting reasoning
- Advice lacking situational context
- Transitions between ideas that require logical leaps
- Conclusions presented without preceding evidence

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Startup fundraising is hard!" | "Startup fundraising is hard! It can drain your energy and kill your confidence." | Added the emotional impact to explain why it matters |
| "Don't waste time on unqualified leads. To find warm leads..." | "Unqualified leads bloat your pipeline, which wastes resources and leads to missed opportunities. To find warm leads..." | Explained specific negative consequences |

### Transformation Techniques
- Add causal connections between recommendations and outcomes
- Include reasoning for claims and assertions
- Connect advice to specific situational contexts
- Build logical bridges between related concepts
- Add evidence that supports conclusions
- Explain negative consequences of alternative choices

---

## Issue 8: Style Weakness - Passive Construction

**Classification:** Voice issue where indirect phrasing reduces clarity and impact

### Detection Patterns
- "Is/are/was/were" + past participle constructions
- Sentences where the subject receives the action
- Agent introduced by "by" phrase or omitted entirely
- Focus on what happened rather than who did it
- Instructions in passive voice ("should be done") rather than imperative

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Meta descriptions should be kept at approximately 150 characters to avoid truncation." | "Keep meta descriptions at or under 150 characters to avoid truncation." | Switched to active voice with direct instruction |
| "To optimize the time of your sales team, utilizing a data-driven marketing automation approach is key." | "Optimize your sales team's time with a data-driven marketing automation approach." | Removed passive construction and made direct statement |

### Transformation Techniques
- Convert passive constructions to active voice
- Make the actor the subject of the sentence
- Replace "is/are" + past participle with direct verbs
- Use imperative mood for instructions
- Move important elements to subject position
- Eliminate unnecessary helping verbs (being, been)

---

## Issue 9: Conclusion Gap - Missing Takeaways

**Classification:** Synthesis issue where content fails to provide actionable conclusions

### Detection Patterns
- Information provided without clear next steps
- Complex concepts without summarizing frameworks
- End of content that trails off without resolution
- Facts presented without significance statements
- Multiple points without unifying theme

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "Canva has forged out and communicated a unique place in the market based on a clear design empowerment mission. The brand's edge is its simplicity reflected in those same three words: Design for everyone." | "Canva has disrupted a traditionally exclusive and compulsory landscape. Their "for the people" USP is a masterclass in collective empowerment in the face of steep competition with a loyal following. 'Design for everyone,' is a strong differentiator and competitive advantage." | Added industry context and specific competitive advantages as takeaways |
| "Books are helpful, but It's important to make connections and find support groups in areas with other people who really understand what you're going through when you start your journey back to regaining your health." | "The healing journey is personal, but connections are powerful. Find support groups and connect with people who deeply understand what you're going through. Share --> Heal --> Thrive" | Added clear process steps as a takeaway |

### Transformation Techniques
- Create actionable next step statements
- Develop frameworks that summarize key concepts (A→B→C)
- Add significance statements that explain "why this matters"
- Connect information to broader industry context
- Build "so what" conclusions that synthesize main points
- Create memorable summations that reinforce core message

---

## Issue 10: Clarity Problem - Vague Language

**Classification:** Precision issue where ambiguous terms create confusion or reduce impact

### Detection Patterns
- Subjective adjectives (good, best, great) without specifics
- Relative terms without reference points
- Abstract verbs that don't clearly convey action
- Ambiguous pronouns with unclear antecedents
- Jargon without definition or explanation

### Examples

| Original | Edited | Improvement |
|----------|--------|-------------|
| "They'll fight over it when your dead isn't just a statement of durability, but ongoing desire, conveying the image of its products being so hard-wearing that they still look good and perform well even decades after purchase." | "They'll fight over it when you're dead doubles as a statement of durability and perennial desire. Not only will you wear their products throughout your lifetime, but they'll last (and be fought over) for generations to come." | Replaced vague "hard-wearing" with specific timeline "generations to come" |
| "Many tech startups fizzle out because of their founders—even if the product is lifechanging." | "Many tech startups fail because the founders are too focused on their product." | Replaced vague "fizzle out" with direct "fail" and specified the reason |

### Transformation Techniques
- Replace subjective terms with specific criteria
- Quantify vague amounts with precise numbers
- Substitute abstract verbs with concrete actions
- Clarify ambiguous pronouns with specific nouns
- Define jargon or replace with plain language
- Add reference points to relative terms

---

## Implementation Guidelines

### Editing Priority Order
1. **Structure Issues** (Parallelism, Logic Gaps)
2. **Clarity Problems** (Vague Language, Missing Context)
3. **Efficiency Issues** (Wordiness, Redundancy)
4. **Engagement Enhancement** (Weak Language, Poor Visualization)
5. **Value Addition** (Missing Outcomes, Missing Takeaways)

### Quality Metrics
- **Conciseness Ratio:** Character reduction while maintaining meaning
- **Clarity Score:** Improved readability metrics  
- **Engagement Uplift:** Impact on predicted reader engagement
- **User Acceptance Rate:** Percentage of suggested edits accepted

### Best Practices
- Apply edits in order of importance
- Maintain document type and audience awareness
- Provide clear rationales for changes
- Use confidence thresholds for suggestions
- Process text in semantic units based on issue type

---

## Vector Database Structure

For AI implementation, structure embeddings to capture:

```json
{
  "issue_id": "wordiness_filler_text",
  "issue_type": "Wordiness",
  "issue_subtype": "Filler Text",
  "priority": "High",
  "detection_patterns": ["redundant phrasing", "obvious context"],
  "transformation_techniques": ["remove_obvious_context", "eliminate_redundant_phrasing"],
  "vectors": {
    "issue_vector": [...],
    "pattern_vector": [...],
    "content_vector": [...],
    "technique_vector": [...]
  }
}
```

This structure enables pattern recognition, appropriate technique application, and continuous learning through feedback loops.