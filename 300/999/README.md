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

- A **role** is an abstract characterization of the behavior of a social actor within some specialized context or domain of endeavor 
- A **task** species a particular way of attaining a goal 
- A **capability** represents the ability of an actor to dene, choose, and execute a plan for the fulfillment of a goal, given certain world conditions and in the presence of a specific event 
- A **hard-goal** is a condition or state of affairs in the world that the stakeholders would like to achieve 
- A **soft-goal** is a condition or state of affairs in the world that the actor would like to achieve. But unlike a hard-goal, there are no clear-cut criteria for whether the condition is achieved, and it is up to the developer to judge whether a particular state of affairs in fact achieves sufficiently the stated soft-goal

...

## 400 - Business Value

...

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

...

## 700 - Problem Statement

...

## 800 - Possible Solution Directions

...

## 900 - High Level Solution

...

## 1000 - In Scope

- Something in scope
- Something else in scope

## 1100 - Out of Scope

- Something out of scope
- Something else out of scope

## 1200 - Definition of Ready (DoR)

...

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

## 1400 - Next Steps

Explanation of what are the next steps for this story.

## 1500 - Additional Information

| | |
| --- | --- |
| Dependencies | A team or a person, or else ... |
| Key Stakeholders | A team or a person, or else ... |
| Risks and Mitigations | **Risks**: ... <br/> **Mitigations**: ... |
| Include in Sprint Review | Yes/No |
| Demo-able | Yes/No |
| Additional Links | [Provide extra information or links here] |