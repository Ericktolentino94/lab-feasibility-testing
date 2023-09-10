# Feasibility Testing

## Getting Started

1. Fork and clone this repository.

1. Answer the questions below by editing this readme. Leave the questions and prompts, and answer in between them. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

1. Where applicable, add screenshots, photos, and links.

## Instructions

You will check the feasibility of two app ideas and determine a better option for a 2-day hack-a-thon project.

The hack-a-thon starts on a Friday. You spend 2 hours meeting your group, coming up with ideas, and planning.

The expectation is for everyone to code from 9am to 9pm Saturday and from 9am to 6pm on Sunday, with presentations from 6pm to 9pm on Sunday.

## Idea One: Save the change

Concept: Saving money is challenging, but what if you could do it in small ways daily?

A user will round up the amount spent for every purchase made and put the change into a savings account. For now, the user must manually enter the amounts in the app. But eventually, connecting to banks and credit cards to automate the process would be the next step.

- What technologies are needed?

> React
> React redux


- Would you have to learn a new technology?

> React Redux

- What would MVP look like (use user stories)

> This would be a mobile app that a user signs into; he is then allowed to connect his personal bank information in order to give the app the access to withdrawl the difference from the cost to the savings account. Here the user will be able to track the savings account growth as he / she continues spending their money on a daily basis. 

- What are the app milestones

> The goal is to get the user to save additional money by creating a new savings account that would store the users remaining cents after their purchases is rounded up to the nearest dollar. 

- What other things need to be considered about this app?

> Security; we dont want our users bank data or their savings account that they have been building to be be hacked or stolen. 
> Functionality; we want the experience very simple and easy for the user, so they can easily see graphs, and pictures that display the financial information they need.

- Is this app idea feasible for a hack-a-thon?

> Yes, it would be very difficult to build out the actual complete functioning app because we would technically be building a bank, but the structure of the front-end and the basic foundation for the back end could be built for the hackaton.

- Can you adapt this idea to make it more feasible for the timeline?

> It is feasible for us to make some type of saving tracker for the user to be able to visually see their savings and be rounding their cost to the exact amount that they should put into their savings on a daily basis.

- How could you encourage users to interact with this app regularly?

> The app would send you daily notification of progress, alerts after purchases, and reminds you where you are after you made your purchases.

- How could people misuse this application?

> Other people can track your spending habbits and possibly location hack if someone is able to get into the purchasing data.

- Are there any safety issues with this application?

> Yes someone could find a way to hack into users personal banking passwords and logins and steal their idetification to commit crime. 

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> React
> React redux
> Postgres SQL
> TQL

- Would you have to learn a new technology?

> React Redux
> Postgres SQL


- What would MVP look like (use user stories)

> Users will be able to log on to the app and create an annonymous account where they will be able to communicate with other humans after they select an option for a topic and a mood. The user will rate their discussions after they are done and give the users a 1-5 rating based on how good the other user was. 

- What are the app milestones

> This will help people by allowing them a space to speak their thoughts and communicate with someone who is on their mood in order to get other opinions or share your ideas and see what people think. 

- What other things need to be considered about this app

> We must find a AI to track the conversations and make sure they dont get out of hand. If the user makes comments about suicide, commiting a crime, or anything like this they will get a warning and the AI would see if police would need to intervien

- Is this app idea feasible for a hack-a-thon?

> Yes we believe that this is a feasible project for a hack-a-thon; it would be a messaging app using CRUD to be able to post messages between users after they complete their conversation they would be given a form to fill with a rating of 1-5 and a comment that he/she has about the user. 

- Can you adapt this idea to make it more feasible for the timeline?

> This is probably a feasible idea for a project for the hackaton, it is less complicated due to the banking situation and connecting the users with the banking stamps. We would have to create a server to store the data and display it for the users when they are communicating.

- How could you encourage users to interact with this app regularly?

> The app can give notifications about popular trending topics people are currently speaking about

- How could people misuse this application?

> The annominity factor could leave people vulnerable to people who will want to hurt them with racially motivated comments or negative comments. 

- Are there any safety issues with this application?

> Yes if the users location or identity is hacked this could lead to someone being targeted in real life and possibly being hurt financially or physically. 
