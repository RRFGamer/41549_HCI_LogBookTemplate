[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Notion| A very flexible and customizable note-taking with project management features, templates, tags ...| [Competitor Analysis Notion](competitors/Competitor_Analysis_Notion.md)| 
| Microsoft OneNote |A digital notebook with freeform note organization, handwriting support, section-based structuring and office type stylization.|[Competitor Analysis Microsoft OneNote](competitors/Competitor_Analysis_Notion.md)|
| Google Keep| A simple note-taking app with color notes, reminders, checklist image annotation.| [Competitor Analysis Google Keep](competitors/Competitor_Analysis_Google_Keep.md)|




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
Three usability experts conducted an evaluation using Jakob Nielsen’s Ten Usability Heuristics. Each expert independently identified issues and rated them based on frequency, impact, and persistence.

The severity scale used:
<li> 0 – Not a usability problem </li>
<li> 1 – Cosmetic issue </li>
<li> 2 – Minor issue </li>
<li> 3 – Major issue </li>
<li> 4 – Usability catastrophe </li>

<br>
After individual assessments, the experts discussed discrepancies and reached a consensus on severity ratings.


#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
The Cognitive Walkthrough was conducted to analyze how easily a new user can complete key tasks in Google Keep. The method focused on evaluating whether users can understand and execute actions without prior knowledge, identifying usability barriers along the way.

#### Task Selection and Task Analysis

The selected tasks represent common actions users perform in Google Keep. Each task was broken down into its essential subtasks.


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Creating and Organizing a Note** | Open Google Keep and tap on "Take a note"     |
|                             | Type text or insert an image/drawing |
|                             | Assign a label, change color, or pin the note      |
|                             | Ensure the note is saved and return to the main view                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Setting a Reminder for a Note** | Open Google Keep and choose a note |
|                               | Tap the reminder icon             |
|                               | Choose a time, date and frequency of the reminder             |
|                               | Ensure the reminder is set and visible in the note        |


#### Results

Task: Creating and Organizing a Note

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      |  Open Google Keep and tap on "Take a note"   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Type text or insert an image/drawing   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Assign a label, change color, or pin the note   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4    | Ensure the note is saved and return to the main view        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

<br>

Task: Creating and Organizing a Note

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      |  Open Google Keep and choose a note   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Tap the reminder icon   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Choose a time, date and frequency of the reminder     | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4    | Ensure the reminder is set and visible in the note        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |


---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role                                 | Key Insights                                                                                                                                                           | Link to Notes                              |
| ---------- | -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| 2025-02-27 | Rafael Claro/University Student with part time job | Two categories of notes. Paper notepad used in part time. Sticky notes software used to aid University project. Would like deeper integration of sticky note software. | [📄 Notes](interviews/interview-Rafael.md) |
| 2025-02-12 | anonymous 1/University Student/ IT researcher | Likes to use notion to take notes of articles for his research/thesis. Likes to use notion because is a very "complete" and customizable app. Thinks that first-time users can be overwhelmed because of all the options that notion can provide. | [📄 Notes](interviews/interview-1.md) |
| 2025-02-12 | anonymous 2/University Student/ IT researcher | Likes note-taking apps that it is as simple as possible. Would like some customization in the default apps. Tried to use notion, but stopped because was very overwhelming to use.  | [📄 Notes](interviews/interview-2.md) |
| 2025-02-12 | anonymous 3/University Student| Likes to use the default apps because of the simplicity and facility to use. Would like some, customization in the default apps. | [📄 Notes](interviews/interview-3.md) |


### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
