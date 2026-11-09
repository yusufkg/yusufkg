Playwright CI entegrasyonunu ve HTTP 403 hata tanılamasını güncelledim. İş deneyimi bilgilerini paylaştığın metne göre korudum.

```markdown
# 👋 Hi, I'm Yusuf Kenan Girgin!

### Software Test Engineer | QA & Test Automation
**Electronics & Communications Engineer**

📍 Ankara, Türkiye

I'm a Software Test Engineer at **BGTS (BilgeAdam Technology)**, working on enterprise web applications in Human Capital Management (HCM) and Learning Management Systems (LMS).

I focus on functional testing, regression testing, defect management, test documentation, and automation. My software development background helps me investigate issues across application behavior, code, and data.

In my personal projects, I develop Java-based UI and API tests with Selenium, Cucumber, Karate, RestAssured, TestNG, and Playwright.

---

## About Me

- Design and execute functional, regression, smoke, and negative tests.
- Document defects, perform retesting, and verify fixes.
- Develop Selenium and Cucumber tests using Page Object Model.
- Write RestAssured API tests with TestNG data providers and test groups.
- Develop browser automation examples with Karate UI and Playwright Java.
- Maintain GitHub Actions workflows and downloadable test reports.
- Investigate browser failures using HTTP responses, HTML snapshots, and screenshots.
- Work with C#, .NET, SQL Server, and web development technologies.
- Explore Artificial Intelligence, Human–Robot Interaction, and Robotics.

---

## Technical Skills

### Test Automation

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![Karate](https://img.shields.io/badge/Karate-000000?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright_Java-2EAD33?style=flat-square)
![RestAssured](https://img.shields.io/badge/RestAssured-4B9B36?style=flat-square)
![TestNG](https://img.shields.io/badge/TestNG-DC382D?style=flat-square)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

- UI and REST API testing
- BDD and Gherkin
- Page Object Model
- XPath locators
- Explicit waits and browser synchronization
- HTTP status and JSON response assertions
- Positive, negative, and data-driven testing
- TestNG DataProvider, groups, and XML suites
- Failure screenshots and browser cleanup
- HTML snapshots and navigation diagnostics
- HTML, JSON, and JUnit XML reporting

### Testing Practices

- Manual Testing
- Functional Testing
- Regression Testing
- Smoke Testing
- Test Case Design
- Boundary and Negative Testing
- Defect Management and Retesting
- Test Documentation
- Agile, Scrum, and SDLC

### CI and Version Control

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

- Maven build and test validation
- Push and pull request workflows
- Cucumber step-mapping checks
- Headless Chrome and Chromium testing
- Independent API and Playwright CI jobs
- Test report artifact collection
- CI log analysis and execution evidence
- Conditional HTML report publication through GitHub Pages

### Programming and Development

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square)
![DotNet](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

C# · Java · JavaScript · SQL · ASP.NET MVC · ASP.NET Core · Entity Framework Core · Windows Forms · HTML · CSS · Bootstrap

### Tools and Collaboration

Azure DevOps · Jira · Bitbucket · Confluence · SharePoint

---

## Professional Experience

### Software Test Engineer
**BGTS (BilgeAdam Technology)**  
November 2024 – Present

- Design and execute manual test cases for HCM and LMS enterprise applications.
- Perform functional, regression, and smoke testing.
- Contribute to Selenium WebDriver and Cucumber automation.
- Track defects, execute retesting, and verify fixes.
- Prepare test documentation.
- Collaborate with development teams in Agile environments.

### Software Development Intern
**BGTS (BilgeAdam Technology)**  
December 2023 – October 2024

- Contributed to ASP.NET MVC and ASP.NET Core MVC applications.
- Worked with C#, .NET, SQL Server, and Entity Framework.
- Implemented CRUD operations and database integrations.
- Gained experience with Windows Forms applications.

### Software Developer
**Yirmibeş Software & Consulting**  
December 2021 – February 2022

- Contributed to web interface development.
- Worked with jQuery and AJAX.
- Supported backend development using C# and SQL.

---

## Featured Projects

### Trendyol Test Automation

**Java 17 | Selenium | Cucumber | Karate UI | Playwright Java | RestAssured | TestNG | JUnit | Maven | GitHub Actions**

A personal QA automation project covering guest-user e-commerce workflows, a controlled local product API, browser automation, and automated test reporting.

#### Current Scope

| Component | Scope and Status |
|---|---|
| Scenario catalog | 48 documented guest-user scenarios |
| Selenium / Cucumber | 7 implemented scenarios, 41 planned |
| Karate UI | 4 implemented Trendyol scenarios, 44 planned |
| Karate setup | 1 headless Chrome test against local HTML |
| RestAssured / TestNG | 5 API scenarios with 10 regression executions |
| API smoke suite | 3 test executions |
| Root unit tests | 11 tests |
| Playwright local smoke | 1 headless Chromium test verified locally and in CI |
| Playwright live TC-001 | Implemented, latest local execution failed with HTTP 403 |
| Reporting | Cucumber and Karate HTML, TestNG reports, JUnit XML, and CI artifacts |

#### Implemented Selenium Workflows

- TC-001 — Open the home page and verify its main elements.
- TC-002 — Return to the home page using the logo.
- TC-003 — Navigate through the category menu to a subcategory.
- TC-005 — Search for a product.
- TC-008 — Verify a search with no matching results.
- TC-010 — Replace the current search query.
- TC-024 — Open a selected product and verify its details.

Dated execution records document the scenarios exercised and their results.

#### Architecture

The repository contains independent Maven projects:

- Root project — Selenium, Cucumber, and JUnit.
- `karate-ui/` — Karate browser automation.
- `api-tests/` — RestAssured and TestNG API automation.
- `playwright-ui/` — Playwright Java browser tests.

The Selenium project organizes feature files, step definitions, page objects, browser lifecycle management, and reusable utilities by responsibility.

#### API Automation

API tests run against a controlled local product API.

- Verify product listing and retrieval.
- Create a product and verify persistence.
- Reject invalid product data without creating records.
- Verify responses for unknown product IDs.
- Execute six invalid payload variations using TestNG DataProvider.
- Select smoke and regression coverage through TestNG XML suites.
- Create an isolated local server for each test.

#### Reliability and Diagnostics

- Use explicit waits for Selenium synchronization.
- Verify product identity and search relevance.
- Parse Turkish currency formats with tested utility code.
- Attach PNG screenshots to Cucumber reports when capture is available.
- Handle screenshot and browser cleanup failures.
- Cover cleanup behavior with unit tests.
- Check navigation HTTP responses in the Playwright live test.
- Capture the URL, HTTP status, HTML, and screenshot after a Playwright failure.
- Preserve the original failure when evidence collection also fails.
- Maintain dated test evidence and investigation notes.

#### Playwright Development

The local Playwright smoke test launches headless Chromium, fills a search field, clicks a button using XPath, and verifies the displayed result.

This test passed locally and in GitHub Actions.

An additional live TC-001 test checks the Trendyol home page URL, logo, search field, category links, and application error elements.

The latest local live execution received HTTP 403. Navigation diagnostics identified the response before element assertions ran. The live scenario remains awaiting a successful execution.

#### CI and Test Evidence

GitHub Actions includes three test jobs:

| Job | Coverage |
|---|---|
| `verify` | Root unit tests, Cucumber dry-run, and Karate local browser smoke |
| `api-tests` | RestAssured and TestNG API regression |
| `playwright-tests` | Chromium installation and Playwright local browser smoke |

Reports are uploaded as:

- `test-reports`
- `api-test-reports`
- `playwright-test-reports`

Artifacts are configured for 14-day retention and collection after test failures.

The verified CI run for commit `28a0a67` completed:

| Test Group | Successful Executions |
|---|---|
| Root JUnit tests | 11 |
| Cucumber step mapping | 7 |
| Karate local browser smoke | 1 |
| RestAssured API regression | 10 |
| Playwright local browser smoke | 1 |

An earlier push run encountered a Karate Chrome startup connection failure. The failed job passed when rerun, and the investigation was recorded.

Live Selenium and Karate tests can be selected manually through the workflow. The Playwright live TC-001 test runs through an explicit Maven command.

GitHub Pages publication is configured for eligible successful main-branch runs. The publication job waits for all three test jobs.

[Repository](https://github.com/yusufkg/Trendyol-Test-Automation) ·
[GitHub Actions](https://github.com/yusufkg/Trendyol-Test-Automation/actions/workflows/ci.yml) ·
[Verified CI Run](https://github.com/yusufkg/Trendyol-Test-Automation/actions/runs/42169491268)

---

### MVC Hamburger Ordering Application

**C# | .NET 8 | ASP.NET Core MVC | EF Core | SQL Server | Identity**

A web application for hamburger ordering and management.

- User authentication
- Menu selection and order customization
- Price calculations
- Database integration

[Repository](https://github.com/yusufkg/MVCHamburgerApp)

### Diet Automation

**C# | .NET 8 | Windows Forms | EF Core | SQL Server**

A desktop application for managing food, meals, and portions.

- Layered architecture
- Repository pattern
- Entity Framework Core
- Relational database operations

[Repository](https://github.com/yusufkg/Diyet-Otomasyonu)

### Record Store Management

**C# | .NET 8 | Windows Forms | EF Core | SQL Server**

A desktop application for album and record management.

- Album management
- User authentication
- Search and filtering
- Database operations

[Repository](https://github.com/yusufkg/Plak-Dukkani)

### ASP.NET Core MVC Blog Management

**C# | ASP.NET Core 5.0 | EF Core | SQL Server | MVC**

A layered blog application with administrator and writer panels.

- Blog and category management
- Database operations
- Web API examples

[Repository](https://github.com/yusufkg/MVC-CORE-KAMPI)

---

## Research Interests

- Human–Robot Interaction
- Artificial Intelligence
- Assistive and Healthcare Robotics
- Human-Centered Technology
- Software Quality and Reliability

I explore how software engineering, AI, and robotics can support reliable and accessible technologies.

[Read My Articles](https://yusufkenangirgin.com/)

---

## Professional Goals

- Expand verified UI and API test coverage.
- Develop maintainable automation code.
- Improve browser synchronization and failure diagnostics.
- Strengthen CI workflows and test evidence.
- Continue developing Playwright Java tests.
- Connect software quality practices with AI and robotics research.

---

## Connect With Me

[Website](https://yusufkenangirgin.com/) ·
[LinkedIn](https://www.linkedin.com/in/yusufkenangirgin/) ·
[X](https://twitter.com/yusufkenangrg) ·
[Instagram](https://www.instagram.com/yusufkenangrgn/)
```
