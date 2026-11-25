# Vietnamese EFL Writing Errors: Human vs AI Annotation

A small pilot study on common English writing errors of
English-major students at Dong Thap University, and how
accurately an AI tool can detect them.

## Research question
Which error types are most common, and how well does AI
agree with manual error annotation?

## Method
1. Collected [số] short texts ([ghi đúng nguồn: bài của
   tác giả / bài bạn bè có đồng ý / câu mẫu tự soạn])
2. Anonymized the texts (E01-E10, no names or IDs)
3. Annotated errors manually, one row per sentence
4. Ran [tên AI] on the same sentences (date: [ngày])
5. Compared AI output with manual labels

## Error codes
ART (article), TNS (tense), SVA (subject-verb agreement),
PREP (preposition), WC (word choice), SP (spelling),
WO (word order), NUM (singular/plural), WF (word form),
OM (omission), OK (no error)

## Data
annotations.csv: one row per sentence with manual error
codes, corrections and AI comparison.

## Results (pilot)
- Sentences annotated: [số câu]
- Most frequent error types: [ví dụ SP, SVA, NUM]
- AI agreement with manual labels: [x]%
- Correct sentences wrongly flagged by AI: [số]

## Limitations
Very small sample ([số câu] sentences). Results are not
generalizable. Part of the annotation notes was written
with AI assistance and checked by the author.

## Author
Nguyen Khanh Duy, English Language student,
Faculty of Foreign Languages, Dong Thap University
