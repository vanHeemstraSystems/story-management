# 999 - Story Management

## 100 - Description

For example:

**As a** [Role: e.g., Product Owner]<br/>
**I want to** [Want: e.g., set and design a framework and guidelines for the copy pasting policy]<br/>
**in order to** [Need: e.g., protect the company source code].

## 200 - ...


## 300 - Acceptance Criteria

Source: https://tech-stack.com/blog/how-to-craft-clear-acceptance-criteria/

Acceptance Criteria (AC) can be **scenarios** or **rules**. 

Both types are key to making sure that features are actually useful to users.

- Acceptance criteria should be **specific**, **measurable**, and **written in simple language**.

- Ensure that acceptance criteria are **comprehensive** and **self-explanatory**, providing enough context for anyone unfamiliar with the project to understand the requirements.

- The solution is to write criteria in a way that is **accessible** to all stakeholders, focusing on **outcomes** rather than technical specifications. This encourages broader participation and ensures that the criteria reflect the needs and perspectives of all parties involved.

- Involve representatives from all relevant groups in the criteria development process. This collaborative approach fosters **mutual understanding**, **aligns expectations**, and **leverages diverse insights** to refine and improve the acceptance criteria.

### 100 - Acceptance Criteria as Scenarios

AC scenarios help to ensure that **features work as intended** in real-world settings.

This type of approach is useful for complex features that will be used in multiple ways. This type of AC list helps to ensure that the final product will help users in a variety of scenarios. For example, if the development team is working on a new search feature, the scenario-oriented AC might specify that the feature must be able to handle misspellings and return results from different parts of the website. In addition, it can also help to identify potential problems during development, allowing team members to make changes before the product is released. The common formula that represents the AC scenario is as follows:

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

| 01 | At the top of the page, there is a search field. |
| 02 | Clicking "Search" initiates the search process. |
| 03 | A placeholder with grey-colored text appears in the field: "Where are you off to?" |
| 04 | The placeholder disappears once the user starts typing. |
| 05 | When a user types in a city, hotel name, street, or all three, a search is performed. |
| 06 | There are four languages available for search: English, French, German, and Ukrainian. |
| 07 | There is a limit of 200 symbols per user. |
| 08 | Special characters cannot be searhced for. Display the warning message: "Search input cannot contain special symbols." if a special symbol is typed. |

## 400 - In Scope

- Something in scope
- Something else in scope

## ??? - Out of Scope

- Something out of scope
- Something else out of scope

## ??? - Possible Solution Directions

## ??? - ...