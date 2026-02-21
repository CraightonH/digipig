---
stepsCompleted: [1, 2, 3, 4]
inputDocuments: [README.md]
session_topic: 'DigiPig — simulated-money banking app for kids with NFC cards and parent management'
session_goals: '1. Give kids experience with modern banking before using real money. 2. Help parents manage kids simulated accounts (balances, transactions).'
selected_approach: 'ai-recommended'
techniques_used: ['Role Playing', 'What If Scenarios', 'SCAMPER Method']
ideas_generated: [50]
session_active: false
workflow_completed: true
---

# DigiPig Brainstorming Session

**Date:** 2026-02-20

---

## Session Overview

**Topic:** DigiPig — a simulated-money banking app for kids with NFC cards and parent management
**Goals:**
1. Give kids experience with modern banking before using real money
2. Help parents manage kids' simulated accounts (balances, transactions)

**Context:** Kids get real-feeling NFC cards they can hold and tap. Currency = "oinks." Multi-account support. All simulated. The physical card is not an enhancement — it IS the product. Without it, DigiPig is a paper ledger and kids feel disconnected from their finances.

**Techniques:** Role Playing → What If Scenarios → SCAMPER Method
**Total Ideas Generated:** 50

---

## Complete Idea Inventory

### Theme 1: Child UX & Emotional Interface
*The pig as emotional translator — state over numbers, always.*

1. **First Tap Confusion** — A child's instinctive reaction to the card is bewilderment. The card needs to teach without words. Onboarding must assume zero banking context.
2. **Balance Blindness** — Numbers mean nothing to young kids without context. Replace numeric balance with visual pig fullness — full, half-full, empty. No number required to feel rich or broke.
3. **The Delight Hook** — The pig animation is the moment connection happens. The character is the interface, not the menus. Pig = hungry (spend), sleeping (savings locked), excited (just got paid).
4. **Consequence Blindness** — Spending doesn't feel real without visible state change. The pig gets thinner, sadder, or hungrier as balance drops. Spending is watching your pig suffer, not decrementing a number.
5. **Pre-Spend Preview** — Before confirming a purchase, show Mia what her pig will look like after. Before/after of pig state teaches cost as felt experience, not arithmetic.
6. **The Empty Pig Moment** — When the pig is empty, it's dramatic and memorable — not just "0 oinks." The pig is visually destitute. Being broke is a character experience, not a database state.
7. **Pig as Ambient Balance Display** — On the physical pig terminal, the display passively shows pig emotional state (not a number). Sitting on Mia's desk, she knows how her finances feel without opening any app.
8. **Pig State is Private** — No social layer, no leaderboards, no peer comparison. Financial state is visible only to Mia and David. The absence of social features is itself a financial literacy lesson — adults don't share balances with friends.

---

### Theme 2: Physical Pig Terminal
*Hardware decisions that need to be made early — cheap to include at manufacturing, expensive to retrofit.*

9. **The Physical Pig Terminal** — A 3D-printed piggy bank with embedded NFC reader and small display. Mia taps her card to the pig itself, not a phone. The pig reads the card, confirms transactions, shows state. The pig IS Mia's terminal.
10. **Platform Split by Persona** — Pig = Mia's device. App/web = David's device. Different interfaces, not just different permissions. Ground-up split optimized for two completely different users and needs.
11. **Interaction Jingles** — The physical pig plays short audio cues on key interactions — deposit sound, spend sound, broke sound, goal-reached fanfare. Borrowed from Yoto's NFC-audio pairing without becoming a media device.
12. **Hardware Audio as Infrastructure** — Speaker + audio chip is cheap at manufacturing time, expensive to retrofit. Decide now even if the jingle library starts small. Ship the speaker, polish the jingles over time.
13. **Dual-Mode Piggy Bank** — The pig terminal has a physical coin/bill slot alongside the NFC reader. Real cash and oinks live in the same object. Mia's single artifact for all her money — real and simulated.
14. **The Hatch** — A physical door on the pig's bottom or belly for accessing real cash. No destruction required. The pig is permanent, the money is accessible, the object has longevity. Eliminates "destroy to access" psychology.
15. **Lost Card Inconvenience** — Losing the NFC card means losing account access until David issues a replacement. Mia can see her balance but can't transact. Mirrors adult card loss exactly — temporary, inconvenient, her responsibility.
16. **Card Replacement Ritual** — David issues a new card through the app — possibly with a small oink fee or waiting period. The process of replacing a lost card is itself a financial literacy moment.

---

### Theme 3: Account Structure & Card Portfolio
*Cards as physical progression — one per account, unlocked with maturity. Core v1 functionality.*

17. **Card-Per-Account Physical Layer** — Each account type gets a distinct physical NFC card. Checking (spend freely), savings (restricted access). The physical card IS the account in Mia's mind. Portfolio grows as understanding matures.
18. **The Credit Card as Milestone** — Credit isn't available from day one. David unlocks it when Mia demonstrates readiness — saved consistently, understands debt, reaches an age threshold. The unlock is a genuine milestone conversation.
19. **Credit Consequences in Miniature** — Credit balance Mia can't repay puts her pig in "debt mode" — visually distinct, red-tinted, clearly stressed. David gets a conversation trigger. The emotional cost of debt at age-appropriate scale.
20. **The Savings Withdrawal Ritual** — Withdrawing from savings isn't a tap — it's a request. Mia initiates ("I want to buy X"), David gets notified with her reason, approves or opens a conversation. The friction is the feature.
21. **The Sacred Account Mental Model** — Savings oinks are visually, physically, and experientially heavier than checking oinks. Different card, different pig state, different withdrawal UX. Mia internalizes the distinction before she can articulate it.
22. **David's Counter-Offer** — When Mia requests a savings withdrawal, David can approve, deny, or counter ("Wait 3 more days and I'll match it"). The negotiation IS the lesson — delayed gratification and discussion of big purchases.
23. **Debit Decline as Reality Check** — Checking account declines at zero by default. No overdraft. The card just doesn't work. The decline is the lesson — identical to how a real debit card behaves. Self-evident consequence, no app lecture needed.
24. **Overdraft as Opt-In Lesson** — David can enable overdraft on checking. Mia can go negative, pig enters visible distress, David gets a conversation trigger. For parents who want Mia to experience debt mechanics before she has a credit card.
25. **Multiple Named Savings Goals** — Mia can run several savings goals simultaneously — each named, each with its own thermometer, each funded deliberately from checking. She allocates oinks across competing goals, learning prioritization naturally.

---

### Theme 4: Earning & Parenting Philosophy
*App reflects the parent's philosophy — no single model enforced.*

26. **Flexible Pay Model** — DigiPig doesn't assume allowance. David chooses his model: scheduled allowance, chore-conditional deposit, or on-demand job payment. App supports all three without moralizing about which is correct.
27. **Job Board** — David posts available jobs with an oink value. Mia browses, claims one, completes it, checks in for payment. Mia learns that different work has different value and that she has agency to choose what she takes on.
28. **The Paycheck Moment** — When David pays Mia for a job, it's a ceremony — not a background transaction. Mia's pig reacts, deposit animation plays, oinks visibly fill the account. Work → pay loop is unmistakable and felt.
29. **Optional Punishment Mechanic** — David can opt into deduction-as-consequence — fine Mia for broken rules or behavior. Not enforced by the app, not required, just available. Two sides of the same behavioral economy: positive earning and negative consequence.
30. **Admin Override** — David can always directly edit any balance, issue corrections, reverse transactions. He's the central bank. Structured mechanics are conveniences, not constraints on his authority.

---

### Theme 5: Parent as Teacher-Coach
*David's surface: behavioral signals, conversation triggers, coaching tools.*

31. **The Teacher Dashboard** — David's view is a behavioral report card, not a transaction ledger. Did Mia save this week? Did she hesitate before spending? Did she ask about her balance? These signals tell David if the lesson is landing.
32. **Proof-of-Learning Milestones** — Four key behaviors become visible in-app milestones: asks about balance unprompted, saves toward a goal, feels genuinely broke, explains oinks to a friend. "Mia saved for 3 days in a row." "Mia checked her balance twice before spending."
33. **The Engagement Validity Crisis** — David's core fear: is the simulation creating genuine value internalization or just compliance theater? The app needs learning signals to reassure skeptical parents that it's working.
34. **Teachable Moment Capture** — When Mia hesitates before a purchase or chooses to save instead of spend, David gets a notification. Not what she did — how she thought. Behavioral signals, not just transaction logs.
35. **The Guardrail Paradox** — David needs soft limits, not hard blocks. The app should let Mia spend unwisely and feel the consequence (that's the point of simulation) while giving David a way to cap damage without removing the learning.
36. **Mistake Budget** — David can designate a portion of Mia's oinks explicitly for her to spend however she wants, even poorly. Mia gets real autonomy and real consequences within a sandbox David intentionally defines. Permission-to-fail, not restriction.
37. **Post-Spend Conversation Trigger** — When Mia spends her entire balance, the app queues a conversation card for David: "Mia spent everything today. Good time to talk about it." The lesson is delivered by dad, not a notification.
38. **David's Parallel Monthly Summary** — David gets the month as a coaching report — behavioral signals surfaced, not just transactions. His version and Mia's are the same underlying data, two completely different presentations for two completely different users.
39. **The Monthly Review Ritual** — End of month, David gets a prompt: "Time for your monthly pig review with Mia." One shared narrative designed to be read together in 5 minutes. The app schedules and scaffolds the human conversation.
40. **The Review Prompt Card** — The monthly narrative includes one pre-written conversation starter for David. "Ask Mia: if you could do this month differently, what would you change?" Low friction for parents who want the conversation but don't know how to start it.

---

### Theme 6: Goals & Savings Behavior
*Saving as anticipation, not deprivation.*

41. **Collaborative Goal Setting** — Mia proposes a goal (name, what it is, rough cost). David reviews, adjusts the oink price if needed, approves. Both must agree before the goal is live. The negotiation models how adults discuss large purchases.
42. **Goal Thermometer** — Active savings goals show visible fill progress. Mia sees she's 60% of the way there. Transforms saving from deprivation into anticipation. When it fills, the pig celebrates.
43. **Goal History** — Completed goals archived — Mia can look back at everything she saved for and achieved. Builds financial identity as "someone who saves." David can reference it: "Remember when you saved for X? You did that."
44. **David Contributes to Goals** — David can see Mia's active goals and contribute oinks to any of them — matching her savings, surprising her with a boost, co-funding "present for mom." His contribution shows in the goal history.
45. **The "Present for Mom" Dynamic** — A goal directed at someone else entirely. Mia learns money can be saved for others, not just yourself. When she reaches the goal and gives the gift, it's a full emotional arc: earn, save, give, witness reaction.
46. **Monthly Prediction** — The monthly narrative asks Mia to predict next month: "What do you want to save for? How will you earn it?" Forward-looking alongside retrospective. Kids who plan spending develop budgeting intuition earlier.

---

### Theme 7: Real-World Bridge
*Connecting simulation to tangible reality.*

47. **Oink-to-Real-World Transactions** — David sets an oink price for any real-world item or experience. Mia "purchases" it from him in the app — oinks deducted, David fulfills in real life. David IS the store. Every real-world purchase is a transaction between Mia and her parent-bank.
48. **Parent as Merchant** — David creates a simple store of available purchases — screen time, a treat, a toy, an outing — each with an oink price. Mia browses what's available and saves toward things she actually wants. Desire drives saving motivation.
49. **Cash-to-Oinks Conversion Ritual** — Mia receives real birthday cash, puts it in the pig, tells David. David manually credits her oinks at the agreed conversion rate and holds the physical cash. Real money entering the system gets the same deposit ceremony as a job payment.
50. **Review Prompt Card (conversation bridge)** — Pre-written conversation starters built into the monthly review. The app facilitates the human conversation rather than replacing it. DigiPig's job is to schedule and scaffold — the lesson is always delivered by the parent.

---

## Prioritization

### Core Insight
The physical NFC card is not a v2 enhancement — it IS the product. Without it, DigiPig is a paper ledger and kids feel disconnected from their money. Software + cards ship together.

### Top Priority Ideas
1. **Card-Per-Account Physical Layer** (#17) — non-negotiable v1 core
2. **Emotional Pig UI** (#2, #3, #4, #5, #6) — the translation layer between banking and child comprehension
3. **Flexible Pay Model + Job Board** (#26, #27, #28) — reflects real parenting diversity, not a single philosophy
4. **Savings Withdrawal Ritual** (#20, #21, #22) — savings as sacred, friction as feature
5. **Post-Spend Conversation Trigger** (#37) — app as teacher's assistant, not teacher

### Quick Wins (build first)
- Balance tracker with checking + savings accounts
- Parent app (mobile + web) as primary interface
- Emotional pig state display (no numbers, just pig fullness)
- Job board + manual deposit flow
- Monthly narrative (story, not spreadsheet)

### Deferred (high value, high complexity)
- Physical pig terminal (hardware barrier — but spec the speaker, hatch, coin slot now)
- Credit card (maturity milestone, not v1)
- Behavioral coaching dashboard (needs data history first)
- Multiple simultaneous savings goals (v2 polish)

---

## Product Roadmap

### v1 — Core Product (Software + Cards)
- Parent app (mobile + web): balance tracker, accounts, job board, transactions, admin override
- Checking + savings accounts with distinct physical NFC cards
- Mia taps card to parent's phone (no dedicated hardware yet)
- Emotional pig UI on parent's phone/screen — state over numbers
- Savings withdrawal ritual requiring David's approval
- Flexible earning model (allowance, chore-conditional, job-board)
- Optional punishment/fine mechanic (opt-in)
- Post-spend conversation triggers
- Monthly kid-friendly narrative + David's coaching summary
- Collaborative goal-setting with thermometer

### v2 — Physical Pig Terminal
- 3D-printed pig with embedded NFC reader, display, speaker, coin slot, hatch
- Mia's fully independent interface — no parent phone required
- Speaker infrastructure decided at hardware design time (cheap now, expensive later)
- Ambient balance display (emotional state, not digits)
- Interaction jingles for key moments

### Long Horizon
- Credit card as earned maturity milestone
- Multiple named simultaneous savings goals
- Behavioral proof-of-learning dashboard for David
- Monthly prediction (forward-looking financial planning habit)

---

## Key Insights

**The pig is the product's soul.** Every abstract banking concept needs an emotional translation — the pig provides it. Numbers don't teach kids; felt consequences do.

**Safe failure is the core value proposition.** The simulation exists precisely so Mia can make mistakes cheaply. David's job is to enable failure within bounds he controls, not prevent it.

**David is a teacher, not an account manager.** His interface should surface behavioral signals, not transaction logs. The app's job is to create conversation opportunities, then get out of the way.

**The card makes it real.** A software-only v1 disconnects Mia from her finances the same way a paper ledger would. The physical card is the bridge between abstract simulation and felt experience.

**Parenting philosophy is a configuration, not a product assumption.** DigiPig doesn't pick a side on allowance vs. earned income vs. punishment mechanics. It supports all models without enforcing any.
