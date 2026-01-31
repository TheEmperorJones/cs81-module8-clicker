# REFLECTION on *cookieClicker.js*

## What helped you understand DOM interaction best?

- It was very incremental, but just iterating on what was working and what wasn't proved to be the most helpful.  I would expect something to appear, but when it did not, I realized I had not added a `document.getElementById` entry in the code, for example.  So I would add it, and presto, it would appear in my Live Server preview, because I had actually planned properly for a <div> for it.  Similarly, I managed to keep a result reporting `.innerText` out of the function which needed to call it, and it would not work.  This was a humbling, slow process over all.

## How did you choose your milestone messages?
- I choose them expressly from the suggested milestone initially, but switched things up and added messages that were way over the top, and verging on abusive, but softened by being delivered in a somewhat Victorian register.

## What challenge or bug surprised you?
- The most challenging element was recollecting all that I had used before, pulling it together in concert.  And it was the little conceptual details that tripped me up, formatting and proper syntax and so forth.

## What personal twist did you add?
- A very minor twist I added was defaulting the milestone div to a sort of visual joke about the fortune cookie emoji being used.  After the first few clicks, it says "I see a lot of cookies in your future ..." until the 5th click hits, and then it is blank until the first actual milestone is called at `i = 10`.

## What real-world app uses this kind of interaction?
- Virtually all e-commerce relies on click events updating visually on a page.  Even RCE's at their core have similar functionality, using icons to call functions that  arrange text strings and mark them up.  Arguably, on the web, almost all but the most sparsely designed (and studiously non-updated) websites benefit from JavaScript relating to HTML via the DOM (or BOM).
