---
title: Guidance
description: What the group project course is trying to teach you, how the four ticks are awarded, and the practical technical decisions — tools, repositories, filespace, hardware — to make early.
hide:
  - toc
---

# Guidance

What the course is actually trying to teach you, how credit is awarded, and the
practical decisions — tools, repositories, filespace, hardware — you'll need to make
in the first fortnight.

## Emulating a professional project, as closely as possible

The group design project course is an opportunity to gain experience of a real
software development project. Projects are expected to take 30–60 hours of work,
spread over seven weeks, and to let you demonstrate skills and understanding across
a broad range of subjects.

<div class="grid cards" markdown>

-   :material-account-group: **Work in a team**

    ---

    Learning how to work with colleagues you did not choose, on a brief you did not
    write.

-   :material-handshake: **Work with a client**

    ---

    Learning how to work with a professional client, and to keep that relationship
    professional.

-   :material-sitemap: **Follow a process**

    ---

    Learning how to plan and follow a systematic management process through all the
    phases of a software development project.

</div>

!!! note "The briefs are meant to be hard"

    For most students, this will be the most significant technical challenge you
    have ever faced. The design briefs are deliberately intended to push the bounds
    of what you can achieve — often involving new technologies, substantial
    engineering effort, or addressing research problems that have never been solved
    before.

## How the four ticks are awarded

Because the projects, groups, clients and individual roles are so diverse, one
person's performance is not assessed relative to another's. Four standard ticks
recognise that you achieved the goals of the course.

<div class="grid cards" markdown>

-   :material-account-multiple-check: **The group tick**

    ---

    One tick is awarded to all of the group members, to recognise that the project
    has succeeded.

-   :material-check-circle: **Worked effectively with your team**

    ---

    Learning how to work in a team.

-   :material-check-circle: **Maintained a professional relationship with your client**

    ---

    Learning how to work with a professional client.

-   :material-check-circle: **Personally made a substantial technical contribution**

    ---

    Demonstrating skills and understanding across a broad range of subjects.

</div>

!!! info "The expectation is that all students receive all four"

    If you are struggling with any of these goals, and believe there is any risk you
    might not receive ticks as a result, discuss the situation with your Director of
    Studies at the earliest opportunity. If you have severe concerns, also speak to
    your College Tutor and email
    [group-project@cl.cam.ac.uk](mailto:group-project@cl.cam.ac.uk). All personal
    correspondence to that address is treated confidentially, being read only by the
    project organisers and the student administration team.

### The interim self-assessment

After Meeting 3, and before Friday of Week 6, every student must review their
personal contribution so far using the questionnaire on Moodle. This is an
individual requirement, not a team one.

### The personal report

Reflection on your experience, a summary of your own contribution, your assessment
of every other member's contribution, and a sample of source code demonstrating one
of your key technical contributions.

## Technical approaches and tools

Except where mentioned in the design brief, there are very few constraints on the
technical approach you take — but the choices you make in Week 2 shape whether
everyone can contribute.

Projects may involve technical topics spanning everything you have learned on the
Tripos so far. Almost all projects will also require you to learn new things. Some
of this will draw on content taught later in the Tripos, which some members of the
group may need to become familiar with. Some will involve learning about new
programming languages or tools. Some might involve original research, or learning
about new technologies for which there is little documentation.

Members of the group must help each other to work out what skills you have, and what
you need to learn. Some projects may require specialist knowledge or proprietary
information that your client will provide, while others can draw on technical
expertise from within the Computer Laboratory or elsewhere in Cambridge.

You are free to use open source tools and new programming languages as appropriate.
However, remember that all members of the group must make a substantial technical
contribution, and tools should be chosen accordingly. All CST students are familiar
with Java, meaning this will be a natural choice for many aspects of a typical
project.

## Source repository

Every team will need a shared repository to maintain and build their source code.
Each team must create an archive copy of the source repository at the end of the
project, uploaded for assessment via Moodle. For most projects, **Git** will be the
most appropriate solution.

| Option | Notes |
| --- | --- |
| [University GitLab service](https://help.uis.cam.ac.uk/service/collaboration/gitlab) | Available to all students |
| [GitHub](https://github.com) | A shared free account is also welcome, if the team agrees |
| [University OneDrive](https://help.uis.cam.ac.uk/service/collaboration/365/onedrive) | 5 TB quota per student; folders can be shared |
| [cl-student-ssh](https://www.cst.cam.ac.uk/teaching/student-resources/ssh) | Shared folder on the undergraduate SSH server |

## MCS Linux and group filespace

There are a wide variety of software development tools and facilities provided on
the MCS Linux system, and this should be a valuable resource for many projects.

Every group is assigned a personal filespace under MCS Linux at
`${CLTEACH}/grpproj`, with sub-directories `alpha`, `bravo`, … for each group. You
are not obliged to use MCS Linux for development work, but **every group must
deposit an archive copy of their source code in the group directory**, to be used in
project assessment.

Disk usage should be kept below 100 Mbytes for source code, test data and
documentation. A project website can be published by creating a sub-directory called
`public_html`, which maps to a URL under `groups.ds.cam.ac.uk`.

## Hardware projects

A few projects require the use of special purpose hardware borrowed from clients,
sponsors, or other sources. Some projects may include electronic or mechanical
construction. Where a project involves significant hardware design, a demonstrator
may be appointed to provide technical assistance — such as advice on selecting and
purchasing electronic components, or access to workshop facilities.

!!! warning "Borrowed hardware must be returned"

    At the end of the project, all hardware borrowed from clients, sponsors or other
    sources must be returned. **The final group tick will not be awarded until this
    has been done.**

---

**Previous:** [Deliverables](team-deliverables.md)

**Back to:** [Project Teams overview](for-teams.md)
