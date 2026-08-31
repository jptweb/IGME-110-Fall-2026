<!--
  JP-ONLY BUILD NOTES. Invisible to students when transcluded into myCourses.

  This page fills in over two stages:

  STAGE 1: weekend of Sat Aug 29, after gruepr runs on the kickoff survey.
    - Team rosters for both sections
    - The review pairing tables (they only need the team COUNT, not any drafts)
    - Delete the "not posted yet" banner below
    - Post by MON AUG 31, before 2A on Tue Sep 1

  STAGE 2: weekend of Sat Sep 5, after the Work Plan comes in Fri Sep 4.
    - Product names and proposal doc URLs, harvested from the Work Plan submissions
      (that dropbox asks for two links: the work plan, and the proposal doc)
    - Delete the "links go up after the Work Plan" note in each section

  Nothing here is blocked on drafts. Reviewers need a URL, not a submission, and the
  proposal doc URL never changes. See 00-Course-Overview/P1-myCourses-Setup.md.

  TEAM BLOCK TEMPLATE, duplicate per team:

    ### Team N: *Product Name*

    **Proposal doc:** <url>

    - Firstname L.
    - Firstname L.

  FIRST NAME + LAST INITIAL ONLY, no usernames. This folder syncs to jptweb/IGME-110-Fall-2026, which is a PUBLIC repo,
  so names plus RIT usernames would be permanently indexed. Names alone are enough for a
  student to find their team. Decided 2026-08-30.

  PAIRING RULE: team N reviews N+1 and N+2, wrapping at the end. Generate once the
  team count is known. Fall 2025 used this and it worked.
-->

# Project 1 Teams: Fall 2026

Your team, the two teams you're reviewing in week 3, and everyone's proposal links.

If you're wondering how these were put together, there's an explanation further down: [How these teams were made](#how-these-teams-were-made).

**→ [Back to Project 1: Product Proposal](p1-product-proposal.md)**

---

## How to use this page

| Week | What you need from here |
|---|---|
| **2** | Find your team and your teammates' names |
| **3** | Find the two teams you're reviewing, and open their proposal docs |
| **3 to 5** | Nothing. You'll be working in your own team's document. |

You stay with this team through all five P1 deliverables.

**Proposal links appear after the Work Plan is due**, since that's the deliverable where each team
hands in the link to its proposal doc.

---

## Section 01 (Tue/Thu 2:00 to 3:15 PM)

*Teams posted Monday, August 31.*

<!-- STAGE 2: add the product name to each heading (### Team N: *Product Name*) and a
     **Proposal doc:** <url> line under it, harvested from the Work Plan submissions. -->

### Team 1

- Gavin B.
- Jake G.
- Adam P.
- Liam P.

### Team 2

- Gavin D.
- Rook P.
- Austin S.
- Saturn T.

### Team 3

- Joshua B.
- Kevyn C.
- Savannah C.
- Phoenix I.

### Team 4

- Maax D.
- Camilla F.
- Moyu W.
- Kevin Y.

### Team 5

- Jonas A.
- Massen H.
- Logan H.
- Charlie R.

### Team 6

- Alex H.
- Wren M.
- Alexa M.
- Antonio O.

### Team 7

- Liam L.
- Ayden N.
- Amalia R.
- Kumar W.

### Team 8

- Madison C.
- Delia C.
- Willow E.
- Kaedyn G.

### Who reviews whom

| Your team | You review |
|---|---|
| **Team 1** | Team 2 and Team 3 |
| **Team 2** | Team 3 and Team 4 |
| **Team 3** | Team 4 and Team 5 |
| **Team 4** | Team 5 and Team 6 |
| **Team 5** | Team 6 and Team 7 |
| **Team 6** | Team 7 and Team 8 |
| **Team 7** | Team 8 and Team 1 |
| **Team 8** | Team 1 and Team 2 |

---

## Section 07 (Tue/Thu 3:30 to 4:45 PM)

*Teams posted Monday, August 31.*

<!-- STAGE 2: add the product name to each heading and a **Proposal doc:** <url> line. -->

### Team 1

- Keon D.
- Kai E.
- Jaxon E.
- Ari K.

### Team 2

- Andres C.
- Joshua M.
- James T.
- Adrianna Z.

### Team 3

- Owen H.
- Xander K.
- Roark O.
- Andrew P.

### Team 4

- Evan J.
- Shea K.
- Evan L.
- Zee S.

### Team 5

- Kacey P.
- Izaiah R.
- Benjamin R.
- Matthew S.

### Team 6

- Charlie H.
- Isaac J.
- Declan M.
- Sage V.

### Team 7

- Angela C.
- Vivi C.
- Zhe W.

### Team 8

- Roger F.
- Ryan W.
- Sebastian Z.

### Who reviews whom

| Your team | You review |
|---|---|
| **Team 1** | Team 2 and Team 3 |
| **Team 2** | Team 3 and Team 4 |
| **Team 3** | Team 4 and Team 5 |
| **Team 4** | Team 5 and Team 6 |
| **Team 5** | Team 6 and Team 7 |
| **Team 6** | Team 7 and Team 8 |
| **Team 7** | Team 8 and Team 1 |
| **Team 8** | Team 1 and Team 2 |

---

## How these teams were made

Short version: a survey, a team formation algorithm, and a lot of checking by hand.

**The survey.** It asked four things: when you are free to meet outside class, how confident you
feel about research and about writing, what kind of product interests you, and who you want to
work with or avoid. 57 of you answered out of 62, which is about 92%. That response rate is the
single biggest reason these teams came out as well as they did, so thank you.

**The algorithm.** I ran the responses through gruepr, a tool built for this exact problem. It
weighs everything at once and looks for the arrangement that scores best overall. Shared free time
counts for the most, then your teammate requests, then a spread of confidence levels and interests
so that no team ends up all researchers or all writers.

**The checking.** An algorithm will hand you a result whether or not it is any good, so every team
was tested against four rules:

1. Everyone on the team shares at least one free hour outside of class.
2. Nobody is on a team with someone they asked to avoid.
3. Every team has at least one person confident about research.
4. Every team has at least one person confident about writing.

Teams that failed a rule got rebuilt. Where rebuilding could not fix it, I moved people by hand and
tested again. Each section took several full runs before it passed.

### Why you may not have gotten who you asked for

Almost every unfilled request comes down to one of these four things.

**Arithmetic.** Teams are four people. In one section, eight students named each other in a single
connected group. There is no way to split eight people into teams of four and give all of them
their picks, so some of those requests could not be filled no matter how the teams were drawn.
Smaller versions of this happened in both sections.

**One-way requests.** A lot of people named someone who did not name them back. I placed as many of
those as I could, but when two people request each other it is much easier to honor.

**Avoid requests take priority.** If someone asked not to be placed with you, I honored it, even
when that meant breaking up a group that would otherwise have worked. Those requests are private
and I do not discuss them.

**Answers I could not read cleanly.** Each section has two students who share a first name, so some
picks could have meant either person. A few responses listed the writer's own name in the avoid
box. Where an answer was unclear, I used the rest of that person's responses to make the best guess
I could.

### What I could not do

I could not give everyone their first choice, and I would rather say that plainly than pretend the
process was perfect. On most teams there is at least one person who is there because that is where
the numbers put them.

That is not a comment on anybody. What every team here does have is a meeting time that actually
works for all of its members, and a mix of strengths. Over five weeks, those two things matter more
than starting out with people you already knew.

---

## Questions about your team

**You review the teams in your own section**, not the other one.

If your team has a problem that you can't solve inside the team, tell me early. In week 2 or 3 there
is a lot I can do. In week 4 there is much less.

If somebody on your team has stopped responding entirely, don't absorb their work silently and don't
wait until the peer evaluation to mention it. Message me on Slack.
