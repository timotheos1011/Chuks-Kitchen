# Chuks Kitchen Food Ordering Webpage  
**Frontend Developer Deliverable – Trueminds Innovations Internship**  
**Popoola Timothy – Frontend Developer**  

## Project Overview
The Live Project Link -- https://timotheos1011.github.io/Chuks-Kitchen/
The Repo Link -- https://github.com/timotheos1011/Chuks-Kitchen

I built a multi-page responsive food ordering prototype for **Chuks Kitchen** (client: Mr. Chukwudi Okorie / Mr. Chuks), converting key screens from the provided Figma design into webpages.  

📝📝📝📝📝
- **Navigation flow** (implemented via anchor tags):  
  - From onboarding page (`index.html`): "Sign in" → `sign-in.html`, brand logo click → `home.html`  
  - From homescreen: "Discover what's next" button → `food-details.html`  
  - From food details: Clicking food name/item → `your-cart.html` (simulated add-to-cart flow)  
📝📝📝📝📝

The project represents the core customer-facing flow of a simple food ordering website:  
- Onboarding/welcome screen  
- Sign-in screen  
- Homescreen (landing with hero and featured content)  
- Food details screen (individual meal view)  
- Your Cart screen (order summary with items and quantity)  

This covers **at least 5 screens** as required, focusing on visual fidelity, smooth navigation, and basic interactivity.  

All navigation is handled via standard `<a>` anchor tags (no JavaScript routing), keeping the implementation lightweight.  

**Tech Stack & Why**  
- **HTML5** – for semantic, accessible structure  
- **CSS3** (vanilla, with Flexbox and Grid) – for layout, responsiveness, and styling without dependencies  
- **Vanilla JavaScript** – only for small interactive features (add/remove cart items, quantity counter)  
- Fonts: Inter, Poppins, Jost, and Island Moments (imported via Google Fonts to match Figma as closely as possible)  

I chose **plain HTML/CSS/JS** (no frameworks like React) to align with the guideline against over-engineering, emphasize fundamentals (semantic markup, responsive techniques, clean code), and focus on translating the design directly. This keeps the project simple, fast-loading, and easy for any developer to pick up.

## Project Structure

All pages are separate HTML files, with shared styling and scripting in single files for simplicity (no build tools or bundlers used).



## Design Interpretation

I aimed for close visual fidelity to the Figma design, using the Inspect panel to extract colors, spacing (padding/margins in px/rem), typography scale, and component styles.  

Key translations and decisions:  
- **Fonts** → Matched as closely as possible: Inter for body/text, Poppins, Jost for headings/buttons, Island Moments for decorative/brand elements (loaded from Google Fonts).  
- **Colors** → Used exact hex codes from Figma where available.
- **Layout** → Flexbox for navigation/hero/buttons, CSS Grid for menu/food cards where multi-column layouts appeared.
   
- **Navigation flow** (implemented via anchor tags):  
  - From onboarding (`index.html`): "Sign in" → `sign-in.html`, brand logo click → `home.html`  
  - From homescreen: "Discover what's next" button → `food-details.html`  
  - From food details: Clicking food name/item → `your-cart.html` (simulated add-to-cart flow)  
- **Responsiveness** → Mobile-first approach with media queries (e.g., @media (min-width: 768px) for tablet/desktop adjustments). Nav collapses to hamburger (CSS-only or basic JS toggle), cards stack vertically, hero text scales down.  


## Limitations & Improvements

**Current Limitations**  
- Image aspect ratios and exact food visuals deviate slightly from Figma due to missing original assets.  
- Accessibility basics implemented (semantic HTML, some alt texts), but no full ARIA labels, keyboard navigation testing, or contrast checks.  

This project gave me great hands-on experience translating static designs to responsive, interactive code while keeping things clean and simple. 

Feel free to reach out via Slack if needed.  
– Timothy [FE]
