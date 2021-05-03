---
permalink: /
layout: default-rules
---
View [PROTOCOL HISTORY](https://github.com/dashincubator/dash-incubator-app/commits/master/rules.md)

# Dash Incubator Protocol V 1.1

This document is a protocol that defines the structure and operations of the [Dash Incubator App](/) and the terms that all of its users implicitly agree to.

# Contents

1. [Introduction](#1-introduction)
2. [Bounty System](#2-bounty-system)
3. [Output](#3-output)
4. [Admins](#4-admins)
5. [Funding](#5-funding)
6. [Resources](#6-resources)
7. [Roadmap](#7-roadmap)

# 1 Introduction

## 1.1 Overview

[Dash Incubator App](https://dashincubator.app) is a blockchain-funded App that incentivizes users to produce valuable output for Dash in the form of Bounties that reward users for completing Tasks.

Each Bounty’s work is divided into Tasks which have an agreed Reward, the output of which is tracked in the App (such as a specification document, a Github commit, or a KPI such as % uptime on a website that can prove the value of the work completed).

The App defines a [Bounty System](#2-bounty-system) that operates like a pipeline where Bounties are created as Concepts that progress through Specification and Production stages until all work is completed.

A Bounty is categorized at the Concept stage as one of three types::

*   **Projects** are groups of Tasks that create products such as a decentralized app built on Dash (DApps).
*   **Services** are ongoing Tasks that reward provision of some service, such as website hosting, code maintenance, or a role within the fund itself.
*   **Jobs** are one-off Tasks, such as finding bugs or fixing a github issue.  Job Tasks don’t need to be reserved like Project and Service bounties by users who want to complete them.

When users complete Tasks, they can make a Claim for the Task Reward.

Task Claims are assessed by [Bounty Admins](#4-admins), who are the users who define and manage Bounties and their Tasks.  Once a claim is approved by an Admin, the Task’s Reward will be Awarded to the user with a Dash transaction.

The App is funded from a series of [Proposals](#5-funding) submitted to the Dash Network on a quarterly basis, with all spending from the fund tracked within the Bounty System itself.

All work is incentivized, from providing ideas, code and promotion, to quality assurance, technical writing or improving the Incubator app itself.   

Both the App’s code and data are fully open-source, making everything fully transparent and auditable at all times without the need for external auditing or private interaction or decision making within the App.  

The App is currently delivered as a frontend website that uses a public Trello board and Google document (GDoc) as the backend. In future phases, a custom backend will be delivered, first as a public database, then as a Dash DApp, and ultimately the plan is to wire the App to the Dash proposal system itself as a Governance DApp.  

## 1.2 Motivation

The Incubator was created in February of 2020 from a [blockchain proposal](https://www.dashcentral.org/p/dash-platform-incubator) to provide incentives for developers to build on Dash’s forthcoming protocol upgrade (codenamed Evolution).

The Incubator maximizes value to the Dash network by minimizing management and decentralizing, automating, and incentivizing as much as possible.

The Incubator is built from the ground up in a fully transparent way, from data to code.  This gives everyone access to all information regarding operations, decision making, finances and priorities, to minimize trust and communication needs.

The key principles the Incubator is built on are:

*   Incentivize user’s output not time
*   Incentives and micro incentives will be offered for all work, without reliance on altruism
*   Minimize the level of trust required in human actors by tracking, matching and comparing their reputations of past output value
*   Use free market principles at all levels of the incentive structure to maximize productivity, efficiency, decentralization and value
*   Avoid centralized leadership via governance by quorums of users with the highest reputations based on output
*   Maintain transparency of all information and operations of the app to avoid compartmentalization and maximize communications and visibility
*   Raise only levels of funding that match what the Incubator can scale to
*   Always put the needs of the Dash Network ahead of any needs of the Incubator or the people who come to rely on its rewards as it grows
*   Promote and support easy replication of the Incubator with alternative strategies to improve decentralization and efficiency within Dash’s proposal ecosystem

## 1.3 Mission

Our mission is to grow Dash userbase, ecosystem and developer community by incentivizing & supporting entrepreneurs to innovate useful, easy-to-use trustless apps on Dash (DApps) and the tools, infrastructure and protocols that enable that.

We develop and maintain the Dash Incubator App as a platform for supporting these goals by onboarding, connecting and incentivizing new users to improve and grow Dash.

The Incubator will always be operated and improved with the ethos of finding the most efficient and productive ways to deliver value back to the Dash Network that’s funding our activities with a commitment of full transparency, full incentivization, and putting the needs of the Dash Network and the entirety of its stakeholders first.

## 1.4 Strategy

The current strategy of the Incubator is to:

*   Incentivize primarily the early-stage development of tools, resources and DApps (decentralized apps built on Dash Platform)
*   Prioritize development of Social, Video, E-commerce, Retail, Identity Security, Payments, P2P commerce and Governance DApps
*   Incentivize growth and investment in a strong Dash developer ecosystem with easy onboarding, tools and support
*   Incentivize activities that may be non-development but are aligned to this strategy within the wider ecosystem
*   Incentivize services required for the successful operation of the Incubator itself
*   Incentivize development of the Incubator App itself
*   Incentivize replication of the incubator model within the Dash Network to promote decentralization
*   Incentivize the raising of Proposals to implement the Incubator’s strategy

## 1.5 Structure

Dash Incubator is a fully open-source community-driven App without any corporate or commercial interests owning, licensing or providing it.  

It exists purely as an open-source Website frontend connected to a public backend operated by the Dash community, funded from a Dash Proposal, with all spending of funds commissioned and tracked within the App itself by users.  

All source code (for projects the Incubator funds or the Incubator code itself) is open-source on Github under MIT license and all data in the Incubator app is available in the public backend.

There aren’t any fixed costs, employees or official representatives required for the Incubator to operate. There is no  organizational body to speak of, just users interacting with the Protocol defined in this document, and using the Incubator software. Instead, any work in developing the App itself or for it’s infrastructure, management or service provision, are offered as Bounties within the App that can be completed by anyone with the right skills and reputation.

App management, strategy, and roadmap, are decided by quorums of Admin users who are community members with positive reputations of past contribution. They are assigned greater rights to administer the App’s usage and govern its development and strategy.  Currently the Proposal Owner for the App's funding proposals retains overall control of decision making but this will be decentralized once V1 of the App is mature.  

## 1.6 Licensing

The Incubator doesn't own any assets, including any rights to any Task output,  nor does the Incubator apply any restrictions on providers' usage of their own Task output. This maximizes incentives and minimizes friction for entrepreneurs considering whether to invest in building on or integrating with Dash.

All data and interaction in the App is in the public domain, apart from any user authentication credentials.  

All output from Tasks procured by the fund must be open-source and licensed under [MIT license](https://opensource.org/licenses/MIT), except for cases where proprietary resources are being used, which must be pre approved by an Admin before such Tasks can be claimed.

## 1.7 Proposal Funding

Funding for the Incubator comes from Dash Network [Proposals](#5-funding), voted on by the Masternode Network and awarded at each Superblock to the proposal’s address.

Admins add approved claims in the [Claim Awards List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0) which get awarded via a Dash transaction from the Fund wallet. Every payment from the fund’s Wallet must be listed in the Claim Awards List and therefore relate back to a Bounty Card so that all accounting and payments are tracked and publicly auditable in unmixed address histories derived from the Proposal's payment address.

## 1.8 Transparency

The fund itself must remain fully open-source and transparent, with all transactions out of the wallet matching Claim Awards in the Incubator app, so everyone has the same access to all information relating to the App.

# 2 Bounty System

The Bounty System is the set of tools and data that facilitates and represents how Bounties are defined, managed, and awarded as they progress through Stages in the App.

The core of the system is the concept of a Bounty which is a grouping of Tasks that achieve a certain output, such as a software product, an ongoing service or a one-off job.

Every piece of output from the Incubator is created via a Bounty, whether that’s a Dapp that’s produced, a website that’s hosted, or a Funding Proposal raised to the Dash Network, it’s tracked as a Bounty managed by Admins in the App.

Each Bounty is represented by an individual Card in the App and refers to a piece of work proposed as a Concept by an App user.  Bounties are categorized into one of the three types mentioned in the Overview: Project, Service or Job.  Each Bounty comprises a set of Tasks grouped into one of the four Task Types: Concept, Specification, Production and QA Tasks, described later.  Every Bounty has a Primary Admin, and an optional Secondary Admin. [Admins](#4-admins) are users incentivized to create and manage the Bounty’s Tasks.  An admin earns [commission](#44-admin-rewards) by approving Bounty Tasks, which for a given task is carried out by either the Primary Admin or the Secondary Admin (but not both; only one admin earns the commission for a given task).

> The Bounty System is represented by a Trello Board, with each Bounty represented by an individual Trello Card. The Bounty's stage is represented by the column the Card is in on the Board, with Cards progressing from left to right across the Board forming a pipeline.

## 2.1 Bounty Stages

Bounties progress through four stages like a pipeline.  They are moved from stage to stage by Admins as Tasks are completed, as shown in the following table.

<table>
  <tr>
   <td><strong>Stage #</strong>
   </td>
   <td><strong>Stage</strong>
   </td>
   <td><strong>List(s)</strong>
   </td>
   <td><strong>Next Stage</strong>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>At Concept
   </td>
   <td>Concept
   </td>
   <td>In Specification
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>In Specification
   </td>
   <td>Specification
   </td>
   <td>In Production
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>In Production
   </td>
   <td>Project, Service, Job
   </td>
   <td>Completed
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>Completed
   </td>
   <td>Complete
   </td>
   <td>n/a
   </td>
  </tr>
</table>

Admins are incentivized to add new Bounties and lead them through each stage as quickly as possible as they earn commission on all Tasks at each stage.

Bounties can be moved forwards and backwards across the Pipeline in certain cases, for example a Bounty that’s ‘In Production’ can be moved back to ‘In Specification’ for additional requirements to be defined. A ‘Completed’ Bounty can also have the 'Completed' status removed if more work is required, although it’s usually better to add a new Card for the Bounty marking an additional phase in such cases.

Technically, Stage is determined by the state of a Bounty's Tasks, so it could be, for example, ‘In Production’ (open tasks in the Production Tasks checklist) and also have Specification work being done simultaneously.  In such cases, the List the Bounty Card is in is only an indication of the Stage the Bounty is at and tasks for different stages can be worked on concurrently.

 > Bounty Cards can be marked as Completed in Trello by checking the Completed checkbox in the Card's Custom Fields.  An additional label for Paused indicates that the work on a Bounty's Tasks is on hold.

## 2.2 Meta Bounties

Meta Bounties are the same as Bounties except their Project, Service or Job tasks relate directly to the Incubator App itself, in terms of developing, maintaining and hosting it, and not to 3rd party projects.  

Meta bounties allow easy segregation of Tasks that are needed in providing the Incubator App and improving its features.

> Meta Bounties are indicated on the Trello Board with the pink Meta label

## 2.3 Bounty Tasks

Bounty work is broken up into Tasks, which are individual pieces of work that users can complete to earn a reward, using a [Claims process](#234-claiming-a-reward).

Each Task must produce some quantifiable Output that’s tracked with the Task’s Claim (a document, commit, etc), with special users called [Admins](#4-admins) who are incentivized and given rights to define and Tasks and approve their Claims.

There are four types of Task available within any Bounty Card:

*   [Concept Tasks](#31-concepts) - work related to newly created Bounties at the Concept stage
*   [Production Tasks](#33-projects) - work related to Tasks required to complete Project, Service and Job bounties
*   [Specification Tasks](#32-specifications) - work that provides the detail necessary to define Production Tasks
*   [QA Tasks](#36-qa) - work that assures the quality of Production Tasks

> Each of the four Task types are represented as named Checklists on the Bounty’s Trello Card.

### 2.3.1 Task Fields

Tasks are defined with the following fields:

<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Task Number</strong>
   </td>
   <td>Integer representing the sequence of the Task in whatever list it’s in (Concept, Specification, Production or QA)
   </td>
  </tr>
  <tr>
   <td><strong>Description</strong>
   </td>
   <td>Description of the work to be completed, or references to the same in other resources (such as a prior Specification document link)
   </td>
  </tr>
  <tr>
   <td><strong>Due date</strong>
   </td>
   <td>Date representing deadlines by when tasks must be delivered
   </td>
  </tr>
  <tr>
   <td><strong>Completed</strong>
   </td>
   <td>Indication that the Task is complete (checkbox yes/no)
   </td>
  </tr>
  <tr>
   <td><strong>User</strong>
   </td>
   <td>Name of the user assigned to the Task who has reserved it.
   </td>
  </tr>
</table>

> Task Number and Description shown as text in a checklist on the Trello card, whereas Due Date, Completed and User are represented using the corresponding Trello Advanced Checklist feature, and User is represented by assigning the member to the checklist Task on the Bounty Card in Trello.

### 2.3.2 Task States

Tasks are in either of the following States at any one time, depending on which of the **Task Fields** are set:

<table>
  <tr>
   <td><strong>Task Status</strong>
   </td>
   <td><strong>Meaning</strong>
   </td>
   <td><strong>Field States</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Undefined</strong>
   </td>
   <td>Tasks exists but is not yet defined
   </td>
   <td>Task number or description are null
   </td>
  </tr>
  <tr>
   <td><strong>Unassigned</strong>
   </td>
   <td>Task is defined but not assigned to a user
   </td>
   <td>Task Number, Description, Reward exist
   </td>
  </tr>
  <tr>
   <td><strong>Assigned</strong>
   </td>
   <td>Task is assigned to a user (meaning the work is in progress)
   </td>
   <td>Task Number, Description, Reward, Due Date, Member exist
   </td>
  </tr>
  <tr>
   <td><strong>Overdue</strong>
   </td>
   <td>The task is past its due date (requires attention by an Admin)
   </td>
   <td>Task Number, Description, Reward, Due Date, Member exist, where due date is in the past
   </td>
  </tr>
  <tr>
   <td><strong>Completed</strong>
   </td>
   <td>The task user created a claim that was approved by an Admin
   </td>
   <td>Task Number, Description, Reward, Due Date, Member exist, where Completed equals True
   </td>
  </tr>
</table>

For Project and Service Tasks, users can reserve Unassigned Tasks, which means that an Admin will assign a Member to the Task exclusively along with a due date for the work to be completed.

For Job Tasks, no reservations are available, meaning Assigned and Overdue states are not applicable.

Once the Task is complete, the Member can claim the reward for the task by leaving a comment on the Card referencing the task(s).

> Admins set the Completed state for Tasks by checking the Task's item in the Checklist on the Bounty Card on Trello.

### 2.3.3 Reserving a Task

Reserving a Task means you have exclusive rights to Complete it and make a Claim for the Task Reward upto and including the Due Date.

To be able to Reserve a Task please join as a Member of our Trello Board by leaving a comment on our [Member Signup Card](https://trello.com/c/VlpK4dgl/95-member-signup).

Then you can reserve the Task by leaving a comment on the relevant Trello Card of the Task and including the number of the Task(s) you want to reserve from the Checklist it's in, e.g.

```I want to reserve Production Tasks 1-3```

An Admin will assign you to the Task on the Card along with a due date for completion, or will discuss any questions or issues with the reservation in the comments. Primary Admins are responsible for assigning users to tasks except when the Primary Admin is the user requesting a task, in which case the Secondary Admin makes the assignment.

If this is the first work you are producing in the Incubator it might benefit you to provide some examples of prior work to build some positive reputation e.g. by linking your Github repositories or completing some Jobs first.

If a reserved Task isn’t claimed by the given Due Date, an Admin has the right to unreserve the task and reserve it for another user. However, Admins should use discretion when unreserving overdue Tasks, for example to extend the date if there are extenuating circumstances the user can provide evidence for, and/or settle for the portion of the valid work delivered within the task.

### 2.3.4 Claiming a reward

To claim a reward on a Task create a comment on the Trello card with the following information:

1. The name of the checklist the Task is in (e.g. Concept Tasks, Production Tasks, QA Tasks etc).
2. The Tasks Number(s) you want to claim
3. Link to the source for the tasks output (usually a PR or commit on Github)
4. Link to any deploy links relevant to the output (e.g. a URL for a website)
5. Specify a valid Dash address to receive the reward

Your claim will then be processed by an admin.

### 2.3.5 Processing claims

Claims are assessed based on the rules for the type of output produced, and whether the work completes the Task adequately as it was defined.  All claims are processed by Admins.  Claims are processed by the Primary Admin, unless the claim is being made by the Bounty's Primary Admin, in which case the claim is processed by the bounty's Secondary Admin.

If the claim is approved, the Admin will leave a [Claim Approved comment](#435-task-claims) on the Trello Card, otherwise they may discuss any issues directly on the card comments with you.  Approved claims will be awarded usually within 7 days and will be listed in the [Claim Awards List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0).

## 2.5 Price List

Each type of reward for Tasks in the App are listed below along with the min/max amounts of Dash that can be offered and basic criteria upon which claims will be approved.  

Rewards are fixed, Dash-denominated amounts decided by the Primary Admin in all cases except when the Primary Admin is the user requesting to add, reserve, or claim the task, in which case the amount is decided by the Secondary Admin.  Users may negotiate the amount with the appropriate Admin before requesting a reservation or making a claim (see Section 5 for details).

The Admin % is an added commission that an Admin earns for processing a task claim, which is carried out by either the Bounty's Primary Admin, or its Secondary Admin. For example, under 10% commission, an approved 10 DASH Task yields 10 DASH for the user completing the task, and 1 DASH for the Admin processing the claim, either the Primary Admin (most cases) or the Secondary Admin (when the Primary Admin completes the task and claims its reward).

### 2.5.1 Bounty Rewards

<table>
  <tr>
   <td><strong>Task Type</strong>
   </td>
   <td><strong>Approval Criteria</strong>
   </td>
   <td><strong>Amount</strong>
   </td>
   <td><strong>Admin %</strong>
   </td>
  </tr>
  <tr>
   <td>Concept Task
   </td>
   <td>Valid Specification
   </td>
   <td>1 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Specification Task
   </td>
   <td>Valid Specification
   </td>
   <td>0.1-5 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Production Task (Project or Service)
   </td>
   <td>QA Complete
   </td>
   <td>0.1-20 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>Production Task (Job)
   </td>
   <td>Valid Job (to Spec or QA)
   </td>
   <td>0.1-10 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
  <tr>
   <td>QA Task
   </td>
   <td>Valid QA Report
   </td>
   <td>0.1-5 Dash
   </td>
   <td>10% - 15%
   </td>
  </tr>
</table>

### 2.5.2 Admin Commission Rates

Each individual admin's commission is variable based on the number of contributions (bounty claims processed) in the previous 30 days (including "today"). There are 3 Tiers of commissions and admin can earn: 10%, 12%, 15%

<table>
  <tr>
   <td><strong>Count of bounty claims processed</strong>
   </td>
   <td><strong>Commission Rate</strong>
   </td>
  </tr>
  <tr>
    <td>0 - 14
    </td>
    <td>10%
    </td>
  </tr>
  <tr>
    <td>15 - 29
    </td>
    <td>12%
    </td>
  </tr>
  <tr>
    <td>30 +
    </td>
    <td>15%
    </td>
  </tr>
</table>

Each reward an admin receives is valued based on the Tier the admin’s previous 30 days contributions fall into. The "next" tier of commission is effective immediately once an Admin crosses the threshold, and is effective for all claims as long as the Admin meets the criteria.

For example:
* Admin Alice has processed 10 claims in the past 30 days (including today). If Alice processes 5 additional claims today, Alice will be eligible for a 12% commission on the 5th claim (and any additional claims).
* Admin Albert has processed 34 claims in the past 30 days, but 7 of those were processed exactly 30 days ago. If Albert processes claims today, each of those will earn 15%. If Albert does not process at least 2 claims today, his commission rate will be 12% for claims processed tomorrow until his 30 day count is 30 or more again, at which point Albert will return to a 15% commission.
* Admin Ash has processed 9 claims in the past 30 days. Today Ash processes 21 claims. For the first 5 claims Ash processes today the commission is 10%. For the next 15 (claims 15 - 29) the commissions is 12%. The final claim Ash processes has a 15% commission.

# 3 Output

In this section we detail the types of output the Bounty Tasks incentivized in the App.

## 3.1 Concepts

Concepts are new Bounties proposed by users in the App and are stored in the Concepts List.

Users receive a reward if the Concept is approved and subsequently enters Production (the Card is moved to either the Projects, Services, or Jobs Lists).

Bounties at the Concept stage require specific info from a user to enable [Admins](#4-admins) to approve them and move them to the Specification stage.

Concepts are value propositions that both define how some idea would work and what problems it would solve, and a [New Concept Template](https://trello.com/c/6XAuy9DW/94-request-new-concept) is provided as a guideline for the kind of info Admins want to assess new Concepts.

Admins should approve any Concept that is clearly defined, within budget and inline with the current Incubator [Strategy](#14-strategy).  Concepts require approval from at least one Admin, and are accepted according to the [Bounty Card](#421-bounty-cards) rules.

The user who creates a Concept has 24hrs of exclusive privilege to request to reserve the corresponding Specification Tasks once the Bounty is moved to the Specification List, after which time it is open to anyone.

Admins take the following into account when deciding which Concepts to complete and move to the Specification stage:

*   ROI of value proposition to Dash as a whole
*   Alignment with Incubator strategy
*   Input from other users (factoring in reputation / contributions)
*   Feasibility of idea in terms of available skills, developers and budget

### 3.1.1 Creating a Concept

To propose a new Concept:

1. Fill in the info detailed in the [New Concept Template](https://trello.com/c/6XAuy9DW/94-request-new-concept) document.  
2. Add a comment on the [New Concept Card](https://trello.com/c/6XAuy9DW/94-request-new-concept) on the Trello Board, linking the template you’ve created.

Admins will then review your concept, and if it satisfies the [Concept requirements](#31-concepts) it will be added as a new card in the Concepts list on Trello.  Admins may ask you to expand on or amend some of the info in the template doc you posted.  

The Primary Admin will reserve the Concept Task for you, so that you can claim the reward if the concept completes the [specification](#32-specifications) stage.  Concepts provide fixed rewards as specified in the [Price List](#25-price-list).

### 3.1.2 Claiming a Concept Task Reward

Once an Admin has marked your reserved Concept Task(s) as completed, it can be moved to the Specification stage.  When the relevant Specification tasks have been completed, you can claim your Concept Reward.

## 3.2 Specifications

A Specification is a detailed definition of the work that needs to be completed for a Project, Service or Job Bounty.

Bounties can be moved to the Specification stage (represented by their Card being in the Specifications list on Trello) meaning they need to have work specified before some production tasks can be completed.

Producing a Specification involves taking an approved [Concept](#31-concepts) and defining the criteria (such as features) that then allows a user to implement the concept.

Admins measure the quality of the Specification in terms of its fitness for purpose, adequate detail level to determine Production Tasks to implement it.

The Specification must also define the QA Tasks required to test it’s fit for purpose.

Admins reserve the right to define a minimum requirement for each Specification.

#### 3.2.1 Reserving a Specification Task

Unassigned Specification tasks can be found on the [Trello Board](https://trello.com/b/FPJzDcok/dash-bounty-board) and listed in the [Incubator App](https://dashincubator.app/).  Follow the [Reservations](#233-reserving-a-task) process to reserve a specification task.

#### 3.2.2 Claiming a Specification Task Reward

Once a specification task is complete you can claim a reward for the work that will then be assessed by an Admin by following the [Claims Process](#234-claiming-a-reward).

## 3.3 Projects

Projects are Bounties that deliver a product such as a DApp or some other usually IP based output in line with our Strategy.

Projects Tasks are a type of Production Task that can be reserved by users.

### 3.3.1 Project Tasks

Project Tasks are the Production Tasks that comprise each Project Bounty.

They are created by an Admin and appear in the Project Tasks checklist on the Trello on the Bounty’s Card.  

Producers can ask Admins to add a certain task or help them to create the task definition.

### 3.3.2 Reserving a Project Task

Unassigned Project tasks can be found on the [Trello Board](https://trello.com/b/FPJzDcok/dash-bounty-board) and listed in the [Incubator App](https://dashincubator.app/).  Follow the [Reservations](#233-reserving-a-task) process to reserve a project task.

### 3.3.3 Claiming a Project Task Reward

Once a project task is complete you can claim a reward for the work that will then be assessed by an Admin by following the [Claims process](#234-claiming-a-reward).

## 3.4 Services

Services are ongoing Bounties with Production Tasks that pay rewards based on some key performance indicator (KPI).  For example, receiving a reward for hosting a website with 95% uptime on a month-to-month basis.

Service Tasks appear in the Project Tasks checklist on the Trello card of the Bounty.

### 3.4.1 Reserving a Service Task

Unassigned Service tasks can be found on the [Trello Board](https://trello.com/b/FPJzDcok/dash-bounty-board) and listed in the [Incubator App](https://dashincubator.app/).  Follow the [Reservations](#233-reserving-a-task) process to reserve a service task.

### 3.4.2 Claiming a Service Task Reward

Once a service task is complete you can claim a reward for the work that will then be assessed by an Admin by following the [Claims process](#234-claiming-a-reward).

## 3.5 Jobs

Jobs are on-off Bounties with singular Production Tasks that can be claimed at any time without reservation, such as a bug bounty, fixing a Github issue or adding content to the Incubator website, for a fixed price.

### 3.5.1 Claiming a Job Task Reward

Jobs are found on the [Trello Board](https://trello.com/b/FPJzDcok/dash-bounty-board) and the [Incubator website](https://dashincubator.app/). Follow the [Claims](#234-claiming-a-reward) process to reserve a project task.

## 3.6 QA

Quality Assurance tasks validate Production Tasks (Project, Service or Job), each referring to a Work task in their description. They can be reserved and the output should follow the [QA Report Template](https://docs.google.com/document/d/1FCIPJTGGNe-bmjEadO1QtJIvNI5L93Dgv0UeJ6lJzaM/edit) unless the admin requests some alternative information. [Example](https://docs.google.com/document/d/1Ty8T_c9aXkmxYR02NpiItXbKTS6Tm7tjvy1kLhEaV-Q/edit#heading=h.jys2v7f243gx)

### 3.6.1 Reserving a Service Task

Unassigned QA tasks can be found on the [Trello Board](https://trello.com/b/FPJzDcok/dash-bounty-board) and listed in the [Incubator App](https://dashincubator.app/).  Follow the [Reservations](#233-reserving-a-task) process to reserve a QA task.

### 3.6.2 Claiming a Service Task Reward

Once a QA task is complete you can claim a reward for the work that will then be assessed by an Admin by following the [Claims Process](#234-claiming-a-reward).

# 4 Admins

This section relates to the special Admin role and rules on how they operate.

Admins work to facilitate the production of output and regulate the operations of the fund itself.  A given Bounty can have both a Primary Admin and a Secondary Admin, as detailed in the appropriate sections below and throughout this document.

Admins earn commission, as defined in the [Price List](#25-price-list).  This is to incentivize ownership of Bounty Tasks in terms of defining them, promoting them and supporting the work involved in their completion.  Admins earn commission at the task level.  For a given task the commission is awarded to the Admin who processes requests and claims for that task.  This is either the Primary Admin or the Secondary Admin (not both), as detailed in later sections.

The number of users given Admin rights is limited and Admins effectively compete with each other on performance (how good is their output). Low performing Admins may be replaced with new Admins periodically at the discretion of the Proposal owner.  An Admin's reputation and performance is based on the history of Bounties they have delivered, and as everything in the App is public, all metrics for an Admins performance can be mined from the App’s data.

In general, an Admin's main goal is to get as many bounties completed as quickly as possible, so that they can maximize commission and secondly grow a list of successful and popular bounties that deliver the most value at the least cost when compared to other Admins in the system.  Admins also ensure that data is correct and following the protocol defined in this document, and moderate where needed.

## 4.1 Permissions

Primary Admins are configured as Members of the Trello Board, who are the only users who can change data on the board.  Public users can’t change anything on the board apart from adding comments on cards.  There is no authoritative or rank difference betweeen Primary Admins and Secondary Admins in general, only as it relates to specific Bounties and Tasks, as detailed in the following section.

## 4.2 Bounty Admin

As described in [Section 3](#31-concepts) above, the first Admin who accepts a Concept becomes that Bounty's initial Primary Admin.  Any Admin may subsequently claim the Secondary Admin role for that Bounty.  No more than two Admins are allowed to administer Tasks on a Bounty at a given time.  The main purpose of the Secondary Admin is to allow the Primary Admin to reserve, do, and claim Tasks on a Primary Admin's own Bounty.  Admins may not receive rewards for Tasks that they define or specify.  When a Primary Admin wants to do work (specification, production, or QA) on his own Bounty the Secondary Admin must administer such tasks, and they (the Secondary Admin) then gets the commissions for those tasks. This applies to [reserving tasks](#233-reserving-a-task) and [claiming rewards](#234-claiming-a-reward).  Secondary Admins are allowed to reserve, do, and claim task as any normal user would.  This effectively allows any individual the ability to both administer Tasks and reserve, do, and claim Tasks belonging to any Bounty.  It does this while also retaining checks and balances, disallowing anyone from being able to approve their own work.

For example, Admin Alice is the first Admin to approve a Concept.  Admin Bob subsequently claims the role of Secondary Admin.  The Concept becomes a Bounty with Alice as the Primary Admin and Bob as the Secondary Admin.  Specifier Sam creates a Spec that results in Production Tasks 1 and 2.  Developer Dave requests, implements, and claims Production Task 1.  Admin Alice processes Dave's claim and receives commission.  Primary Admin Alice requests to reserve Production Task 2.  Secondary Admin Bob approves the reservation.  Alice finishes the work and makes her claim.  Bob processes the claim and receives his commission.

The Primary Admin has the default permission to edit (add tasks, move from stage to stage, etc.) the Bounty Cards.  Non-admin users can only comment on Cards.  Secondary Admins only have permission to process requests from the Primary Admin, as explained above.  

### 4.2.1 Bounty Cards

Primary Admins assign themselves as Card Members on Trello to signify their role for that Bounty.  Secondary Admins assign their username to a given Card's "Secondary Admin" custom field to signify their role for that Bounty.  Cards should always have a Primary Admin, and may have a Secondary Admin.  No more than two Admins are allowed on a Card at any given time.

Primary Admins can authorize Secondary Admins to temporarily take over the responsibilities and accompanying rewards belonging to the Primary Admin.  This is done by commenting on the Trello card with a date when the responsibilities and rewards are should fall back onto the Primary Admin.  When a Primary Admin no longer wishes to administer a given bounty, the Secondary Admins has the first right to take over as Primary Admin.  If the Secondary Admin does not want to become Primary Admin the role is open to any Admin who wants it.  This is done by changing the Card’s assigned member(s) to the new Primary and Secondary Admins.  Ideally this is agreed upon this first in the Card’s comments.  The new Primary Admin then earns the rewards on any new task assignments.

If a Bounty has any outstanding Task Claims for more than 7 days with no reply to the user, the Secondary Admin can assign themselves as the Primary Admin and any other Admin can assign themselves Secondary Admin on that card, stating the change to the prior Bounty Admin(s) in the card comments.

> Primary Admins assign their username to the card in Trello as follows: find ‘ADD TO CARD' > click 'Members’ > click 'yourusername'.  This card-level assignment is displayed on the front of the card on the Trello board.

> Secondary Admins assign their username to the card in Trello as follows: find ‘Custom Fields’ > click 'Secondary Admin' > type 'yourusername'.  This card-level assignment is displayed in the Custom Fields section of the card on the Trello board.

### 4.2.2 Card Description

Description should just contain the Value Proposition from the New Concept Template submitted when the Card was created, and a link to that info so anyone can read the concept.

### 4.2.3 Card Custom Fields

Custom fields (using the Trello Powerup) should be set by the Bounty Admin at the Concept stage and provide basic background info / category for the Card.

## 4.3 Task Admin

### 4.3.1 Task Format

All tasks must be specified in the relevant Checklist on the Trello card, with the following format, to allow API retrieval:

```[taskId]) [taskDescription]([amount] DASH)```

For example:

```1) Fix current build issue (1 DASH)```

When a task is reserved, it must also have a due date and a member who reserved it set using the relevant functions on Trello’s advanced checklist.

### 4.3.2 Task Scope

The description field of the task, i.e more broadly the requirements by which the task will be assessed as completed or not, is up to the discretion of the appropriate Admin as detailed in section 4.2 above.  Unless the Task is a small piece of work that’s easy to test / know if it’s completed correctly, the Admin should link some info from the Task description describing the criteria for completion of the task.  

For Specification tasks, the scope could be quite broad, for example R&D that’s required, feasibility studies, analysis.  It’s up to the appropriate Admin to decide how best to define Tasks to achieve the best results.

### 4.3.3 Task QA

Most tasks in Projects, Services and Jobs should require related QA tasks, which should be created at the time of the Work Task, so that there is a clear metric of what the Work task needs to achieve, and how the QA (and the Admin that approves the QA’s claim) can validate that.

QA Tasks must reference the relevant task (i.e. one of the other checklists on the card) and produce some QA report output.

**Format:**

```[qaTaskId])[checklistName]([taskIds])([amount] Dash)```

For example:

```1) QA: Production Tasks (1,2) using [spec section 5]([url]) (0.1 Dash)```

QA Rewards are set as a % added to the relevant Task the QA refers to, defined in the [Price List](#25-price-list).

QA Tasks claims should be requested by users and processed by Admins like regular Production tasks.  In cases where the QA provider is the Primary Admin, the Secondary Admin is required to approve the claim as with all tasks.

### 4.3.4 Task Reservations

The Primary Admin can reserve unassigned tasks to users who have left a valid [Request Reservation](#233-reserving-a-task) comment.  If the Admin deems the request valid, they assign the user to the tasks in the Tasks checklist, which removes those tasks from availability on the Incubator website. They may also comment to alert the user that the relevant tasks were reserved, for example:

```@username reserved tasks: 1,2,3,4,5```

If the comment is invalid, either technically or for another reason such as lack of reputation or some previous issue, the Admin should reply to the comment to request clarification or give the reason(s) why the request was denied, for example:

```@username, there are two "task 3"s, are you requesting to reserve Specification Task 3, or Production Task 3?```

### 4.3.5 Task Claims

When an Admin wants to approve a user’s Claim comment, they add a Claim Approved comment as follows:

```Claim Approved: [@username][checklistName]([taskIds])([amount] Dash)```

For example:

```Claim Approved: @somedev Production Tasks (1,2) (1 Dash)```

If there is an issue with the claim, for example some info was missing like a Dash address, or there was an issue with the work, the Admin should try to resolve it fairly with the user via the comments section.

Admins must enter Approved Claims into the [Claim Awards List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0), filling in all columns and double checking the user’s payment address and reward amount, to enable the claim to be awarded.

Once an approved Claim is awarded (the txid was entered into the sheet), the Bounty Admin should reply to the user on the Bounty Card with the txid of the Dash transaction.

## 4.4 Admin Rewards

Admins receive a % of the reward for Tasks on Bounty’s they administer, added to the Task reward, using the rates defined in the [Rewards List](#252-admin-commission-rates).

For example, if a Task Reward is 1 Dash and the Admin Reward is fixed at 10%, the user completing the Task is awarded the 1 Dash and the Bounty Admin is awarded an additional 0.1 Dash.

To receive rewards Admins must enter in the additional info in the Claim Awards List inline with each user’s Task claim, stating their name, Dash address and the reward amount (auto calculated).  The txid for the transaction should be pasted by the Admin who sends it.


## 4.5 Governance

Currently Admins are appointed by the Incubator’s Proposal Owner on Dash who is an Admin with veto permissions on other Admin decisions and has responsibility for maintaining these App Rules and payment of Rewards from the Proposal address.

The goal is to move to full decentralized decision making by Admins with rules for elections, removal, decisions (such as altering Rules).


# 5 Funding

Dash to use to award Bounty Task Rewards are sought via Dash Proposals every 3 superblock cycles (roughly 3 months).

The Funding Proposal Owner is the App user designated by Admins who may create a Dash Proposal requesting Bounty funding on behalf of the Dash Incubator App (the Incubator Funding Proposal).

This user controls the private key for the address listed in the Proposal (the Proposal Wallet) that will receive the Dash requested by the Proposal if it’s granted.

The Proposal Owner agrees to transfer Dash from the Proposal Wallet only for the purposes of awarding approved Task Claims by App users when approved by Admins, and not to withhold those funds or create transactions from the Proposal Wallet for any other reason.

The Proposal Owner will track all transactions from the Proposal Wallet in the [Claim Awards List](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0).

The Proposal Owner is granted Admin rights automatically.

> Note that in Phase 4 of the Incubator Roadmap, the Proposal Owner won’t be needed, as the Incubator as a Funded-Dapp can request and distribute funds trustlessly using smart code.

# 6 Resources

This section links the resources required to access any information relating to the Incubator, from code to data to the Proposal that funds it, to satisfy the full-transparency and open-source requirements of the Incubator and allow full public auditing.

## 6.1 Software & Data

<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
  <tr>
   <td>Website:
   </td>
   <td><a href="https://dashinc.app">https://dashincubator.app</a>
   </td>
  </tr>
  <tr>
   <td>App Data (Trello):
   </td>
   <td><a href="https://trello.com/b/FPJzDcok/dash-incubator-app">https://trello.com/b/FPJzDcok/dash-incubator-app</a>
   </td>
  </tr>
  <tr>
   <td>Discussion:<a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing"> </a>
   </td>
   <td><a href="https://discord.gg/mU79ZWx">https://discord.gg/mU79ZWx</a>
   </td>
  </tr>
</table>

## 6.2 Funding

<table>
  <tr>
   <td><strong>Resource</strong>
   </td>
   <td><strong>Link</strong>
   </td>
  </tr>
  <tr>
   <td>Awarded Claims:<a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing"> </a>
   </td>
   <td><a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing">https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing</a>
   </td>
  </tr>
  <tr>
   <td>Proposal Wallet:
   </td>
   <td><a href="https://chainz.cryptoid.info/dash/address.dws?XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc.htm">https://chainz.cryptoid.info/dash/address.dws?XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc.htm</a>
   </td>
  </tr>
  <tr>
   <td>Dash proposals:
   </td>
    <td>
   <p>
  Phase 1:<a href="https://www.dashcentral.org/p/dash-platform-incubator"> https://www.dashcentral.org/p/dash-platform-incubator</a>
</p>
<p>
Phase 2:<a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-2"> https://www.dashcentral.org/p/dash-platform-incubator-phase-2</a>
</p>
<p>
Phase 3: <a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-3">https://www.dashcentral.org/p/dash-platform-incubator-phase-3</a>
</p>
<p>
Phase 4: <a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-4">https://www.dashcentral.org/p/dash-platform-incubator-phase-4</a>
</p>
   </td>
  </tr>
</table>

# 7 Roadmap

Currently we’re in version 1 of the Incubator app.  

Three further versions of the App are planned leading to the implementation as a DAO (Decentralized Autonomous Organization) running on the Dash Network.

<table>
  <tr>
   <td><strong>Version</strong>
   </td>
   <td><strong>Features</strong>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>Read-only frontend website using <a href="https://trello.com/b/FPJzDcok/dash-incubator-app">Trello</a> and <a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing">GDocs</a> for the backend.  Users enter info on Trello.
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>CRUD enabled website using a (public) database on the backend.  Rules are fully implemented via the website frontend for users.
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>DApp version of the website using Dash for the backend.  Each user cryptographically signs their actions and output in the App, removing the need for trust in any of the Dapps information.
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>Smart funding; MNOs (Masternode Operators) fund the Incubator DApp directly from the block reward without an intermediary Proposal Owner.
   </td>
  </tr>
</table>
