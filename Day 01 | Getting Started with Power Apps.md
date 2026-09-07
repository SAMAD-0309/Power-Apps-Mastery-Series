# Day 01 | Getting Started with Power Apps

## 1. Why Do We Need Low-Code Platforms?

Before understanding what a Low-Code Platform is, let's first understand the problem with traditional application development.

When we build a business application using traditional development, we generally need to develop and manage multiple layers such as the user interface, business logic, database, APIs, authentication, security, deployment, and maintenance.

For example, consider a simple **Employee Leave Management Application**.

A traditional approach may require developers to design the user interface, create the database, write application and backend logic, develop APIs and integrations, implement authentication and security, build the approval process, and then deploy and maintain the application.

For a relatively simple business requirement, this can involve considerable **development time, effort, and technical resources**.

This creates a need for a development approach that can:

- Reduce repetitive development effort
- Accelerate application development
- Reuse existing capabilities
- Connect easily with business data and services
- Still provide flexibility for implementing business requirements

This is where **Low-Code Platforms** come into the picture.

---

## 2. What Is a Low-Code Platform?

A **Low-Code Platform** is a development platform that allows applications to be built with minimal hand-written code.

Instead of developing every application component from scratch, developers can use visual development tools, pre-built components, connectors, configuration, and reusable capabilities.

The objective is to **reduce repetitive coding and accelerate application development**.

### Low-Code Does Not Mean No-Code

Low-code does not mean that coding is completely eliminated.

Developers can still use code or expressions when the business requirement requires additional logic or customization.

For example, Power Apps uses **Power Fx** to implement formulas and application logic.

> **Low-Code = Visual Development + Configuration + Reusable Capabilities + Less Hand-Written Code**

---

## 3. What Is Microsoft Power Platform?

**Microsoft Power Platform** is Microsoft's low-code platform for building applications, automating business processes, analyzing data, creating websites, and building AI-powered solutions.


<p align="center"><img width="600" height="300"" alt="image" src="https://github.com/user-attachments/assets/b9ba8cfa-6180-428d-a595-b8e5b3a3d891" /></p>

The main components of Microsoft Power Platform are:

| Component | Purpose |
|---|---|
| **Power Apps** | Build business applications |
| **Power Automate** | Automate business processes |
| **Power BI** | Analyze and visualize data |
| **Power Pages** | Build external-facing websites |
| **Copilot Studio** | Build and customize AI agents |

These components can work together to create complete business solutions.

### Example

Consider an **Employee Leave Management** scenario.

An employee submits a leave request using **Power Apps**.

**Power Automate** can manage the approval process.

The request and approval information can be stored in a business data source.

**Power BI** can then be used to analyze the leave data.

---

## 4. What Is Microsoft Power Apps?

**Microsoft Power Apps** is a low-code application development platform that enables organizations to build business applications.

Power Apps allows developers and business users to:

- Build custom business applications
- Connect applications to business data
- Implement business logic
- Create user interfaces
- Integrate with other services

Power Apps provides different application experiences depending on the type of business requirement.

---

## 5. Why Power Apps?

The need for Power Apps comes from a common business problem:

> **Businesses need custom applications, but building every application from scratch can require significant development effort and time.**

Power Apps helps organizations develop solutions faster by providing visual development tools, pre-built capabilities, connectors, Dataverse, and integration with the Microsoft ecosystem.

| Business Requirement | Power Apps Capability |
|---|---|
| Build applications faster | Low-code development |
| Create a customized user experience | Canvas Apps |
| Build data-driven applications | Model-Driven Apps |
| Build external-facing websites | Power Pages |
| Connect to different data sources | Connectors |
| Store and manage business data | Dataverse |
| Implement application logic | Power Fx |
| Automate business processes | Power Automate |

The objective is not simply to eliminate coding.

The objective is to **reduce unnecessary development effort while still providing the flexibility required to build business solutions**.

---

## 6. Types of Power Apps

Power Apps provides different ways to build applications and business experiences.

The major types covered in this series are:

1. **Canvas Apps**
2. **Model-Driven Apps**
3. **Power Pages**

### Canvas Apps

Canvas Apps follow a **UI-first** approach.

They provide extensive control over the application's:

- Screens
- Layout
- Controls
- Navigation
- User experience

Canvas Apps can connect to multiple data sources through connectors.

For example, a Canvas App can work with business data from sources such as:

**SharePoint | Dataverse | SQL Server | Excel | Other Connectors**

<p align="center"><img width="600" height="420" alt="image" src="https://github.com/user-attachments/assets/554782e3-8a05-492a-88cc-47b7fb88ffbf" /></p>

Canvas Apps are suitable when the application requires a **highly customized user experience**.

### Model-Driven Apps

Model-Driven Apps follow a **data and business-process-first** approach.

They are built on **Microsoft Dataverse**.

The application experience is largely driven by the underlying data model and components such as:

- Tables
- Relationships
- Forms
- Views
- Charts
- Dashboards
- Business Rules
- Business Process Flows

<p align="center"><img width="700" height="440" alt="image" src="https://github.com/user-attachments/assets/bc73169a-4c53-45c6-9815-148a95daed29" /></p>

Model-Driven Apps are suitable for **structured, data-driven business applications** where the data model and business processes are central to the solution.

### Power Pages

**Power Pages** is used to create **external-facing business websites**.

It is useful when external users such as customers, partners, or other audiences need to interact with business data and processes through a website.

Power Pages can work with **Microsoft Dataverse** and provides a low-code approach for creating data-driven external websites.

<p align="center"><img width="720" height="110" alt="image" src="https://github.com/user-attachments/assets/74700577-8469-48c1-97ec-c1bac6361e20" /></p>

---

## 7. Canvas App vs Model-Driven App

Canvas Apps and Model-Driven Apps solve different types of business requirements.

| Feature | Canvas App | Model-Driven App |
|---|---|---|
| Approach | UI-first | Data-first |
| UI Control | High | More standardized |
| Data Sources | Multiple | Dataverse |
| Design Flexibility | Very High | Structured |
| Dataverse Required | No | Yes |
| Best Suited For | Customized user experiences | Data-driven business applications |

---

## 8. When Should You Use Which?

The choice should always depend on the **business requirement**.

### Use Canvas Apps When

You need:

- A highly customized user interface
- Greater control over the user experience
- Custom screen layouts
- An application that works with multiple data sources

### Use Model-Driven Apps When

You need:

- A data-driven application
- Dataverse as the primary data platform
- Structured forms and views
- Relationships between business data
- Business rules and structured business processes

### Use Power Pages When

You need:

- An external-facing website
- Customers or partners to access business information
- External users to submit or interact with business data
- A website-based experience connected to business data

---

## 9. Interview Questions

If you understand the concepts covered in Day 01, you should be able to answer the following interview questions:

1. What Is a Low-Code Platform?
2. Why Do Organizations Need Low-Code Platforms?
3. What Is the Difference Between Low-Code and No-Code?
4. What Is Microsoft Power Platform?
5. What Are the Major Components of Microsoft Power Platform?
6. How Can Power Platform Components Work Together?
7. What Is Microsoft Power Apps?
8. Why Would You Choose Power Apps Instead of Traditional Application Development?
9. What Are the Major Types of Power Apps?
10. What Is a Canvas App?
11. What Is a Model-Driven App?
12. What Is Power Pages?
13. What Is the Difference Between Canvas Apps and Model-Driven Apps?
14. Why Are Model-Driven Apps Built on Dataverse?
15. Can Canvas Apps Connect to Multiple Data Sources?
16. When Would You Choose a Canvas App?
17. When Would You Choose a Model-Driven App?
18. When Would You Use Power Pages?
19. How Would You Decide Which Power Apps Experience Is Appropriate for a Business Requirement?
