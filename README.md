<div align="center">

# 🎨 Tailwind Landing Blocks

[![Stars](https://img.shields.io/github/stars/turkcode-ai/tailwind-landing-blocks?style=social)](https://github.com/turkcode-ai/tailwind-landing-blocks)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

**150+ Copy-Paste Tailwind CSS Landing Page Components**

Hero • Features • Pricing • Testimonials • CTA • Footer • Navigation

[Browse Components](#-components) • [Quick Start](#-quick-start) • [Live Demo](https://tailwind-landing-blocks.vercel.app)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=06B6D4&center=true&vCenter=true&width=500&lines=150%2B+Production+Ready+Components;Copy+%26+Paste+%E2%86%92+Ship;Dark+Mode+%7C+Responsive+%7C+A11y" alt="Typing SVG" />

</div>

---

## ✨ Why This?

- **🚀 Ship Fast** - Copy, paste, customize, done
- **📱 Responsive** - Mobile-first, works everywhere
- **🌙 Dark Mode** - All components support dark mode
- **♿ Accessible** - WCAG 2.1 compliant
- **⚡ Performance** - Pure CSS, no JavaScript required
- **🎨 Customizable** - Easy to modify with Tailwind

---

## 🧩 Components

### Navigation (15+)

| Component | Variants | Features |
|-----------|----------|----------|
| **Navbar** | Simple, Centered, Mega Menu | Sticky, Mobile drawer, CTA button |
| **Sidebar** | Dashboard, Collapsible | Icons, Nested items, Badge |
| **Breadcrumb** | Simple, With icons | Responsive |
| **Mobile Menu** | Slide, Overlay, Bottom sheet | Animation, Backdrop |

### Hero Sections (25+)

| Style | Description |
|-------|-------------|
| **Centered** | Classic centered hero with CTA |
| **Split** | Image on side, content opposite |
| **Video Background** | Full-width video hero |
| **Gradient** | Animated gradient backgrounds |
| **3D** | Perspective effects |
| **Minimal** | Clean, typography-focused |
| **Product** | App screenshot showcase |
| **Dark** | Dark theme variations |

### Feature Sections (20+)

| Style | Description |
|-------|-------------|
| **Grid** | 3-4 column feature grid |
| **Alternating** | Zig-zag layout with images |
| **Icon Cards** | Cards with icons |
| **List** | Checklist style features |
| **Tabs** | Tabbed feature showcase |
| **Comparison** | Before/after or vs layout |
| **Bento** | Modern bento grid layout |

### Pricing Tables (15+)

| Style | Description |
|-------|-------------|
| **Simple** | 3-tier pricing |
| **Highlighted** | With popular badge |
| **Toggle** | Monthly/yearly switch |
| **Comparison** | Full feature comparison |
| **Enterprise** | With custom quote CTA |
| **Gradient** | Gradient backgrounds |

### Testimonials (15+)

| Style | Description |
|-------|-------------|
| **Cards** | Grid of testimonial cards |
| **Carousel** | Sliding testimonials |
| **Quote** | Large quote with avatar |
| **Wall** | Masonry testimonial wall |
| **Video** | Video testimonials |
| **Tweet** | Twitter-style cards |

### CTA Sections (12+)

| Style | Description |
|-------|-------------|
| **Simple** | Centered with button |
| **Newsletter** | Email subscription |
| **Download** | App download buttons |
| **Split** | Image + form |
| **Banner** | Full-width banner |
| **Floating** | Fixed bottom CTA |

### Footer (10+)

| Style | Description |
|-------|-------------|
| **Simple** | Links + copyright |
| **Multi-column** | 4-5 columns |
| **Newsletter** | With subscription |
| **Social** | Social icons focus |
| **Dark** | Dark variations |
| **Minimal** | Super clean |

### Other Components (40+)

- **FAQ** - Accordion, grid, tabs
- **Team** - Cards, grid, carousel
- **Stats** - Numbers, charts, counters
- **Logos** - Client/partner logos
- **Contact** - Forms, maps, info
- **Blog** - Post cards, grids
- **404** - Error pages
- **Login/Signup** - Auth forms

---

## 🚀 Quick Start

### Option 1: Copy from README

Browse sections below, copy the code you need.

### Option 2: Clone Repository

```bash
git clone https://github.com/turkcode-ai/tailwind-landing-blocks.git
cd tailwind-landing-blocks
pnpm install
pnpm dev
```

### Option 3: CDN (HTML only)

```html
<!DOCTYPE html>
<html>
<head>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
  <!-- Paste components here -->
</body>
</html>
```

---

## 📦 Code Examples

### Hero - Centered with Gradient

```html
<section class="relative overflow-hidden bg-gradient-to-br from-indigo-500 via-purple-500 to-pink-500">
  <div class="absolute inset-0 bg-[url('/grid.svg')] opacity-20"></div>
  <div class="relative mx-auto max-w-7xl px-6 py-24 sm:py-32 lg:px-8 lg:py-40">
    <div class="mx-auto max-w-2xl text-center">
      <h1 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">
        Build beautiful landing pages in minutes
      </h1>
      <p class="mt-6 text-lg leading-8 text-white/80">
        Copy-paste Tailwind CSS components for your next project. 
        Fully responsive, accessible, and customizable.
      </p>
      <div class="mt-10 flex items-center justify-center gap-x-6">
        <a href="#" class="rounded-full bg-white px-8 py-3 text-sm font-semibold text-indigo-600 shadow-lg hover:bg-gray-100 transition-all hover:scale-105">
          Get Started
        </a>
        <a href="#" class="text-sm font-semibold text-white hover:text-white/80">
          Learn more <span aria-hidden="true">→</span>
        </a>
      </div>
    </div>
  </div>
</section>
```

### Feature Grid with Icons

```html
<section class="py-24 bg-white dark:bg-gray-900">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl text-center">
      <h2 class="text-base font-semibold text-indigo-600 dark:text-indigo-400">
        Features
      </h2>
      <p class="mt-2 text-3xl font-bold tracking-tight text-gray-900 dark:text-white sm:text-4xl">
        Everything you need to ship fast
      </p>
    </div>
    <div class="mx-auto mt-16 max-w-5xl">
      <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
        <!-- Feature 1 -->
        <div class="group relative rounded-2xl border border-gray-200 dark:border-gray-700 p-8 hover:border-indigo-500 transition-colors">
          <div class="flex h-12 w-12 items-center justify-center rounded-xl bg-indigo-500 text-white">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <h3 class="mt-6 text-lg font-semibold text-gray-900 dark:text-white">
            Lightning Fast
          </h3>
          <p class="mt-2 text-gray-600 dark:text-gray-400">
            Pure CSS components with zero JavaScript. Blazing fast load times.
          </p>
        </div>
        <!-- Feature 2 -->
        <div class="group relative rounded-2xl border border-gray-200 dark:border-gray-700 p-8 hover:border-indigo-500 transition-colors">
          <div class="flex h-12 w-12 items-center justify-center rounded-xl bg-indigo-500 text-white">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" />
            </svg>
          </div>
          <h3 class="mt-6 text-lg font-semibold text-gray-900 dark:text-white">
            Fully Responsive
          </h3>
          <p class="mt-2 text-gray-600 dark:text-gray-400">
            Mobile-first design that looks great on any screen size.
          </p>
        </div>
        <!-- Feature 3 -->
        <div class="group relative rounded-2xl border border-gray-200 dark:border-gray-700 p-8 hover:border-indigo-500 transition-colors">
          <div class="flex h-12 w-12 items-center justify-center rounded-xl bg-indigo-500 text-white">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
            </svg>
          </div>
          <h3 class="mt-6 text-lg font-semibold text-gray-900 dark:text-white">
            Dark Mode Ready
          </h3>
          <p class="mt-2 text-gray-600 dark:text-gray-400">
            All components include dark mode variants out of the box.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
```

### Pricing - 3 Tier with Toggle

```html
<section class="py-24 bg-gray-50 dark:bg-gray-900">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl text-center">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white sm:text-4xl">
        Simple, transparent pricing
      </h2>
      <p class="mt-4 text-lg text-gray-600 dark:text-gray-400">
        Choose the plan that's right for you
      </p>
    </div>
    <div class="mx-auto mt-16 grid max-w-5xl gap-8 lg:grid-cols-3">
      <!-- Free -->
      <div class="rounded-2xl border border-gray-200 dark:border-gray-700 bg-white dark:bg-gray-800 p-8">
        <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Starter</h3>
        <p class="mt-2 text-sm text-gray-600 dark:text-gray-400">Perfect for side projects</p>
        <p class="mt-6">
          <span class="text-4xl font-bold text-gray-900 dark:text-white">$0</span>
          <span class="text-gray-600 dark:text-gray-400">/month</span>
        </p>
        <ul class="mt-8 space-y-4">
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            10 components
          </li>
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Basic support
          </li>
        </ul>
        <a href="#" class="mt-8 block w-full rounded-lg border border-gray-300 dark:border-gray-600 py-3 text-center text-sm font-semibold text-gray-900 dark:text-white hover:bg-gray-50 dark:hover:bg-gray-700 transition-colors">
          Get started
        </a>
      </div>
      <!-- Pro -->
      <div class="rounded-2xl border-2 border-indigo-500 bg-white dark:bg-gray-800 p-8 relative">
        <span class="absolute -top-4 left-1/2 -translate-x-1/2 rounded-full bg-indigo-500 px-4 py-1 text-xs font-semibold text-white">
          Popular
        </span>
        <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Pro</h3>
        <p class="mt-2 text-sm text-gray-600 dark:text-gray-400">For growing businesses</p>
        <p class="mt-6">
          <span class="text-4xl font-bold text-gray-900 dark:text-white">$29</span>
          <span class="text-gray-600 dark:text-gray-400">/month</span>
        </p>
        <ul class="mt-8 space-y-4">
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Unlimited components
          </li>
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Priority support
          </li>
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Figma files
          </li>
        </ul>
        <a href="#" class="mt-8 block w-full rounded-lg bg-indigo-500 py-3 text-center text-sm font-semibold text-white hover:bg-indigo-600 transition-colors">
          Get started
        </a>
      </div>
      <!-- Enterprise -->
      <div class="rounded-2xl border border-gray-200 dark:border-gray-700 bg-white dark:bg-gray-800 p-8">
        <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Enterprise</h3>
        <p class="mt-2 text-sm text-gray-600 dark:text-gray-400">For large teams</p>
        <p class="mt-6">
          <span class="text-4xl font-bold text-gray-900 dark:text-white">$99</span>
          <span class="text-gray-600 dark:text-gray-400">/month</span>
        </p>
        <ul class="mt-8 space-y-4">
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Everything in Pro
          </li>
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Dedicated support
          </li>
          <li class="flex items-center gap-3 text-sm text-gray-600 dark:text-gray-400">
            <svg class="h-5 w-5 text-indigo-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
            Custom components
          </li>
        </ul>
        <a href="#" class="mt-8 block w-full rounded-lg border border-gray-300 dark:border-gray-600 py-3 text-center text-sm font-semibold text-gray-900 dark:text-white hover:bg-gray-50 dark:hover:bg-gray-700 transition-colors">
          Contact sales
        </a>
      </div>
    </div>
  </div>
</section>
```

### Testimonial Cards

```html
<section class="py-24 bg-white dark:bg-gray-900">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl text-center">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white sm:text-4xl">
        Loved by developers worldwide
      </h2>
    </div>
    <div class="mx-auto mt-16 grid max-w-5xl gap-8 md:grid-cols-2 lg:grid-cols-3">
      <!-- Testimonial 1 -->
      <div class="rounded-2xl bg-gray-50 dark:bg-gray-800 p-8">
        <div class="flex gap-1">
          <svg class="h-5 w-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
          </svg>
          <!-- Repeat 5x -->
        </div>
        <p class="mt-6 text-gray-600 dark:text-gray-400">
          "These components saved me weeks of work. The code quality is excellent 
          and they're so easy to customize."
        </p>
        <div class="mt-6 flex items-center gap-4">
          <img src="https://i.pravatar.cc/100?img=1" alt="Avatar" class="h-12 w-12 rounded-full">
          <div>
            <p class="font-semibold text-gray-900 dark:text-white">Sarah Johnson</p>
            <p class="text-sm text-gray-600 dark:text-gray-400">Founder, TechCo</p>
          </div>
        </div>
      </div>
      <!-- Add more testimonials -->
    </div>
  </div>
</section>
```

### Newsletter CTA

```html
<section class="py-24 bg-indigo-600">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl text-center">
      <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
        Get updates in your inbox
      </h2>
      <p class="mt-4 text-lg text-indigo-100">
        Join 10,000+ developers getting weekly component updates
      </p>
      <form class="mt-10 flex flex-col sm:flex-row gap-4 justify-center">
        <input 
          type="email" 
          placeholder="Enter your email" 
          class="min-w-[300px] rounded-lg border-0 px-4 py-3 text-gray-900 placeholder:text-gray-500 focus:ring-2 focus:ring-white"
        >
        <button 
          type="submit" 
          class="rounded-lg bg-white px-8 py-3 font-semibold text-indigo-600 hover:bg-indigo-50 transition-colors"
        >
          Subscribe
        </button>
      </form>
      <p class="mt-4 text-sm text-indigo-200">
        No spam, unsubscribe anytime
      </p>
    </div>
  </div>
</section>
```

### Footer - Multi Column

```html
<footer class="bg-gray-900 text-gray-400">
  <div class="mx-auto max-w-7xl px-6 py-16 lg:px-8">
    <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-5">
      <!-- Brand -->
      <div class="lg:col-span-2">
        <a href="#" class="text-2xl font-bold text-white">TurkCode</a>
        <p class="mt-4 max-w-xs">
          Beautiful landing page components for your next project.
        </p>
        <div class="mt-6 flex gap-4">
          <a href="#" class="hover:text-white transition-colors">
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/></svg>
          </a>
          <a href="#" class="hover:text-white transition-colors">
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
          </a>
        </div>
      </div>
      <!-- Links -->
      <div>
        <h3 class="text-sm font-semibold text-white">Product</h3>
        <ul class="mt-4 space-y-3 text-sm">
          <li><a href="#" class="hover:text-white transition-colors">Features</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Pricing</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Components</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Templates</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-sm font-semibold text-white">Company</h3>
        <ul class="mt-4 space-y-3 text-sm">
          <li><a href="#" class="hover:text-white transition-colors">About</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Blog</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Careers</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Contact</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-sm font-semibold text-white">Legal</h3>
        <ul class="mt-4 space-y-3 text-sm">
          <li><a href="#" class="hover:text-white transition-colors">Privacy</a></li>
          <li><a href="#" class="hover:text-white transition-colors">Terms</a></li>
          <li><a href="#" class="hover:text-white transition-colors">License</a></li>
        </ul>
      </div>
    </div>
    <div class="mt-16 border-t border-gray-800 pt-8 text-sm">
      <p>&copy; 2024 TurkCode. All rights reserved.</p>
    </div>
  </div>
</footer>
```

---

## 🎨 Customization

### Tailwind Config

```javascript
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        brand: {
          50: '#f0f9ff',
          500: '#0ea5e9',
          600: '#0284c7',
          700: '#0369a1',
        }
      },
      fontFamily: {
        sans: ['Inter', 'sans-serif'],
        display: ['Cal Sans', 'sans-serif'],
      }
    }
  }
}
```

### Global Styles

```css
/* globals.css */
@layer base {
  html {
    scroll-behavior: smooth;
  }
  
  ::selection {
    background-color: theme('colors.indigo.500');
    color: white;
  }
}
```

---

## 📋 Frameworks Support

| Framework | Support |
|-----------|---------|
| HTML | ✅ Copy-paste |
| React/Next.js | ✅ Full support |
| Vue/Nuxt | ✅ Full support |
| Svelte | ✅ Full support |
| Astro | ✅ Full support |
| Laravel Blade | ✅ Full support |
| PHP | ✅ Full support |

---

## 🤝 Contributing

1. Fork the repository
2. Add your component in the relevant category
3. Ensure dark mode support
4. Test responsiveness
5. Submit a PR

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📄 License

MIT License - see [LICENSE](LICENSE)

---

## 💖 Support

- ⭐ Star this repo
- 🐦 [Follow on Twitter](https://twitter.com/ersindorlak)
- 💬 [Join Discord](https://discord.gg/turkcode)

---

<div align="center">

[![GitHub](https://img.shields.io/badge/Made%20by-Ersin%20Dorlak-0369A1?style=for-the-badge)](https://ersindorlak.com)

**Part of the [TurkCode](https://turkcode.net) ecosystem**

</div>
