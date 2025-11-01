# 📚 Bookstore Template Development Roadmap (Vite + Tailwind + Vue)

This roadmap outlines the Minimum Viable Product (MVP) tasks and future expansion ideas, structured as a checklist for easy progress tracking.

---

## I. Core Template Structure (Static HTML & Tailwind MVP)

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P1-1** | [ ] | **A** | **Vite & Tailwind Verification** | Confirm `npm run dev` is running and Tailwind classes are compiling and reflected in the browser. |
| **P1-2** | [ ] | **B** | **Configuration Finalization** | Finalize core colors (Primary, Accent, Text) and any custom font stacks in `tailwind.config.js`. |
| **P1-3** | [ ] | **A** | **Header & Navigation (with Mega Menu)** | 🆕 Build **responsive header** including logo, search, account/cart icons, and **mega menu** for genres/authors. |
| **P1-4** | [ ] | **B** | **Footer Implementation** | Include About, Contact, Privacy, and Social links + **Instagram feed integration**. 🆕 |
| **P1-5** | [ ] | **B** | **Homepage Layout** | Hero Banner, Featured Categories, New Arrivals, and Bestseller sections with CTA blocks. |
| **P1-6** | [ ] | **A** | **Product Detail Page (PDP)** | Image Gallery, Description/Specs, Price/Format Picker, Reviews placeholder, and **Wishlist button**. 🆕 |
| **P1-7** | [ ] | **B** | **Author Bio / Spotlight Component** | 🆕 Optional author sidebar or dedicated component reused across product pages. |

---

## II. Product Listing Page (PLP) Readiness (Filter Core)

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P2-1** | [ ] | **A** | **Filter Sidebar HTML** | Genre, Author (autocomplete/checkbox), Format, Rating, and Tag toggles. |
| **P2-2** | [ ] | **A** | **Price & Format Filters** | Range slider (Min/Max) + Format radio buttons (ebook / print / audiobook). |
| **P2-3** | [ ] | **A** | **Reusable Product Card** | Image, Title, Author, Price, Format tag, and **Wishlist icon**. 🆕 |
| **P2-4** | [ ] | **A** | **Grid Mock-up** | Populate 20+ static cards using component from P2-3. |
| **P2-5** | [ ] | **B** | **PLP Top Bar** | Results count, Sort-by dropdown, and **Filter summary tags**. 🆕 |
| **P2-6** | [ ] | **B** | **Responsiveness & Polish** | Ensure sidebar/grid adapt to all breakpoints. |
| **P2-7** | [ ] | **B** | **Quick-View Modal** | 🆕 Implement a hover/tap preview of product info. |

---

## III. Vue.js Integration (Dynamic Functionality MVP)

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P3-1** | [ ] | **A** | **Vue Setup** | Install and configure Vue with Vite. |
| **P3-2** | [ ] | **A** | **Mock Data Store** | 50+ book objects with Genre, Author, Format, Price, Rating. |
| **P3-3** | [ ] | **A** | **Filter Component** | Mount `FilterSidebar.vue` and connect checkboxes/sliders to reactive state. |
| **P3-4** | [ ] | **A** | **Product Grid Component** | Consume store data and render cards dynamically. |
| **P3-5** | [ ] | **A** | **Core Filtering Logic** | Combine filters (multi-select + range) with instant computed results. |
| **P3-6** | [ ] | **B** | **Real-Time Update & Transition Animations** | Smooth transitions on grid updates. |
| **P3-7** | [ ] | **B** | **Wishlist State Management** | 🆕 LocalStorage-based wishlist persistence and icon state toggle. |

---

## 🚀 Future Options & Expansion

| ID | Status | Type | Task Description | Goal |
| :---: | :---: | :---: | :--- | :--- |
| **F1-1** | [ ] | **Quiz** | **Book Recommendation Quiz** | Vue multi-step quiz that filters PLP results. |
| **F1-2** | [ ] | **Search** | **Ajax/Instant Search** | Live autocomplete with results dropdown. |
| **F1-3** | [ ] | **Platform** | **Shopify/WooCommerce Block Mapping** | Tag key sections with `data-shopify-section` comments for conversion. |
| **F1-4** | [ ] | **State** | **URL State Management** | Persist filters in query params. |
| **F1-5** | [ ] | **Performance** | **TypeScript Conversion** | Gradual TS refactor. |
| **F1-6** | [ ] | **UI** | **Advanced Mega Menu Enhancements** | 🆕 Add icons, cover previews, and featured author blocks inside mega menu. |
| **F1-7** | [ ] | **Integration** | **Instagram Feed Component** | 🆕 Pull recent posts using GraphQL API or static JSON; grid with hover captions. |
| **F1-8** | [ ] | **UX** | **Reader Club / Newsletter Modal** | 🆕 Modal opt-in tied to email capture and discount automation. |
| **F1-9** | [ ] | **Analytics** | **Engagement Tracking** | Optional tracking for wishlist interactions and filter usage. |

---
