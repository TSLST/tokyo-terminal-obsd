- **2026-06-21T15:55+02:00**:<br>
Release Candidate *v1.5.10*
Rounded up more tokens and renderers for embedded code.
The toolbar items are left blue but the toolbar itself now has a solid background.
I am using quite a few workarounds to get where I wanted to and will only consider going to *1.6.0* if I solve them.
I expect a lot of oddities with keywords in language embeds but I barely use obsidian so and also some tokens are missing to get really where I want to. I still use VS Codium primarily for coding purposes.
I may release 1.5.11 if I find other minor discrepancies with my liking but this is already a good Release Candidate.
- **2026-09-10T17:47+02:00**:<br>
*v1.5.12* should be quite complete, I noticed that strong was not visually accented in block quotes so I just tweaked that with `cm-quote.cm-quote-1.cm-strong`.
- **2026-09-21T16:50+02:00**:<br>
I corrected the table headers to have text on accent applied and all thead row background accented (It was only 2n+2 = every other row, I changed it to n = all). I corrected the checkboxes colors and also the unrendered callout name to look fancier. HTML attribute are now correctly aligned with VS Code theme. I cannot change the in-code color of the attributes string to light green nor the color of the main text to cyan. Colors strong and italic unrendered are different to look smoother when writing in quote blocks; rendered are normal strong and italic colors. Also changed the weight of the highlights but would rather have changes the size of the font as well though I believe the whole line would be affected, so weight does the job.