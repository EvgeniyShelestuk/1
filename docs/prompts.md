# AI Prompts

## NanoBanana Prompt v1

```text
Act as a senior UI/UX designer creating a modern landing page for a digital fitness product.

Project name: LumaFit AI

Concept:
LumaFit AI is an AI-powered fitness coach for busy people. It creates personalized 15-minute workouts, tracks habits, and gives simple daily guidance.

Create a complete website design with:
- Hero section
- Navigation menu
- Main content sections
- Clear call-to-action buttons
- Pricing or plan section
- Testimonials section
- Footer
- Mobile-responsive layout

Visual style:
- Clean, modern, energetic
- Premium SaaS + fitness app feeling
- White background with charcoal text
- Accent colors: electric teal and warm coral
- Rounded but professional UI
- Realistic app dashboard preview in the hero section
- Fitness, progress, habit tracking, and AI personalization should be visually clear

Layout requirements:
- Desktop website screenshot
- Mobile website screenshot
- Clear hierarchy
- Readable text
- Strong CTA: "Start Your Plan"
- Secondary CTA: "See How It Works"

Avoid:
- Generic stock photo look
- Overly dark design
- Too many gradients
- Cluttered layout
- Illegible small text

Output a polished website mockup suitable for development reference.
```

## NanoBanana Prompt v2

```text
Act as a senior product designer and brand designer. Improve the previous LumaFit AI website design into a more polished, production-ready responsive landing page.

Design goal:
Create a cohesive website for "LumaFit AI", an AI fitness coach that helps busy people build consistent fitness habits with 15-minute personalized workouts.

Brand direction:
- Confident, motivating, clean, and practical
- Not a bodybuilding brand
- Not a generic gym website
- Should feel like a smart health-tech product

Desktop layout:
1. Top navigation:
   Logo: LumaFit AI
   Links: Features, How It Works, Plans, Results
   CTA button: Start Your Plan

2. Hero section:
   Headline: "Your AI fitness coach for busy days"
   Supporting text: "Personalized 15-minute workouts, habit tracking, and daily guidance built around your schedule."
   Primary button: Start Your Plan
   Secondary button: See How It Works
   Include a realistic mobile app/dashboard preview showing workout plan, streak, progress chart, and AI coach tip.

3. Feature section:
   Three clear feature blocks:
   - Adaptive workouts
   - Habit streaks
   - Progress insights

4. How it works:
   Three simple steps:
   - Set your goal
   - Get your daily plan
   - Track your progress

5. Pricing section:
   Two plan cards: Starter and Pro

6. Testimonial section:
   Use realistic short user quotes

7. Footer:
   Logo, navigation links, social links, copyright

Mobile layout:
- Create a separate mobile version
- Single-column layout
- Sticky-feeling top nav or compact header
- Large readable CTA
- App preview should fit without overlapping text
- No text should be cropped

Visual constraints:
- Use mostly white and light neutral backgrounds
- Use charcoal for text
- Use electric teal and warm coral as accents
- Use subtle shadows only
- Avoid purple/blue gradient dominance
- Avoid decorative blobs or meaningless abstract shapes
- Keep cards clean with small border radius
- Use consistent spacing and alignment

Output:
Show both desktop and mobile website mockups. Make the design clean enough that a developer can recreate it accurately.
```

## NanoBanana Iteration Explanation

In the first prompt, I defined the general product concept, required website sections, visual direction, and basic constraints. The result established the brand and layout direction, but the prompt was still broad.

In the second prompt, I improved the output by adding a stronger role prompt, exact website structure, specific section content, CTA labels, mobile layout requirements, and stricter visual constraints. This made the design easier to control and more suitable as a development reference.

Prompt techniques used:

- Role prompting: asking the tool to act as a senior UI/UX designer and brand designer.
- Constraint-based instructions: defining colors, layout rules, responsive behavior, and avoid-list items.
- Structured formatting: using numbered website sections and precise content blocks.
- Style conditioning: describing the desired brand as clean, motivating, practical, and health-tech focused.
- Iterative refinement: improving the second prompt based on the first design output.

## dev0 Prompt

```text
Create a responsive landing page website for a product called LumaFit AI.

Use the attached NanoBanana design as the visual reference.

Product concept:
LumaFit AI is an AI-powered fitness coach for busy people. It creates personalized 15-minute workouts, habit streaks, and daily progress guidance.

Build requirements:
- Create a functional responsive website.
- Use clean semantic HTML, CSS, and minimal JavaScript.
- The first screen should be the real landing page, not a marketing explanation page.
- Recreate the design direction from the reference: white/light background, charcoal text, electric teal primary CTA, warm coral secondary accents, clean cards, subtle shadows, and a realistic app dashboard preview.
- Make the layout polished on desktop and mobile.
- Include navigation links: Features, How It Works, Plans, Results.
- Include CTA buttons: "Start Your Plan" and "See How It Works".
- Include these sections:
  1. Hero section with headline, supporting text, CTA buttons, and app dashboard preview.
  2. Three feature cards: Adaptive Workouts, Habit Streaks, Progress Insights.
  3. Three-step How It Works section: Set Your Goal, Get Your Daily Plan, Track Your Progress.
  4. Pricing section with Starter and Pro plans.
  5. Results/testimonial section.
  6. Footer with logo, navigation, and copyright.

Responsive requirements:
- On mobile, use a compact header and single-column content.
- Ensure all text remains readable.
- Ensure no dashboard, card, button, or heading overlaps.
- CTA buttons should be easy to tap.

Repository requirements:
- Add source code.
- Add README.md with project overview, concept, structure, and run instructions.
- Add resources.md with placeholders for YouTube video link, project image links, Suno audio link, external assets, and GitHub repository link.
- Keep the project clean and easy to push to GitHub.

After generation:
- Connect the project to my GitHub repository.
- Push the completed code to GitHub.
```

## dev0 Iteration / Adjustment Prompt

```text
Refine the LumaFit AI website.

Fix these issues:
- Improve mobile spacing so the dashboard preview does not feel cramped.
- Make the hero hierarchy closer to the NanoBanana reference.
- Keep cards at a small border radius and avoid decorative blobs.
- Make CTA buttons consistent across the page.
- Ensure the README.md and resources.md files are present in the repository root.

Do not change the core brand direction or product concept.
```

## VEO3 Prompt

```text
Create an 8-second promotional video for LumaFit AI.

Brand:
LumaFit AI is an AI-powered fitness coach for busy people. It creates personalized 15-minute workouts, habit streaks, and daily progress guidance.

Visual style:
Clean health-tech SaaS, bright white environment, charcoal text, electric teal and warm coral accents, modern app UI, energetic but not aggressive fitness mood.

Video structure:
0-2 seconds:
Show a busy professional opening the LumaFit AI app on a phone. On-screen text: "LumaFit AI"

2-5 seconds:
Show the app generating a personalized 15-minute workout plan with a progress chart, habit streak, and AI coach tip. Smooth UI animation, teal highlights, warm coral accents.

5-8 seconds:
Show the person starting a short workout confidently. End card with brand name and call to action: "Start Your Plan"

Constraints:
- Maximum 8 seconds.
- No cluttered text.
- Keep the style consistent with a clean fitness SaaS website.
- Use realistic lighting and polished product-ad visuals.
- Make the brand name and CTA clearly readable.
```

## Suno Prompt

```text
Create a short promotional music track for LumaFit AI, an AI fitness coach for busy people.

Style:
Modern upbeat electronic pop with light percussion, clean synth pulses, and a motivational but not aggressive tone.

Mood:
Fresh, focused, energetic, optimistic, health-tech.

Length:
Short promo-friendly audio suitable for an 8-second video.

Brand fit:
The sound should match a clean white fitness app website with electric teal and warm coral accents. It should feel like a smart morning workout routine, not a heavy gym commercial.

Avoid:
Dark trap, intense rock, dramatic cinematic music, or vocals that distract from a short product ad.
```
