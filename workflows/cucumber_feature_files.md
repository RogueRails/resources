# Cucumber Feature File Workflow

2. Create a cucumber feature file ` ./features/{theme}/{story}.feature => ./features/authentication/login.feature `
3. Duplicate the feature template below into the new feature file
4. In the "Feature" section, fill out "GOAL", "ROLE" and "ACTION" with the details from the user story
5. Add a new "Scenario" section for the first "acceptance criteria" and give it a descriptive title
6. Create the steps needed to meet the acceptance criteria

#### Feature Template

````
Feature:
  In order to [ GOAL ]
  As a [ STAKEHOLDER ]
  I want to [ BEHAVIOR ]

Background:
  ...

Scenario: [ TITLE ]
  ...
````