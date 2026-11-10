# 👋 Hi, I'm Yusuf Kenan Girgin!

### Software Test Engineer | QA Automation Engineer
**Electronics & Communications Engineer**



[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yusufkenangirgin/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yusufkg)
[![Website](https://img.shields.io/badge/Website-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://yusufkenangirgin.com/)

---

## 👨‍💻 About Me

I'm a **Software Test Engineer** with approximately **2 years of professional QA experience**, working on enterprise web applications, manual testing, test automation, and software quality assurance.

At **BGTS (BilgeAdam Technology)**, I contribute to testing **Human Capital Management (HCM)** and **Learning Management Systems (LMS)**.

My development background in C#, .NET, and SQL helps me investigate defects across application behavior, code, and data.

In my personal projects, I build Java-based UI and API tests, automate execution through GitHub Actions, and maintain documented test evidence.

---

## 🛠️ Technical Skills

### Test Automation

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![Karate](https://img.shields.io/badge/Karate-000000?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright_Java-2EAD33?style=flat-square)
![RestAssured](https://img.shields.io/badge/RestAssured-4B9B36?style=flat-square)
![TestNG](https://img.shields.io/badge/TestNG-DC382D?style=flat-square)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

- Selenium WebDriver and Cucumber BDD
- Karate UI and Playwright Java
- RestAssured API automation
- TestNG DataProvider, groups, and XML suites
- Page Object Model
- XPath locators and explicit waits
- Positive, negative, and data-driven testing
- HTTP status and JSON response assertions
- Failure screenshots, HTML snapshots, and browser cleanup
- HTML, JSON, and JUnit XML reporting

### Software Testing

Functional Testing · Regression Testing · Smoke Testing · Test Case Design · Defect Management · Retesting · API Validation · SQL Database Validation · Agile · Scrum · SDLC

### CI and Version Control

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

- Maven build and test validation
- Push and pull request workflows
- Independent API and browser test jobs
- Automated report collection
- CI failure investigation
- Conditional HTML report publication through GitHub Pages

### Programming and Development

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![DotNet](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square)

Java 17 · C# · .NET · ASP.NET MVC · ASP.NET Core MVC · Entity Framework Core · SQL Server · HTML · CSS · JavaScript · Bootstrap

### Tools and Collaboration

Jira · Azure DevOps · Bitbucket · Confluence · SharePoint

---

## 💼 Professional Experience

### Software Test Engineer
**BGTS (BilgeAdam Technology)**  
November 2024 – Present

- Design and execute test scenarios for enterprise HCM and LMS applications.
- Perform functional, regression, smoke, and negative testing.
- Contribute to Selenium WebDriver and Cucumber automation.
- Investigate defects and verify fixes through retesting.
- Perform API and SQL database validation.
- Track bugs and tasks using Jira and Azure DevOps.
- Prepare documentation using Confluence and SharePoint.
- Collaborate with developers and analysts in Agile teams.

### Software Development Intern
**BGTS (BilgeAdam Technology)**  
December 2023 – October 2024

- Contributed to ASP.NET MVC and ASP.NET Core MVC applications.
- Worked with C#, .NET, SQL Server, and Entity Framework.
- Implemented CRUD operations and database integrations.
- Gained experience in desktop and web development.

### Software Developer
**Yirmibeş Software & Consulting**  
December 2021 – February 2022

- Contributed to web interfaces using jQuery and AJAX.
- Supported backend development using C# and SQL.

---

## 🚀 Featured Project

### 🧪 Trendyol Test Automation

**Java 17 | Selenium | Cucumber | Karate UI | Playwright Java | RestAssured | TestNG | JUnit | Maven | GitHub Actions**

A personal QA automation project covering guest-user e-commerce workflows, a controlled local product API, browser automation, and automated reporting.

### Current Coverage

| Component | Implementation and Verification |
|---|---|
| Scenario catalog | 48 documented guest-user scenarios |
| Selenium / Cucumber | 7 implemented scenarios, 41 planned |
| Karate UI | 4 implemented Trendyol scenarios, 44 planned |
| Karate setup | 1 headless Chrome test against local HTML |
| RestAssured / TestNG | 5 API scenarios with 10 regression executions |
| API smoke suite | 3 executions |
| Root JUnit tests | 11 tests |
| Playwright local smoke | 1 Chromium test verified locally and in CI |
| Playwright live TC-001 | Implemented; 9 November execution failed with HTTP 403 |

Implementation status and execution evidence are tracked in separate documentation.

### Selenium Workflows

- TC-001 — Open the home page and verify its main elements.
- TC-002 — Return to the home page using the logo.
- TC-003 — Navigate through the category menu.
- TC-005 — Search with a valid keyword.
- TC-008 — Verify a search with no matching results.
- TC-010 — Replace the search query.
- TC-024 — Open and verify selected product details.

The tests use page objects, reusable step definitions, XPath locators, explicit waits, and scenario-level browser lifecycle management.

### Project Structure

```text
Trendyol-Test-Automation/
├── pom.xml
├── src/
│   ├── main/java/
│   │   └── com/yusuf/qa/pricing/
│   └── test/
│       ├── java/com/yusuf/qa/
│       │   ├── runners/
│       │   ├── steps/
│       │   ├── pages/
│       │   ├── support/
│       │   └── pricing/
│       └── resources/
│           └── features/
├── karate-ui/
│   ├── pom.xml
│   └── src/test/java/
├── api-tests/
│   ├── pom.xml
│   └── src/test/
├── playwright-ui/
│   ├── pom.xml
│   └── src/test/java/
├── .github/workflows/
│   └── ci.yml
├── scripts/
└── docs/
    ├── architecture.md
    ├── scenario-status.md
    ├── test-plani.md
    ├── roadmap.md
    └── evidence/
```

Each automation project has an independent Maven configuration. The documentation describes responsibilities, execution commands, scenario status, and dated verification results.

### API Automation

RestAssured tests exercise a controlled local product API.

- Product listing and retrieval
- Product creation and persistence checks
- Invalid request rejection
- Unknown product ID responses
- HTTP status and JSON assertions
- Six invalid payload variations through TestNG DataProvider
- Smoke and regression selection through XML suites
- An isolated local server for each test

### Playwright Automation

The local smoke test launches headless Chromium, enters text using XPath, clicks a search button, and verifies the result. It runs locally and in a dedicated GitHub Actions job.

The live TC-001 test checks:

- Navigation HTTP response
- Home page URL
- Logo visibility
- Search field visibility
- Category navigation visibility
- Application error elements

During the latest documented live execution, the site returned **HTTP 403**. The test reported the HTTP failure before continuing to element checks.

Failure diagnostics record:

- HTTP status and current URL
- Page HTML
- Browser screenshot

Evidence collection errors are attached to the original failure. The live scenario remains awaiting a successful execution.

### Reliability and Reporting

- Explicit waits for Selenium synchronization
- Product identity and search relevance checks
- Unit-tested Turkish currency parsing
- PNG attachments for failed Selenium scenarios
- Browser cleanup behavior covered by unit tests
- Playwright HTTP and page diagnostics
- Dated records of successful and failed executions

### GitHub Actions

| Job | Purpose |
|---|---|
| `verify` | JUnit tests, Cucumber dry-run, and Karate local browser smoke |
| `api-tests` | RestAssured and TestNG regression |
| `playwright-tests` | Chromium installation and local Playwright smoke |
| `publish-reports` | Conditional GitHub Pages report publication |

The documented successful CI run for commit `28a0a67` includes:

| Test Group | Successful Executions |
|---|---|
| Root JUnit tests | 11 |
| Cucumber step mappings | 7 |
| Karate local browser smoke | 1 |
| API regression | 10 |
| Playwright local browser smoke | 1 |

Cucumber dry-run validates step mapping. Karate and Playwright smoke tests exercise local HTML fixtures. Live Selenium and Karate execution is available through a manual workflow option.

Reports are collected as `test-reports`, `api-test-reports`, and `playwright-test-reports`, with 14-day retention. Pages publication waits for all three test jobs to succeed.

### Documentation

The `docs/` directory contains:

- Automation architecture and execution flow
- Scenario implementation status
- Test plan and development roadmap
- Dated CI and local test evidence
- Failure investigation records

The documentation was prepared with AI assistance and reviewed against source code and execution records. Test report files are generated automatically during execution.

[Repository](https://github.com/yusufkg/Trendyol-Test-Automation) ·
[GitHub Actions](https://github.com/yusufkg/Trendyol-Test-Automation/actions/workflows/ci.yml) ·
[Documented CI Run](https://github.com/yusufkg/Trendyol-Test-Automation/actions/runs/42169491268)

---

## 📂 Other Projects

### 🍔 MVC Hamburger Ordering Application

**C# | .NET 8 | ASP.NET Core MVC | EF Core | SQL Server | Identity**

- User authentication
- Menu selection and order customization
- Price calculation
- Database integration

[Repository](https://github.com/yusufkg/MVCHamburgerApp)

### 🥗 Diet Automation

**C# | .NET 8 | Windows Forms | EF Core | SQL Server**

- Layered architecture and repository pattern
- Food and meal management
- CRUD operations
- Relational database operations

[Repository](https://github.com/yusufkg/Diyet-Otomasyonu)

### 💿 Record Store Management

**C# | .NET 8 | Windows Forms | EF Core | SQL Server**

- Album management
- User authentication
- Search and filtering
- Database operations

[Repository](https://github.com/yusufkg/Plak-Dukkani)

### 📝 ASP.NET Core MVC Blog Management

**C# | ASP.NET Core 5.0 | EF Core | SQL Server**

- Administrator and writer panels
- Blog and category management
- Database operations
- Web API examples

[Repository](https://github.com/yusufkg/MVC-CORE-KAMPI)

---

## 🎓 Education

**B.Sc. Electronics and Communications Engineering**  
Çankaya University — 2021

---

## 🔬 Research Interests

Artificial Intelligence · Human–Robot Interaction · Robotics · Software Quality and Reliability

---

## 🎯 Professional Goals

- Expand verified UI and API automation coverage.
- Develop reusable and maintainable test components.
- Improve Playwright Java skills and failure diagnostics.
- Strengthen CI reliability and reporting.
- Explore performance testing.
- Apply software quality practices to AI and robotics.

---

## 📫 Connect With Me

[Website](https://yusufkenangirgin.com/) ·
[LinkedIn](https://www.linkedin.com/in/yusufkenangirgin/) ·
[GitHub](https://github.com/yusufkg) ·
[X](https://twitter.com/yusufkenangrg) ·
[Instagram](https://www.instagram.com/yusufkenangrgn/)
