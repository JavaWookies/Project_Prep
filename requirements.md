# Software Requirements

## Vision

- What is the vision of this product?

> The vision of this product is to create a user-friendly mobile application that replicates the experience of a traditional tarot card reading.

- What pain point does this project solve?

> This project aims to solve the pain point of accessibility to tarot card readings, as traditional readings require physical cards and an experienced reader. The app aims to make tarot readings more accessible to a wider audience.

- Why should we care about your product?

> Users should care about this product because it offers a convenient way to receive daily tarot card readings and access interpretations, enhancing their spiritual and self-reflective experiences.

## Scope

- In
  - The app will allow users to sign in and create basic user profiles.
  - Users will receive one free tarot card reading per day after signing in.
  - Additional tarot card readings can be unlocked by watching reward ad videos.
  - Users can shuffle and draw three tarot cards.
  - The app will showcase the three drawn cards with associated interpretations.
  - An index section will provide users with pre-stored meanings and explanations for all possible tarot cards.

- Out
  - The app will not offer personal consultations with live tarot card readers.
  - It will not provide additional services unrelated to tarot card readings.
  - The application will not offer different modes of getting tarot readings outside of a 3 card spread.


## MVP and Stretch

Minimum Viable Product (MVP):

The MVP functionality will include user registration, one free daily tarot card reading after signing in, the ability to draw and display three tarot cards with interpretations, and access to pre-stored card meanings.
Stretch Goals:

The stretch goals include allowing users to revisit past readings and the potential integration of AI to generate fresh interpretations of card groupings.

## Functional Requirements

- User registration and profile management.
- Daily free tarot card reading functionality.
- Drawing and displaying three tarot cards with interpretations.
- Integration with reward ad videos to unlock additional readings.
- Access to an index section with pre-stored tarot card meanings.

## Data Flow

- User registration and login.
- User selects to draw tarot cards.
- App shuffles and draws three cards.
- App displays the drawn cards along with their interpretations.
- Users can revisit past readings if the stretch goal is implemented.
- Users can navigate to an index with all of the cards and their meanings

## Non Functional Requirements

1. Usability:

The app should have an intuitive and user-friendly interface, making it easy for users to navigate and understand the tarot card readings and interpretations. Usability testing will be conducted to ensure a positive user experience.

2. Security:

User data, including registration information and past readings, should be securely stored and protected. Authentication mechanisms should be in place to ensure user privacy and data security. We plan to utilize Cognito to achieve our security goals.