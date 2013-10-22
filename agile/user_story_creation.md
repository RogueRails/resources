## User Stories

#### GOAL
  Why are we doing it? This can be tied to the value of the story.  Try to go "5 Why's Deep."

#### STAKEHOLDER
  Who is take the action? Who's perspective are we viewing the story from?

  This changes the GOAL/WHY of the story.  A registered user and an admin user both need a login form, but for potentially different reasons.

#### BEHAVIOR 
  What is the stakeholder doing? What needs to take place to fulfill the goal. 

#### FORMAT

Story formats may differ, but always include the same elements.  Put the goal first, because the value of the story caries the most weight.

```
  In order to ... (GOAL)
  As a ... (STAKEHOLDER)
  I want to .... (BEHAVIOR)
```

#### QUALITY STORIES (INVEST)

* **I**NDEPENDENT
  ... of any other story.
* **N**EGOTIABLE
  ... so it's not set in stone.
* **V**ALUABLE
  ... to the users or business.
* **E**STIMABLE
  ... so it can be measured.
* **S**MALL
  ... enought to fit within a single iteration.
* **T**ESTABLE
  ... so it can be diffinitely validated.

#### ACCEPTANCE CRITERIA

The details of a story can be documented as "acceptance criteria" in a "gherkin" model.

#### GHERKIN MODEL

* GIVEN  _(Background)_
* WHEN  _(Event)_
* THEN  _(Expectation)_

#### Declarative (Informative)

Expresses the intent, not the solution.

```
  Given I am on my profile page
  When I update my profile
  Then I will see the changes
```

#### Imperative (Communicative)

Expresses the solution, not the intent.

```
  Given I am on the page '/my_profile'
  When I fill in "Name" with "John Doe"
  And I fill in "Email" with "john@example.com"
  And I click "Save"
  Then I will see "Profile Updated!"
  And I will see "John Doe"
  And I will see "john@example.com"
```