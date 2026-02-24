---
title: "SCH-60: Change Request – WhatsApp Integration"
project: "Schedula"
type: "Change Request Document"
status: "Under Review"
date: 2026-02-19
prepared_by: "Raj Kori"
tags:
  - project-management
  - change-control
  - schedula
  - internship
---

# SCH-60 – Change Request Document

## Project Management Internship – PearlThoughts  
**Date:** February 19, 2026  
**Focus:** Managing Change Requests & Preventing Scope Creep  

---

# 1️⃣ Request Details

| Field | Details |
|-------|----------|
| Change Request ID | CR-012 |
| Requestor | Salon Owner (Client) |
| Priority | High |
| Date Raised | 19 Feb 2026 |
| Status | Under Review |

### 📌 Request Description

Client has requested integration of **WhatsApp Booking Functionality** allowing customers to:

- Book appointments via WhatsApp  
- Receive booking confirmations  
- Receive reminders via WhatsApp  

### 🎯 Business Objective

- Increase customer engagement  
- Simplify booking process  
- Capture social media and walk-in audience  
- Improve booking conversion rate  

---

# 2️⃣ Impact Assessment

## 🔍 Scope Impact

| Item | Current Plan | With Change | Impact |
|------|--------------|-------------|--------|
| Story Points | 18 SP | 23 SP | +5 SP (+28%) |
| New Module | None | WhatsApp Booking Logic | Added |
| New Screens | 0 | 2 Screens | UI Increase |
| External API | No | WhatsApp Business API | New Dependency |

**Scope Increase:** 28%  
⚠ This exceeds recommended sprint change threshold (15%).  
Formal approval required.

---

## ⏱ Time Impact

| Activity | Estimated Duration |
|-----------|-------------------|
| API Integration | 3 days |
| Backend Development | 2 days |
| Frontend Changes | 2 days |
| Testing & QA | 3 days |
| Buffer | 2 days |
| **Total Estimated Impact** | **~12 Days (1.5 Weeks)** |

### Timeline Effect

- Original Launch: **28 Feb 2026**  
- New Launch (if implemented now): **7–10 March 2026**  
- Estimated Delay: **7–10 days**

---

## 💰 Cost Impact

| Cost Component           | Estimated Cost        |
| ------------------------ | --------------------- |
| Developer Effort         | ₹25,000               |
| WhatsApp API Setup       | ₹5,000                |
| QA Effort                | ₹3,000                |
| Recurring API Cost       | ₹2,000–₹4,000/month   |
| **Total Immediate Cost** | **₹30,000 – ₹35,000** |

Budget Impact: +3–4% increase

---

## ⚠ Risk Impact

| Risk | Level | Explanation |
|------|-------|-------------|
| API Approval Delay | High | Dependent on WhatsApp approval |
| Launch Delay | Medium | Marketing campaign impact |
| Technical Complexity | Medium | New integration area |
| Team Overload | High | Team currently at full capacity |

Overall Risk Rating: **Medium–High**

---

# 3️⃣ Options for Decision

---

## Option A – Approve Now & Delay Launch

### Description
Implement WhatsApp integration in current sprint.

### Pros
- Feature available at launch  
- Strong competitive advantage  
- Improved customer engagement  

### Cons
- Launch delayed 1–2 weeks  
- Increased cost  
- Higher execution risk  
- Team stress increase  

### Impact Summary
- Launch shifts to 7–10 March  
- Budget increases ₹30,000+  
- Risk increases  

---

## Option B – Defer to Phase 2 (Recommended)

### Description
Launch MVP on Feb 28. Add WhatsApp in March sprint.

### Pros
- On-time launch  
- Budget remains stable  
- Lower technical risk  
- Can market as “WhatsApp Coming Soon”  
- Structured integration planning  

### Cons
- Feature not available at launch  
- Client waits 2–3 weeks  

### Impact Summary
- No launch delay  
- No immediate cost increase  
- Controlled risk  

---

## Option C – Scope Swap

### Description
Add WhatsApp integration but remove “Monthly Reports” feature.

### Pros
- Launch on time  
- Budget neutral  
- WhatsApp available at launch  

### Cons
- Loss of reporting capability  
- Reduced management insights  
- Requires stakeholder alignment  

### Impact Summary
- Same total story points  
- Functional trade-off  

---

# 4️⃣ Recommendation

## Recommended Option: **Option B – Defer to Phase 2**

### Reason 1 – Protect Launch Deadline
Wedding season is strategically important. Timely launch has higher business value.

### Reason 2 – Reduce Risk
API approval delays could create unpredictable blockers.

### Reason 3 – Budget Stability
Avoid immediate ₹30,000–₹35,000 cost increase.

### Implementation Plan (If Approved)

- Add to Phase 2 Roadmap  
- Planning: 1 March  
- Development: 3–10 March  
- Testing: 10–14 March  
- Release: Mid-March Update  

---

# 5️⃣ Communication Plan

## Client Communication

- Schedule 30-minute decision meeting  
- Present impact assessment clearly  
- Explain Iron Triangle trade-offs (Scope, Time, Cost)  
- Provide 3 structured options  
- Ask: “Which constraint is most flexible for you?”  
- Confirm decision via email  

## Internal Team Communication (If Option B Selected)

1. Update product roadmap  
2. Create Phase 2 Epic in Jira  
3. Adjust sprint board  
4. Update risk register  
5. Mention in daily standup  

---

# 6️⃣ Decision Log (To Be Updated After Client Approval)

| Field | Entry |
|-------|-------|
| Final Decision | Pending |
| Approved By | — |
| Date | — |
| Action Items | — |

---

> **Conclusion:**  
> Any approved change affects Scope, Time, or Cost.  
> This document ensures the decision is informed, structured, and aligned with business priorities.
