# One-Screen Send Concept

A UI concept for an internal call center screen where an agent picks a topic
and sends the customer an SMS with an info link.

## The problem

In the current layout the agent scrolls through long vertical lists of topics,
and the customer fields sit far below the fold. During a live call that costs
time and causes wrong links to be sent.

## The idea

- Every topic fits on one screen as a compact tile, so no scrolling is needed.
- Topics are grouped into categories, sorted A–Z inside each group.
- Each category has its own shade of green, from light to dark, so related
  topics always look alike and sit together.
- A "Most used" row pins the topics sent most often.
- The left rail holds everything needed for one send: mobile number,
  account ID, first name, consent, the selected topic, a live phone preview
  and the send button.
- Works at full screen, half screen (split view) and on a phone.

## Try it

Open `index.html` in any browser. No build step and no dependencies.
Resize the window to see the split-screen and mobile layouts.

## Customizing

Everything editable is in the `EDIT HERE` block near the bottom of the file:

- `CATEGORIES` — column order and colors
- `EXPERIENCES` — the topic list
- `MOST_USED` — pinned topics
- `MESSAGES` — message wording per topic

## Note

This is a design concept only. Topic names and message text are samples.
Nothing is sent; the button is a mockup.
