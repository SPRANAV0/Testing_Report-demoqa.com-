# Project 1: Testing Report (DemoQA.com)

Manual functional test case documentation for the **Elements module** of [demoqa.com](https://demoqa.com), a public Selenium/QA practice site. Test cases are written and tracked in **`Testing_Report_DEMOQA.xlsx`**, structured in an industry-style test case report format (Test Case ID, Scenario, Title, Pre-requisites, Steps, Test Data, Expected/Actual Result, Priority, Result, Comments).

## Workbook Structure

| Sheet | Scope | Test Cases |
|---|---|---|
| **Scenarios** | Project overview and full scenario-to-test-case mapping across all modules | 26 scenarios |
| **Text Box** | `/text-box` — Full Name, Email, Current Address, Permanent Address, Submit & Output | 16 |
| **Check Box** | `/checkbox` — expandable tree, parent/child selection, partial-selection state, result output | 15 |
| **Radio Button** | `/radio-button` — Yes / Impressive / No (disabled), selection & output messages | 12 |
| **Web Tables** | `/webtables` — Add, Edit, Delete, Search, Pagination on the records table | 18 |
| **Buttons** | `/buttons` — Click, Double Click, Right Click interactions | 10 |

Each module sheet is capped at **20 test cases**, grouped into labelled test scenarios (e.g. `(TS_02) Full Name Field Validation`) and tagged with a **Priority** (P0–P2) and **Result** (Pass/Fail, colour-coded).

**Total: 71 test cases across 5 modules — 71/71 Pass.**

## Test Design Approach

- Positive, negative, and boundary scenarios for every field/control (e.g. valid vs. invalid email, empty submissions, special characters, disabled controls).
- UI/layout checks (visibility, alignment, placeholders) alongside functional checks (selection logic, CRUD behaviour, output verification).
- Keyboard accessibility checks where relevant (Tab navigation, disabled-control skipping).

## Legacy Google Sheet references

The module was originally tracked across three separate Google Sheets before being consolidated into the single structured workbook above:

1. Textbox testing report : https://docs.google.com/spreadsheets/d/127Zaij08SEGRuHYeCFyp3_Gu88Ewrs8qtsWcrTvlhcY/edit?usp=sharing
2. Checkbox testing report : https://docs.google.com/spreadsheets/d/1tWYHMeXCWzodxVjbOrl2SWV01wG2QgIkbQW2NZVBcUo/edit?usp=sharing
3. Radio button testing report : https://docs.google.com/spreadsheets/d/1WWkxi1igk5bnEn4sDKsmaSbkWzdTN_hacNPBCMkFojI/edit?usp=sharing
