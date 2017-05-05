About HTML Entities & Special Characters
======================
I frquently use these scripts to switch files from special characters to HTML and back. (I have another script that converts straight quotes to smart quotes, but that one is still rough.)

## Why did I write this?

I'm often hired to work in straight HTML—to fix quirks or outright convert something altogether. Web browsers can often change special characters on their own, but various applications of code work better with the characters in one form or the other. Like, an EPUB will be more universally compatible with the entities, but a book description for Amazon's electronic publishing arm should have the special character.

I also tend to code from scratch a lot. Having the script (and binding it to a keyboard command) lets me easily bounce between human-readable and cross-compatible, without a problem.

## Why would someone else want to use this?

If you intentionally format your text, using things like nonbreaking spaces to prevent line breakage where it shouldn't be for page layout reasons, this can be handy as a formatting check. Are nonbreaking spaces and hyphens used only where they should be? Convert them all to special characters and get a sense of their use at a glance.

The scripts also allow you to ensure that your HTML is **consistent** about what it uses. I pulled from the official list of entities on W3.org, so it's far more exhaustive than most entity lists. Make your entire document use whichever method it needs, with a single filter.

## Why is this available in PHP *and* Python?

Because some contexts make one or the other easier to use, and I figure it's good practice.
