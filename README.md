# DigiPig

A money learning app for kids. Think piggy bank, but digital.

Kids get real-feeling NFC cards they can hold and tap — one per account — while parents manage everything behind the scenes. All money is simulated. Currency is **oinks**.

The physical card isn't a feature. It's the product. Without it, DigiPig is a paper ledger.

## Goals

1. **For kids:** Experience modern banking concepts (accounts, earning, saving, spending) before handling real money
2. **For parents:** Manage kids' simulated finances — fund accounts, set earning models, monitor behavior, trigger conversations

## How it works

### The cards
- Each account has a distinct physical NFC card the child holds and taps
- Tapping the card to a phone (v1) or the pig terminal (v2) initiates transactions
- Losing the card means losing access — same as a real card

### The accounts
- **Checking** — spend freely; declines at zero by default (real debit behavior)
- **Savings** — sacred; withdrawals require the child to request and the parent to approve
- **Credit** — unlocked by the parent as a maturity milestone, not available from day one

### The pig
- The pig is the emotional interface — state over numbers, always
- Full pig = rich; empty pig = broke; no digits required for a kid to understand
- Spending makes the pig visibly thinner; going broke is dramatic, not a "0 oinks" message
- Pre-spend preview shows the child what their pig looks like *after* before committing

### Earning
Parent configures their preferred model — app doesn't pick a side:
- Scheduled allowance
- Chore-conditional deposit
- Job board (parent posts jobs with oink values, child claims and earns)
- Manual payment anytime

### Parent controls
- Admin override — parent can always edit any balance directly
- Optional fine/deduction mechanic (opt-in, not default)
- Savings withdrawal approval with counter-offer option
- Mistake budget — designate oinks for the child to spend however they want, even poorly
- Collaborative goal-setting (child proposes, parent approves, both can contribute)

### Conversation layer
- Post-spend trigger: when the child spends everything, the parent gets a nudge to talk
- Monthly narrative: a story about the pig's month (not a spreadsheet), designed to be read together
- Pre-written conversation starter included each month
- Behavioral signals surfaced for parents: hesitated before spending, saved unprompted, asked about balance

## Roadmap

### v1 — Core product
Software + NFC cards. Child taps card to parent's phone.
- Parent mobile + web app
- Checking and savings accounts
- Emotional pig UI, job board, savings rituals, monthly narrative
- Flexible earning model, admin override, conversation triggers

### v2 — Physical pig terminal
Dedicated hardware: 3D-printed pig with embedded NFC reader, display, speaker, coin slot, and hatch.
- Child's independent interface — no parent phone required
- Ambient balance display (emotional state, not digits)
- Interaction jingles on key moments (deposit, spend, broke, goal reached)

### Long horizon
- Credit card as earned maturity milestone
- Multiple simultaneous named savings goals
- Behavioral coaching dashboard for parents
- Monthly forward-looking prediction ("what do you want to save for next month?")
