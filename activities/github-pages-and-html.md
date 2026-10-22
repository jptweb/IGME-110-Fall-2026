# Activity: GitHub Pages & HTML

**IGME-110 | On your own | Makeup or extra credit | 10 points**

In Week 4 you made a GitHub repository and wrote markdown in it. This time you make a website.

This is a first look at HTML, not a web development course. You get that properly in IGME-235.
The point here is that the gap between "a file on my computer" and "a page anyone on the
internet can open" turns out to be about fifteen minutes, and knowing that changes what you
think you're allowed to build.

**There's no class day for this one.** You do it on your own time, and it counts one of two ways:

- **If you're missing an in-class activity,** this fills that gap.
- **If you're not,** it's extra credit.

Same work and same 10 points either way. It covers one missed activity, not several.

> ⚠️ **Spend about an hour and hand in what you have, finished or not.** Some of you have built
> whole websites. Some of you have never unzipped a file. Both are completely normal in a first
> year course. I'm looking for honest effort, not perfection, and everything below is written so
> you can do it without having seen any HTML before.

## What you'll need

- **A GitHub account.** If you did Markdown and GitHub in Week 4, you have one. If not, follow
  [the account steps from that activity](https://github.com/jptweb/IGME-110-Fall-2026/blob/main/activities/markdown-and-github.md#before-class-on-thursday)
  first.
- **A verified email address on that account.** Check it on GitHub: your profile picture, then
  **Settings**, then **Emails**. GitHub won't publish a website for an account with an unverified
  email, and it doesn't tell you that's the reason.
- **VS Code** ([download it here](https://code.visualstudio.com/)). It's on the lab machines. Any
  plain text editor works. Word and Google Docs don't, because they add formatting that breaks HTML.
- **The starter files:** [first-html-pages.zip](https://github.com/jptweb/IGME-110-Fall-2026/raw/main/activities/_files/first-html-pages.zip)

## How to read HTML

You already know markdown, so start there. HTML does the same jobs with more typing:

| You want | Markdown | HTML |
|---|---|---|
| A big heading | `# Tacos` | `<h1>Tacos</h1>` |
| A bulleted list item | `- Salsa` | `<li>Salsa</li>`, inside a `<ul>` |
| A link | `[RIT](https://www.rit.edu)` | `<a href="https://www.rit.edu">RIT</a>` |
| Bold | `**hot**` | `<b>hot</b>` |
| An image | `![a taco](taco.jpeg)` | `<img src="taco.jpeg" alt="a taco">` |

Four ideas cover almost everything in this activity:

1. **Tags come in pairs.** `<h1>` opens, `</h1>` closes (note the slash), and whatever is between
   them is the heading. A few tags, like `<img>` and `<br>`, stand alone because there's nothing
   to put inside them.
2. **Tags nest like boxes.** List items go inside a list. Everything you can see goes inside
   `<body>`. Close the inner box before the outer one.
3. **The `<head>` is about the page. The `<body>` is the page.** The `<title>` in the head is the
   text on the browser tab.
4. **Attributes add details to an opening tag.** In `<a href="https://www.rit.edu">`, `href` is the
   attribute and the address is its value. They always look like `name="value"`.

Indenting doesn't matter to the browser. It matters a lot to you when you're hunting for the tag
you forgot to close.

Want more than this? MDN's [Creating the content](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content)
is a good free walkthrough.

## Get set up

1. **Download and unzip** `first-html-pages.zip`.
   - **Mac:** double-click it.
   - **Windows:** right-click it and choose **Extract All**. Don't just double-click. Windows will
     show you the files inside the zip and even let you open them, but anything you save in there
     disappears.
2. **Open the folder in VS Code:** File, then **Open Folder…**, then choose `first-html-pages`.
3. **Open `minimal.html` in your browser** by double-clicking it in Finder or File Explorer, or by
   dragging it onto a Chrome window.

Here's the loop you'll use for the whole activity:

> **Change it in VS Code. Save (Cmd+S or Ctrl+S). Refresh the browser.**

If nothing changed, you probably didn't save. VS Code puts a dot on the tab of any file with
unsaved changes.

## Part 1: Four small pages

Each file adds one new idea. Read the note, make the changes, check it in the browser.

### minimal.html

**New here:** the bare minimum a page needs. Find the `<head>`, the `<body>`, and the list. The
two lines that explain themselves are **comments**: notes for whoever reads the file next, which
the browser skips.

Change:

- The title to `My GitHub Pages Site`
- The heading to `My schedule for Fall 2026`
- The three colors to the courses you're taking this semester, one per `<li>`
- The numbered list to a bulleted one. `<ol>` means ordered (numbered) and `<ul>` means
  unordered (bullets). Change the opening tag **and** the closing tag.

**Check:** the browser tab says My GitHub Pages Site, and your courses show up with bullets.

### links.html

**New here:** links. Also the lines at the top (`<!DOCTYPE html>` and the `<meta>` tags), which
every real web page starts with. You don't need to memorize them. Copy them when you need them.

Notice the two kinds of link. The Wikipedia ones start with `https://` because they go somewhere
else on the internet. The three at the bottom are just file names, like `tacos.html`, because
those files are sitting in the same folder. Remember that. Your home page will use it.

Change:

- Make the two Wikipedia links open in a new tab. Add `target="_blank"` to each of their opening
  `<a>` tags, after the `href`, with a space in between: `<a href="..." target="_blank">`

**Check:** clicking Tacos opens a new tab, and the three links at the bottom open your other pages.

### tacos.html

**New here:** an image, and **CSS**, which controls how things look. The CSS lives inside the
`<style>` tag at the top, and every rule has the same shape:

```css
h2 {
  color: #d1633c;
}
```

Read that as *every `h2` gets this color*. The part before the curly brace says which tags the
rule applies to. That's the **selector**. Inside are `property: value;` pairs, each ending in a
semicolon.

`#d1633c` is a hex color code. Browsers also know about 140 color names, like `tomato`, `gold`,
and `lightseagreen`. [Here's the full list.](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/named-color)

Change:

- The page background to a color **name** from that list. Find the `body` rule and change its
  `background-color` value.
- All paragraph text to a color name. There's no rule for paragraphs yet, so write one: copy the
  whole `h2 { ... }` rule, change `h2` to `p`, and change the color.
- Wrap the heading in a `<header>`. Type `<header>` on the line before `<h1>` and `</header>` on
  the line after it. Then give `header` a rule of its own and style it. A background color and
  `padding: 20px;` is a good start.

**Check:** the taco picture shows, and so do your colors. If the picture is broken, the `images`
folder isn't next to `tacos.html` anymore.

### dice-roller.html

**New here:** JavaScript, inside the `<script>` tag at the bottom. It's what makes a page *do*
something. You don't need to understand every line. You need to spot the pattern.

Every die is three matching pieces:

| Piece | Where it lives | The D20's version |
|---|---|---|
| A button with an `id` | the HTML | `<button id="btn20">D20</button>` |
| A color rule for that `id` | the `<style>` tag | `#btn20 { background-color: #f44336; }` |
| A click handler that rolls it | the `<script>` tag | `btn20.onclick = function(){ showRandomInt(1, 20); };` |

Change:

- Add a **D4, D8, D12, and D100**. For each one, copy all three D20 pieces and change the `id` and
  the number. The `id` has to match exactly in all three places, capital letters included.
- Give every button its own background color. In CSS, a `#` in front of a name means "the tag with
  this `id`."

**Optional, not graded:** keep a history of rolls, newest on top, and add a Clear History button.
Hint: look at what `numberSpan.innerHTML = number;` does, and think about adding to it instead of
replacing it.

**Check:** every button rolls a number in its range. If one does nothing, its `id` doesn't match
between the button and the script.

## Part 2: Put it on the internet

### Make your home page

When someone visits a website without naming a page, they get `index.html`. You need one.

1. In VS Code, open `minimal.html` and copy everything in it (Cmd+A then Cmd+C on a Mac, Ctrl+A
   then Ctrl+C on Windows).
2. Make a new file. Hover over the folder name in VS Code's left sidebar, click the **New File**
   icon, and type `index.html`. Do this in VS Code rather than File Explorer: Windows hides file
   extensions, and it's easy to end up with a file secretly named `index.html.html`.
3. Paste, and save.

Now add two things to `index.html`, below your course list:

- **At least five links on a theme,** written in HTML, in a list, with an `<h2>` heading above
  them. If you made a listicle in Week 4, use those links. If you didn't, pick any theme you'd be
  comfortable showing a professor. Each link looks like this:

  ```html
  <li><a href="https://boardgamegeek.com/">BoardGameGeek</a></li>
  ```

- **Links to your four practice pages,** so someone landing on your site can reach them. The
  bottom of `links.html` already has three. Copy those over and add one for `links.html` itself.

**Check:** open `index.html` in your browser and click every link.

### Make the repository

1. On GitHub, click the **+** in the top right, then **New repository**.
2. Name it **exactly** `yourusername.github.io`, all lowercase, using your GitHub username (not
   your real name). If your username is `JaneDoe42`, the repository is `janedoe42.github.io`. That
   name is what makes it a website.
3. Make it **Public**.
4. Turn on **Add README**.
5. Click **Create repository**.

### Upload your files

1. In your new repository, click **Add file**, then **Upload files**.
2. Open your `first-html-pages` folder in Finder or File Explorer. Select **everything inside it**
   (Cmd+A or Ctrl+A) and drag it all onto the GitHub page.
   - **Drag what's inside the folder, not the folder itself.** If you drag the folder, everything
     lands one level down and the site can't find your `index.html`.
   - **Drag rather than clicking "choose your files."** The file picker can't upload the `images`
     folder, and `tacos.html` needs it.
3. Click **Commit changes**.

**Check:** your repository's main page lists `index.html`, the four practice pages, and the
`images` folder, all at the top level next to `README.md`.

### Turn on GitHub Pages

This is the step people get stuck on, so go slowly.

1. In your repository, click the **Settings** tab. It has a gear icon and sits in the same row as
   **Code** and **Issues**. This is not the Settings in your profile menu, which is a different
   page. If you can't see the tab, it's under the **⋯** menu.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Under **Branch**, choose **main**, leave the folder as **/ (root)**, and click **Save**.
5. Wait a minute or two and reload the page. When the site is ready, the top of this page says
   your site is live and shows a **Visit site** button.

GitHub moves these settings around now and then. If a label doesn't match, look for **Pages** in
the sidebar and the word **Source**.

**To watch it build,** open the **Actions** tab. A yellow dot means it's working, a green check
means it's done, and a red X means something failed. Screenshot a red X and send it to me.

### Check it

Go to `https://yourusername.github.io/`. Click every link, open all four practice pages, and roll
some dice.

## Stuck?

| What you see | What's usually wrong |
|---|---|
| **404:** "There isn't a GitHub Pages site here" | Give it ten minutes first. Then check three things: the repository name matches your username exactly, Pages is turned on, and your email is verified. |
| **Your README shows up instead of your page** | `index.html` isn't at the top level. It's inside a folder, or it's named `Index.html` or `index.html.html`. |
| **The taco picture works on your computer but not online** | The `images` folder didn't upload, or the capitalization is different. Your computer treats `Taco.jpeg` and `taco.jpeg` as the same file. GitHub Pages doesn't. |
| **You fixed something but the site didn't change** | Changes on your computer don't go online by themselves. Upload the changed file again (the same name replaces the old one) and commit. Wait a minute, then hard refresh with Cmd+Shift+R or Ctrl+Shift+R. |

Still stuck after twenty minutes? Post a screenshot in `#110-general` or message me on Slack.

## What to hand in

**The address of your website:** `https://yourusername.github.io/`

Paste it into myCourses. There's nothing to upload. Make sure it's the `.github.io` address and
not the `github.com/...` address of your repository. They look alike, and only one of them is the
website.

**If your site won't publish** and you've been through the Stuck list, hand in your repository's
address instead and say so. I can still see your files and grade the work in them. Publishing is
one part of the grade, not all of it.

## AI Expectations

**Use it to get unstuck.** Asking an AI assistant "why is my image broken" or "what does `target`
do on a link" is exactly the kind of question it's good at.

**Type the changes yourself.** Don't paste in finished files. The whole point is seeing what each
change does, and pasting skips that part.

If you used AI, add a line at the bottom of `index.html` saying which tool and what for:

```html
<p>AI use: ChatGPT, to figure out why my D100 button didn't work.</p>
```

## Why this matters

- **That address is yours.** `yourusername.github.io` stays up as long as your GitHub account
  does. When you need a portfolio, you already have somewhere to put it.
- **IGME-235 starts here.** You get HTML, CSS, and JavaScript properly there, and you'll walk in
  having already published a page.
