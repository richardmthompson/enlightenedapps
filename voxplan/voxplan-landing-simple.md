# VoxPlan Landing Page - Simple Version

## Above the Fold

**Headline:** Stop Managing Tasks. Start Achieving Goals.

**Subheadline:** The Android app that turns ambitious goals into daily focused action — with a gamified timer that makes deep work addictive.

**CTA Buttons:**
- [Download APK] (Primary - Green)
- [View on GitHub] (Secondary - Outline)

**Hero Image:** Phone mockup showing the app's goal hierarchy

---

## 3 Key Features (Icons + Short Text)

### 🎯 Hierarchical Goals
Organize goals naturally in a 3-level tree. Complex enough to be meaningful, simple enough to stay sane.

### ⏱️ Daily Time Quotas
Set minute targets for each goal. "60 min coding Mon-Fri" or "30 min guitar daily."

### 🏅 Gamified Focus
Earn medals every 30 minutes. Bronze → Silver → Gold → Diamond. Real rewards for real focus.

---

## How It Works (4 Steps)

1. **Create Your Goal Tree**
   Break "Learn Guitar" into "Master Chords" into "Practice F Chord"

2. **Set Daily Quotas**
   Decide how many minutes per day and which days

3. **Start Focus Mode**
   Timer runs, distractions disappear, medals accumulate

4. **Track Progress**
   See your weekly achievements with visual indicators

---

## Download Section

### VoxPlan v3.2 for Android

**[Download APK (2.4 MB)]** - Big green button

✓ Android 8.1+ Required
✓ No ads, no tracking
✓ 100% Free & Open Source

*Google Play Store coming soon*

---

## Developer Section

### Built by Richard Thompson

AI Engineer | Android Developer | Productivity Enthusiast

"I built VoxPlan because every other app treats time management wrong. Goals aren't lists — they're trees. Time isn't infinite — it's your only real constraint."

[GitHub] [Twitter] [LinkedIn]

---

## Footer

© 2025 Enlightened Apps | [Privacy] | [Terms] | [Contact]

---

# Quick Implementation Guide

## Essential Assets Needed

1. **Screenshots** (3-4 key screens):
   - Goal hierarchy view
   - Focus mode with timer
   - Progress/quota tracking
   - Medal achievement

2. **APK File**:
   - Signed release build
   - Version 3.2
   - ~2.4 MB size

3. **Icons/Graphics**:
   - App icon (512x512)
   - Feature icons (hierarchical, timer, medal)
   - Optional: Phone mockup

## HTML Structure (Tailwind CSS)

```html
<!-- Hero Section -->
<section class="bg-gradient-to-b from-green-50 to-white py-20">
  <div class="container mx-auto px-4">
    <h1 class="text-5xl font-bold text-gray-900 mb-4">
      Stop Managing Tasks. Start Achieving Goals.
    </h1>
    <p class="text-xl text-gray-600 mb-8 max-w-2xl">
      The Android app that turns ambitious goals into daily focused action —
      with a gamified timer that makes deep work addictive.
    </p>
    <div class="flex gap-4">
      <a href="/download/voxplan.apk"
         class="bg-green-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-green-700">
        Download APK
      </a>
      <a href="https://github.com/richardmthompson/VoxPlanApp"
         class="border-2 border-green-600 text-green-600 px-8 py-3 rounded-lg font-semibold hover:bg-green-50">
        View on GitHub
      </a>
    </div>
  </div>
</section>

<!-- Features Grid -->
<section class="py-16">
  <div class="container mx-auto px-4 grid md:grid-cols-3 gap-8">
    <div class="text-center">
      <div class="text-4xl mb-4">🎯</div>
      <h3 class="text-xl font-bold mb-2">Hierarchical Goals</h3>
      <p class="text-gray-600">
        Organize goals naturally in a 3-level tree.
        Complex enough to be meaningful, simple enough to stay sane.
      </p>
    </div>
    <!-- Repeat for other features -->
  </div>
</section>
```

## Deployment Checklist

- [ ] Build signed APK from Android Studio
- [ ] Upload APK to server/CDN
- [ ] Take 4-5 high-quality screenshots
- [ ] Create simple landing page (HTML or Markdown-to-HTML)
- [ ] Add download tracking (optional - Google Analytics event)
- [ ] Test download on real Android device
- [ ] Share on Twitter/LinkedIn
- [ ] Submit to Product Hunt (Tuesday optimal)

## Quick Win URLs

After deployment, the landing page could live at:
- `enlightenedapps.dev/voxplan`
- `arlabs.tech/projects/voxplan`
- `voxplan.enlightenedapps.dev` (subdomain)