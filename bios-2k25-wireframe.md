# BIOS 2K25 - Conceptual Wireframe & Design Strategy

> **Project:** BIOS 2K25 Interactive Event Website
> **Audience:** Gen Z (University Students)
> **Goal:** Create a fluid, narrative-driven experience that guides students through the event's story. Focus on smooth transitions, lightness, and elegant modernism.

## 1. Design Constraints & Psychology (Applying `frontend-design`)

- **Theme/Vibe:** "Fluid Innovation & Storytelling." Moving away from aggressive gaming styles to a welcoming, inspiring, and polished light-mode journey.
- **Color Palette:**
  - **Base (60%):** Warm Off-White (`#FAFAFA`) - Soft on the eyes, creates a breathing canvas.
  - **Secondary (30%):** Deep Slate (`#1E293B`) - Used for text and elegant contrast.
  - **Accent (10%):** Fluid Gradient (Ocean Blue `#3B82F6` to Soft Violet `#8B5CF6`) - Used to guide the eye smoothly down the page and highlight key elements (Von Restorff Effect without harshness).
- **Typography:**
  - **Display:** _Outfit_ or _Plus Jakarta Sans_ (Smooth, geometric, welcoming).
  - **Body:** _Inter_ (Classic, highly readable).
  - **Scale Ratio:** 1.333 (Perfect Fourth) for elegant, balanced scaling (not too aggressive).
- **Interactive Effects:**
  - Soft, fading entrances as the user scrolls (Scroll-triggered storytelling).
  - Subtle blur/glassmorphism for nav/navigating elements.
  - Floating background gradient "blobs" that slowly morph to feel alive but not frantic.

---

## 2. Layout & Wireframe Structure

### 0. Global Elements

- **Navigation (Top):** Floating pill-shaped glass header. Smooth and unobtrusive.
- **Pacing:** Each section has generous whitespace to let the story "breathe" (Golden Ratio principle for margins).

### 1. Act I: The Invitation (Hero Section)

- **Visuals:** A soft gradient background that slowly morphs. Large, elegant text that fades in smoothly.
- **Content:**
  - Subtitle: "A journey of innovation and creativity"
  - Title: "Welcome to BIOS 2K25"
  - Date: "March 21, 2025"
- **Calls to Action (Fitts' Law):**
  - A pill-shaped, soft-gradient button with a gentle hover lift: "Begin Your Journey"

### 2. Act II: The Story Unfolds (About & Events)

- **Concept:** Instead of a harsh "Gauntlet," we frame the events as chapters of an experience.
- **Layout:** Alternating left/right image (or abstract shape) and text layout. As you scroll, the text fades up smoothly.
- **Categories:**
  - _The Technical Mind:_ Techtonic Clash, Logic Loom, The Web Architect. (Cards have soft 24px rounded corners and large soft shadows).
  - _The Creative Spirit:_ Dance, Photography, Memory Games.

### 3. Act III: Our Heritage (Gallery)

- **Layout:** An elegant, horizontal masonry layout.
- **Style:** Images start slightly blurred or desaturated, and smoothly come into sharp focus and full color on hover.
- **Psychology:** Social Proof told through a museum-like gallery, reflecting the longevity of BIOS since 2K13.

### 4. Act IV: The Next Chapter (Registration)

- **Layout:** A clean, centralized card.
- **Messaging:** Soft urgency. "The journey begins soon. Secure your place before March 07."
- **CTAs:** A prominent, glowing "Join BIOS 2K25" button. Contact information is laid out below cleanly in small, readable type.

---

## 3. Recommended Tech Stack for Implementation (When ready)

- **Framework:** Next.js (React) for elegant routing and optimized performance.
- **Styling:** Tailwind CSS (Focusing on large `rounded-3xl` corners, `shadow-xl`, and `backdrop-blur`).
- **Animations:** Framer Motion (for `initial={{ opacity: 0, y: 20 }}` fade-up storytelling elements).
