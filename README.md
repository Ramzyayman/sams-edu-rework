# Human-Computer Interaction (HCI) Usability Case Study
## Redesigning the Sadat Academy for Management Sciences (SAMS) Homepage

- **Course:** Human-Computer Interaction / UI/UX Design
- **Target URL:** [http://sams.edu.eg/en/](http://sams.edu.eg/en/)
- **Scope:** Single Homepage Usability Audit & Interactive Redesign
- **Tooling:** Figma (Interactive Prototype)

---

## 1. Project Background & User Context

Sadat Academy for Management Sciences (SAMS) is an accredited public Egyptian academic institution established under Presidential Decree No. 127 of 1981. The homepage functions as the critical digital front door for three core user groups:

1. **Prospective Students & Parents:** Seeking program catalogs, admission criteria, tuition information, and application pathways.
2. **Current Enrolled Students:** Looking for academic calendars, student portals, course registration, exam results, and schedules.
3. **Faculty & Executive Trainees:** Needing LMS access, research publications, and corporate executive training diplomas.

While the existing site contains vital academic data, its layout suffers from structural usability bottlenecks, visual noise, and cognitive friction rooted in legacy CMS patterns.

---

## 2. Usability & Interface Design Problems (Before)

### Problem 1: Passive Hero Area & Severe Affordance Failure
- **HCI Principles:** **Don Norman’s Signifiers & Affordances**, **Fitts’s Law** ($T = a + b \log_2(2D/W)$)
- **Interface Flaw:** The above-the-fold hero space is entirely occupied by an automatic photo carousel of the academy building. It contains **no value proposition, no text overlay, and zero Call-to-Action (CTA) buttons**.
- **UX Impact:** In Norman's terms, the interface fails to provide **signifiers** that bridge the *Gulf of Execution*. A prospective student wishing to apply or explore degrees is given no starting point in the most visible area of the page. Under Fitts's Law, prime screen real estate with rapid target acquisition time is completely non-interactive.

### Problem 2: Illogical Grouping & Low Information Scent
- **HCI Principles:** **Gestalt Law of Similarity**, **Cognitive Load Theory (Miller’s Law)**, **Information Scent**
- **Interface Flaw:** Directly below the hero slider, four identical cards group core educational tracks (`Graduate Programs`, `Undergraduates`) together with static institutional reading (`Mission`, `History`). All four cards feature identical blue icon boxes and identical generic buttons labeled **"READ MORE"** in low-contrast gray.
- **UX Impact:**
  - Violates the **Gestalt Law of Similarity**: Because distinct categories of content are styled identically, users cannot perceive the hierarchy.
  - Weak **Information Scent**: Generic "READ MORE" labels force users to guess the outcome of clicks, increasing extraneous cognitive load.

### Problem 3: Misplaced Utility Navigation Violating Web Standards
- **HCI Principles:** **Nielsen’s Heuristic #4 (Consistency and Standards)**, **Jakob’s Law of Internet UX**
- **Interface Flaw:** Core utility tools—**Student Login**, **Registration**, and **Language Switching**—are located in a secondary dark-blue bar **halfway down the page**, between the top cards and image banners.
- **UX Impact:** Jakob’s Law states that users expect your site to conform to patterns learned across the wider web. Users instinctively scan the **top-right header** for authentication and locale controls. Burying them below the fold leads to failed visual searches and user confusion.

### Problem 4: Visual Clutter & Low-Utility Diagnostic Widgets
- **HCI Principles:** **Nielsen’s Heuristic #8 (Aesthetic and Minimalist Design)**, **Extraneous Cognitive Load (Sweller)**
- **Interface Flaw:** The bottom-left sidebar includes an obsolete diagnostic module: **"Who's Online"** (*"We have 127 guests and no members online"*), followed by an uncurated vertical tree menu that duplicates the top navigation bar.
- **UX Impact:** Every unnecessary piece of data competes with essential information for user attention. Visitor counters provide zero task utility to students or applicants, increasing extraneous visual clutter and forcing endless vertical scrolling.

---

## 3. Proposed Redesign & HCI Solutions (After)

The redesigned SAMS homepage restructures the experience into a single, cohesive, task-oriented layout:

1. **Persistent Global Utility Header (Top-Right):**
   - Placed `Student Portal`, `Staff LMS`, `Hotline: 19541`, and a dedicated `[عربي]` language switch at the very top, directly satisfying **Jakob's Law** and **Nielsen Heuristic #4**.
2. **Actionable Hero with Dual High-Visibility CTAs:**
   - Added an inspiring headline: *"Empowering Future Leaders in Management, Computing & Languages"*.
   - Positioned a high-contrast primary CTA: `[ Apply for 2026/2027 ]` (Amber gold, optimized for **Fitts's Law**) and a secondary CTA: `[ Explore Degrees & Study Plans ]`.
3. **Task-Based Persona Quick-Access Strip:**
   - Replaced the mixed "History/Mission" cards with **4 distinct persona pathways** using the **Gestalt Law of Common Region**: *Prospective Students*, *Current Students*, *Postgraduate & Research*, and *Executive Training*.
4. **Interactive Academic Program Tabs:**
   - Created an interactive tabbed component allowing students to switch between *Management Sciences*, *Computing & Information*, and *Languages & Translation* with zero page reloads, applying **progressive disclosure**.
5. **Curated 3-Card News & Events Grid:**
   - Replaced the legacy blog roll and "Who's Online" counter with clean, high-contrast event cards featuring category tags, dates, and real SAMS initiative imagery.

---

## 4. Usability Evaluation Matrix: Before vs. After

| Evaluation Criteria | Original SAMS Homepage (Before) | Redesigned Homepage (After) | HCI Concept Grounding |
| :--- | :--- | :--- | :--- |
| **Primary Call-to-Action** | None. Only a passive image slider. | Prominent, high-contrast `[ Apply Now ]` button above the fold. | **Norman's Signifiers & Fitts's Law** |
| **Authentication & Language** | Hidden midway down the page in a secondary bar. | Consolidated in the persistent top utility header. | **Jakob’s Law & Nielsen Heuristic #4 (Consistency)** |
| **Information Architecture** | Programs mixed with static history & mission text. | Persona-based routing cards + interactive faculty tabs. | **Gestalt Proximity & Miller’s Law (Chunking)** |
| **Button Labels** | Repeated generic "READ MORE" pill buttons. | Descriptive action labels (`Admissions Guide →`, `Student Services →`). | **Information Scent & Heuristic #6 (Recognition over Recall)** |
| **Extraneous Clutter** | "Who's Online" counter + duplicated sitemap list. | Completely eliminated; replaced with a 3-card news grid. | **Nielsen Heuristic #8 (Aesthetic & Minimalist Design)** |
| **Search Functionality** | Narrow, low-contrast input buried in the left sidebar. | Accessible modal search overlay with auto-complete suggestions. | **Error Prevention & Heuristic #7 (Flexibility of Use)** |

---

## 5. Presentation Slide-by-Slide Outline

- **Slide 1:** Title Slide (Project Name, Student Name, SAMS Logo).
- **Slide 2:** Target Audience & User Personas (Prospective, Enrolled, Executive).
- **Slide 3:** The Original Homepage (Screenshot with red annotated problem callouts).
- **Slide 4:** Deep-Dive into the 4 HCI Flaws (Heuristics, Norman, Fitts, Hick, Gestalt).
- **Slide 5:** Information Architecture & Wireframe Transformation.
- **Slide 6:** The Redesign Walkthrough (Screenshot of the modern Figma layout).
- **Slide 7:** Interactive Prototype Demo (Live walkthrough of Tabs, Search Modal & Hover states).
- **Slide 8:** Usability Matrix & Conclusion (Summary of UX improvements).
