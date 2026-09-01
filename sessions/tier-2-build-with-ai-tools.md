# Tier 2: Build a Real App with AI Tools

**Audience:** Participants who have chatted with an AI assistant but have never built an app. Comfortable with a browser and signing up for accounts; no coding assumed.

**Length:** 30 minutes of content + 10–15 minutes Q&A
**Format:** Live demo-driven, two browser windows visible the whole time.

## Session goal

By the end, every attendee knows the **two-window workflow**: develop your idea and business logic in a chat assistant, then hand a well-formed prompt to a build tool that generates a working app. They leave knowing which build tool fits their project and how not to waste their credits.

## The core workflow (teach this picture first)

```
Window 1: Chat assistant          Window 2: Build tool
(ChatGPT / Claude)                (Lovable for web, Rork for mobile)

 Talk through your idea    ──►    Paste the build prompt
 Refine the business logic ──►    Watch it generate the app
 Ask "what should change?" ──►    Request one change at a time
```

The chat window is where thinking happens. The build window is where building happens. Keeping them separate is the #1 credit-saver: build tools charge credits per message, so don't brainstorm inside them.

## Outline

### 1. Pick your build tool (4 min)

- **Web app** (works on phones too): **Lovable**. For a hackathon, a mobile-friendly web app is almost always enough — tell it to make the design responsive.
- **True mobile app:** **Rork** — it's essentially Lovable for Expo/React Native. Choose this only if a native mobile experience is the point of your idea.
- Either way, the workflow is identical.
- Note on "what about the App Store?": you won't ship to an app store this weekend, and judges don't expect you to.

### 2. Live demo, part 1 — shape the idea in chat (10 min)

With a pillar-relevant example idea:

1. Describe the idea and audience to the chat assistant.
2. Work out the core logic: what does the app do, for whom, what are the 2–3 essential screens? Cut everything else — small scope finishes; big scope doesn't.
3. The key move — ask for the handoff artifact: *"Write a single detailed prompt I can paste into Lovable to build the first version of this app. Include the screens, the data it tracks, and the look and feel."*

### 3. Live demo, part 2 — build it (8 min)

1. Paste the generated prompt into Lovable. Let it build while you talk.
2. Show the iteration loop: one specific change per message ("make the submit button save to the list", not "make it better").
3. When something breaks or looks wrong: go back to Window 1, describe the problem, ask how to phrase the fix — then spend one build-tool message on it.
4. Show how to share/preview the running app — that link is your demo.

### 4. Credits, pitfalls, and the weekend plan (5 min)

- Credits are limited (see `../resources/tools-and-credits.md`). Chat is cheap or free; build-tool messages are the scarce resource. Budget them.
- Classic failure from last year: a participant used up their Lovable credits *chatting* with it about the idea. Don't chat in the build tool.
- Start smaller than you want to. A finished small app beats an unfinished big one — last year only 17 of ~30 teams finished.
- Coaches are around all weekend for debugging and "I'm stuck" moments. That includes helping you re-scope.

### Q&A (10–15 min)

Be ready for: "Can I export the code?" (yes, both tools can — a coach can help), "Can my whole team work in one Lovable project?" (workshop briefly; one driver + teammates in the chat window works well), "What if I actually know some code?" (great — you can eject to the Tier 3 resources any time).

## Facilitator notes

- Rehearse the demo idea once, but let the live run be imperfect — recovery is the lesson.
- Have the handoff-prompt move ("ask chat to write the Lovable prompt") on a slide or handout; it's the single highest-value takeaway.
- Watch for people who are actually Tier 1 (lost at "sign up for an account") — pair them with a coach rather than letting them sink.
