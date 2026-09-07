# Day 02 | Setting Up Your Development Experience

In Day 01, we understood **what Power Apps is, why organizations use it, and the different types of Power Apps**.

Now let's understand **how we access Power Apps and start building an application**.

---

## 1. Accessing Power Apps

Before creating an application, we first need to sign in to Power Apps.

**URL:**  https://make.powerapps.com

### How to Sign In?

1. Open **https://make.powerapps.com**
2. Sign in using your Microsoft account.
3. Complete authentication or MFA if required.
4. After successful sign-in, Power Apps opens in the browser.
5. Check the selected **Environment** before starting your development work.

Power Apps uses the selected environment to determine where you create and work with applications and other resources.

### What Do You Need?

For regular organizational Power Apps development, you typically need:

- A Microsoft work or school account
- Appropriate Power Apps permissions/licensing
- Access to the required environment

For practice and learning, Microsoft also provides Developer/Trial options depending on your account and setup.

> The **Environment Maker** security role is typically required to create and manage resources in an environment.

---

## 2. Understanding Environment

Once we sign in to Power Apps, we need to know **where our application is going to be created and managed**.
  
Imagine a company is building an **Employee Leave Management App**.

The development team is creating the application, but they don't want developers to make changes directly in the application that is being used by business users.

So, the organization can maintain separate environments for different stages:

**DEV → TEST → PROD**

<img width="2056" height="765" alt="image" src="https://github.com/user-attachments/assets/458996d7-8ff9-4d40-a51e-abd5a1486909" />

> **Environment = An Environment is a container used to store, manage, and share business data, apps, and flows while keeping them separated based on different roles, security requirements, or audiences.**

### What Can Exist Inside an Environment?

An environment can contain resources such as:

- Power Apps
- Power Automate flows
- Dataverse
- Connections
- Solutions
- Environment Variables

### Why Is Environment Important?

Because it keeps different stages of development **separated and organized**.

```
DEV  → Build & Modify
TEST → Test & Validate
PROD → Business Users
```
---

## 3. Power Apps Home

After selecting the appropriate environment, we arrive at the **Power Apps Home** experience.

Think of Power Apps Home as the **starting point of our development work**.

From here, we can create new applications, access existing applications, search for resources, and navigate to different areas of Power Apps.

<img width="1821" height="864" alt="image" src="https://github.com/user-attachments/assets/4508a5bc-a029-435e-a9ae-a714a6af37fe" />

The Home experience mainly includes:

1. **Left Navigation Pane** — Navigate to different areas of Power Apps.
2. **Search** — Quickly find applications and resources.
3. **Environment Information and Settings** — View information and settings for the current environment.
4. **Build Apps** — Start creating applications.
5. **View and Edit Apps** — Access existing applications.
6. **Learning Resources** — Access learning and help resources.

> **Power Apps Home = The starting point from where we access and manage our Power Apps development experience.**

---

## 4. Interview Questions

If you understand the concepts covered in Day 02, you should be able to answer the following interview questions:

1. How Do You Access Power Apps?
2. What URL Is Used to Access Power Apps?
3. What Do You Need to Access Power Apps?
4. What Is an Environment in Power Apps?
5. Why Is an Environment Important?
6. Why Do Organizations Use Separate DEV, TEST, and PROD Environments?
7. What Can Exist Inside a Power Platform Environment?
8. What Is the Environment Maker Security Role?
9. What Is Power Apps Home?
10. What Are the Main Areas of Power Apps Home?
11. What Is the Purpose of the Environment Information and Settings Area?
