# Playwright Page Object Model Framework

## 🚀 Project Overview  
This repository demonstrates a **Page Object Model (POM)** test automation framework built using **Playwright** (JavaScript/TypeScript). The framework is structured to facilitate maintainable and scalable UI test automation, following best practices for separation of concerns, readability, and reusability.

## 🧱 Key Features  
- Organized directory structure separating page-objects and test files.  
- Page Object Model design pattern for enhanced maintainability.  
- Reusable locators and methods encapsulated in page classes.  
- Sample tests that demonstrate usage of page objects.  
- Easy to extend for additional pages and test scenarios.
  

## 🛠️ Getting Started  
### Prerequisites  
- Node.js (v14 or higher) installed on your machine.  
- npm or yarn package manager.

### Installation  
```bash
# Clone the repository  
git clone https://github.com/ATULHIRAY/Playwright_Page_Object_Model.git  
cd Playwright_Page_Object_Model  

# Install dependencies  
npm install  
# or  
yarn install  

# To run all tests  
npx playwright test  

# To run a specific test file  
npx playwright test tests/<test-file>.ts  
