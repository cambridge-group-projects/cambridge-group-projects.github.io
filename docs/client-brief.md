---
title: Writing a Brief
description: What the published design briefs have in common, four things worth doing, and what makes a brief hard for a student team to work with.
hide:
  - toc
---

# Writing a brief

Your brief is the only thing students see before they choose. It has to
[make them want the project](design_a_good_project.md), tell them honestly what
the hard part is, and leave them room to design a solution — in about a
paragraph.

## Three published briefs

... from 2026 as examples of what a great brief can look like.

!!! example "Draught Detective — Fran Sutton, Cambridge Retrofit Hub"

    A key priority in making homes more energy efficient is to find and
    plug air draughts. In principle, a builder upgrading an existing house
    could simply fasten a fan in an open window, use a differential
    pressure meter to determine how airtight the house is, and start
    plugging holes, adjusting the number of air changes per hour to fall
    within a desirable range. A cheap and easy phone app could help the
    builder to setup and calibrate the equipment, then provide practical
    guidance to prioritise the most urgent repairs, giving feedback on what
    has been gained with each of those.

!!! example "Digging for Data — Leontien Talboom, Cambridge University Library"

    In the century before the World-Wide Web, a whole generation of
    scientists kept their data and archives on floppy disks, often encoded
    in formats specific to a particular disk drive or PC manufacturer.
    Much of that data has never gone online, and is now in danger of being
    lost forever. This project is an archaeological exercise, developing a
    tool that can excavate and decode that data, perhaps applying machine
    learning methods to identify and reverse-engineer texts and tables
    from the magnetic media. Your client is a digital archive specialist,
    who can provide many samples, as well as technical documentation, to
    get you started.

!!! example "Wise Banking — Tokunboh Ishmael, Alitheia Capital"

    Mobile banking apps are convenient, and help many students with
    monthly budgets, but can make it hard to plan for the long term. A
    particular failing is how to get life advice from other generations,
    not just parents, but wise friends and mentors in your home community.
    Your challenge is to create a personal wisdom-based banking app that
    connects across generations, drawing on principles from the Yellow
    Cowries curriculum that empower young adults to make improved
    financial decisions such as savings, loans, investments and insurance.
    It's important to consider and go beyond AI advice models, building
    whatever is special in local communities and lifestyles.

## What the published briefs have in common

Almost every published brief follows roughly the same shape.

- A short, memorable title — most are two or three words ("Draught Detective",
  "Digging for Data", "Wise Banking").
- A named client: one person, plus the organisation they represent.
- Roughly 100–200 words of prose, in a single paragraph. No headings, no bullet
  lists, no requirements tables.
- Opens with the context and the problem, in plain language a second-year student
  can follow without domain knowledge.
- States what the team should build, usually as "Your task is to…" or "The goal of
  this project is…".
- Names the technical challenge — the interesting, hard part that makes it worth
  seven weeks.
- Leaves the design open. Almost none of them specify a language, framework or
  architecture.

## Four things worth doing

<div class="grid cards" markdown>

-   :material-target: **Aim at the hard bit, not the whole product**

    ---

    The briefs that work describe one substantial technical challenge, not a full
    product backlog. If your brief could plausibly take a startup a year, narrow it
    until it could take a small team seven weeks.

-   :material-account-group: **Make room for everyone to contribute**

    ---

    Every member must make a substantial technical contribution and gain real
    programming experience. Briefs that split naturally into components — an
    interface, a data pipeline, a model, a test harness — allocate more easily than a
    single monolithic algorithm.

-   :material-server: **Say what you can supply**

    ---

    If the project depends on data, credentials, API access, documentation or
    hardware, mention it. Access that has not been approved is one of the most common
    risks teams report in week 1.

-   :material-compass: **Leave the technical approach open**

    ---

    There are very few constraints on the technical approach teams take, and they are
    free to use open-source tools and new languages. Specify a stack only where the
    project genuinely requires it.

</div>

## The shape, annotated

This is **Draught Detective**, from a published set, broken into the four moves
almost every successful brief makes.

| Move | Example |
| --- | --- |
| **Title** | **Draught Detective** — two words, memorable, hints at the problem without explaining it. |
| **Client** | **Fran Sutton, Cambridge Carbon Footprint** — a named person and the organisation they represent. |
| **Context** | "A key priority in making homes more energy efficient is to find and plug air draughts…" — the problem, in language a second-year needs no domain knowledge to follow. |
| **The build** | "A cheap and easy phone app could help the builder to setup and calibrate the equipment, then provide practical guidance to prioritise the most urgent repairs…" — what to make, without dictating how. |

Reading the published briefs is the best preparation for writing one — see the
[2026 design briefs](2026.md) and the
[2025](2025.md) and [2024](2024.md) sets.

## What makes a brief hard to work with

<div class="grid cards" markdown>

-   :material-alert: **A product backlog, not a project**

    ---

    A list of twelve features reads as a contract. Teams then spend Meeting 2
    negotiating it down, and finish feeling they failed. Describe one substantial
    challenge instead.

-   :material-lock: **Dependencies you can't actually clear**

    ---

    If the project needs data or system access that requires approval you don't
    control, the team can lose weeks. Either secure it before the brief goes out, or
    design the project so it isn't blocking.

-   :material-file-tree: **A prescribed architecture**

    ---

    Naming the framework, database and deployment target removes most of the design
    work — which is the part being assessed. Constrain only what genuinely has to be
    constrained.

-   :material-account-group: **A single indivisible problem**

    ---

    Every member must make a substantial technical contribution. A brief that is one
    tightly-coupled algorithm is hard to share out; one with distinguishable
    components is much easier.

</div>

## Sending your brief in

Send your project brief to
[group-project@cl.cam.ac.uk](mailto:group-project@cl.cam.ac.uk?subject=Part%20IB%20group%20project%20design%20brief).
