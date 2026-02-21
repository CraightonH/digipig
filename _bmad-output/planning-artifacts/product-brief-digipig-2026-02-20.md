---
stepsCompleted: [1, 2, 3, 4, 5, 6]
workflowComplete: true
inputDocuments:
  - README.md
  - _bmad-output/brainstorming/brainstorming-session-2026-02-20.md
date: 2026-02-20
author: Craighton
---

# Product Brief: digipig

## Executive Summary

DigiPig is a simulated banking app for children aged 6–12, paired with physical NFC cards that give kids independent access to their own finances. Parents manage a real-time digital ledger; children check balances, feel the consequences of spending, and develop financial intuition — all without touching real money.

The core insight: children internalize financial decisions through felt consequence, not instruction. DigiPig creates a safe-to-fail environment where spending makes the pig visibly hungrier, saving makes it full, and going broke is a character experience — not a number on a screen. The NFC card is the child's self-service terminal: tap to check balance, tap to transact, no parent required for the loop to work.

---

## Core Vision

### Problem Statement

Children aged 6–12 have no way to practice financial decision-making in a real-feeling, consequence-safe environment. Parents who want to teach money management are stuck maintaining a mental or paper ledger that is perpetually out of sync — reconciled only when the child asks for money — and completely inaccessible to the child themselves.

### Problem Impact

Without a self-service interface, every financial question a child has requires a parent. The result: children don't develop the habit of checking their balance, planning purchases, or thinking ahead — because the friction is too high. Parents carry the full cognitive load of the ledger. The teaching moment arrives late, if at all.

### Why Existing Solutions Fall Short

Paper ledgers and chore charts are parent-only, manually maintained, and opaque to the child. Real-money apps (Greenlight, GoHenry) remove the safe-to-fail property — a child who overspends loses real money, which limits how freely parents can let them fail and learn. No existing solution gives the child an independent, always-current, comprehensible view of their own financial state.

### Proposed Solution

DigiPig gives each child a physical NFC card per account. Tapping the card surfaces their balance as a pig emotional state — full, hungry, empty — not a number. Children self-serve: check balance, plan purchases, track savings goals without asking a parent. Parents get a real-time ledger, earning tools (allowance, job board, manual payment), and conversation triggers when teachable moments occur.

Currency is *oinks* — parent-configurable: fully simulated, or mapped 1:1 to USD, or any exchange rate the parent sets. DigiPig doesn't pick a financial philosophy; it supports any model the parent chooses.

### Key Differentiators

1. **Safe-to-fail simulation** — consequences are emotionally real (the pig suffers) but financially safe; parents can let children fail without real loss
2. **Child self-service** — the NFC card removes the parent from every balance-check interaction; the child develops the habit of checking independently
3. **Flexible currency** — oinks can be fully simulated or pegged to real currency; parents choose the model that fits their family
4. **Real-time parent ledger** — always reconciled; no lag between transaction and parent awareness
5. **Emotional interface** — pig state translates abstract balance into felt experience appropriate for ages 6–12

---

## Target Users

### Primary Users

#### The Child — Ages 6–12

**Profile:** A child in the early-to-middle financial literacy window. At 6, they're learning that money is finite and that choices have consequences. By 12, they're ready for abstract concepts like credit, interest, and debt. DigiPig serves the full range through progressive complexity — accounts and earning first, credit and loans unlocked by a caregiver as the child matures.

**Motivations:** Autonomy. Knowing their balance without asking mom or dad. Saving toward something they want. The satisfaction of a full pig.

**Current experience:** No visibility into their own "account." Every balance inquiry requires interrupting a parent. No consequence feels real because nothing is tracked in real time.

**Success:** The child checks their balance before asking for something. They hesitate before spending. They ask "how much more do I need to earn?" without prompting. They feel the pig get hungry after a purchase.

**Key interactions:**
- Tap NFC tag to check balance (pig state, not number)
- Tap to initiate a spend transaction
- View savings goal progress
- Request a savings withdrawal

---

#### The Caregivers — Mom and/or Dad, Co-Managing Multiple Children

**Profile:** One or two caregivers sharing management of one or more children's accounts. Both parents can view balances, approve requests, post jobs, and issue payments. Neither is the sole administrator — the household shares the ledger.

**Motivations:** Reduce cognitive load of tracking. Create teachable moments without manufacturing them. Give each child age-appropriate financial experience without being locked into a single parenting philosophy.

**Current experience:** Mental or paper ledger, reconciled on demand, typically by whichever parent the child asks. No shared real-time view — one parent often doesn't know what the other approved or paid. Teaching happens accidentally, not by design.

**Success:** Both parents see the same current ledger. Either can act — approve a withdrawal, pay out a job, add a fine — without coordinating first. The child stops asking "how much do I have?" and starts knowing.

**Key interactions:**
- Create and link NFC tags to child accounts (onboarding)
- Approve or deny savings withdrawal requests
- Post jobs, pay out earnings, set allowance schedule
- View transaction history and behavioral signals per child
- Unlock advanced account types (credit, loans) as the child ages
- Manage multiple children from a single household view

---

### Secondary Users

**Grandparents / Gift-givers (v2–v3):** Adults outside the household who want to contribute oinks to a child's account or savings goal. Not system managers — one-time or occasional actors. Deferred to later versions.

---

### User Journey

#### Child Journey

| Stage | Experience |
|---|---|
| **First tap** | Caregiver sets up NFC tag and links it to checking account. Child taps for the first time — sees pig state. The tag is theirs. |
| **Core loop** | Child taps to check balance before wanting to spend something. Sees pig fullness. Decides: spend or save. Taps to transact. Pig changes state immediately. |
| **Savings goal** | Child proposes a goal. A caregiver approves. Child watches thermometer fill over days/weeks. Requests withdrawal when ready. Caregiver approves or counters. |
| **Progression** | As child ages and demonstrates readiness, a caregiver unlocks credit. Child experiences debt-mode pig. Learns repayment before stakes are real. |
| **Aha moment** | The first time the child checks their balance unprompted, before asking to buy something. Self-directed financial thinking without a parent in the loop. |

#### Caregiver Journey

| Stage | Experience |
|---|---|
| **Setup** | One caregiver installs, creates accounts for each child, writes NFC tags. Second caregiver joins the household. Both have full visibility and action rights from there. Should take under 10 minutes per child. |
| **Core loop** | Either caregiver receives transaction notifications in real time. Either can approve savings requests, post jobs, pay earnings. Ledger is always current and shared — no reconciliation, no "did you pay her yet?" |
| **Teaching moments** | Either caregiver gets nudged when a teachable moment occurs. Whichever parent is present can act on it. |
| **Multi-child view** | Single household dashboard across all children's accounts. Different ages, different unlocked features, one place. |
| **Aha moment** | The first week neither parent has to answer "how much do I have?" — because the child already knows. |

---

## Success Metrics

This is a personal open source project. Success is defined by whether it works well for the household that built it — not by growth, revenue, or adoption targets.

### What Success Looks Like

**For the child:**
- Checks balance independently by tapping their NFC tag — without asking a parent
- Visibly hesitates or thinks before initiating a spend transaction
- Asks questions like "how much more do I need to earn?" before requesting something
- Understands their pig state (full, hungry, empty) without needing a number explained

**For the caregivers:**
- Any NFC tap → transaction amount entry → recorded: fast, accurate, done
- Ledger is always current — no mental reconciliation between requests
- Either caregiver can act on any account event without coordinating with the other
- No parent needs to answer "how much do I have?" because the child already knows

### Key Performance Indicators

| Indicator | Target |
|---|---|
| Time to record a transaction (tap to saved) | Under 30 seconds |
| Ledger accuracy | Zero unrecorded or misrecorded transactions |
| Child self-service rate | Child initiates balance checks without prompting |
| Caregiver sync | Both parents see the same state in real time |

### Business Objectives

N/A — personal project. No acquisition, retention, or revenue targets.

---

## MVP Scope

### Core Features

The MVP is the smallest version that replaces the paper ledger and gives the child self-service access to their balance. Every feature below is load-bearing for that core loop.

**NFC Interaction**
- Caregiver writes account identity to a generic NFC tag
- Child taps tag to view their balance as pig emotional state (full, hungry, empty — no number required)
- Caregiver taps tag to initiate a transaction against that account

**Accounts**
- Checking account: spend freely, declines at zero by default
- Savings account: withdrawal requires child request + caregiver approval
- Each account linked to its own NFC tag

**Transaction Recording**
- Caregiver enters amount after NFC tap; transaction saved immediately
- Ledger accurate and real-time — no reconciliation required
- Both caregivers share the same live ledger

**Caregiver App**
- Create and manage children's accounts
- Link NFC tags to accounts
- View transaction history per child and per account
- Admin override: edit any balance directly
- Approve or deny savings withdrawal requests with optional counter-offer
- Add funds manually (allowance, one-time payment, fine/deduction)
- Two caregivers per household, both with full access

**Pig UI**
- Emotional state display — pig fullness maps to balance
- Pre-spend preview: show pig state after proposed transaction before confirming
- Empty pig state is visually distinct and memorable

---

### Out of Scope for MVP

| Feature | Deferred To |
|---|---|
| Job board (post jobs, child claims, earns) | v2 |
| Monthly narrative / coaching summary | v2 |
| Physical pig terminal (dedicated NFC hardware) | v2 |
| Post-spend conversation triggers | v2 |
| Credit / loan accounts | v2+ |
| Multiple simultaneous named savings goals | v2 |
| Grandparent / external gift-giver access | v3 |
| Behavioral coaching dashboard | v3 |

---

### MVP Success Criteria

The MVP is successful when:
- Child taps their NFC tag and sees their pig state without asking a parent
- Caregiver records a transaction in under 30 seconds from tap to saved
- Ledger matches reality — zero unrecorded or misrecorded transactions
- Both caregivers see the same account state in real time
- The paper ledger is retired

---

### Future Vision

**v2 — Richer Earning & Insight**
- Job board: caregivers post jobs with oink values, child claims and completes them
- Monthly narrative: a story about the pig's month, designed to be read together
- Physical pig terminal: dedicated NFC hardware the child interacts with independently
- Post-spend conversation triggers for caregivers

**v2+ — Progressive Complexity**
- Credit account unlocked by caregiver as a maturity milestone
- Loan mechanics with repayment tracking
- Multiple named simultaneous savings goals

**v3 — Extended Household**
- Grandparent / gift-giver access to contribute oinks to a child's account or savings goal
- Behavioral coaching dashboard surfacing learning signals over time
