# Cineplex Authentication – Simulated Manual Testing

**Full QA lifecycle: test design, execution planning, bug reporting, test management**  
*100% simulation — no real environment access. Demonstrates real-world QA process.*

---

## Simulation Disclaimer

> This project is **fully simulated**.  
> No access to Cineplex production or staging.  
> All test cases, bugs, and structure were **designed and documented** using **ISTQB standards** and **real QA tools**.

---

## Test Cases (13 Total)

[View Full Test Cases (Google Sheets)](https://docs.google.com/spreadsheets/d/1p_dh9j3zE4ykpGYMWzxKMYyOIIfSkXDe/edit?usp=sharing)

| Suite | Count | Examples |
|------|-------|---------|
| Login Functional | 4 | Valid login, Remember Me, Rate limit, Logout |
| Login Validation | 2 | Invalid password, empty fields |
| Registration Functional | 2 | Valid data, password = 8 chars |
| Registration Validation | 3 | Existing email, invalid email, password < 8 |
| Password Recovery | 1 | Reset link flow |
| UI & Accessibility | 1 | Alignment, contrast, console |

---

## Simulated Bugs (6 Jira-Style)

| ID | Title | Priority | Severity |
|----|------|----------|----------|
| BUG-001 | Login accepts invalid password | High | Major |
| BUG-002 | "Remember Me" does not persist | Medium | Major |
| BUG-003 | Registration accepts invalid email | High | Major |
| BUG-004 | Password < 8 chars accepted | High | Major |
| BUG-005 | No rate limit after 5 fails | Medium | Minor |
| BUG-006 | Logout leaves session active | Medium | Major |


---

## Skills Demonstrated

- **Test Design** (positive, negative, boundary, security)
- **Bug Reporting** (steps, expected/actual, priority)
- **Test Management** (TestRail, Google Sheets)
- **Documentation** (XLSX, screenshots, traceability)

---

## Tools Used

`TestRail` `Jira (simulated)` `Google Sheets` `Chrome DevTools`



