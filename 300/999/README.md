# 999 - Story Management

## 100 - Description

- Who
- What
- Why

For example:

**As a** [Who/Role: e.g., Product Owner]<br/>
**I want to** [What/Want: e.g., set and design a framework and guidelines for the copy pasting policy]<br/>
**in order to** [Why/Need: e.g., protect the company source code].

## 200 - Rationale

For example:

**We believe** providing a well-prepared environment for the FooBar application<br/>
**will** result in reducing deployment issues and post-deployment performance concerns<br/>
**by** at least 50%<br/>
**by** the end of Q4 2024.

## 300 - Goal

Source: [Using a Goal-Driven Approach to Structure User Story Sets](http://www.staff.science.uu.nl/~dalpi001/symposium-nl-re/wautelet.pdf)

![Image](https://github.com/user-attachments/assets/a5c98b42-8a91-4e6f-909e-cb0fdad9c486)

- A **role** is an abstract characterization of the behavior of a social actor within some specialized context or domain of endeavor. 
- A **task** species a particular way of attaining a goal.
- A **capability** represents the ability of an actor to dene, choose, and execute a plan for the fulfillment of a goal, given certain world conditions and in the presence of a specific event.
- A **hard-goal** is a condition or state of affairs in the world that the stakeholders would like to achieve.
- A **soft-goal** is a condition or state of affairs in the world that the actor would like to achieve. But unlike a hard-goal, there are no clear-cut criteria for whether the condition is achieved, and it is up to the developer to judge whether a particular state of affairs in fact achieves sufficiently the stated soft-goal.

![Image](https://github.com/user-attachments/assets/adac1ad5-577a-435f-9992-e703990b2cfb)

Source: [The Infinite Product Manager](https://medium.com/@skibinski.james/the-infinite-product-manager-a383d8ea23c3)

In a product team, the infinite-minded product manager will work with the finite-minded development team to advance toward the infinite, one finite step at a time. The team may not succeed in all their finite goals, but they will learn valuable lessons that will still take them closer to the just cause.

How do I write a **SMART** goal plan?

- **S**pecific: Start by asking exactly what you need to accomplish. This will make your goal specific.
- **M**easurable: Quantify your goals. Measurable goals are easier to track, so build in milestones.
- **A**chievable: Your goal should be achievable. ...
- **R**ealistic: Think why you're setting this goal. ...
- **T**imely: Know exactly when you'll have reached your goal.

## 400 - Business Value

Source: [What is Business Value: Definition, Components, and Strategies](https://www.invensislearning.com/blog/what-is-business-value/)

### 100 - How to Measure Business Value?

The subjective and dynamic nature of business value may land you on the question that whether it can be measured or not and the answer is yes. The following factors can help you determine it for a particular organization:

- Revenue
- Profitability
- Market share
- Brand recognition
- Customer loyalty
- Customer retention
- Share of wallet
- Cross-selling ratio
- Campaign response rate
- Customer satisfaction

### 200 - Must-Have Values

For a project to be able to deliver business value, it should ensure the following conditions:

- It should have a clear objective.
- The project should be aligned with the business goals.
- It should have required stakeholder support.

## 500 - Acceptance Criteria

Source: https://tech-stack.com/blog/how-to-craft-clear-acceptance-criteria/

Acceptance Criteria (AC) can be **scenarios** or **rules**. 

Both types are key to making sure that features are actually useful to users.

- Acceptance criteria should be **specific**, **measurable**, and **written in simple language**.

- Ensure that acceptance criteria are **comprehensive** and **self-explanatory**, providing enough context for anyone unfamiliar with the project to understand the requirements.

- The solution is to write criteria in a way that is **accessible** to all stakeholders, focusing on **outcomes** rather than technical specifications. This encourages broader participation and ensures that the criteria reflect the needs and perspectives of all parties involved.

- Involve representatives from all relevant groups in the criteria development process. This collaborative approach fosters **mutual understanding**, **aligns expectations**, and **leverages diverse insights** to refine and improve the acceptance criteria.

### 100 - Acceptance Criteria as Scenarios

AC scenarios help to ensure that **features work as intended** in real-world settings.

This type of approach is useful for complex features that will be used in multiple ways. This type of AC list helps to ensure that the final product will help users in a variety of scenarios. For example, if the development team is working on a new search feature, the scenario-oriented AC might specify that the feature must be able to handle misspellings and return results from different parts of the website. In addition, it can also help to identify potential problems during development, allowing team members to make changes before the product is released. The common formula from Behavior-Driven Development (BDD) that represents the AC scenario is as follows:

- **Given** {pre-condition}
- **When** {action}
- **Then** {results}

Using this approach, testers start by writing test cases for each feature. They then use these test cases to drive the development process, ensuring that each feature meets the required standards. This approach has a plethora of benefits, including improved coverage and reduced development time.

Example:

> **As** a website customer **I would like** to get an additional offer during the buying process **so that** I can find a worthwhile and satisfying offer that I actually need for my mobile device.

1a. Ignoring and closing the special offered products

| | |
| --- | --- |
| Given that | I'm a website user |
| When       | I do not want to buy the special product |
| Then       | I can close this window and continue my online shopping |

1b. Adding the offered product to the shopping cart

| | |
| --- | --- |
| Given that | I'm a website user |
| When       | I selected the offered product |
| Then       | I add it to the shopping cart by clicking on 'Add to Cart' |

### 200 - Acceptance Criteria as Rules

In contrast, rule-oriented acceptance criteria help to ensure that **features meet minimum standards for performance and reliability**.

Some backlog items need another approach to writing AC rather than the Given/When/Then for objective reasons.

- System-level requirements (such as beta testing and alpha releases with volatile data sets) wouldn’t benefit from Given/When/Then structures;
- Given/When/Then cannot describe UX specifics that can be critically important;
- There is simply no need to cover details about test scenarios to your customers.

AC rules, unlike previous ones, aim to specify conditions to be met in order for the feature to be considered complete. For the search feature example, AC rules might determine that it must be able to handle at least 10 simultaneous searches and return results within 2 seconds. 

Example:

> **As** a user **I would like** to use a search field to type a city, name, or street **so that** I can find matching hotel options.

| | |
| --- | --- |
| 01 | At the top of the page, there is a search field. |
| 02 | Clicking "Search" initiates the search process. |
| 03 | A placeholder with grey-colored text appears in the field: "Where are you off to?" |
| 04 | The placeholder disappears once the user starts typing. |
| 05 | When a user types in a city, hotel name, street, or all three, a search is performed. |
| 06 | There are four languages available for search: English, French, German, and Ukrainian. |
| 07 | There is a limit of 200 symbols per user. |
| 08 | Special characters cannot be searched for. Display the warning message: "Search input cannot contain special symbols." if a special symbol is typed. |

## 600 - User Interaction

Source: [How To Design User Scenarios](https://www.justinmind.com/blog/how-to-design-user-scenarios/)

### Step 1: Identify Your Users

### Step 2: Define The Context

### Step 3: Focus On User Goals

### Step 4: Map Out The Steps

## 700 - Problem Statement

Source: [How To Craft A Compelling Problem Statement](https://www.antler.co/academy/how-to-write-a-problem-statement)

A good problem statement is beautiful in its simplicity. It should be a one or two sentence statement that clearly articulates a problem that you — and your business — want to address. Its purpose is to inspire creative thinking but (and this is critical), it is not there to describe the solution.

### 100 - The seven questions behind every good problem statement

- 1) What is the problem that needs to be solved? 

For example; *People can’t work in their offices for at least a few months, and possibly indefinitely.*

- 2) Why is that a problem? 

For example; *If people can’t work, a business isn’t likely to survive for long.*

- 3) Where is the problem observed? 

For example; *The office location, or, more accurately, the absence of a previously existing location to do work.*

- 4) Who is impacted? 

For example; *Everyone that works in the office, and, by extension, any customer that interacted with those people.*

- 5) When was the problem first observed? 

For example; *The day the lockdowns were announced.*

- 6) How is the problem observed? 

For example; *Are people in the office? If not, the problem has been observed.*

- 7) How often is the problem observed? 

For example; *Massive scale, with just about every business being affected by lockdowns and office closures, globally.*

Once you have answers to these seven questions, then you’ll be able to consolidate them down to arrive at the essence of the problem — your problem statement. With that drafted, ask yourself if it contains the following information: 

Does it identify a **gap (pain point)**, explain **when**, **where** and **what** that gap is speaking to, **quantify** the gap in terms of cost, size, quality, and so on, and explain **why** this gap needs to be filled?

If it has all this information, congratulations — you’ve got the material that you need to clearly draft up your problem statement!

## 800 - Possible Solution Directions

Source: [40 problem-solving techniques and processes](https://www.sessionlab.com/blog/problem-solving-techniques/)

## 900 - High Level Solution

Source: [Solution design document](https://academy.pega.com/topic/solution-design-document/v2)

The solution design document (SDD) defines the overall goals and objectives of the solution while also capturing the automation processes that are necessary to complete the solution. Developers receive the SDD, divide the work, and then focus on specific portions of the solution.

As a best practice, read the SDD entirely, even if you are only developing one portion of the total solution. By following the document, you can ensure a more seamless integration of the supporting processes or applications in your project.

The SDD has two main sections: the overview and the storyboard.

### 100 - Overview

The overview of the SDD provides a high-level description of the solution and projects. The description contains the business driver and success metrics that the team must meet once the development and deployment of the solution are complete. This information gives insight into the reasoning behind the solution and its need and priority.

### 200 - Storyboard

The storyboard is a visual representation of the overall look and feel of the completed solution. The storyboard has separate referenceable, numbered processes that can help you define the flow and functionality of the solution.

The storyboard has three feature areas: UI Feature, Data Feature, and the Rules or Processes Feature. Depending on the needs of your solution, there might be more or fewer feature options. You configure the information in each feature area to:

Describe the workflow and specific tasks of the solution by referenced storyboard items.
Provide specific information steps to automate, including specific requirements related to the storyboard phase (such as ASO for login, testing criteria, and assumptions).
The storyboard also maps the solution through the different processes that you define. This storyboard map outlines the overall flow of the solution and the interaction points between projects and applications, as shown in the following figure:

![Image](https://github.com/user-attachments/assets/41cf9b5f-f134-4735-b57c-746b28ed9800)

## 1000 - Non-Functional Requirements

Source: [Non-functional Requirements: What They Do, Examples, and Best Practices](https://www.perforce.com/blog/alm/what-are-non-functional-requirements-examples)

Non-functional requirements are the criteria that define how a system should behave, rather than what it is supposed to do. Unlike functional requirements, which describe specific system functions, non-functional requirements define aspects like performance, security, usability, reliability, and scalability. 

![Image](https://github.com/user-attachments/assets/a361e034-d90c-4754-b02e-2fb52f1834a3)

- **Security** — Does your product store or transmit sensitive information? Does your IT department require adherence to specific standards? What security best practices are used in your industry?

- **Capacity** — What are your system’s storage requirements, today and in the future? How will your system scale up for increasing data storage volume demands?

- **Compatibility** — What are the minimum hardware requirements? What operating systems and their versions must be supported?

- **Reliability and Availability** — What is the critical failure time under normal usage? Does a user need access to this all hours of every day?

- **Maintainability and Manageability** — How much time does it take to fix components, and how easily can an administrator manage the system? Under this umbrella, you could also define Recoverability and Serviceability.

- **Scalability** – The Black Friday test. What are the highest workloads under which the system will still perform as expected?

- **Usability** — How easy is it to use the product? What defines the experience of using the product?

- **Performance** — How quickly does the system respond to users’ actions, or how long does a user wait for a specific operation to happen?

- **Regulatory** — Are there specific requirements you need to satisfy for compliance in your industry?

- **Environmental** — What types of environments will the system be expected to perform within?

## 1100 - Monitoring

Source: [Writing user stories to drive observability usage](https://medium.com/contino-engineering/writing-user-stories-to-drive-observability-usage-a86b885019)

...

## 1200 - Dependencies

Source: [5 Strategies to Manage & REMOVE Dependencies in Agile Scrum](https://www.youtube.com/watch?v=QzyAG1f_Obs)

Examples of dependencies:

- Organizational Structure: For example, the development team depends on the testing team and vice versa if these are separate teams.
- Non-Agile Teams: Teams that work in waterfall don't work in Sprints. Dependency on such a team is blocking if they do not deliver within the Sprint.
- Non-Cross Functional Teams: People lack skills, knowledge, and or tools like database access.

7 Strategies to manage and remove dependencies:

1) Internal Dependencies: Automation: Automate everything.
2) Internal Dependencies: Standardization: Standardize the Process. 
3) External Dependencies: Ad-Hoc Meetings: Set up a quick call with other teams if information is missing.
4) External Dependencies: Refine Your Definition of Ready: Ensure the dependencies on other teams have been completed before pulling the story into the Sprint.
5) External Dependencies: Scrum of Scrums Meeting: To synchronize the work between teams, removing blockers.
6) External Dependencies: Pairing: Pairing between people of different teams.
7) External Dependencies: Remove the Dependency from the Scope of the Sprint: Fake or mock the dependency.

## 1300 - In Scope

- Something in scope
- Something else in scope

## 1400 - Out of Scope

- Something out of scope
- Something else out of scope

## 1500 - Definition of Ready (DoR)

Source: [Definition of Ready: What It Is and Why Its Dangerous](https://www.mountaingoatsoftware.com/blog/the-dangers-of-a-definition-of-ready)

What does **definition of ready** mean? It means that the user story or product backlog item meets a set of team-established criteria as to whether the story is ready for a sprint. These criteria are typically things like small enough to fit in a sprint, has acceptance criteria, and so on.

You can think of a definition of ready as a big, burly bouncer standing at the door of the iteration. Just as a bouncer at a nightclub only lets certain people in—the young, the hip, the stylishly dressed—our definition-of-ready bouncer only allows certain user stories to enter the iteration.

**Warning**: When a definition of ready includes a rule that something must be done before the next thing can start, it moves the team dangerously close to stage-gate process. And that will hamper the team’s ability to be agile. A stage-gate approach is, after all, another way of describing a waterfall process.

## 1300 - Definition of Done (DoD)

Source: https://theproductmanager.com/general/how-to-write-excellent-acceptance-criteria-with-examples/

The **definition of done** represents completeness in terms of the team’s development processes:

e.g., 

- We have written the unit tests and all of them pass.
- We do not have any showstopper bugs left.
- We have communicated the changes with the product documentation team.

While the **acceptance criteria** are representing functional requirements (how the feature should look and behave).

e.g.,

- When clicking on the "edit" button, a modal should open where the user can edit the name. {screenshot_with_modal_design}
- When editing the name and clicking on "Save", the modal should close, the name should change, and the user should see a success message about it.

This means that the **definition of done** will remain the same for all the stories that the team is implementing unless they decide to make changes to it during the retrospectives. The **acceptance criteria**, on the other hand, are unique for each story as they are explaining the way that feature should work.

## 1600 - Next Steps

Explanation of what are the next steps for this story.

## 1700 - Additional Information

| | |
| --- | --- |
| Dependencies | A team or a person, or else ... |
| Key Stakeholders | A team or a person, or else ... |
| Risks and Mitigations | **Risks**: ... <br/> **Mitigations**: ... |
| Include in Sprint Review | Yes/No |
| Demo-able | Yes/No |
| Additional Links | [Provide extra information or links here] |
