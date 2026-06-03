# StyleGlobe — Full Project Documentation

**Course:** E-Commerce and Web Application  
**Assignment:** Group Assignment II — UI/UX Design Using Figma  
**Institution:** University of Lay Adventists of Kigali (UNILAK)  

---

## 👥 Group Members

| Name | Registration Number |
|------|-------------------|
| [Member 1 Full Name] | [Reg. Number] |
| [Member 2 Full Name] | [Reg. Number] |

---

## 1. 🧩 Problem Statement

### What problem does the application solve?
Shopping for fashion and clothing globally is often fragmented, inconsistent, and frustrating. Consumers face challenges such as:
- Difficulty finding trendy, quality clothing across different brands in one place
- Lack of personalized recommendations based on style preferences
- Poor mobile shopping experiences with confusing navigation
- Limited size guides and unclear product descriptions leading to wrong purchases
- Complicated or untrustworthy checkout processes

**StyleGlobe** solves these problems by offering a single, elegant platform where users can discover, browse, and purchase fashion items from global brands and independent designers — all within a smooth, personalized, and secure mobile experience.

### Who are the target users?
- Fashion-conscious individuals aged 18–40 worldwide
- Online shoppers who prefer mobile-first experiences
- People who follow global fashion trends
- Budget-conscious buyers looking for deals and discounts
- Style explorers who enjoy discovering new brands

### Why is the system important?
The global online fashion market is worth over $1 trillion and growing rapidly. A well-designed, user-centered fashion app can significantly improve the shopping experience, reduce cart abandonment, increase customer loyalty, and help both buyers and sellers thrive in the digital economy.

---

## 2. 👤 User Personas

### Persona 1 — Primary User

| Field | Details |
|-------|---------|
| **Name** | Amara Diallo |
| **Age** | 26 |
| **Occupation** | Marketing Specialist |
| **Location** | Nairobi, Kenya |
| **Device** | iPhone 14, shops mostly on mobile |
| **Goals** | Discover the latest fashion trends, buy quality clothing at fair prices, track her orders easily |
| **Challenges/Frustrations** | Overwhelmed by too many options with poor filtering, distrust of unclear return policies, slow-loading apps with poor UX, difficulty finding her size across different brand sizing |

### Persona 2 — Secondary User

| Field | Details |
|-------|---------|
| **Name** | Lucas Ferreira |
| **Age** | 32 |
| **Occupation** | Freelance Graphic Designer |
| **Location** | São Paulo, Brazil |
| **Device** | Android Samsung, heavy social media user |
| **Goals** | Shop for unique, designer pieces, save favorite items and share with friends, get notified about sales |
| **Challenges/Frustrations** | Hard to find unique/indie brands, checkout processes are too long, apps don't remember preferences |

---

## 3. 🗺️ User Flow Diagram

### Main User Flow

```
[Splash Screen]
      ↓
[Onboarding (3 slides)]
      ↓
[Login / Register]
      ↓
[Home Page]
      ├──→ [Search & Filter]
      │         ↓
      │   [Product Listing]
      │         ↓
      │   [Product Detail Page]
      │         ↓
      │   [Add to Cart / Wishlist]
      │
      ├──→ [Categories Browse]
      │         ↓
      │   [Product Listing]
      │
      └──→ [Profile Page]
                ├── My Orders
                ├── Wishlist
                ├── Settings
                └── Logout

[Cart]
  ↓
[Checkout]
  ├── Shipping Address
  ├── Payment Method
  └── Order Summary
        ↓
[Order Confirmation]
        ↓
[Order Tracking]
```

### Key Navigation Flow Summary

| Step | Screen |
|------|--------|
| 1 | Splash Screen |
| 2 | Onboarding |
| 3 | Login / Register |
| 4 | Home Page |
| 5 | Browse Categories or Search |
| 6 | Product Listing |
| 7 | Product Detail |
| 8 | Cart |
| 9 | Checkout |
| 10 | Order Confirmation |

---

## 4. 📐 Wireframes (Low-Fidelity Design)

### Screen 1 — Login / Register
- App logo at top center
- Email input field
- Password input field
- "Login" button (primary)
- "Register" link below
- Social login options (Google, Apple)

### Screen 2 — Home Page
- Top bar: Search icon + Cart icon + Profile avatar
- Banner/Hero carousel (featured collections)
- Category icons row (Women, Men, Kids, Sale, New In)
- "Trending Now" horizontal scroll product cards
- "Recommended for You" product grid

### Screen 3 — Product Detail Page
- Full-width product image (swipeable gallery)
- Product name, brand, price
- Size selector (XS, S, M, L, XL)
- Color selector
- "Add to Cart" button (primary)
- "Add to Wishlist" icon
- Product description & details accordion
- Reviews section

### Screen 4 — Cart & Checkout
- List of cart items (image, name, size, price, quantity controls)
- Subtotal, shipping, total breakdown
- "Proceed to Checkout" button
- Checkout: address form → payment method → order summary → confirm

### Screen 5 — Profile Page
- User avatar + name + email
- My Orders (list with status badges)
- Wishlist shortcut
- Settings, Notifications, Help & Support
- Logout button

### Screen 6 — Search & Filter
- Search bar (active state)
- Recent searches
- Filter panel: Category, Price Range, Size, Color, Brand, Rating
- Sorted product grid results

---

## 5. 🎨 High-Fidelity UI Design

### Design System

#### Color Palette
| Role | Color | Hex |
|------|-------|-----|
| Primary | Deep Charcoal | `#1A1A2E` |
| Accent | Warm Gold | `#E8B86D` |
| Background | Off White | `#F8F6F2` |
| Surface | Pure White | `#FFFFFF` |
| Text Primary | Near Black | `#1C1C1C` |
| Text Secondary | Medium Gray | `#7A7A7A` |
| Success | Sage Green | `#4CAF82` |
| Error | Soft Red | `#E05252` |

#### Typography
| Role | Font | Weight | Size |
|------|------|--------|------|
| Display / Logo | Playfair Display | Bold | 28–36px |
| Headings | Cormorant Garamond | SemiBold | 20–24px |
| Body | DM Sans | Regular | 14–16px |
| Captions | DM Sans | Light | 12px |
| Buttons | DM Sans | Medium | 15px |

#### Screens Designed (Minimum 6)
1. **Splash Screen** — Logo centered on deep charcoal background, animated gold underline
2. **Onboarding** — 3 illustrated slides with bold fashion photography mockups
3. **Login / Register** — Clean form on white, gold CTA button, social login
4. **Home Page** — Hero banner, category chips, trending products grid
5. **Category Browse** — Full-bleed category cards (Women, Men, Kids, Sale)
6. **Product Listing** — 2-column grid, filter chips, sort dropdown
7. **Product Detail** — Immersive image gallery, size/color selectors, sticky CTA
8. **Cart** — Item list with swipe-to-delete, price summary, checkout CTA
9. **Checkout** — Multi-step form (Address → Payment → Review)
10. **Order Confirmation** — Success animation, order number, "Continue Shopping"
11. **Profile Page** — User info card, order history, settings list
12. **Wishlist** — Saved items grid with quick-add-to-cart

---

## 6. 🔗 Interactive Prototype

### Prototype Interactions Implemented
- Splash screen auto-transitions to Onboarding after 2 seconds
- Onboarding slides swipe left/right with dot indicators
- "Get Started" button navigates to Login/Register
- Login → Home Page on success
- Category tap → Product Listing
- Product card tap → Product Detail
- "Add to Cart" → Cart badge updates, Cart screen accessible
- Cart → Checkout multi-step flow
- Order Confirm → back to Home
- Bottom navigation bar (Home, Search, Wishlist, Cart, Profile) active on all main screens

**Figma Prototype Link:** [View Interactive Prototype →](#) *(add your link)*

---

## 7. ♿ Accessibility Considerations

| Consideration | Implementation |
|--------------|----------------|
| **Font sizes** | Minimum 14px for body text, 12px for captions only |
| **Color contrast** | All text meets WCAG AA contrast ratio (4.5:1 minimum) |
| **Touch targets** | All buttons minimum 44×44px for easy tapping |
| **Navigation** | Clear bottom navigation bar always visible |
| **Feedback** | Loading spinners, success/error toasts for all actions |
| **Images** | Alt text labels on all product images |
| **Forms** | Clear labels, inline error messages, not just color-coded |
| **Consistency** | Same icons, colors, and patterns used throughout |

---

## 8. ✅ Features Implemented

- User onboarding flow
- Authentication (Login & Register)
- Home page with hero banners and product highlights
- Category browsing
- Product search with filters (category, price, size, color)
- Product detail with image gallery
- Wishlist / Save for later
- Shopping cart with quantity management
- Multi-step checkout (address, payment, confirmation)
- Order confirmation and tracking status
- User profile with order history
- Bottom navigation bar

---

## 9. 🚧 Challenges Faced

- **Consistency across screens:** Maintaining the same design language (spacing, typography, colors) across 12+ screens required careful use of Figma components and styles.
- **Mobile constraints:** Fitting all necessary information on small screens without cluttering required multiple iterations of layout adjustments.
- **User flow complexity:** Designing a smooth checkout flow that feels simple but handles all edge cases (address, payment, confirmation) was challenging.
- **Sizing across brands:** Representing a universal size selector that works for global brands required creative UI solutions.

---

## 10. 🏁 Conclusion

StyleGlobe successfully demonstrates a modern, user-centered fashion e-commerce mobile application designed for a global audience. Through thorough research, user persona development, and iterative design using Figma, we created a prototype that prioritizes usability, visual appeal, and accessibility. The project allowed us to apply core UI/UX principles including wireframing, high-fidelity design, component-based systems, and interactive prototyping — all within a real-world e-commerce context.

---

*Submitted by Group [X] | UNILAK | E-Commerce and Web Application | June 2026*
