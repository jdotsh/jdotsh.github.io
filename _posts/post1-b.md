---
title: What I do when a student asks for help
date: 2020-03-01
tags:
  - Learn
  - CNNs
author: jdotsh
---

-

For the last three months, I’ve been working at x as a programming coach.

I spend part of my time working with students who have asked me for help. My goal is for the student to learn to learn. To improve my ability to help with this, I wrote down a process that I follow. The process has changed as I’ve learnt more. Here’s the latest version:
Process

    Map the student’s request for help to one of the underlying problems:
        No clear problem explanation
        Want a concrete piece of information
        Not clear on how to implement a piece of functionality
        Not clear about how to implement a piece of functionality, and neither am I
        Want my opinion of their idea
        Want an intro to a topic
        A bug they should be able to solve on their own
        A bug they don’t have the background knowledge to fix on their own
        A bug for which I can’t predict the likely cause
        A bug that will take them a long time to fix
    Apply one of the suggested solutions:
        Suggest the escalation process
        Help the student clarify their explanation of their problem
        Suggest they Google it
        Suggest the debugging process
        Suggest reading material
        Identify and train a developer skill
        Identify and train a developer behaviour
        Solve their problem
    Ask the student for feedback on my help.

Problems underlying a request for help
The student doesn’t have a clear problem explanation

    Maybe suggest they follow the escalation process.

    Help the student clarify their explanation of their problem.

The student wants a concrete piece of information

    Maybe suggest they follow the escalation process.

    Maybe suggest they Google their question.

The student doesn’t know how to implement a piece of functionality

    Maybe suggest they follow the escalation process.

    Maybe identify and train a developer skill that will help them implement the functionality.

    Maybe suggest reading material on a topic that will solve their problem.

The student doesn’t know how to implement a piece of functionality, and neither do I

    Maybe suggest they follow the escalation process.

    Identify and train a developer skill.

The student wants my opinion on their idea

    Maybe suggest they follow the escalation process.

    Maybe identify and train a developer skill like fast prototyping or diagramming.

    Maybe identify and train a developer behaviour like reflection.

The student wants an intro to a topic

    Maybe suggest they follow the escalation process.

    Maybe suggest reading material.

The student has a bug they should be able to solve on their own

    Maybe suggest they follow the debugging process.

The student has a bug they don’t have the background knowledge to fix on their own

    Maybe suggest they follow the escalation process.

    Suggest reading material that will provide the background knowledge.

The student has a bug for which I can’t predict the likely cause

    Run through a partly closed debugging process with the student.

The student has a bug that will take them a long time to fix

    Solve the student’s problem. Make the process as open as possible.

Solutions
Suggest the escalation process

    Make the student feel held first. Then suggest the escalation process. (This link isn’t publicly accessible, I’m afraid. It points to an internal Makers Academy document. The document describes a process that helps the student help themselves. It suggests: gathering words to describe the problem, Googling, talking to a pair programming partner, and asking on the student Slack channel.)

Help the student clarify their explanation of their problem

    Maybe ask them questions to clarify their request for help.

    Maybe use 5 whys.

Suggest they Google it

    Make the student feel held first. Then suggest they Google their problem.

Suggest the debugging process

    Tighten the loop. This means following the flow of execution to find the line of code that’s causing the bug.

    Get visibility (aka p everywhere). This means using stdout or a debugger to see the current state of the program.

Suggest reading material

    Suggest a blog post. Or suggest a pill [an internal document that gives a condensed introduction to a topic].

Identify and train a developer skill

For example: diagramming, delegating behaviour, breaking classes into single responsibilities, debugging asynchronous code, 5 whys, falsifying assumptions, following the flow.

    I can identify a skill that’s lacking by looking at how the student makes their request, how they’ve tried to find the problem and what solutions they’ve tried.

    To set the student’s expectations, name the skill I’m going to help them train. Suggest they employ the skill to solve the problem. Name the skill at the end of the session to help them remember to use it.

    Figure out how open the process should be. Maybe the first time that I suggest diagramming, I’ll need to walk the student through it. But, in the future, I should be able to give less detailed support.

Identify and train a developer behaviour

    For example, one of the XP values.

Solve their problem

    If the student has a really tricky problem that will delay them for a long time, it’s often better to just solve it for them so they can get going again. Whilst keeping the process efficient, try and make it as open as possible. Try and explain how I know to try the things I’m trying.

Definitions
Feeling held

    Reassure the student that I’ve heard and understood their request. Reassure the student that I care about them and their request. This may involve explaining why I’m not giving them the answer.

Open process (vs closed)

    An open process is one that helps the student to learn more than a closed process. For example, letting the student type, rather than typing myself, or saying “can you use the filter function for that?” rather than “type dot f i l t e r …”.

