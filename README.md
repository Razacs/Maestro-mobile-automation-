# 📱 Mobile Test Automation for Android using [Maestro](https://maestro.mobile.dev/) by mobile.dev

This repository provides a Mobile test automation framework for mobile test automation using **[Maestro](https://maestro.mobile.dev/)**. This contains Pages and Objects Framework, It supports:

- ✅ Android Apps (Real Device & Emulator)  

> Powered by Maestro – the simplest UI testing framework for mobile developers.

---

## 📦 Requirements

Ensure the following tools are installed and configured on your system:

### 🔧 Development Environment

- [ ] **VS Code** or any code editor of your choice
- [ ] **Java Development Kit (JDK)**
- [ ] **Android Studio**
  - Install the **Android SDK** using Android Studio

### 🛠️ Environment Variables

Set the following environment variables:

- `JAVA_HOME`
- `ANDROID_HOME`


> 💡 If you're not sure how to do this, refer to online guides or [this helpful link](https://stackoverflow.com/questions/24342886/how-to-set-java-home-on-windows-8).


## Folder Structure

1) apps --> Folder contains apps for android & ios
2) flows folder contains elements, Objects
3) subflows folder contains validations and elements
4) dashboard & onboarding folder contains all Pages function and definition
5) run-test.yaml is E2E test suits runner that contains all functions and classes defined


![image](https://github.com/user-attachments/assets/270621ad-02e7-473b-b28b-41b203dfcec6)

## Steps of Execution 

Install app in Mobile **(adb install sample.apk)**

**There are 2 types of Report for Test Execution using Maestro : html and junit.**

- `Run Android Tests with Html Report` :

maestro test wikipedia-android-advanced/run-test.yaml --format html

- `Run Android Test with junit Report` :

maestro test wikipedia-android-advanced/run-test.yaml --format junit --output report.xml

Output of the test 

![image](https://github.com/user-attachments/assets/c89bac73-fef5-4d42-b4ca-486ff50b4f87)

https://github.com/user-attachments/assets/7e83df26-0a2e-4180-9945-858d85031c0f


### 📊 Reporting Tools

- **Allure Report**  
  Install via:
  ```bash
  npm install -g allure-commandline --save-dev

Refer to the commands and Official Documenation of Maestro 

https://github.com/mobile-dev-inc/maestro-docs/tree/main/api-reference/commands

https://docs.maestro.dev/

Let me know if you need more information from my side. 
Thanks
