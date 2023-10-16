# Requirements && More Info

### Vision

1. What is the vision of this product?

* The vision of QuestForge is to provide users with an on-demand, simple escape from reality with minimal work on the users end.
* We want the user to be able to feel captivated by a story on a whim, while giving them the opportunity to interact with the story how they choose.


2. What paint point does this project solve?

* This solves a problem for people looking for a dnd "fix" without having to either:
*  A) Engage in the lengthy, rule-saturated, time-consuming aspects of tabletop D&D.
   B) Spend money in order to purchase access to a video game that may or may not engage the player outside of
   moving a character model around in order to give them a fantasy-realm filled experience.

3. Why should we care about your product?

* Because our product offers users an enagaging story, generated on-demand without the need for external resources such as dice, minature figurines, maps, tables, or books in order to get started and experience a great story.

## SCOPE

#### In

* The application will provide text-based "D&D" scenarios for users to engage with
* The application will give users the option to choose how their story plays out, dynamically.
* Users will be able to interact with the console and "choose" their adventures.
* Each scenario will have potential "outlier" scenarios, resulting in potentially fatal events, or lucrative bonuses, based on the "roll of the dice".

#### Out

* This application will never become a fully 3D rendered video game with heavy graphical assets
* This application will not allow mulitplayer functionality in it's current state (Back-end only).

# MVP Product

1. What will your MVP functionality be?

* Utilizing the terminal, user will be able to choose from a host of choices given to them via prompt(s) from OpenAI
* in rounds, until either the user ends the game, or the game is ended for them.

2. What are your stretch goals?

* Using AWS S3 Buckets as a method for saving user's stories and "campaigns".
* Feat and Stat checks included in dialogue options
* Determing eligibility between ending a "Session" vs ending the "Campaign"
* User account creation and authentication, with the availability to edit campaigns, check inventory, and review previous dialogue choices.
* Data persistence for user prompts (See last note)
* Add a "proof of life" display in HTML/CSS so the user can visibly see their choices played out.

* We will be aiming for stretches 1 and 2 listed above if time and resources allow.

### Functional Requirements

1. A user can engage with OpenAI in order to choose their next generated dialogue.
2. A user can play the game as many times as they want

### Data Flow

[UML](https://projects.invisionapp.com/freehand/document/Og97QVUVy)

### Non-Functional Requirements

1. Testability - Functional tests: - Test each function to ensure behavior is expected such as narrative progression, user choices.
                                   - Unit tests: Testing all components, Lambda functions, and schema models to ensure they work as intended.

2. Scalability
  - DynamoDB for scaling and saving user input for later use if stretch goals are implemented

3. Maintainability
  - Following DRY principle, prioritizing use of singletons (1 function, 1 purpose)
  - Version control implemenation, (V0.1.4.6)

### Database Schema

[UML](https://projects.invisionapp.com/freehand/document/Og97QVUVy)

 
