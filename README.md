# CAU Faculty and Staff AI Workshop

The website for Dr. Dewayne A. Dixon's Fall 2026 AI workshop at Clark Atlanta University.

**Live site:** https://drdixon24.github.io/cau-ai-workshop/

## Sessions

- Workshop, Friday September 18, 1:00 PM
- Follow-up, Thursday October 15, 12:30 PM
- McPheeters-Dennis Hall, Room 150B

## October 15 materials

The follow-up session ("Leave with a rubric you trust") has its own section at the top of the page (`#oct15`) and a group in Session materials:

- `materials/Oct15-Take-Home-Packet.pdf` (six-page take-home guide)
- `materials/Oct15-Practice-Grading-Sheet.pdf` ("You vs. the AI" sheet; answers rewritten so no student can be identified)
- `materials/Oct15-Flyer.pdf`
- The five Oct 15 prompts are in `const PROMPTS` with the category `oct15`, which is the default filter.

Questions go to ddixon1@cau.edu, linked in the header, the Oct 15 section, Session materials, the presenter card, and the footer.

## How to post slides or handouts

1. Put the PDF in the `materials` folder.
2. In `index.html`, find the "Session materials" section.
3. Change the dashed "pending" card for that session into a normal card with an "Open PDF" button. The flyer card shows the pattern.
4. Commit and push. GitHub Pages updates in about a minute.

## How to add a prompt starter

In `index.html`, find `const PROMPTS` near the bottom and copy one entry. Use `oct15`, `workshop`, `teaching`, or `office` for the category. Words in [brackets] show up in red for people to replace.
