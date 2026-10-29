# Project 3 Sample: Lo-Fi Prototype and Test Script

**→ [Back to Project 3](p3-prototype.md#2-lo-fi-prototype-and-test-script)**

> 🛑 **Do not copy this sample.** It shows the shape of a submission. It is not a form to fill in.
>
> Copying the [test script template](p3-test-script.md) is expected. Copying Meal Pro is not. Handing
> in its personas, tasks, screens, or wording as your team's work is plagiarism, an academic
> integrity violation under [RIT policy D08.0](https://www.rit.edu/policies/d080). That includes
> leftovers: a "Busy Brian" or an "Under 30 min" chip in your submission means it was copied.

This is deliverable 2 from a made-up team for a made-up app, to show how the parts fit together.
Your product, your personas, and your tasks will be your own.

> ⚠️ **The screens below are described in words so you can see what's on them. Yours have to be
> actual drawings**, on paper (best) or in Figma. A written description of a screen is not a lo-fi
> prototype.

Yours should look more like this: boxes, icons, and labels, one screen at a time, each with its name
written underneath.

<img src="https://people.rit.edu/~jxtadm/IGME110/note-photos/10b-paper-prototype.webp" alt="Hand-drawn paper prototype screens for a tablet app, spread across a table with two pens. Each sheet has two or three screens drawn in blue ink as simple boxes, icons and labels, and each screen has its name written underneath, like ‘set temp’ and ‘meeting with’." width="600">

---

## Background: the sample team

*Not part of your PDF. It's here so the sample's tasks make sense. Your PDF starts at Part 1.*

Meal Pro is a recipe and meal-planning app for college students. A team of three: Ana, Ben, and
Chris. Their personas from deliverable 1:

| Persona | Who | Owner |
|---|---|---|
| **Busy Brian** (main user) | 19, first year, rarely cooks, wants dinner in under 30 minutes | Ana |
| **Meal Prep Morgan** (power user) | 21, plans every week's meals on Sunday, watches what she spends | Ben |
| **Dietary Dana** (casual user) | 20, vegetarian, opens the app once or twice a week | Chris |

---

## Part 1: Screens

Six screens cover all three tasks. Each one is labeled with the tasks that use it.

In your PDF, this part is **photos of your drawn screens**, one per screen with its name written on
it. If you used Figma, export each frame instead. Home is drawn below the way yours should be. The rest are written out
so you can read them.

**Home** (tasks 1, 2, 3)

<img src="https://people.rit.edu/~jxtadm/IGME110/note-photos/10b-eatlikeking.png" alt="Hand-drawn Home screen for Meal Pro, in pencil. A menu icon and a profile icon at the top, a search bar asking what you want to cook, a banner with a drawn burger that says Eat like a King, a Featured Meals card for Pasta Bake with a 25 minute prep time, wavy lines standing in for text, and Home, Planner and Favorites tabs along the bottom." width="300">

The wavy lines stand in for text. That's all a lo-fi needs.

- Menu icon top left, profile icon top right
- Search bar: "What do you want to cook?"
- A banner: "Eat like a King!"
- A "Featured meals" card: picture box, meal name, prep time
- Bottom tabs: Home, Planner, Favorites

**Results** (tasks 1, 2)
- Filter chips across the top, including "Under 30 min"
- Recipe cards: picture box, name, cook time

**Recipe** (task 1)
- Name, cook time, Save button
- Ingredients, then steps

**Planner** (task 2)
- Monday to Sunday, one dinner slot each
- Empty slots say "+ Add"
- "Make grocery list" button at the bottom

**Grocery List** (task 2)
- Ingredients from every planned meal, combined, with checkboxes

**Food Preferences** (task 3)
- Switches: Vegetarian, Vegan, Gluten-free, Nut-free
- Save button

---

## Part 2: Test script

This is the [test script template](p3-test-script.md) with the team's ✏️ parts filled in, the way it
looks when they hand it in. The wrap-up, the fixed ask-afterward question, and the "What happened"
notes (filled in on test day) are left out here to keep it short.

- **Product:** Meal Pro
- **Section and team:** Section 01, Team 3
- **Facilitator:** Ana
- **Computer:** Ben
- **Scribe:** Chris
- **Tester's first name:** *(filled in on test day)*

### Before you start (Facilitator reads this out loud)

> Thanks for helping. We're testing our app, not you, so you can't do anything wrong. If something
> is confusing, that's exactly what we need to find out.
>
> This is a sketch, so nothing really works. Tap things with your finger, and Ben will show you what
> would happen.
>
> Please think out loud the whole time: what you're looking at, what you're looking for, and what
> you expect to happen. We can't help during the tasks, but we'll answer anything at the end.

### First look

Show the home screen. Don't explain it.

1. Looking at this screen, what do you think this app is for?
2. What would you tap first?

### Task 1: Find a quick dinner · Ana

**Read to the tester:** "You have 30 minutes before you need to leave for a club meeting, and
you're hungry. Find something you could make for dinner in that time."

**Expected path:** Home → Results (tap "Under 30 min") → Recipe

**Their ask-afterward question:** "When you tapped the Under 30 min chip, what did you expect to
happen?"

### Task 2: Plan two dinners and shop for them · Ben

**Read to the tester:** "It's Sunday. Plan dinners for Monday and Tuesday, then get one shopping
list that covers both."

**Expected path:** Home → Planner → "+ Add" Monday → Results → Planner → "+ Add" Tuesday → Results
→ Planner → Grocery List

**Their ask-afterward question:** "When you tapped + Add, what did you expect to see?"

### Task 3: Stop seeing meat · Chris

**Read to the tester:** "You don't eat meat, and you're tired of scrolling past chicken recipes.
Make the app stop showing them to you."

**Expected path:** Home → profile icon → Food Preferences (turn on Vegetarian, Save) → Home

**Their ask-afterward question:** "When you tapped the profile icon, what did you expect to see?"

### AI line

**AI use:** We used ChatGPT to come up with recipe names for the cards on the Results screen.
Nothing else.

---

## Why the tasks are written this way

None of them names a button. Task 3 doesn't even say "settings." If Dana can't work out that food
preferences live behind the profile icon, that isn't a bad tester. It's the most useful thing the
team will learn all day, and it becomes one of their three fixes.
