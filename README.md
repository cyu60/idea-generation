# idea-generation

## Key Modifications to Ideation Tool

### Overall Flow Adjustment:

* **Maintain:** Process up to "Edge Analysis".
* **Remove:** The brainstorming step around work, relationships, health, and play to avoid distraction.
* **New Step (Post-Edge Analysis):**
  * Display a consolidated **Checklist** with:
    * Strengths (pre-populated from edge analysis)
    * Interests (pre-populated from edge analysis)
    * User-defined "meaningful" problems (customizable)
    * Ability to inject **new trend or source material** for greater diversity.
  * Check https://github.com/cyu60/mentor-matching for the right flow

---

### Enhanced "How Might We" (HMW) Statements Generation:

* Generate dynamic **"How Might We"** statements based on:
  * Strengths, interests, custom problems, and injected sources/trends.
* Each HMW statement comes bundled with  **3 AI-focused ideas** .
* Allow users to:
  * **Regenerate** HMW statements and their associated ideas easily.
  * **Pin favorite** HMW statements and specific ideas to keep them for the PRD stage.

---

### Project Requirement Document (PRD) Integration:

* After pinning preferred ideas, users can:
  * Generate an automatic **AI-focused PRD** based on their pinned selections.
* PRD output will explicitly integrate:
  * The pinned HMW statement.
  * Selected project ideas.
* Allow users to  **link PRD directly to** :
  * The auto-generated **10-week curriculum plan** tailored to their project.
  * A specific  **user-defined project goal input** .

---

### Curriculum & Goal Integration:

* Upon PRD completion, provide seamless integration to:
  * **Curriculum Plan Generation** (auto-generating a personalized, AI-focused, 10-week curriculum).
  * Allow explicit input for:
    * User's personal project **goal/desired outcome** to guide curriculum content.

---

### UX/UI Considerations:

* Clearly defined screen transitions after edge analysis:
  1. Checklist of Strengths, Interests, Custom Problems & Sources
  2. "How Might We" statement & Idea Generation Screen (with pinning functionality)
  3. PRD generation & refinement page
  4. Curriculum & Goal integration screen
* Include opportunities to regularly inject **fresh trends** or **news sources** to diversify project ideation.
* Facilitate collaboration & mentorship by enabling easy  **screen sharing & breakout room compatibility** .

---

### Why These Changes?

**Based on student and facilitator feedback:**

* Students valued exploring **their own curiosity** deeply.
* Increased emphasis on **AI-driven projects** aligned with strategic focus.
* A need for **greater diversity** in generated ideas, avoiding repetitive productivity-based tools.
* Clear desire for structured, actionable **curriculum integration** aligned with individual project goals.
* More personalized mentorship facilitated by interactive screen-sharing and breakout groups.

---

### Actionable Implementation Checklist:

* [X] Update flow post-edge analysis to incorporate the new consolidated checklist page.
* [ ] Develop functionality for injecting new trends/sources directly into the checklist page.
* [X] Create new logic to generate varied, AI-focused HMW statements and bundled ideas.
* [ ] Add regeneration & pinning functionality for user-selected statements and ideas.
* [X] Implement seamless transition from pinned ideas to AI-generated PRD creation.
* [X] Design the curriculum planner integration page, including explicit goal-setting input.
