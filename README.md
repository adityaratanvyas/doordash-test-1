# 🎁 Rewards US - DoorDash $500 Landing Page

Premium, minimalist, fully responsive single-page landing experience for the DoorDash $500 Dynamic Rewarded Discovery offer.

## 🌐 Live Demo

**URL:** `https://adityaratanvyas.github.io/doordash-test-1/`

Visit the link above to see the landing page in action.

---

## ✨ Features

### Design Excellence
- ✅ **Premium Minimalist Aesthetic** – Clean lines, refined typography, generous whitespace
- ✅ **Full-Screen Experience** – No scrolling required, all content visible in one viewport
- ✅ **Dark Gradient Background** – DoorDash-inspired color scheme (deep red, black, dark gray)
- ✅ **Orange Accent Color** (#ff4d00) – Professional and on-brand
- ✅ **Smooth Animations** – Elegant transitions without flashy effects

### Content Structure
- ✅ **Hero Section** – Strong headline with fade-up animation
- ✅ **Primary CTA Button** – Large, prominent "Claim Your Rewards" button
- ✅ **Three-Step Process** – Clean icons, benefit-focused copy, centered layout
- ✅ **Eligibility Notice** – Clear regional availability statement
- ✅ **Live Notifications** – Rotating reward claims in bottom-left corner

### Technical Excellence
- ✅ **Vanilla HTML5/CSS/JavaScript** – No dependencies or frameworks
- ✅ **Fully Responsive** – Desktop, tablet, mobile, and landscape modes
- ✅ **Mobile Optimized** – Full-width CTA, touch-friendly, proper spacing
- ✅ **Accessibility** – Reduced motion support, semantic HTML, dark mode preference
- ✅ **Performance** – GPU-accelerated animations, lightweight code

---

## 🎯 Customization Guide

### 1. **CTA Button Link**
Update the affiliate URL in `index.html` (line ~486):
```html
<a href="https://giftclick.org/aff_c?offer_id=455&aff_id=117413&source=doordash-test-1" 
   class="cta-button">Claim Your Rewards</a>
```

Change the `href` to your desired destination.

### 2. **Hero Headlines**
Update the main headline and subheading (lines ~480-481):
```html
<h1>Unlock <span class="accent">$500</span> in DoorDash Value</h1>
<p>Discover exclusive rewards tailored to your preferences. Seamless, rewarding, premium.</p>
```

### 3. **Accent Color**
Search for `#ff4d00` in the CSS and replace with your desired color:
- Update in background colors, text colors, borders, and effects

### 4. **Notification Names**
Add or modify names in the JavaScript section (lines ~573-581):
```javascript
const firstNames = ['Sarah', 'James', 'Emma', ...];
const lastNames = ['Smith', 'Johnson', 'Williams', ...];
```

### 5. **Reward Text**
Change the notification reward text (line ~583):
```javascript
const rewardText = 'DoorDash $500';
```

### 6. **Notification Timing**
Adjust display duration and hidden interval (lines ~617-618):
- **5000ms** = Display duration (5 seconds visible)
- **8000ms** = Hidden duration (8 seconds hidden before next)

---

## 🚀 Deployment

### GitHub Pages (Already Configured)
1. Your repository is already configured for GitHub Pages
2. Go to **Settings** → **Pages** → **Source** → **Deploy from Branch** → **Main**
3. Live URL: `https://adityaratanvyas.github.io/doordash-test-1/`

### Other Hosting Options
- **Netlify**: Connect repository, auto-deploys on push
- **Vercel**: Same as Netlify, excellent performance
- **AWS S3 + CloudFront**: Scalable for high traffic
- **Any Web Server**: Just upload the `index.html` file

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Optimization |
|--------|-----------|-------------|
| Desktop | 1024px+ | Full layout, 3-column steps |
| Tablet | 768px-1024px | Adjusted spacing, flexible layout |
| Mobile | 480px-768px | Full-width CTA, stacked steps |
| Small Mobile | <480px | Compact layout, mobile cards |
| Landscape | Max-height 600px | Special CSS for horizontal view |

---

## 🎨 Animation Details

### Notification Animations
- **Slide-In**: 0.5s smooth left entry with scale effect
- **Icon**: 0.6s rotate + scale entrance
- **Label**: Staggered fade-up (0.1s delay)
- **Text**: Staggered fade-up (0.2s delay)
- **Exit**: 0.6s smooth slide-out with fade
- **Pulse**: 2s continuous pulsing indicator

### Page Load
- **Hero**: 0.8s fade-up
- **CTA**: 1s fade-up (0.1s delay)
- **Steps**: 1.2s fade-up (0.2s delay)
- **Eligibility**: 1.4s fade-up (0.3s delay)

---

## ✅ Best Practices Applied

- ✅ **No "Free" Language** – Premium, confident tone throughout
- ✅ **No Urgency/Scarcity** – No countdowns or pushy language
- ✅ **Confident & Exclusive** – Professional, understated tone
- ✅ **Clean & Spacious** – Minimalist design with breathing room
- ✅ **GPU Accelerated** – Animations use transforms/opacity only
- ✅ **Mobile-First** – Scales beautifully down to small screens
- ✅ **Accessibility** – Respects user preferences for reduced motion

---

## 📊 File Structure

```
doordash-test-1/
├── index.html          # Complete landing page (single file)
├── README.md          # This documentation
└── .github/workflows/ # (Optional) CI/CD deployment
```

---

## 🔧 Browser Support

| Browser | Support |
|---------|----------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile Safari | ✅ Full |
| Chrome Mobile | ✅ Full |

---

## 📝 Content Guidelines

### Tone
- Confident, exclusive, premium
- Understated, not flashy
- Professional, clean language
- Zero urgency or pushy tactics

### Message Hierarchy
1. **Hero Headline** – Main value proposition
2. **Subheadline** – Supporting benefit
3. **CTA Button** – Clear call-to-action
4. **Steps** – How it works (easy to follow)
5. **Eligibility** – Legal/regional info

### Content Length
- Headlines: Short & punchy (no fluff)
- Descriptions: 1-2 short sentences max
- Button text: 2-3 words
- Step descriptions: 1-2 lines only

---

## 🎉 Ready to Launch!

Your premium DoorDash landing page is ready for production.

**Next Steps:**
1. ✅ Customize CTA link with your tracking parameters
2. ✅ Update hero headlines if needed
3. ✅ Test across devices
4. ✅ Deploy and monitor performance
5. ✅ Track conversions and optimize

**Live URL:** `https://adityaratanvyas.github.io/doordash-test-1/`

---

Built with ❤️ using vanilla HTML5, CSS, and JavaScript.