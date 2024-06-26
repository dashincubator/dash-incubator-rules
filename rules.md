---
permalink: /
layout: default-rules
---
View [RULES HISTORY](https://github.com/dashincubator/dash-incubator-app/commits/master/rules.md)

# Dash Incubator Rules v4.1.0

# Contents

1. [Dash Incubator](#1-dash-incubator)
2. [Bounties](#2-bounties)
3. [Contributing](#3-contributing)
4. [Admins](#4-admins)
5. [Funds](#5-funds)
6. [Resources](#6-resources)

# 1 Dash Incubator

[Dash Incubator](https://dashincubator.app/) is an open-source, blockchain-funded organization that redistributes [Dash](https://www.dash.org/) issued from [Superblocks](https://docs.dash.org/en/stable/governance/understanding.html) to users who produce open-source output that supports our [Mission](#11-mission) and [Vision](#12-dash-vision).

The Incubator uses a [Bounty](#2-bounties) system to fund and manage the end-to-end delivery of a wide variety of projects [proposed](#21-concepts) by the community, ranging from small [jobs](#22-bounty-types) such as bug bounties, to ongoing [services](#22-bounty-types) such as promotions or infrastructure provision, to mid-size development [projects](#22-bounty-types) such as decentralized apps and development tools, to large development [programmes](#22-bounty-types) involving multiple products that need to be developed and launched together.

Fund allocation and management is decentralized across [Admin](#4-admins) users and [Strategists](#46-strategists).

The Incubator is a [Dash Funded Organization (DFO)](#14-full-transparency). All internal operations of the Incubator are conducted in the public domain at all times. This includes how work is proposed, selected, specified, developed, tested, approved, which users are completing or managing work, what rewards they are allocating or receiving and all internal decision making and governance.

All work produced by the Incubator, known as Output, is open-source and licensed under MIT License.

All handling and allocation of Incubator [funds](#5-funds) can be publicly verified down to [user-task](#25-tasks) level via the [Dash Blockchain](#53-auditing) in realtime.

## 1.1 Mission

Our mission is to find, support and fund the most promising developers and entrepreneurs to build and grow the most innovative and user-friendly applications that maximize the usecases and utility of Dash.

## 1.2 Dash Vision

Our vision is to grow Dash to become the number one cryptocurrency for everyday payments by constantly innovating the fastest, easiest-to-use and most cost-effective digital cash at global scale.

## 1.3 Strategy

Strategy in the Incubator is defined by each individual Incubator [Strategist](#46-strategists). Each Strategist aims to achieve our overall [Mission](#11-mission) and [Dash Vision](#12-dash-vision).

The Incubator's roadmap is the collection of [Bounty](#2-bounties) priorities as stated in [Proposals](#64-proposals) submitted by Incubator Strategists.

## 1.4 Full-Transparency

To ensure that the Incubator's processes and information remain fully open-source and encourage the same standard for other DFOs in Dash, we introduce the following criteria for an **Open-Source DFO** classification that the Incubator implements:

1. All funding receipts and expenditure are tracked
2. All work systems and their data are public
3. All work preparation and pricing is public
4. All work output is public
5. All people's work and rewards are public and verifiable
6. All rules governing the Incubator and decisions on how to maintain those rules are public

## 1.5 Users

There are several types of Incubator users, summarized as follows:

- Users - Anyone who accesses the Incubator or its underlying data
- Members - Users who have signed to the Incubator
- [Contributors](#3-contributing) - Members who create output for the Incubator
- [Admins](#4-admins) - Members who manage Bounties accepted by Strategists
- [Strategists](#46-strategists) - Members with approved network proposals who accept and report on projects
- [Lead Strategist](#47-lead-strategist) - Strategist with key responsibilites including handling funds, ensuring rules are followed, and representing the Incubator publicly

See linked sections for further detail regarding User roles.

## 1.6 Network Contract

This document contains the Rules that define the terms between [Dash Incubator](#1-dash-incubator) and the [Dash Network](https://docs.dash.org/en/stable/governance/understanding.html#) for how any funding awarded to the Incubator by the Network will be used.

When coupled with Incubator's [full transparency](#14-full-transparency) policy, anyone can audit how well the Incubator is meeting the commitments of these terms in realtime, including verifying the use of all funding via the Dash blockchain itself down to a user and task level.

We refer to the transparent implementation of the terms defined in this document in return for the funding provided from Dash Network as the Network Contract.

The Incubator is required to abide by the Network Contract at all times.

The authoritative source for the Rules are contained in a single document hosted on [Github](https://github.com/DashIncubator/dash-incubator-rules/blob/master/rules.md), with updates to the Rules (enacted as merged commits to the master branch) taking effect immediately.

## 1.7 Legal

The Incubator is not a legal entity and as such doesn’t own any assets, including any rights to any output, nor does the Incubator apply any restrictions on contributor's usage of their own Task output, apart from the requirement that all output must be open-sourced under MIT license.

The only funding the Incubator receives is in the form of Dash issued directly from the Dash blockchain, which it redistributes to users who provide verifiable open-source output for defined tasks approved by Admins, who agree to operate in accordance with the Rules defined in this document.

The Incubator does not handle, hold or pay fiat currency. All rewards are issued in Dash as incentives for creating some open-source output, at the sole discretion of Incubator Admins, and without any agreement or action to purchase or procure any assets, intellectual property or labor.

# 2 Bounties

A Bounty in the Incubator means a collection of work that can be completed by contributors for a reward, such as development or promotion of Dash or of the Incubator itself.

Bounties are first proposed as Concepts by the community, and there are four [types](#22-bounty-types) of Bounty that can be funded, each containing a series of [Tasks](#22-bounty-types) that are managed by the Bounty's [Admin](#4-admins), who earn a commission of all rewards that the Bounty generates.

## 2.1 Concepts

All Bounties start as a Concept that is [proposed](#31-proposing-concepts) to the Incubator by a community member.

Concepts are proposals for some work that the Incubator should fund as a Bounty, that provide enough detail about the value proposition and requirements of the work to enable Contributors to complete it.

[Strategists](#46-strategists) create a Bounty for each Concept they accept that they then own, meaning they have the rights to manage and earn commission from its delivery. They [accept](#434-processing-task-claims) Concepts that meet our [Concept Acceptance Criteria](#411-concept-acceptance-criteria) on a first-come first-serve basis. Once accepted, the user who created the Concept is assigned as a [Stakeholder](#24-bounty-stakeholders) of the corresponding bounty.

## 2.2 Bounty Types

When a Bounty is created from a [Concept](#21-concepts) by a [Strategist](#46-strategists), they assign one of four types for the new Bounty that determine how work will be structured:

- **Projects** develop products such as decentralized apps built on Dash, tools for the community, or improvements to the Dash Protocol itself.
- **Services** provide ongoing work that involves provision of some service, such as website hosting, code maintenance, or a recurring requirement for servicing the Incubator itself.
- **Jobs** are one-off pieces of work, such as finding bugs or fixing a github issue.
- **Programmes** are collections of Project, Service or Job Bounties that coordinate large pieces of work.

Bounties in the Incubator are managed publicly. Historically, this has been done on our [Trello Board](#https://trello.com/b/FPJzDcok/dash-incubator-app), but strategists [Strategist](#46-strategists) may use any project management tooling accessible from a public website.

## 2.3 Bounty Status

Each Bounty can be set to have one of the following Statuses at any time:

- **Active** - The Bounty is in progress any Tasks can be created, edited or completed
- **Paused** - The Bounty is on-hold and no Tasks can be created, edited or completed
- **Completed** - The Bounty is archived and no changes can be made.

## 2.4 Bounty Stakeholders

For some bounties, Admins may wish to regularly solicit the views of subject area experts or other key stakeholders as part of the decision making process when defining bounty tasks. 

Whilst bounty administration remains under the Admins of the bounty, a record of these Stakeholders, the nature of their interest, and the circumstances under which they should be consulted, may be added to the Bounty data.

[Concept](#21-concepts) creators are automatically added as Stakeholders of any Bounty that derives from the Concept.

## 2.5 Tasks

A Task is the basic unit of work in the Incubator and represents a unit of open-source output that a user can produce for a specified reward.

All work in the Incubator, and consequently any use of funds, is performed via completion of a Task by a user, or the management of that Task by an [Admin](#4-admins), within a specific Bounty.

Tasks can be proposed by any Incubator User. If a task is created by an Admin, any user may request to [reserve](#33-reserving-tasks) it with the Admin. Tasks created by Admins can be categorized as [Job](#22-bounty-types) tasks to communicate that they may be completed without reservation or pre-approval.

Each Task includes a description of the quantifiable Output (a document, commit, etc) and the specified price denominated in Dash that a user can [Claim](#26-claims).

There are four types of Task available within the Incubator:

- [Concept Tasks](#251-concept-tasks) - the initial creation of a Concept that results in the creation of a new Bounty
- [Specification Tasks](#252-specification-tasks) - work that provides the detail necessary to define Production Tasks
- [Production Tasks](#253-production-tasks) - work related to Tasks required to complete Project, Service and Job bounties
- [QA Tasks](#254-qa-tasks) - work that assures the quality of Production Tasks

### 2.5.1 Concept Tasks

A Concept Task is defined as the [submission of new Concept](#31-proposing-concepts) by an Incubator user.

The [Claim](#34-claiming-tasks) for a Concept Reward is considered to be implicit and approved as soon as a Strategist [accepts](#41-accepting-concepts) the Concept.

### 2.5.2 Specification Tasks

Specification Tasks define how [Production Tasks](#253-production-tasks) should be completed and [QA'd](#254-qa-tasks).

The output is usually a document such as a Design Requirements doc, Functional Specification, or any resource that enables output relating to achieving the Value Proposition of the Bounty to be produced effectively.

Admins measure the quality of the Specification in terms of its fitness for purpose and adequate detail level to define the Production Tasks a [Contributor](#15-users) needs to implement it.

### 2.5.3 Production Tasks

Production Tasks are the actual output of a Bounty that deliver the value proposition. 

Usually Production Tasks output some code or a working product, but if the Bounty is for example a research project, the Production Tasks could output documents or analysis, or any format that satisfies the goals of the Bounty.

### 2.5.4 QA Tasks

Quality Assurance tasks validate and test that [Production Tasks](#253-production-tasks) meet their [Specification](#252-specification-tasks). Production Tasks may require related QA tasks, particularly if prior Specification Tasks include QA criteria. QA Tasks must reference the relevant Specification or Production Task and produce some QA report output.

> QA reports may use a [QA Report Template](https://docs.google.com/document/d/1FCIPJTGGNe-bmjEadO1QtJIvNI5L93Dgv0UeJ6lJzaM/edit), or any other format the admin requests or approves.

## 2.6 Claims

A Claim is the process of a user signalling that they have completed a [Task](#25-tasks) and wish to receive the Task's stated reward.

Users can create Claims for Tasks they believe to be complete from the [Admin](#4-admins) who owns the Task using the [Claims process](#34-claiming-tasks).

Once a Task Claim is approved by an Admin, the Task Reward will be awarded to the Dash address the claimant specified in the Claim within 7 days.

## 2.7 Rewards

The Incubator is a pure Dash fund, meaning all rewards are priced and paid in Dash.

Admins can price tasks up to the max price. Strategists can claim a commission up to the max commission listed in the table below. They can either keep the full claimed [reward](#44-admin-rewards) or split it with a non-Strategist admin who has assisted in the administration process.

### 2.7.1 Price List

<table>
  <tr>
    <td><strong>Task Type</strong></td>
    <td><strong>Approval Criteria</strong></td>
    <td><strong>Max Price</strong></td>
    <td><strong>Max Commission</strong></td>
  </tr>
  <tr>
    <td>Concept Task</td>
    <td>Accepted Concept</td>
    <td>1 DASH</td>
    <td>20%</td>
  </tr>
  <tr>
    <td>Specification Task</td>
    <td>Valid Specification</td>
    <td>100 DASH</td>
    <td>20%</td>
  </tr>
  <tr>
    <td>Production Task</td>
    <td>QA Complete</td>
    <td>100 DASH</td>
    <td>20%</td>
  </tr>
  <tr>
    <td>QA Task</td>
    <td>Valid QA Report</td>
    <td>10 Dash</td>
    <td>20%</td>
  </tr>
</table>

# 3 Contributing

Contributing to the Incubator involves completing [Tasks](#25-tasks) on [Bounties](#2-bounties) to earn [Rewards](#27-rewards).

A reward can also be earned by proposing a Concept for new Bounties that get accepted by a [Strategist](#46-strategists).

All work produced at the Incubator must be open-sourced under MIT license before any rewards can be paid, to satisfy the Incubator's [full-transparency](#14-full-transparency) requirements.

## 3.1 Proposing Concepts

Anyone can propose a new [Concept](#21-concepts) by submitting a description and value proposition to a [Strategist](#46-strategists).  Examples are found on the [New Concept Template on Trello](https://trello.com/c/6XAuy9DW/94-request-new-concept), but these proposals can be hosted on any persistent and public URL controlled by an Incubator Strategist.

Any [Strategist](#46-strategists) can [accept](#434-processing-task-claims) a Concept that meets our [Concept Acceptance Criteria](#411-concept-acceptance-criteria), meaning they create a new [Bounty](#2-bounties) for it that they become the owner of.  The [Concept Reward](#271-price-list) is paid to the Dash address listed in the Concept when accepted.

## 3.2 Completing Job Tasks

Job Tasks on Bounties are open to be claimed by anyone without needing to reserve the task.

To claim a reward on a Job task, use the [Claims process](#34-claiming-tasks)

## 3.3 Reserving Tasks

Any tasks other than Jobs can be reserved. This means that you can agree with the Task's Admin to have exclusive rights to claim the Task until the due date. 

To reserve a task, leave a comment for the Admin of the Bounty that the Task is a part of, so that they can assign the task to you, and/or discuss the Task details and negotiate the reward.

Once you have completed the Task, use the [Claims process](#34-claiming-tasks) to claim the reward.

If a claim isn't made by the due date, the Admin can extend the date, alter the reward, and/or cancel the reservation.

## 3.4 Claiming Tasks

Once you have completed the work for a Task you can make a [Claim](#26-claims) for the reward on the Task, by providing the following information:

1. The task type and number you are claiming (e.g. production task 3)
2. Link to the source for the tasks output (specific PR or commit for Github code)
3. Link to any deploy links relevant to the output (e.g. a URL for a website)
4. A valid Dash address to receive the reward, or set to [NULL](#341-null-claims) to decline the reward.

Once your Claim has been created it will be [processed](#434-processing-task-claims) by an admin.

# 4 Admins

Admins are users in the Incubator who are authorized and permitted to manage [Bounties](#2-bounties) in the Incubator. [Strategists](#46-strategists) are a subset of Admins who assume extra responsibilities, and can carry out all Admin actions. All [Bounties](#2-bounties) must be [originally accepted](#41-accepting-concepts) and [owned](#422-bounty-ownership) by a Strategist, but Admins can perform most administrative [Bounty Management](#42-bounty-management) actions.

## 4.1 Accepting Concepts

Bounties are created via the Acceptance of a user-submitted [Concept](#31-concepts) by a [Strategists](#46-strategists).

 - A Bounty is only created from a Concept approval, and all Bounties must refer back to a single Concept
 - Any Strategist can Accept a new Concept but must first validate that it meets our [Concept Acceptance Criteria](#411-concept-acceptance-criteria)
 - Strategists do not need permission from or consensus between other Admins to accept a Concept
 - Strategists can submit and accept new Concepts themselves
 - Once a Concept is accepted, an implicit Claim for the Concept Task reward is considered to be approved automatically

Admins accept a Concept by [creating a new Bounty](#421-creating-bounties) for it in a Strategist's project management tool, and linking to it in a reply to the user's [proposed concept](#31-proposing-concepts).

The Admin must also add an entry to the [Incubator Accounting Spreadsheet](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0), using a new or existing username and the Dash address from the Concept they submitted.

### 4.1.1 Concept Acceptance Criteria

Strategists must judge that Concepts they wish to accept meet all of the following criteria:

1. Provide a clear Value Proposition that can return value to Dash that's inline with our [Dash Vision](#12-dash-vision)
2. Provide enough detail on requirements to enable a Bounty to achieve the stated goals
3. Be technically feasible using the current Dash Protocol or some unreleased but known iteration of it
4. Be achievable in terms of costs compared to the Incubator's current funding levels

## 4.2 Bounty Management

### 4.2.1 Creating Bounties

Bounties are created exclusively by Strategists who [Accept](#434-processing-task-claims) a community-submitted Concept and consequently receive [Ownership](#422-bounty-ownership) of the Bounty. Strategists can either administer the bounty themselves, or delegate administrative work to a separate Admin.

Admins must ensure the following information is correctly configured on new Bounties that they create:

1. The creator of the Bounty is set as the [Owner](#422-bounty-ownership) Admin of the Bounty
2. The correct [Type](#22-bounty-types) for the Bounty is selected field (either Project, Specification, Job or Programme)
3. The Concept the Bounty was created from is linked in the Concept Doc field
4. The Description text reflects the Value Proposition of the related Concept
5. The Concept creator is listed as a [Stakeholder](#24-bounty-stakeholders)

### 4.2.2 Bounty Ownership

The Strategist who created a Bounty is considered the owner of that Bounty and has priority rights to edit the Bounty's fields, define Tasks and process resulting Claims, and change the Bounty's [Status](#23-bounty-status). The Strategist may transfer ownership to another Strategist at any time.

### 4.2.3 Assistant Admins

The Strategist can optionally appoint an assistant Admin to the Bounty, enabling a maximum of two Admins to manage a bounty at one time. Assistant admins can edit the Bounty's details and carry out all administrative actions, but the Bounty is owned by the Strategist. Assistant Admin rewards are described in [Admin Rewards](#44-admin-rewards).

## 4.3 Task Management

### 4.3.1 Creating Tasks

Admins can create [Tasks](#25-tasks) on any Bounty that they are an Assistant Admin on. When creating a Task, the Admin sets the Description, which must provide enough information to allow a Contributor to complete the work, either in the description itself or by linking a Specification.

The due-date is the date whereby if a [Claim](#26-claims) is not made for the Task, the Admin may edit the task (including changing the reward and/or description, extending the due date, or canceling it completely).

When defining a Task, the Admin must specify the following information:
>1. A task [Type](#22-bounty-types)
>2. A Task number, which is the sequential number of the Task for the relevant type.
>3. A Description, summarising the broad requirements by a short definition is needed, and a link to a Specification to provide further detail if needed.
>4. An amount of Dash for the Reward. This can be [negotiated](#432-pricing-tasks) between the Admin and prospective users
>5. A due date and Task assignee

### 4.3.2 Pricing Tasks

Pricing Tasks in the Incubator takes a different and more flexible approach to traditional methods of sourcing as it factors in externalities such as priority, time constraints, skills availability (or overheads due to sourcing additional resources) and productivity incentives, whilst factoring out notions that ignore these factors such as fixed hourly-rates, market-rates or salary-based arrangements that won't necessarily achieve our goals at the speed we want or with the level of productivity we want to achieve for the value we want to deliver.

For example, if Tasks are urgent or highly specialized and resources are not available, or Tasks have existed for a long time without uptake, higher rewards can be set to achieve uptake on the Tasks, including the option to offer rewards for promoting those Tasks and/or placing the necessary resources, which can result in reward levels above traditional "market rates" to deliver the output we want in the time needed.

On the other hand, low priority tasks with multiple resources already on-boarded and available who could under-bid each other and without time-constraints can often provide output well below "market rates".

In other words, Tasks should be priced via a process to discover what is the minimum reward level needed to incentivize a Contributor to deliver something and deciding whether externalities such as needing to find & onboard the necessary resources or meet a certain deadline need to be factored in based on the Bounty's priority.

Fiat prices should be taken into consideration when a Task is created, but Tasks are typically not repriced based on fiat value changes after creation.

### 4.3.3 Reserving Tasks

When Admins create tasks ahead of time, Members may request to reserve them and negotiate the Task's terms (description, reward, due date) within the comments or via private communication, but once the Task is reserved to the user, the terms are considered agreed and are public information.

### 4.3.4 Processing Task Claims

When a user completes a Task, they create a [Claim](#26-claims) that the Admin needs to process to decide if the Claim is Approved, if QA is needed, or if there are issues that need to be resolved.

Approved Claims on Tasks go into the [Incubator Accounting Spreadsheet](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0) from which the reward will be sent to the claimant.

If a Contributor wants to dispute a Claim decision, they can ask for a second opinion from the other Admin on the Bounty or the Lead Strategist.

Ultimately, decisions on whether some output meets the requirements specified in the Task definition are the sole discretion of the Strategist that owns the Bounty.

Upon approveal, Admins must enter the details into the [Incubator Accounting Spreadsheet](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0), filling in all columns and double checking the user’s payment address and reward amount, to enable the claim to be awarded.

## 4.4 Admin Rewards

Admins are rewarded with a commission based on approved task claims. In addition, strategists (a type of admin) are rewarded with a commission based on approved funding. See the commmission table below for details.

Each quarter all Strategists submit a network proposal with that quarter's monthly budget request. Admins are rewarded as follows:

- Strategists may claim a [commission](#441-commissions) on each monthly budget payout approved by MNOs.
- Strategists may claim a [commission](#441-commissions) on each task they approve on Bounties they own.
- Assistant Admins, when used, are awarded a portion of the Strategist's task-based commission.

Reward calculations are shown in the Claims and Reserve Planning tabs of the [Dash Incubator Accounting](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=941386650) spreadsheet. Note that the Reserve Planning model and values change over time and may not be accurate depending on when the sheet is accessed. The Claims tab data is accurate when accompanied by transaction identification (TxId) values.

Current approved reward limits are found in the [Price List](#27-rewards) and [commission table](#441-commissions).

Strategists can assign, complete, and claim Bounty Tasks for themselves, provided they carry out the task and claim processes and explictily assign themselves to the task for clear auditing purposes.

Task commission rewards don't require separate claims, they are implicit claims recorded with their associated work Tasks in the [Incubator Accounting Spreadsheet](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=0).

Note that Admin reward claims can be lower than the limits listed below. 
Admins simply claim a specific commission, up to but not exceeding the maximum claimable value.


### 4.4.1 Commissions

<table>
  <tr>
    <td><strong>Role</strong></td>
    <td><strong>Commission Limit</strong></td>
    <td><strong>Time of Award</strong></td>
  </tr>
  <tr>
    <td>Strategist</td>
    <td>10% of MNO-approved budget</td>
    <td>After approved superblocks are paid out each month</td>
  </tr>
  <tr>
    <td>Strategist</td>
    <td>20% of task claim (10% if using Assistant Admin)</td>
    <td>When approved tasks are paid out</td>
  </tr>
  <tr>
    <td>Assistant Admin</td>
    <td>10% of task claim (half of Strategist's 20%)</td>
    <td>When approved tasks are paid out</td> 
  </tr>
</table>

## 4.5 Governance

[Strategists](#46-strategists) are responsible for governance and the strategic direction of the Incubator. They collectively form a group referred to as the strategic committee.

The Strategic Committee is responsible to:

- Approve or reject Incubator rule changes (updates to this document).
- Remove any Admin other than the [Lead Strategist](#47-lead-strategist).
- Appoint a new Lead Strategist when the current Lead Strategist steps down.

Simple majority support is required for any of the above, meaning >50% of voting Strategists. Strategists may recuse themselves from voting by not registering a vote (within an agreed voting period) or selecting/commenting ‘Recuse’ against the vote itself.

The [Lead Strategist](#47-lead-strategist) can be replaced by masternode approval through a 1 DASH superblock proposal where the proposed new Lead Strategist is named and proves control over the proposal payout address. The normal passing criteria for funding proposals must be achieved to be considered valid. If that occurs, all funds under the Lead Strategist's control must be transferred to the address given in the proposal. The new Lead Strategist assumes the role upon receipt of those funds.

## 4.6 Strategists

Strategists are [Admins](#4-admins) who define and execute strategies for achieving the Incubator's [mission](#11-mission) and [vision](#12-dash-vision). They ensure that the Incubator as a whole is delivering value to the Dash network.

Each Strategist submits a quarterly Dash network funding proposal, identifying priorites, updates, budget requests, etc related to the projects they own.

Strategists may also carry out the following:

- Appoint new Admins to the Incubator.
- Add existing Admins as Assistant Admins on Bounties they own.
- Accept new Concepts and thus create new Bounties in the Incubator.

## 4.7 Lead Strategist

The Lead Strategist is the [Strategist](#46-strategists) who handles (but isn't liable for) custody of and transactions from the Dash received from the network. All proposal payout addresses for stategist proposals are controlled by the Lead Strategist to ensure that that all payouts adhere to Incubator rules.

The Lead Strategist agrees to use funds solely for the purposes of [Task Claims](#26-claims) and [Admin Rewards](#44-admin-rewards).

The Lead Strategist also carries out the following:

- Represents the Incubator publicly
- Recruits developers and admins to the Incubator
- Handles permissions for key Incubator [Resources](#6-resources)
- Interfaces with Masternode Owners to receive feedback
- Helps settle Incubator-related disputes, internal and external


# 5 Funds

The Incubator is fully transparent about all incoming and all outgoing funds. Funds are received through proposals, managed through reserves, and spent on Tasks and commissions.

## 5.1 Proposals

There are two types of proposals from the Incuabtor to the Dash Network:

- Proposals from the Lead Strategist
- Proposals from (or for) additional Strategists

The Incubator is funded from a series of [Proposals](#64-proposals) submitted to the [Dash Network](https://docs.dash.org/en/stable/governance/understanding.html) on a quarterly basis. The Lead Strategist submits the first proposal of each quarter. After that, anyone can submit additional proposals to participate as an Incubator Strategist. Requirements for each type of proposal are shown in the following two sections.

### 5.1.1 Lead Strategist Proposals

Each quarter's proposal from the Lead Strategist includes:

- Reporting of Incubator-wide accounting
- Reporting of the Lead Strategist's current projects and focus
- Dash addresses used as payout addresses for all existing strategist proposals
- Dash addresses for propspective strategists to use as payout addresses in their proposals


Funding requested by the Lead Strategist is to support only their own projects, not the Incubator as a whole. 

### 5.1.2 Additional Strategist Proposals

Each existing and prospective Strategist submits quarterly proposals to the Dash network for funding of their own projects. These proposals should be submitted with the same cadence as the Lead Strategist's proposal; it should be a three-month proposal submitted within one week of the Lead Strategist's proposal being live on the Dash network. Strategist proposals should include:

- Reporting of project updates, value propositions, reserve spending, quarterly priorities
- Anything else the strategist wants to commmunicate in order to help justify the value delivered to the network for the funding received and requested


## 5.2 Reserves

There are two types of reserves in the Incuabtor:

- The Lead Strategist reserve
- Individual Stategist reserves

Network proposal funds are received into the published [Incubator Wallet](#63-accounting) address(es) for each Strategist (including the Lead Strategist). These addresses are referred to as reserves because funds for each strategist collect into and remain in (through coin control transactions) a single address. Once an individual is approved (through a sucessful Incubator proposal) to be a strategist they retain the same Dash address for their Incubator reserve (unless and until updated Incubator rules dictate otherwise).

All reserve addresses are under the control of the Lead Strategist. Funds are kept in separate reserves for accounting, auditing, and proposal funding purposes. The Incubator maintains Dash reserves only; no other assets are held.


### 5.2.1 Lead Strategist Reserve

When any strategist decides to stop working for the Incubator their reserve is transferred to the Lead Strategist reserve. This is what differentiates the Lead Strategist reserve from all others. The Lead Strategist does not transfer funds to other Strategist reserves. Funds only leave the Lead Strategist reserve in one of two ways:

- rewards for approved tasks
- transfer to a new Lead Strategist through the [governance](#45-governance) process.



### 5.2.2 Strategist Reserves

Funds from approved Strategist proposals are sent directly from superblocks to distinct addresses for each Strategist. These addresses are all controlled by the Lead Strategist.

Each Strategist's published address carries funds in a rolling reserve. Strategists have full autonomy over their reserve spending, so long as they serve the Incubator's vision and mission, and are accounted for according to the [auditing rules](#53-auditing).

When a Strategist leaves or is removed from the Incubator their reserve is transferred to the Lead Strategist's reserve.

## 5.3 Auditing

Anyone can perform a full public audit (#14-full-transparency) of the Incubator at any time to check that all work is being conducted as per these Rules, and verify the rewards issued to individual Incubator users for that work via the Dash blockchain.

### 5.3.1 Auditing Accounts

All spending by the Incubator is tracked via [Task Claims](#26-claims) approved by [Admins](#4-admins), with associated transactions accounted for in the [Dash Incubator Accounting](https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit#gid=941386650) spreadsheet.

- The Balance tab shows all incoming funds and compares it with all approved Task Claims and the current blockchain balance. 
- The Claims tab lists transaction ids for all rewarded claims which can be parsed to verify the reward amounts.

### 5.3.2 Auditing Work

All work must be conducted inline with the Rules in this document and in the public domain. Therefore anyone can audit how well the work being conducted in the Incubator is adhering to these rules at any time.

As a guideline, the following aspects of work are key areas to ensure the Rules are being implemented effectively.

- Admins are pricing work fairly
- Admins are interpreting the rules effectively
- Approved concepts are are inline with our [Mission](#11-mission) and [Vision](#12-dash-vision)
- Quality of output is sufficient for rewards
- Task deadlines and due dates are being managed effectively

# 6 Resources

Below are links to all resources needed to access, fork or audit every aspect of the Incubator, to satisfy our [full transparency](#14-full-transparency) requirements.

## 6.1 General

<table>
  <tr>
    <td><strong>Resource</strong></td>
    <td><strong>Link</strong></td>
  </tr>
  <tr>
    <td>Website</td>
    <td><a href="https://dashincubator.app">dashincubator.app</a></td>
  </tr>
  <tr>
    <td>Website Source</td>
    <td><a href="https://github.com/dashincubator/dash-incubator-app">github.com/dashincubator/dash-incubator-app</a></td>
  </tr>
  <tr>
    <td>Rules Source</td>
    <td><a href="https://github.com/dashincubator/dash-incubator-rules/blob/master/rules.md">github.com/DashIncubator/dash-incubator-rules</a></td>
  </tr>
  <tr>
    <td>Discussion</td>
    <td><a href="https://discord.gg/mU79ZWx">DashDevs Discord</a></td></tr>
</table>

## 6.2 Data

<table>
  <tr>
    <td><strong>Resource</strong></td>
    <td><strong>Link</strong></td>
  </tr>
  <tr>
    <td>Trello Board</td>
    <td><a href="https://trello.com/b/FPJzDcok/dash-incubator-app">Dash Incubator</a></td>
  </tr>
</table>

## 6.3 Accounting

<table>
  <tr>
    <td><strong>Resource</strong></td>
    <td><strong>Link</strong></td>
  </tr>
  <tr>
    <td>General Reserve A (Andy as Proposal Owner)</td>
    <td><a href="https://insight.dash.org/insight/address/XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc">XbFb9b1qaoLykngDbUwBVBFwSHuwQRhSqc</a></td>
  </tr>  
  <tr>
    <td>General Reserve B (Rion as Proposal Owner)</td>
    <td><a href="https://insight.dash.org/insight/address/XoNcU93gE6yMegtTSQpzHGPfHMRUiLS8Ub">XoNcU93gE6yMegtTSQpzHGPfHMRUiLS8Ub</a></td>
  </tr>
  <tr>
    <td>General Reserve C (Rion as Lead Strategist)</td>
    <td><a href="https://insight.dash.org/insight/address/XpVFECgympGyGwRLet2xy14BBhFCWLiXhW">XpVFECgympGyGwRLet2xy14BBhFCWLiXhW</a></td>
  </tr>
  <tr>
    <td>Strategist Reserve 1 (Rion's Lead Strategist Reserve)</td>
    <td><a href="https://insight.dash.org/insight/address/XwxXr39ErU7CK5fPe6N3AnDTi1kK9iDSmm">XwxXr39ErU7CK5fPe6N3AnDTi1kK9iDSmm</a></td>
  </tr>
  <tr>
    <td>Strategist Reserve 2 (Ash's Strategist Reserve)</td>
    <td><a href="https://insight.dash.org/insight/address/XdpS7kop2SowZvVqu7th9dRhZQAvSoJRL4">XdpS7kop2SowZvVqu7th9dRhZQAvSoJRL4</a></td>
  </tr>
  <tr>
    <td>Strategist Reserve 3 (Tim's Strategist Reserve)</td>
    <td><a href="https://insight.dash.org/insight/address/XekTLjeHhtHzN3KNKBkA5hwCBRnftY5GMm">XekTLjeHhtHzN3KNKBkA5hwCBRnftY5GMm</a></td>
  </tr>


  <tr>
    <td>Task Rewards</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1mhXlo4ylqWLLSYN4MGiLWlp7Gq3jrsDt0kB701dwMNU/edit?usp=sharing">Incubator Accounting Spreadsheet</a></td>
  </tr>
</table>

## 6.4 Proposals
<table>
  <tr>
    <td><strong>Proposal</strong></td>
    <td><strong>Link</strong></td>
  </tr>
  <tr>
    <td>2020 Q1 (Phase 1)</td>
    <td><a href="https://www.dashcentral.org/p/dash-platform-incubator"> dash-platform-incubator</a></td>
  </tr>
  <tr>
    <td>2020 Q2 (Phase 2)</td>
    <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-2"> dash-platform-incubator-phase-2</a></td>
  </tr>
  <tr>
    <td>2020 Q3 (Phase 3)</td>
    <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-3">dash-platform-incubator-phase-3</a></td>
  </tr>
  <tr>
    <td>2020 Q4 (Phase 4)</td>
    <td><a href="https://www.dashcentral.org/p/dash-platform-incubator-phase-4">dash-platform-incubator-phase-4</a></td>
  </tr>
  <tr>
    <td>2021 Q1</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2021-q1">dash-incubator-2021-q1</a></td>
  </tr>
  <tr>
    <td>2021 Q2</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2021-q2">dash-incubator-2021-q2</a></td>
  </tr>
  <tr>
    <td>2021 Q3</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2021-q3">dash-incubator-2021-q3</a></td>
  </tr>
  <tr>
    <td>2021 Q4</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2021-q4">dash-incubator-2021-q4</a></td>
  </tr>
  <tr>
    <td>2022 Q1</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2022-q1">dash-incubator-2022-q1</a></td>
  </tr>
  <tr>
    <td>2022 Q2</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2022-q2">dash-incubator-2022-q2</a></td>
  </tr>
  <tr>
    <td>2022 Q3</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2022-q3">dash-incubator-2022-q3</a></td>
  </tr>
  <tr>
    <td>2022 Q4</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2022-q4">dash-incubator-2022-q4</a></td>
  </tr>
  <tr>
    <td>2023 Q1</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2023-q1">dash-incubator-2023-q1</a></td>
  </tr>
  <tr>
    <td>2023 Q2</td>
    <td><a href="https://www.dashcentral.org/p/dash-incubator-2023-q2">dash-incubator-2023-q2</a></td>
  </tr>
</table>
