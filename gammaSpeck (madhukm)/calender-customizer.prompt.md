**Overview:**

You are to build a clean, playful, and highly usable landing page for [GiftCal] — a free online tool that lets users create personalized calendars by uploading photos and exporting them as PDFs for gifting or personal use.

The goal is to **generate interest**, **capture emails**, and **encourage early feedback** by letting users try the editor instantly with minimal friction.

---

**Stack:**

* ⚙️ Vite + Vue 3 + TypeScript
* 💨 TailwindCSS
* 🧩 Composition API (`<script setup>` only)
* 🧼 Prettier & ESLint formatting based on this `cursorrc`:

  * 2-space indentation
  * 100-character line width
  * Arrow functions with parens
  * Explicit return types for functions
  * Type over interface preference
  * Guard clauses preferred over nested logic
  * Max nesting depth: 2
  * Max complexity: 5
  * Prefer early returns, single-statement lines
  * TS target: ES2023, strict mode on
* ✅ See full cursorrc at end of this prompt

---

**Core Sections (each as separate Vue components):**

1. **Hero Section**

   * Clear pitch: “Create beautiful, personalized calendars in minutes.”
   * Subtext: “Upload your photos, preview your calendar live, and download it as a printable PDF.”
   * Primary CTA: “Try It Now” (scrolls to embedded editor or opens it)
   * Secondary CTA: “See how it works” (scrolls to explainer)

2. **How It Works**

   * 3 simple steps in cards or icons: Upload → Customize → Download
   * Keep this minimal but visual (fun icons, emojis, or line illustrations)

3. **Call to Action Strip**

   * Prompt for email when attempting to download
   * Option to give feedback after trying the editor

4. **Playful Testimonials**

   * Placeholder testimonials with humorous CTA:
     *“Like it? Your face could be here! Send us a love note 💌”*

5. **FAQs**

   * “Do I have to pay?” → “Nope, it’s totally free while in beta!”
   * “Can I give feedback?” → “Absolutely! There’s a feedback button below.”
   * “Can I print this?” → “Yes! Download the PDF and take it to your favorite print shop.”
   * Keep the tone human and casual.

6. **Footer**

   * Light footer with credits and social/contact info
   * Link to feedback form or email

---

**Style Guidelines:**

* **Tone:** Warm, playful, creative — aimed at casual users, gift-givers, teachers, and artists
* **Typography:** Clean sans-serif (e.g., Inter or Lexend)
* **Colors:** Light theme with 1-2 playful accent colors (e.g., coral, teal)
* **Layout:** Responsive (mobile-first); maintain accessibility basics
* **Animation:** Light fade/slide-in animations (optional), no flashy effects
* **Tailwind best practices**: Use semantic classes, componentize where appropriate

---

**Not Needed:**

* Hosting
* Backend logic
* Domain setup
* Editor embedding (assume editor exists separately)
* No brand design, but use **GiftCal** as project name and placeholder logo text

---

**Goal:**
Produce a polished landing page that builds trust, explains the value quickly, and gets users into the tool fast. Clean code, modular structure, and alignment with the provided lint rules are a must.

