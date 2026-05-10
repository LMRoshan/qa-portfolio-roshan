QA Portfolio - Roshan Lama
eSewa Payment Testing Project
This repository contains my QA testing portfolio for eSewa's "Send Money" feature, created as part of my application for the QA Intern position at eSewa.

What's Inside

Test Plan
8 test cases covering:
  Positive flows (valid transactions)
  Negative flows (invalid inputs, insufficient balance)
  Boundary testing (minimum amounts, zero values)
  Security testing (session timeout, PIN validation)
  Functional testing (transaction history accuracy)
  
Bug Reports
  1 observation documented with:
  Severity and priority classification
  Step-by-step reproduction instructions
  Impact analysis
  

Test Environment
Device:	Google Pixel 6 (Android 16)
App:	eSewa Mobile App v4.8.3.0
Network:	WiFi (50 Mbps)
Tools:	Manual testing

Key Findings
Core functionality (send money, balance check, PIN validation) works correctly
Error handling for invalid inputs is robust
Session security observation: PIN re-authentication occurs at final confirmation step rather than immediately upon returning from idle period

All testing conducted on my personal verified eSewa account using my own funds (NPR 1-500 test transactions).
