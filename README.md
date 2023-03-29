# Token
A non-judgemental habit-tracking for tracking every day routines

# Goals

Habit-changing goals broadly fall into three categories:

1. I want to do more of this thing

2. I want to do less of this thing

But to accomplish these goals, or even be able to set them, you must know how often you do this thing right now.

So there is a need to measure how often we do this thing now to know whether we are achieving goals,
or perhaps to be able to set the goal at all.

# Approach

So the primary fundamental goal of the app is to easily record when we do the thing.
The main obstacle to recording is that the user forgets.
It must be easy to integrate the recording process to the routine.

Most people these days, they have the phone with them almost always.
The phone can be used to record the event.
The goal being to make it as easy to possible to record.

# Concept

User configures a new "Token" which represents an action to be tracked.
Basic Token simply adds an entry to a database when the user activates the Token.
Entry would at least include timestamp, could include other metadata, customizable.
User activates the token whenever they perform the action.
An app with a widget capability.
A widget on the home screen can be tapped to activate the token.
The user just needs to pull out their phone, unlock, and tap a button on one of their home pages.
More involved actions could be available in the app.
Data would be synced to allow access from other devices.
Data could be visualized.
Tokens can be customized to warn the user or remind the user.

# Development

- Define models for Token data
- Define REST API for recording token data
- iPhone app that can access REST API
- Widget that can trigger app actions
