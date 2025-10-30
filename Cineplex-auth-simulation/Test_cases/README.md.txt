# Cineplex Authentication – Test Cases (13 Total)

**Detailed test case documentation for login, registration, password recovery, and UI validation**

---

## Live Test Cases (Google Sheets)

[Open Full Test Cases](https://docs.google.com/spreadsheets/d/1p_dh9j3zE4ykpGYMWzxKMYyOIIfSkXDe/edit?usp=sharing&ouid=110017686233802591467&rtpof=true&sd=true)

> **Columns**:  
> `ID | Suite | Title | Type | Priority | Preconditions | Steps | Expected Result | Status | Bug ID`

---

## Test Case Summary

| Suite | # of Cases | Examples |
|------|------------|---------|
| **Login Functional** | 4 | Valid login, Remember Me, Rate limit, Logout |
| **Login Validation** | 2 | Invalid password, empty fields |
| **Registration Functional** | 2 | Valid data, password = 8 chars |
| **Registration Validation** | 3 | Existing email, invalid email, password < 8 |
| **Password Recovery** | 1 | Reset link flow |
| **UI & Accessibility** | 1 | Alignment, contrast, console |

---

**All test cases are simulated. No real execution.**  
