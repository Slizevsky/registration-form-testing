# Registration Form — Manual Testing Portfolio

## Project Overview
Manual testing of a web registration form on a QA practice site.
The goal was to design test cases, execute them, and document found bugs.

**Site under test:** https://practice.qabrains.com/registration

---

## Test Cases
- 15 test cases covering all 6 required fields
- Types: Positive, Negative, Boundary, Functional
- Tool: Excel

| Total | Passed | Failed |
|-------|--------|--------|
| 15    | 12     | 3      |

---

## Bug Reports
3 bugs found during testing:

| Bug ID | Title | Severity | Priority |
|--------|-------|----------|----------|
| BUG-01 | Misleading error message on Login page after registration | Major | High |
| BUG-02 | Redundant wording in Email validation error message | Trivial | Low |
| BUG-03 | System allows registration with already existing email | Major | High |

---

## Files
- `registration_test_cases.xlsx` — test cases
- `Bug_report.xlsx` - bug reports
- `screenshots/` - screenshots for each bug

---

## Skills Used
Manual Testing · Test Case Design · Bug Reporting · Web Testing · Excel

---

## Environment
Chrome 145.0.7632.160, macOS 26.3.1
