[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                                                                               |
| ----------------- | --------------------------------------------------------------------------------------------- |
| Drivvo            | Vehicle management application that allows you to control expenses, maintenance and deadlines |
| Fuelio            | Application similar to Drivvo, focused on managing fuel and vehicle expenses                  |



## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution

Drivvo


### - Heuristic Evaluation

#### Method

Heuristic evaluation carried out by the 3 members of the group, using the given template.
Severity scale: 0 (No problem) to 4 (Critical problem).
Method: Everyone did their own and then we discussed


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                            | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| ------------------------------------ | ------------ | -------- | -------- | ------------------------------------------- |
| Subscription pop-up cannot be closed | 4            | 3        | 3        | Ensure that all pop-ups have a close button |
| Polluted screen                      | 2            | 3        | 1        | Clean the pop-ups                           |
| Not very intuitive                   | 2            | 1        | 2        |                                             |
| Week feedback                        | 2            | 2        | 2        | Add more visual confimations                |
| No help offer                        | 2            | 2        | 2        | Make it easier for people who have w                                                                                difficulties working with smartphones
| Outdated design                      | 1            | 1        | 1        | Updating the design to be more modern       |
| Limited customization                | 1            | 1        | 1        | Allow users to customize the interface      |



---
### - Cognitive Walkthrough

#### Method

We chose simple tasks and put ourselves in the user's shoes

#### Task Selection and Task Analysis

Register new vehicle
Register service
Set reminders


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Register new vehicle** | Open app                               |
|                             | Navigate to “... More”                 |
|                             | Choose the vehicles option             |
|                             | Click on "+"                           |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Register service**       | Open app                                |
|                               | Click on "+"                            |
|                               | Choose "service"                        |
|                               | Complete the fields                     |


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **3. Set reminders**        | Open app                               |
|                             | Click on "+"                           |
|                             | Choose "reminder"                      |
|                             | Complete the fields                    |


#### Results

Task: Register new vehicle

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Navigate to “... More”   | No                                         |       | Yes                                                                                |       | Yes                       | As add a vehicle is important it should have a better option             |     |
| 2      | Choose the vehicles option   | Yes                                         |       | Yes                                                                                  |       | Yes                      |               |     |
| 3      | Click on "+"   | Yes                                         |       | Yes                                                                                  |       | Yes                       |               |     |
|

Task: Register service

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on "+"   | Yes                                         |       | Yes                                                                                |       | Yes                       |              |     |
| 2      | Choose "service"   | Yes                                         |       | Yes                                                                                  |       | Yes                      |               |     |
| 3      | Complete the fields   | Yes                                         |       | Yes                                                                                  |       | Yes                       |               |     |
|

Task: Register service

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on "+"   | Yes                                         |       | Yes                                                                                |       | Yes                       |             |     |
| 2      | Choose "reminder"   | Yes                                         |       | Yes                                                                                  |       | Yes                      |               |     |
| 3      | Complete the fields   | Yes                                         |       | Yes                                                                                  |       | Yes                       |               |     |
|

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

Drivvo's analysis revealed strengths and weaknesses that can inform the design of a competitive solution. Below are the main insights:

Despite the many features, the visual design is functional but seems outdated, It offers few options for customizing the interface, The interface can be confusing for less experienced users, Lack of visual confirmations after actions.
It could definitely be improved in terms of visuals and especially in terms of functionality (avoiding so many pop-ups and the subscription screen problem).
Danger of being overtaken by more modern applications and can have difficulty in retaining users due to limited usability.

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

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
