# Case template

Copy this tree for each new case:

```text
cases/YYYY/XX-YYYY-NNNN/
  INFO.md
  FINDINGS.md
  CLAIMS.md
  SOURCE-DELTA.md
  SLIDE-INDEX.md          # or ARTIFACT-INDEX.md
  sources/SRC-INDEX.md
  evidence/README.md
```

Optional: `timeline/XX-YYYY-NNNN.csv`, `decision-log/DL-*.md`

## INFO.md (minimum fields)
- Case ID, title, date of primary, artifact type
- Status overall
- One-line finding
- Core distinction (what PRIMARY answers vs does not)

## FINDINGS.md rules
- Each finding: Status (PRIMARY/SECONDARY/ANALYSIS/UNRESOLVED) + Evidence + Implication
- No finding without an anchor

## CLAIMS.md rules
- One row per atomic claim
- Status column mandatory
- UNRESOLVED is a valid final state

## SOURCE-DELTA.md rules
- PRIMARY only / SECONDARY only / Overlap / Timeline without invented causation

## Evidence policy
- Prefer public URLs + hash of local copy
- Do not commit stolen payloads or non-public intercepts
- Binary evidence may stay external with pointer + sha256 + last_checked
