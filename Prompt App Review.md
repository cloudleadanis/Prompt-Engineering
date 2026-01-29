# App Build Feedback & Change Requests

---

## 1. Context & Scope

### 1.1 Build Information
- **App name:**
- **Platform:** (macOS / iOS)
- **Build number / commit:**
- **Review date:**
- **Reviewer:**

### 1.2 Review Goal
- What this feedback session is optimizing for  
  _(e.g. usability, polish, correctness, Apple HIG compliance, bug fixing)_

### 1.3 Non-Goals for This Feedback
- Explicitly list what should **not** be changed in this iteration

---

## 2. Summary of Key Issues (High Level)
_(Optional but very helpful for AI)_

- **Critical issues:**
- **UX / polish issues:**
- **Minor issues / nits:**
- **What’s working well:**

---

# Screen-by-Screen Feedback

_Repeat Sections 3 → 10 for each screen_

---

## 3. Screen: \<Screen Name\>

### 3.1 Purpose of This Screen
- What this screen is supposed to do
- What success looks like for the user here

### 3.2 Screenshot References
- Screenshot 3.1:
- Screenshot 3.2:
- _(Use consistent numbering the AI can reference)_

---

## 4. Visual & Layout Feedback
- Spacing
- Alignment
- Typography
- Density
- Emphasis / hierarchy
- Apple HIG compliance

**Feedback & Change Requests**
- Bullet points tied to screenshot numbers

---

## 5. Interaction & Behavior Feedback
- Click / tap behavior
- Drag & drop
- Hover states
- Keyboard shortcuts
- Focus handling
- Animations / transitions (or lack thereof)

**Feedback & Change Requests**
- What feels wrong
- What should change
- What should remain exactly the same

---

## 6. Data, State & Edge Cases
- Empty states
- Loading states
- Error states
- Unexpected transitions
- State inconsistencies

**Observed Issues**
- What happens now

**Expected Behavior**
- What should happen instead

---

## 7. Validation & Error Handling
- Input validation issues
- Missing user feedback
- Confusing or absent error messages
- Silent failures

**Feedback & Change Requests**

---

## 8. Accessibility & Keyboard Review
- Keyboard navigation
- Focus order
- Hit targets
- Readability / contrast

**Feedback & Change Requests**

---

## 9. Implementation Hints (Optional but Powerful)
_(Use when you have a strong intuition)_

- **Likely source:**
  - View
  - ViewModel
  - Persistence / Core Data
  - Layout logic
- **Constraints:**
  - Avoid refactors
  - Preserve current behavior
  - Performance-sensitive
  - macOS-specific expectations

---

## 10. Explicit “Do Not Change”
- UI elements that must remain untouched
- Behaviors that are correct as-is

---

# Cross-Screen Guidance

---

## 11. Consistency Issues Across Screens
- Inconsistent spacing, behavior, terminology, shortcuts, etc.

---

## 12. Acceptance Criteria for This Feedback
_(Critical for AI correctness)_

- After changes, the following must be true:
  - AC1:
  - AC2:
  - AC3:

---

## 13. Regression Watchlist
- Things likely to break while implementing changes
- Areas to double-check after fixes

---

## 14. Instructions for the Implementing AI
_(Paste once, reuse every time)_

- Use screenshots and written notes as the source of truth
- Prefer minimal, targeted changes
- Do not refactor unless explicitly requested
- Preserve existing behavior unless contradicted by feedback
- Ask clarifying questions **before** implementing if ambiguous

---

## Optional Note (Recommended)
> **This document contains human feedback and screenshots.  
> Implement changes conservatively and incrementally.**
