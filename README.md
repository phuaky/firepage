# fire page

A single HTML page that gets one drafted-but-unsent message **out the door**.

Not a template for writing the message. AI already writes a perfect draft in 3 seconds. The problem is the gap after that: the draft sits for days because sending it means understanding it well enough to stand behind it, and re-reading a wall of text never quite gets you there.

A fire page closes that gap. It's a one-screen memo where the verification is already done and stamped, the draft is copy-without-opening, your personal checks are a short bounded list, and the **last step is the send itself.**

**See it live:** [phuaky.github.io/firepage](https://phuaky.github.io/firepage/) — that's a real fire page, filled in.

Copy [`template.html`](template.html) to make your own.

## Why drafts don't get sent

The bottleneck was never the writing. It's that you won't put your name on something you can't defend — and reading back a wall of markdown or some ugly HTML dump doesn't get you to "I understand this." So the send waits. And waits.

The fix is to turn "ready" from a *state* into a *procedure*: a finite page whose steps you can only walk in one direction, ending in the message leaving the building.

## The six mechanisms

Every fire page does all six. Drop any one and the send stalls again.

1. **Verification pre-paid and stamped.** A header asserts everything is confirmed, with provenance (`verified Mar 14 · source: the thread`). Zero open questions on the page. You're not re-checking; you're reading a receipt.
2. **Re-reading structurally discouraged.** The draft lives in a collapsed `<details>` with a *copy-without-opening* button. You can't re-litigate what you never re-open.
3. **Every action mechanical, ≤5s.** A copy button per field. No decisions live on the page.
4. **Personal verification bounded.** A short finish checklist holding *only* what you alone can attest — tick a statement, hit send. Six items max.
5. **Finite, one screen, time-boxed.** "Ten minutes." The first step is trivially easy: a button that just opens the form or the inbox.
6. **External loop closure.** The last checkbox tells another person "fired." Completion gets a witness and a receipt, not just a feeling.

## How to use it

1. Draft the message however you like (any model, or by hand).
2. Copy `template.html`, fill the four blocks: the **stamp** (what you verified + where), the **draft** (paste it, leave it collapsed), the **what this is built on** table (each source and *why it matters*), and the **finish** list (ending in the send).
3. Open it in a browser. Walk it top to bottom. Don't re-open the draft.
4. Hit send. Tell someone.

The "what this is built on" table is the part that lets you stand behind it: every claim in the message traces to a named source, so if anyone asks *why you said that*, the answer is on the page — not "the AI wrote it."

## Design

One column, system fonts, two colors plus one accent, native `<details>`, one tiny script for the copy buttons. Document, not marketing page. Works in light and dark. Steal the CSS.

## License

MIT. Do whatever.
