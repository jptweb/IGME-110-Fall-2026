# Project 3 Sample: Lo-Fi Prototype and Test Script

**→ [Back to Project 3](p3-prototype.md#2-lo-fi-prototype-and-test-script)**

This is deliverable 2 from a made-up team for a made-up app, to show how the parts fit together.
Your product, your personas, and your tasks will be your own.

> ⚠️ **The screens below are described in words so you can see what's on them. Yours have to be
> actual drawings**, on paper or on screen. A written description of a screen is not a lo-fi
> prototype.

---

## The app: MealMate

A recipe and meal-planning app for college students. A team of three: Ana, Ben, and Chris. Their
personas from deliverable 1:

| Persona | Who | Owner |
|---|---|---|
| **Busy Brian** (main user) | 19, first year, rarely cooks, wants dinner in under 30 minutes | Ana |
| **Meal Prep Morgan** (power user) | 21, plans every week's meals on Sunday, watches what she spends | Ben |
| **Dietary Dana** (casual user) | 20, vegetarian, opens the app once or twice a week | Chris |

---

## Part 1: Screens

Six screens cover all three tasks. Each one is labeled with the tasks that use it.

**Home** (tasks 1, 2, 3)
- Search bar: "What do you want to cook?"
- Profile icon, top right
- Bottom tabs: Home, Planner, Favorites
- A "Quick dinners" row

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

## Part 2: Test tasks

The rest of the script (the opening, the first-look questions, the wrap-up) is filled in exactly as
the template has it. These are the three tasks.

### Task 1: Find a quick dinner · Ana

**Read to the tester:** "You have 30 minutes before you need to leave for a club meeting, and
you're hungry. Find something you could make for dinner in that time."

**Expected path:** Home → Results (tap "Under 30 min") → Recipe

**Ask afterward, question 3:** "When you tapped the Under 30 min chip, what did you expect to
happen?"

### Task 2: Plan two dinners and shop for them · Ben

**Read to the tester:** "It's Sunday. Plan dinners for Monday and Tuesday, then get one shopping
list that covers both."

**Expected path:** Home → Planner → "+ Add" Monday → Results → Planner → "+ Add" Tuesday → Results
→ Planner → Grocery List

**Ask afterward, question 3:** "When you tapped + Add, what did you expect to see?"

### Task 3: Stop seeing meat · Chris

**Read to the tester:** "You don't eat meat, and you're tired of scrolling past chicken recipes.
Make the app stop showing them to you."

**Expected path:** Home → profile icon → Food Preferences (turn on Vegetarian, Save) → Home

**Ask afterward, question 3:** "Where did you expect to find that setting?"

---

## Why the tasks are written this way

None of them names a button. Task 3 doesn't even say "settings." If Dana can't work out that food
preferences live behind the profile icon, that isn't a bad tester. It's the most useful thing the
team will learn all day, and it becomes one of their three fixes.
