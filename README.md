# ASD - Attendance Register

**USERS:**
- Admin *(with full access)*
- Trainer *(with limited access)*


## ADMIN Requirements
- Ability to:
  - insert, delete, and edit **trainers**
  - insert, delete, and edit **athletes**
  - assign **athletes** to **one or more categories** (example category_A, category_B)
  - assign **trainer** to **one or more categories** (example category_A, category_B)
  - view the list of **athletes**, **categories** and **trainers**
  - view the **monthly hours** for **each trainer**, *with the option of generating a pdf file*
  - view a **monthly report "trainer : hours/monthly", **with the option of generating a pdf file**


## TRAINER Requirements
- Access to the **calendar**
- For each date, the trainer must be able to:
  - view the **list of own categories**
  - view the **list of athletes** assigned to the specific category
  - **flag** zero or more athletes as present for training
  - enter the number of **hours/minutes** of training (in increments of 30 minutes)
  - **confirm** what was entered
  - make **changes** to the entered data **up to 7 days** from the date
  - view the attendance list for each **month** and be able to **generate a PDF file**


## RULES to follow
- Create an **ADR** *(Architectural Decision Record)* with a description of the **implementation choices**
- **Provide a Flowchart of the project** 
- **Create/Upgrade a Github Project** connected to the repository
- Read **carefully** the task description
- Analyze the task, and **create relative subtasks** to track any requirement and knowledge needed
- Define a **deadline** for the main task
- **Create Issue** connected to the Task and **assign** it to a team **member**
- When working on a task, move it to the **In progress** column
- After each task completion, **move it to the Done column** and **open a PR** *(Pull Request)* that will have to be validated by the **Team Lead**
- Once a **POC** *(Proof of Concept)* is created the project needs to be implemented using the **CI**, so **every PR** needs to be **tested**
- The **entire project** must be:
  - implemented and **tested** with more than **85% coverage**
  - **fully described** in the **README** file
  - **deployed** and work on both **desktop and mobile**
