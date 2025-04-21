# GitHub Updates Tracker with n8n

This project is an automation built with n8n that monitors GitHub for new or recently updated repositories from major tech companies such as Google and Microsoft.  
Whenever a new repository is added or an existing one is updated, the system sends an email alert with key details.

---
### 1. Overview of the complete workflow  
![alt text](./images/workflow.png)
### 2. Example email result  
![alt text](./images/gmail.message.png)
### 3. GitHub API response  
![alt text](./images/json.output.png)
---

##  Project Goals

- Learn how to build a full automation flow using n8n
- Understand how to work with the GitHub REST API
- Practice working with HTTP requests, API, JSON parsing, expressions, conditions, and scheduling
- Build a professional, well-documented repository from scratch

---

##  What This Automation Does

1. Sends an HTTP request to GitHub's API for selected organization accounts (e.g., `microsoft`, `google`)
2. Scans the returned list of repositories
3. Filters only the recently updated ones based on today's date
4. Constructs a summary message with name, URL, and updated time
5. Sends one email containing all updates
6. Runs automatically once a day via a Schedule trigger

---

##  What I Learned From This Project

- What an API is and how to use HTTP requests inside n8n
- What a method is in HTTP
- The difference between HTTP request and HTTP response
- How to understand and extract values from JSON
- How to structure a URL and access data from endpoints
- What credentials are and why they matter when using APIs
- What status codes are and how they reflect request success or failure
- What headers are and how they work
- How data is passed from one node to the next in n8n
- How to use IF nodes for conditional logic
- How to format and combine data before sending it as an email
- How to run n8n both in the cloud and locally with Docker

---

##  Table of Contents

| Section | Link |
|--------|------|
| 01 - Setup and Installation | [01-setup/README.md](./01-setup/README.md) |
| 02 - Workflow Architecture | [02-workflow/README.md](./02-workflow/README.md) |
| 03 - Workflow Example Files | [03-examples/README.md](./03-examples/README.md) |
| 04 - Learning Notes | [04-learning-notes/README.md](./04-learning-notes/README.md) |
| Screenshots | [images/](./images/) |

---

##  Useful Links

- [n8n.io – Official Site](https://n8n.io)
- [GitHub REST API – Repositories](https://docs.github.com/en/rest/repos/repos)
- [n8n YouTube – Beginner Guide](https://www.youtube.com/watch?v=4BVTkqbn_tY&list=PLlET0GsrLUL59YbxstZE71WszP3pVnZfI&index=2)
- [n8n YouTube – Advanced Concepts](https://www.youtube.com/playlist?list=PLlET0GsrLUL5bxmx5c1H1Ms_OtOPYZIEG)
- [JSON Viewer – Helps visualize JSON output](https://jsonformatter.org/json-viewer)

---

