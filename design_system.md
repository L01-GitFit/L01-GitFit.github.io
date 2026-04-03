## Design System: GitFit

### Pattern
- **Name:** App Store Style Landing
- **Conversion Focus:** Show real screenshots. Include ratings (4.5+ stars). QR code for mobile. Platform-specific CTAs.
- **CTA Placement:** Download buttons prominent (App Store + Play Store) throughout
- **Color Strategy:** Dark/light matching app store feel. Star ratings in gold. Screenshots with device frames.
- **Sections:** 1. Hero with device mockup, 2. Screenshots carousel, 3. Features with icons, 4. Reviews/ratings, 5. Download CTAs

### Style
- **Name:** Social Proof-Focused
- **Keywords:** Testimonials prominent, client logos displayed, case studies sections, reviews/ratings, user avatars, success metrics, credibility markers
- **Best For:** B2B SaaS, professional services, premium products, e-commerce conversion pages, established brands
- **Performance:** ⚡ Good | **Accessibility:** ✓ WCAG AA

### Colors
| Role | Hex |
|------|-----|
| Primary | #0EA5E9 |
| Secondary | #38BDF8 |
| CTA | #F97316 |
| Background | #F0F9FF |
| Text | #0C4A6E |

*Notes: Sky blue trust + warm CTA*

### Typography
- **Heading:** Barlow Condensed
- **Body:** Barlow
- **Mood:** sports, fitness, athletic, energetic, condensed, action
- **Best For:** Sports, fitness, gyms, athletic brands, competition
- **Google Fonts:** https://fonts.google.com/share?selection.family=Barlow+Condensed:wght@400;500;600;700|Barlow:wght@300;400;500;600;700
- **CSS Import:**
```css
@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;500;600;700&family=Barlow:wght@300;400;500;600;700&display=swap');
```

### Key Effects
Testimonial carousel animations, logo grid fade-in, stat counter animations (number count-up), review star ratings

### Avoid (Anti-patterns)
- Complex navigation
- Hidden contact info

### Pre-Delivery Checklist
- [ ] No emojis as icons (use SVG: Heroicons/Lucide)
- [ ] cursor-pointer on all clickable elements
- [ ] Hover states with smooth transitions (150-300ms)
- [ ] Light mode: text contrast 4.5:1 minimum
- [ ] Focus states visible for keyboard nav
- [ ] prefers-reduced-motion respected
- [ ] Responsive: 375px, 768px, 1024px, 1440px

