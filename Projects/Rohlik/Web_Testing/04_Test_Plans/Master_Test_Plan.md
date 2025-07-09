# 📝 Master Test Plan

## 1. Project Overview
Rohlik.cz is an online grocery delivery platform available via website and mobile apps.  
This test plan covers web testing activities for the main e-commerce flow on the website [rohlik.cz](https://www.rohlik.cz/en-CZ).

## 2. Objectives
- Validate core functionalities of the e-commerce platform  
- Ensure a smooth and bug-free user experience for desktop users  
- Confirm correct behavior of search, cart, checkout, and user profile flows  
- Identify and document any critical or high-severity issues

## 3. Test Strategy
The testing approach includes:
- Manual functional testing using structured test cases  
- Negative testing to validate input handling and edge cases  
- Smoke and sanity testing before deeper sessions  
- Use of checklists for regression and pre-release validation  
- Exploratory testing in critical flows (cart, checkout)  
- Manual execution only (no automation at this stage)

## 4. Scope of Testing
The scope includes the following key features:
- User authentication
- Product search and filtering
- Cart and checkout process
- User profile management
- Voucher application
- Localization and language switching (EN/CZ)

## 5. Types of Testing
- Functional Testing  
- Smoke and Sanity Testing  
- UI and Usability Testing  
- Negative Testing  
- Regression Testing  
- Compatibility Testing (desktop browsers)  
- Exploratory Testing  

## 6. Test Environment
- Browsers: Chrome, Firefox, Edge, Safari (latest versions)  
- OS: Windows 10/11, macOS  
- Test accounts: Pre-registered user credentials  
- Language variants: Czech, English

## 7. Test Artifacts
- ✅ [Test Cases](../01_Test_Cases)
- 🐞 [Bug Reports](../02_Bug_Reports)
- 📋 [Checklists](../03_Checklists)
- ⚙️ [Automation Tests](../05_Automation_Tests) *(planned)*

## 8. Roles and Responsibilities
- **Manual QA Engineer** – test case execution, bug reporting  
- **QA Lead / Owner (me)** – documentation, strategy, planning  
- **(Optional) Dev Support** – if automation or API testing is added

## 9. Test Schedule
- Week 1: Scope definition & test case design  
- Week 2: Manual test execution  
- Week 3+: Exploratory sessions & checklist coverage  
_(Schedule flexible due to personal project nature)_

## 10. Entry & Exit Criteria

**Entry:**
- Website is accessible and test account is available  
- Basic flows are stable enough for manual testing

**Exit:**
- All critical test cases passed  
- No blocker/high-priority bugs open  
- All findings and documentation are complete and reviewed

## 11. Risks and Assumptions
- The public website may update frequently, affecting repeatability  
- No direct access to backend, staging, or internal logs  
- Live data may impact test consistency (e.g., cart, availability)
