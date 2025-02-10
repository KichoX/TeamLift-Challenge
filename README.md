# TeamLift-Challenge - README
Challenge for internship @TeamLift

## 👋 Hello and Welcome!
Hi there! My name is Kristijan Lazarov, and I'm excited to take on this internship challenge. I have a passion for problem-solving, API development, and building efficient software solutions. This document outlines my approach to solving the challenge, including both theoretical explanations and practical implementation details.

## 🛠 Technical Part: Database Design and API Structure

#### Concept 1: Entity-Relationship (ER) Diagram

An **Entity-Relationship (ER) Diagram** is a visual representation of the data model, showcasing how different entities relate to each other within the system. It helps in understanding the structure and logical flow of the database.

**Solution Image 1:**  
<img width="763" alt="diagram" src="https://github.com/user-attachments/assets/7441a230-6208-49bf-a9ae-c8fe279b34c7" />

#### Concept 2: Relationships in ER Diagrams

ER diagrams consist of **entities**, **attributes**, and **relationships**. The relationships define how entities interact with each other. Common relationships include one-to-one, one-to-many, and many-to-many.

**Solution Image 2:**  
<img width="749" alt="Chen Notation" src="https://github.com/user-attachments/assets/1908e1e5-23af-4360-a318-d17879a86384" />

---

## 🔌 API Endpoints

#### Create a New Skill
```http
POST /managers/{id}/skill/{skillName}
```
-Creates a new skill for the specified manager.


#### Verify an Employee's Skill
```http
POST /managers/{id}/employees/{employeeId}/skills/{skillId}/verify
```
-Verifies an employee's skill under a manager's supervision.


#### Retrieve All Skills in an Employee's Skill Wallet
```http
GET /employees/{id}/skills
```
-Retrieves all skills associated with a specific employee.


#### Retrieve All Skills for a Manager
```http
GET /managers/{id}/skills
```
-Retrieves all skills managed by a specific manager.


---

##  Creative Part

### Scenario 1: Using Teamo to Boost Efficiency ⚡

- **Objective:** Explore how AI tools can enhance workflow efficiency using Teamo.
- **Steps Taken:**
  - Researched Teamo as an AI productivity tool.
  - Attempted to register for the free version to test features.
  - Explored TeamLift's website in search for the Registering process.
- **Issue Encountered:**
  Unfortunately, I couldn't find a link to register and test Teamo. However, based on my prior experience with AI tools like ChatGPT and Cursor:
  - AI tools assist in automating repetitive tasks.
  - They enhance coding efficiency by providing intelligent suggestions.
  - Time spent on debugging and documentation is significantly reduced.
- **Outcome:**
AI tools have had a positive impact on productivity, even though I couldn't directly test Teamo. With proper access, it would be interesting to explore its benefits further. However, tools like ChatGPT were invaluable during the brainstorming process for ER diagrams and API calls. They also helped me structure and refine this README file to perfectly represent my solution to this challenge!


### Scenario 2: AI Use Cases in Recruitment 📈

- **Objective:** Identify AI tools that optimize recruitment processes.
- **Steps Taken:**
  - Researched common recruitment pain points, and acording to Emi Labs - Manually screening applications and resumes is one of the most time-consuming parts of recruitment.
  - Found AI tools tailored for recruitment:
    - **HireVue** – AI-driven video interview analysis.
    - **Textio** – Enhances job descriptions for better hiring outcomes.
    - **Paradox** – AI chatbot for candidate engagement.
  - Explored unique ways AI can optimize workflows.
- **Outcome:**
  - AI significantly reduces manual effort in candidate screening and engagement.
  - Automated tools improve hiring efficiency, reducing time-to-hire.
  - Recruitment agencies can benefit from integrating AI to streamline their processes.

---

## 🚀 Conclusion

Summing up, this challenge helped me understand key concepts related to **AI tool integration, and recruitment automation**. Through both Technical and Creative part, I explored how technology enhances efficiency across different domains.

Looking forward to further discussions and feedback!

Thank you for reviewing my challenge submission! 😊



