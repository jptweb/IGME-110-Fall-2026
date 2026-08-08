# Activity: Markdown and GitHub

**IGME-110 | Week 4B | In-Class Activity | 10 points**

Markdown is how you write anything technical: documentation, READMEs, issues, notes, half the
tools you will touch in the next four years. Every weekly note in this course is a markdown
file. It takes about twenty minutes to learn and then you use it constantly.

GitHub is where that writing lives. IGME-235 assumes you have used it. Today is so that
assumption is true.

**We do this in class. It closes tonight.**

> ⚠️ **Read this before you panic.** Some of you have shipped a website. Some of you have never
> made a GitHub account. Both are completely normal in a first year course and neither one is a
> problem. **I am looking for honest effort, not perfection.** Spend the period on it, hand in
> whatever you have at the end, and ask me questions while I'm standing right there.

## Before class on Thursday

**Make a GitHub account if you don't have one.** This is the only part that has to happen
outside class, because account creation and two-factor setup can eat twenty minutes and I would
rather spend those twenty minutes on markdown.

1. Sign up at [github.com](https://github.com/). Use your RIT email address.
2. **Pick a username you would be comfortable putting on a resume.** You will have this account
   for a long time. This is not the moment for a username from middle school.
3. Set up two-factor authentication. GitHub requires it. Duo works, and so does any
   authenticator app.
4. Apply for the [student developer pack](https://github.com/education), which is free and gets
   you unlimited private repositories plus a pile of other tools.

If you already have an account, you are done with this part. Bring the login.

## Part A: make a repository

1. Click the **+** in the top right, then **New repository**
2. Name it `IGME-110-Repo`
3. Make it **Public**
4. Check the box to add a README file
5. Click **Create repository**

You now have a repository, which is just a folder with a history.

## Part B: learn the syntax in the README

Open `README.md` and click the pencil icon to edit it. Practice in here. It's yours and nothing
depends on it.

References, in increasing order of detail:

- [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)
- [Basic syntax guide](https://www.markdownguide.org/basic-syntax/)
- [Interactive tutorial](https://www.markdowntutorial.com/)

Things to get working before you move on:

- A level 1 and a level 2 heading
- A horizontal rule
- An ordered list and an unordered list
- A link to RIT's home page
- The same link again, but with the word **RIT** as the clickable text
- An image, using a URL from the web
- Bold and italic text

Click **Commit changes** when you want to save. Every commit is a save point you can go back
to, which is the whole reason this system exists.

**Try the Preview tab** while you edit. Markdown is plain text on the left and formatted text on
the right, and watching those two stay in sync is the fastest way to understand what it actually
is.

## Part C: make a listicle

A listicle is a list of links on a theme, useful or interesting to somebody else. Two real
examples:

- [public-api-lists](https://github.com/public-api-lists/public-api-lists)
- [leereilly/games](https://github.com/leereilly/games)

**In your repository, create a new file named `my-listicle.md`.** Use the **Add file → Create new
file** button.

Pick any theme you like, as long as it's something you would show a professor. Board games,
places to eat near campus, tools for a hobby, artists, generative AI resources, horror movies,
mechanical keyboards. Something you actually care about, because you'll be looking at it for a
while and a bored list is obvious.

**Requirements:**

- A level 1 heading and at least one level 2 heading
- A list of at least **five clickable links**
- Some bold text
- At least **two images**
- At least **five emoji** ([reference list](https://gist.github.com/rxaviers/7360908))

Commit it when you're done.

## What to hand in

**The URL of your `my-listicle.md` file on GitHub.** Navigate to the file in your browser and
copy what's in the address bar. It looks like:

```
https://github.com/yourusername/IGME-110-Repo/blob/main/my-listicle.md
```

Paste that into myCourses. There is nothing to upload.

If your repository is private, I can't open it, and a link I can't open counts as not handed in.
Make sure it's public.

## AI Expectations

**Use it if you want, for this one.** Asking an AI assistant "how do I make a table in markdown"
is exactly the kind of question it's good at, and it's what you would do at a job.

Two things, though. **Type the syntax yourself rather than pasting a finished file**, because
twenty minutes of typing is what makes the syntax stick and pasting teaches you nothing. And if
you used AI, add a line at the bottom of your listicle saying which tool and what for.

## Why this matters

- **Markdown transfers.** READMEs, documentation, issues, pull requests, Discord, Reddit,
  Obsidian, most note apps. Learn it once.
- **IGME-235 assumes you have a GitHub account** and can put files in a repository. So do 330,
  430, and most internships.
- **A public repository is a portfolio you didn't have to build.** People do look.
- **Commits are a safety net.** Version control is the reason nobody in this field has a folder
  full of `final_v2_FINAL_real.psd`.

You will do the serious version of this in 235. Today is the part where it stops being scary.
