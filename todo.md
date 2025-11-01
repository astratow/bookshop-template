# 📚 Bookstore Template Development Roadmap (Vite + Tailwind + Vue)

This roadmap outlines the Minimum Viable Product (MVP) tasks and future expansion ideas, structured as a checklist for easy progress tracking.

---

## I. Core Template Structure (Static HTML & Tailwind MVP)

The focus is building the static, semantic HTML skeleton styled with Tailwind CSS.

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P1-1** | [ ] | **A** | **Vite & Tailwind Verification** | Confirm `npm run dev` is running and Tailwind classes are compiling and reflected in the browser. |
| **P1-2** | [ ] | **B** | **Configuration Finalization** | Finalize core colors (Primary, Accent, Text) and any custom font stacks in `tailwind.config.js`. |
| **P1-3** | [ ] | **A** | **Header & Navigation** | Implement **responsive Header** with Logo, Primary Navigation, Search Bar, and Cart/Account Icons. |
| **P1-4** | [ ] | **B** | **Footer Implementation** | Build the full Footer with About, Contact, Privacy, and Social Media links. |
| **P1-5** | [ ] | **B** | **Homepage Layout** | Build the main sections: Hero Banner (w/ clear CTA), Featured Categories Grid, and New Arrivals Section. |
| **P1-6** | [ ] | **A** | **Product Detail Page (PDP)** | Create the full PDP layout: Image Gallery, Description/Specs, Price/Format Picker, and **Reviews Section** placeholder. |

---

## II. Product Listing Page (PLP) Readiness (Filter Core)

This phase establishes the HTML structure necessary for the future dynamic Vue filtering.

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P2-1** | [ ] | **A** | **Filter Sidebar HTML** | Complete the static structure for the `#product-filters` `<aside>` including Genre and Author checkboxes. |
| **P2-2** | [ ] | **A** | **Price & Format Filters** | Implement HTML for **Price Range inputs** (Min/Max) and Book Format radio buttons/select. |
| **P2-3** | [ ] | **A** | **Reusable Product Card** | Finalize the static design of the **Product Card** (`<article>`) with image placeholder, Title, Author, and Price. |
| **P2-4** | [ ] | **A** | **Grid Mock-up** | Populate the `#product-grid` with **20+ static Product Cards** using the component structure from P2-3. |
| **P2-5** | [ ] | **B** | **PLP Top Bar** | Implement the Results Count display and the **Sort By** dropdown above the product grid. |
| **P2-6** | [ ] | **B** | **Responsiveness & Polish** | Ensure all PLP elements (sidebar, grid) are fully **responsive** and look clean across devices. |

---

## III. Vue.js Integration (Dynamic Functionality MVP)

The integration of the Vue.js framework to handle sophisticated, real-time filtering logic.

| ID | Status | Priority | Task Description | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **P3-1** | [ ] | **A** | **Vue Setup** | Install `vue` and `@vitejs/plugin-vue`; update `vite.config.js` to enable the Vue plugin. |
| **P3-2** | [ ] | **A** | **Mock Data Store** | Create a simple **JavaScript array of 50+ book objects** (`store/books.js`) with Genre, Author, Price, etc. |
| **P3-3** | [ ] | **A** | **Filter Component** | Create and mount the `FilterSidebar.vue` component to the `#product-filters` element. |
| **P3-4** | [ ] | **A** | **Product Grid Component** | Create and mount the `ProductGrid.vue` component to the `#product-grid` element, consuming the mock data. |
| **P3-5** | [ ] | **A** | **Core Filtering Logic** | Implement the central Vue logic to **filter the data store** based on selected sidebar inputs. |
| **P3-6** | [ ] | **B** | **Real-Time Update** | Ensure the **Product Grid** updates instantly (without page reload) whenever a filter selection is changed. |

---

## 🚀 Future Options & Expansion

These tasks are for post-MVP development, adding high-value, unique features.

| ID | Status | Type | Task Description | Goal |
| :---: | :---: | :---: | :--- | :--- |
| **F1-1** | [ ] | **Quiz** | **Book Recommendation Quiz** | Develop the multi-step Vue Quiz component; final output should apply specific filters to the PLP. |
| **F1-2** | [ ] | **Search** | **Faceted/Instant Search** | Implement fast, live search results that filter the product data as the user types. |
| **F1-3** | [ ] | **Platform** | **Shopify/WooCommerce Block Mapping** | Add comments or dummy attributes to key components to mark them for theme conversion (e.g., Liquid/PHP variables). |
| **F1-4** | [ ] | **State** | **URL State Management** | Use Vue Router/URL Query Parameters to persist filter state, allowing users to share filtered links. |
| **F1-5** | [ ] | **Performance** | **TypeScript Conversion** | Convert core Vue/JS logic files to TypeScript for better maintainability and error checking. |