# 📝 Master Test Plan

## 1. Project Overview
Rohlik.cz is a grocery delivery platform with native mobile applications available on both Android and iOS.  
This test plan outlines QA activities for validating the mobile user experience and app functionality.

## 2. Objectives
- Ensure core app features function as expected on Android and iOS  
- Identify mobile-specific bugs affecting usability, navigation, or responsiveness  
- Validate behavior across device types, OS versions, and screen sizes  
- Maintain parity with the web version while leveraging mobile-native flows

## 3. Test Strategy
The testing approach includes:
- Manual testing on real devices and emulators  
- Functional and exploratory testing across key features  
- Smoke testing after installation or update  
- UI validation with focus on mobile-specific behavior  
- Use of structured test cases and concise checklists  
- No automation planned at this stage

## 4. Scope of Testing
The mobile app testing covers:
- App launch, login, and onboarding
- Browsing product categories and search
- Cart and checkout flows
- User profile and saved addresses
- Voucher code application
- Push notifications
- Localization (Czech/English)
- Deep links and external redirects

## 5. Types of Testing
- Functional Testing  
- Smoke & Sanity Testing  
- UI and Usability Testing  
- Compatibility Testing (devices, OS versions)  
- Exploratory Testing  
- Regression Testing (manual only)  
- Installation/Update Testing

## 6. Test Environment
- Devices: iPhone (iOS 15+), Android phones (Android 10+)  
- Emulators/simulators for secondary checks  
- App Store version and beta builds (if applicable)  
- Network conditions: WiFi, mobile data, airplane mode  
- Test data: demo user account(s), sample addresses

## 7. Test Artifacts
- ✅ [Test Cases](../01_Test_Cases)
- 🐞 [Bug Reports](../02_Bug_Reports)
- 📋 [Checklists](../03_Checklists)
- ⚙️ [Automation Tests](../05_Automation_Tests) *(not applicable for now)*

## 8. Roles and Responsibilities
- **Mobile QA** – manual test execution across platforms  
- **QA Owner (me)** – documentation and planning  
- **Developer (optional)** – issue investigation if needed

## 9. Test Schedule
- Week 1: Initial device setup and exploratory testing  
- Week 2: Test case execution (Android & iOS)  
- Week 3: Regression testing and documentation updates  
_(Subject to real app availability and updates)_

## 10. Entry & Exit Criteria

**Entry:**
- App is installed and functional  
- Test data/accounts are available  
- Test devices/emulators are configured

**Exit:**
- All high/critical flows tested on both OSs  
- No blocker bugs remain open  
- All findings are documented and reviewed

## 11. Risks and Assumptions
- Limited access to backend or logs for debugging  
- OS version fragmentation may affect behavior  
- Real devices prioritized; emulator use limited to backup  
- Assumes parity with web functionality, unless stated otherwise
