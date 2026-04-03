You are an expert Frontend Developer and UI/UX Designer. Your task is to build a modern, high-performance, responsive landing page for a mobile fitness app called "GitFit". 

**STRICT DESIGN SYSTEM & GLOBAL STYLING:**
*   **Font Family:** Use "Roboto" exclusively for all typography (import from Google Fonts: `@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap');`).
*   **Background Color:** Exact `#000000` for the main body. Use a slightly lighter dark gray (e.g., `#111111` or `#1A1A1A`) ONLY for card backgrounds to create depth.
*   **Button/Accent Color:** Exact `#EE9033` (Orange). Use this for all Call-to-Action buttons, active states, and key highlights.
*   **Text Color:** Exact `#F4F4F4` for main body text and headings. You may use a slightly lower opacity of `#F4F4F4` (like `#F4F4F4` at 70%) for secondary descriptions.
*   **Alignment & Spacing:** The global container layout MUST have a strict left and right padding/margin of exactly `16px` on mobile screens (e.g., `px-[16px]` or `px-4` in Tailwind). Ensure everything aligns to this 16px grid perfectly.
*   **Icons:** Use Lucide React icons.

Please implement the following 6 sections sequentially using Tailwind CSS (or standard CSS if specified):

**1. Hero Banner (First Touchpoint)**
*   **Layout:** Split-screen on desktop (Text left, Image right), stacked on mobile with `px-[16px]`.
*   **Headline:** "GitFit - 404 Fat Not Found." (Roboto Black/Bold, massive text, color: `#F4F4F4`).
*   **Sub-headline:** "A minimalist, localized fitness app designed to help Vietnamese beginners crush procrastination and stay motivated every single day." (Roboto Regular, 70% opacity of `#F4F4F4`).
*   **CTA Buttons:** 
    *   Primary Button: "🎨 View Full Case Study on Behance" (Background: `#EE9033`, Text: `#F4F4F4`, rounded).
    *   Secondary Button: "✏️ Explore Figma Prototype" (Outline style with `#EE9033` border or solid dark background, Text: `#F4F4F4`).
*   **Visual:** Add a placeholder for a high-quality smartphone mockup (iPhone 15 Pro) displaying the app dashboard.

**2. The Problem & Target Audience**
*   **Heading:** "Why Do Beginners Quit?" (Centered, `#F4F4F4`).
*   **Layout:** A CSS Grid with 3 Cards. Container `px-[16px]`.
*   **Card Styling:** Dark background (`#111111`), subtle border.
*   **Card 1:** Icon: Wallet/Globe. Title: "Language & Cost Barriers". Desc: "Existing apps are in English, use confusing jargon, and lock features behind paywalls."
*   **Card 2:** Icon: Smartphone/Settings. Title: "Clunky UX". Desc: "Logging workout data takes too many taps, disrupting rest times."
*   **Card 3:** Icon: Users. Title: "Crowded Gyms". Desc: "Beginners feel lost when their primary equipment is occupied."

**3. Solution & Value Proposition**
*   **Heading:** "The GitFit Approach" (Centered).
*   **Layout:** 3 Cards. Container `px-[16px]`.
*   **Card 1:** Icon: CheckCircle (Color: `#EE9033`). Title: "100% Localized & Free". Desc: "Fully Vietnamese content with zero language barriers and no core paywalls."
*   **Card 2:** Icon: Layout. Title: "Minimalist & Intuitive". Desc: "Distraction-free interface focused purely on the workout."
*   **Card 3:** Icon: Flame. Title: "Discipline Through Gamification". Desc: "Turning workout pressure into a fun experience with streaks and rewards."

**4. Key MVP Features**
*   **Layout:** Zig-zag layout (Alternating Text and Image). Container `px-[16px]`.
*   **Feature 1:** Text: "Smart Exercise Substitution - One tap to find alternative exercises targeting the same muscle group when a machine is taken." Image placeholder: App mockup showing exercise replacement.
*   **Feature 2:** Text: "1-Tap Logging - Quickly log Sets, Reps, and Weights with intuitive swipe/tap gestures without breaking your flow." Image placeholder: App mockup showing the Numpad and logging table. (Image Left, Text Right).
*   **Feature 3:** Text: "Streak & Gamification - Visually track your progress and earn rewards for maintaining a consistent routine." Image placeholder: App mockup showing profile streak calendar. (Text Left, Image Right).

**5. Design System Showcase**
*   **Heading:** "Design System"
*   **Layout:** A bento-box grid style to display design tokens. Container `px-[16px]`.
*   **Colors:** Display 3 colored blocks with HEX codes: `#000000` (Background), `#F4F4F4` (Text), `#EE9033` (Accent).
*   **Typography:** Display a large "Aa" with "Roboto" and weights (Regular 400, Bold 700).
*   **UI Components:** A clean, abstract arrangement of a button (using `#EE9033`), an input field, and a bottom tab bar to show visual coherence.

**6. Footer & The Team**
*   **Closing Statement:** "Start your fitness transformation with GitFit today." (Large text, centered).
*   **The Team:** Display 5 circular avatars in a row. Below each, put "Team Member" (Bold) and "Role" (Regular).
*   **Quick Links:** Clean text links with hover effects (hover color: `#EE9033`) for GitHub Organization, Figma File, and Behance Case Study.

Ensure the final code uses proper semantic HTML and Tailwind CSS utility classes exactly mapping to the provided HEX codes (e.g., `bg-[#000000]`, `text-[#F4F4F4]`, `bg-[#EE9033]`, `px-[16px]`). Output the complete, runnable code.