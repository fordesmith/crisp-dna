# Using an Inception to kick off a project

Agile Inceptions are powerful and fast ways to get a team to internalize a vision. It’s a two-day investment that saves the company months of up-front planning and allows the teams to begin immediately deliver core product functionality.

## Overview
Over the last 10 years or so I’ve been involved with teams adopting the Agile Inception format kick off new projects. I’ve been fortunate to participate in these inception meetings with a couple teams from Pivotal, and I’d like to share my observations on their agenda and process.
The inception model is a kick-off strategy that is repeatable and well-vetted. At it’s core, the inception deals with how we scope. The session(s) relies on full participation by an engaged audience, and co-location is crucial as we swarm around note-cards on tables and walls.
This page is not a comprehensive documentation of the process, but rather a how-to for interested project leaders to get started spinning up our own inceptions. 
Starter for 10 - The 2-day schedule
Below is a sample schedule for a typical project that has had little formal planning until now. Some projects may not require a full 2 days if they are smaller in scope or have already undergone significant planning efforts. The schedule is a rough timetable (times based on an 8am-5pm day), and it is common to deviate from the exact times specified.
While it is strongly encouraged that every team member – developers, PMs, designers – be present for the entire inception, the use of laptops is frowned upon. (They have a way of distracting people!) In addition to lunch, there are breaks throughout each day – email checking, etc. should be reserved for those times so that all attendees are focused and engaged.

 **Day 1**
 8:15 – Office orientation & get coffee
 8:30 – Welcome: what’s an inception?
 8:45 – Introductions: who’s who?
 9:00 – High-level product concept & background
 9:15 – Break
 9:30 – Goals & Timeline
 10:00 – Risks
 10:45 – Break
 11:00 – User Roles
 11:45 – Lunch Break
 1:00 – Activities and Workflows
 2:15 – Break
 2:30 – Story Mapping
 3:45 – End of Day 1

 --------

 **DAY 2**
 8:15 – Get coffee & be seated8:30 – Summary of where we left off & what’s ahead
 8:45 – Story Mapping (cont.)
 9:30 – Break
 9:45 – Story Mapping (cont.)
 10:45 – Prioritization
 11:45 – Lunch Break
 1:15 – Risks (revisited)
 1:45 – Break
 2:00 – Next Steps
 2:15 – Retrospective
 3:15 – End of Day 2


#Description of Agenda Sections

Below are notes specific to the different parts of the agenda, as well as a few items that aren’t included in the default.
Introduction of People and Agenda
Start with a quick go-around of everyone’s name / role / department / etc.
Discuss the agenda items, pointing out when the breaks take place.
Remind participants to not use electronic devices (laptops, phones, etc.) in order to have everyone engaged with few distractions.
Create a space for terms (acronyms and vocabulary that may not be understood evenly among participants) and another for parking lot items (topics to be discussed later without interrupting the meeting’s flow). Large pieces of paper from an easel pad work well – stuck on a wall somewhere visible.
Ask if everyone is clear with the agenda and rules (ie. get buy-in).
High-level product concept
This is an opportunity for us to introduce the product design. Both UX and UI are covered.
This portion is led by the Product Manager(s) / PO(s), and previous experience with inceptions is helpful.
The design (UX/UI) can be broken out into two types: experience vs visual design. The experience design is important for discussions of goals & risks and should be the focus of this section. The visual design, while important, can usually be covered as we create activities and stories.
Goals
Goals get logged – typically on a large, tear-away (easel pad) paper that can stick to a wall for quick reference.
Goals fall into four categories (with examples):
business goals 
engineering efficiency
better handling of customer growth
paid version of the product
better position for us to ship features
product goals 
product readiness
SLA items (reliability, serviceability, availability, etc.)
no dropped / duplicated messages
engagement goals (for facilitator) 
train how to do inceptions
non-goals (things we explicitly do not want included in the scope) 
community / open source
fancy bells & whistles
It’s important to keep all goals SMART (specific, measurable, achievable, relevant & time-bound). Identifying goals by time (eg. month or quarter) or sequence is useful.
Risks
This agenda section follows the following five steps:
Hand out 3×5 cards to each participant. Based on the goals, each member should identify the risks they see, writing one risk per card.
The facilitator (and helpers) will collect these cards organize them into themed groups spread across the table.
Distribute three pieces of candy (or other tokens) to each participant. Everyone will use their three tokens to vote on the biggest themes (not individual risks) on the table, and they may give multiple votes to a single issue.
Facilitator will tally the results onto another large (easel pad) paper and post on the wall.
Facilitator leads discussion of mitigation strategies.
Actors and Activities
Call out roles (internal and external) and write one per 3×5 card. Ask for each actor what they can do in the system at a high level (activities).
Examples include:
internal developers
other internal teams (billing, operations, support, etc.)
customers (technical & non-technical), their agents & apps
3rd-party entities (eg. remote MTAs, spammers, etc.)
Story Mapping
This activity is the most time-consuming of the process, and facilitators should not rush it. Facilitators especially use their skills to:
Keep one conversation going. Eliminate multiple conversations so that everyone can consume all available information.
Remain impartial (don’t bias the discussion) and ask clarifying questions (assume that not everybody knows the shorthand).
Break each story down as small as possible (eg. by method call).
Log onto 3×5 cards. Two or more colors are helpful; use one color for the epic level, another color for child stories. Use colors different from the Actors/Activities cards.
The goal isn’t to get all the cards created, but to establish a rhythm of story creation. More stories will inevitably get identified and created post-inception, but knowing how to brainstorm is the key.
(insert pics)
Prioritization
Establish the strategy to be used for prioritizing. For example, are we going to address risks first, or do we want many stories to be completed quickly (momentum & visibility)? The product team representatives will take the lead responsibility prioritizing epics & stories.
Tape the cards to a wall by prioritized epic left-to-right across the top. Stories (children) fall under each epic, prioritized top-to-bottom.
Pointing / Sizing the Stories
The developer teams (and others doing the work) will begin sizing each story, writing the points on each card. This activity can probably be done in parallel to the prioritization, at least after the first epic or two has been prioritized.
(insert pics)
Revisiting the Risks
After stories have been prioritized and sized, the team re-convenes to revisit the original list of risks. Follow the same exercise as before, giving each attendee three tokens (pieces of candy, etc.) to vote on risk theme (not individual risk). Tally the votes and compare to the original baseline.
Next Steps
Review any Parking Lot items to see if anything has been missed (stories, etc.) and potentially schedule out additional meetings to cover edge cases, dependencies, etc.
Capturing actions with committed people (including backups) and due dates is a critical part of the process. At a minimum, someone will be tasked with capturing the information on the inceptions artifacts (cards and papers) and enter them into your preferred project-tracking software system and other documents.
Retrospective & Closing
A quick retrospective of the inception is helpful to continually improve the process. Update this wiki with suggestions/improvements, and give constructive feedback to the facilitators so they can sharpen their skills.
Conclusion
Agile Inceptions are both powerful and fast in getting the team to internalize a vision, and the two-day session vets out goals, risks, roles and use cases, as well as other key topics.  All the players are together, focusing on the project and airing the ideas and assumptions about the project so that the entire team starts off on the same page. The design emerges organically, saving months of requirements gathering, and the structured discovery process enables participants to begin delivering core product functionality immediately.
