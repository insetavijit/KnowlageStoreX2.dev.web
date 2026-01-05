### **[[01 CSS Fundamentals]]**

Master CSS (Cascading Style Sheets) as the styling language of the web. Learn selectors, properties, values, and the box model. Understand why CSS is essential—it transforms plain HTML into beautiful, responsive designs. CSS powers 98.7% of all websites globally and is the foundation of modern web design. Essential for front-end development, web design, and creating professional digital experiences.

|Topic|Focus & Purpose|
|---|---|
|**[[1.1 Introduction to CSS]]**|What is CSS; CSS history; CSS3 features; inline vs internal vs external; why learn CSS; styling fundamentals. Understanding CSS.|
|**[[1.2 CSS Syntax]]**|Selectors; properties; values; declarations; rules; comments; syntax structure; formatting. Basic syntax.|
|**[[1.3 Adding CSS to HTML]]**|Inline styles; internal stylesheets; external stylesheets; link tag; best practices; when to use each. Integration methods.|
|**[[1.4 Selectors Basics]]**|Element selectors; class selectors; ID selectors; universal selector; grouping selectors; selector syntax. Targeting elements.|
|**[[1.5 Colors & Backgrounds]]**|Color values (hex, RGB, HSL); color names; background-color; background-image; background properties; gradients basics. Visual styling.|
|**[[1.6 Text Styling]]**|font-family; font-size; font-weight; font-style; text-align; text-decoration; text-transform; line-height; letter-spacing. Typography basics.|
|**[[1.7 CSS Units]]**|Absolute units (px, pt, cm); relative units (em, rem, %, vw, vh); when to use each; unit conversion; best practices. Measurement systems.|
|**[[1.8 Project: Styled Webpage]]**|Creating styled webpage; combining properties; color schemes; typography; layout basics; external stylesheet. First styled site.|

### **[[02 Box Model & Layout Basics]]**

Master the CSS box model—the foundation of all layout. Learn content, padding, border, and margin. Understand box-sizing, display properties, and positioning. The box model is crucial for creating precise, predictable layouts and is the key to understanding CSS layout systems.

|Topic|Focus & Purpose|
|---|---|
|**[[2.1 The Box Model]]**|Content box; padding; border; margin; box-sizing; content-box vs border-box; box model visualization. Layout foundation.|
|**[[2.2 Padding & Margin]]**|Padding properties; margin properties; shorthand notation; margin collapse; negative margins; spacing control. Element spacing.|
|**[[2.3 Borders]]**|Border properties; border-width; border-style; border-color; border-radius; shorthand; individual sides. Element boundaries.|
|**[[2.4 Width & Height]]**|Width and height properties; min/max width/height; auto values; box-sizing impact; responsive dimensions. Element sizing.|
|**[[2.5 Display Property]]**|display: block; inline; inline-block; none; visibility; hiding elements; display types; layout behavior. Element display.|
|**[[2.6 Overflow]]**|overflow: visible; hidden; scroll; auto; overflow-x/y; text-overflow; handling content overflow. Content containment.|
|**[[2.7 Box Shadow]]**|box-shadow syntax; multiple shadows; spread; blur; inset shadows; shadow effects; depth creation. Visual effects.|
|**[[2.8 Project: Card Components]]**|Building card layout; box model in practice; shadows; borders; spacing; hover effects; component design. Practical layout.|

### **[[03 Advanced Selectors & Specificity]]**

Master CSS selectors and the cascade. Learn pseudo-classes, pseudo-elements, attribute selectors, and combinators. Understand specificity, inheritance, and the cascade algorithm. Advanced selectors enable precise targeting and maintainable stylesheets.

|Topic|Focus & Purpose|
|---|---|
|**[[3.1 Combinator Selectors]]**|Descendant combinator; child combinator (>); adjacent sibling (+); general sibling (~); selector relationships. Complex targeting.|
|**[[3.2 Pseudo-Classes]]**|:hover, :active, :focus; :first-child, :last-child, :nth-child; :not(); structural pseudo-classes; interactive states. Dynamic styling.|
|**[[3.3 Pseudo-Elements]]**|::before, ::after; ::first-letter, ::first-line; content property; generated content; decorative elements. Content enhancement.|
|**[[3.4 Attribute Selectors]]**|[attribute]; [attribute="value"]; [attribute^="value"]; [attribute$="value"]; [attribute*="value"]; complex matching. Attribute targeting.|
|**[[3.5 Specificity]]**|Specificity calculation; inline > ID > class > element; !important; specificity rules; specificity conflicts. Cascade rules.|
|**[[3.6 Cascade & Inheritance]]**|Cascade algorithm; inheritance; inherited properties; non-inherited properties; controlling inheritance. CSS fundamentals.|
|**[[3.7 CSS Variables]]**|Custom properties; --variable-name; var() function; scope; fallback values; dynamic theming. Reusable values.|
|**[[3.8 Project: Theme System]]**|Building theme with variables; color schemes; reusable patterns; specificity management; maintainable CSS. Scalable styling.|

### **[[04 Flexbox Layout]]**

Master Flexbox—the one-dimensional layout system. Learn flex containers, flex items, alignment, and distribution. Build navigation bars, card layouts, and flexible components. Flexbox revolutionized CSS layout and is essential for modern web development.

|Topic|Focus & Purpose|
|---|---|
|**[[4.1 Flexbox Basics]]**|display: flex; flex container; flex items; main axis; cross axis; flex direction; flex fundamentals. One-dimensional layout.|
|**[[4.2 Flex Direction & Wrap]]**|flex-direction: row, column; flex-wrap: wrap, nowrap; flex-flow shorthand; axis orientation. Layout direction.|
|**[[4.3 Justify Content]]**|justify-content; flex-start; center; flex-end; space-between; space-around; space-evenly. Main axis alignment.|
|**[[4.4 Align Items & Self]]**|align-items; align-self; stretch; flex-start; center; baseline; cross axis alignment. Cross axis control.|
|**[[4.5 Flex Grow, Shrink, Basis]]**|flex-grow; flex-shrink; flex-basis; flex shorthand; flexible sizing; space distribution. Item flexibility.|
|**[[4.6 Gap Property]]**|gap; row-gap; column-gap; spacing between flex items; modern spacing. Item spacing.|
|**[[4.7 Common Flexbox Patterns]]**|Navigation bars; card layouts; centering; equal height columns; sticky footer; practical patterns. Real-world layouts.|
|**[[4.8 Project: Responsive Navbar]]**|Building responsive navigation; hamburger menu; flexbox alignment; mobile-first; media queries. Production navigation.|

### **[[05 CSS Grid Layout]]**

Master CSS Grid—the two-dimensional layout system. Learn grid containers, grid items, tracks, areas, and complex layouts. Build magazine layouts, dashboards, and sophisticated designs. CSS Grid enables layouts previously impossible or impractical with CSS alone.

|Topic|Focus & Purpose|
|---|---|
|**[[5.1 Grid Basics]]**|display: grid; grid container; grid items; rows and columns; grid lines; grid fundamentals. Two-dimensional layout.|
|**[[5.2 Grid Template Columns/Rows]]**|grid-template-columns; grid-template-rows; fr unit; repeat(); minmax(); auto; track sizing. Defining grid structure.|
|**[[5.3 Grid Gap]]**|gap; row-gap; column-gap; gutter spacing; grid spacing. Grid item spacing.|
|**[[5.4 Grid Item Placement]]**|grid-column; grid-row; grid-area; line-based placement; span keyword; item positioning. Precise placement.|
|**[[5.5 Grid Template Areas]]**|grid-template-areas; named areas; semantic layouts; visual grid design; area-based layouts. Named regions.|
|**[[5.6 Auto-Fill & Auto-Fit]]**|repeat(auto-fill); repeat(auto-fit); responsive grids; automatic columns; intrinsic sizing. Automatic layouts.|
|**[[5.7 Grid Alignment]]**|justify-items; align-items; justify-content; align-content; place-items; place-content. Grid alignment.|
|**[[5.8 Project: Dashboard Layout]]**|Building dashboard; grid template areas; responsive grid; nested grids; complex layout. Production grid.|

### **[[06 Responsive Design]]**

Master responsive web design principles. Learn media queries, mobile-first design, fluid layouts, and responsive images. Build websites that work beautifully on all devices. Responsive design is essential in a mobile-first world where 60%+ of traffic is mobile.

|Topic|Focus & Purpose|
|---|---|
|**[[6.1 Responsive Fundamentals]]**|Mobile-first approach; viewport; fluid layouts; flexible images; responsive philosophy; device diversity. Adaptive design.|
|**[[6.2 Media Queries]]**|@media rule; breakpoints; min-width; max-width; orientation; media types; query syntax. Conditional styling.|
|**[[6.3 Mobile-First Design]]**|Mobile-first workflow; progressive enhancement; starting small; scaling up; content priority. Strategy.|
|**[[6.4 Responsive Typography]]**|Fluid typography; clamp(); viewport units; responsive font sizing; readable text; scalable type. Adaptive text.|
|**[[6.5 Responsive Images]]**|max-width: 100%; object-fit; aspect-ratio; picture element (HTML); responsive image techniques. Flexible media.|
|**[[6.6 Container Queries]]**|@container; container-type; component-based responsive; intrinsic design; modern responsive. Component queries.|
|**[[6.7 Responsive Layout Patterns]]**|Column drop; mostly fluid; layout shifter; off canvas; common patterns; responsive strategies. Layout techniques.|
|**[[6.8 Project: Responsive Portfolio]]**|Building responsive site; mobile-first approach; breakpoints; flexible grid; responsive images; media queries. Complete responsive site.|

### **[[07 Positioning & Z-Index]]**

Master CSS positioning for precise element placement. Learn static, relative, absolute, fixed, and sticky positioning. Understand stacking contexts and z-index. Positioning enables overlays, dropdowns, tooltips, and complex layouts.

|Topic|Focus & Purpose|
|---|---|
|**[[7.1 Position Property]]**|position: static; relative; absolute; fixed; sticky; positioning types; coordinate properties. Element positioning.|
|**[[7.2 Relative Positioning]]**|position: relative; offset from normal; top, right, bottom, left; preserving space; subtle adjustments. Relative movement.|
|**[[7.3 Absolute Positioning]]**|position: absolute; positioning context; containing block; removing from flow; precise placement. Absolute placement.|
|**[[7.4 Fixed Positioning]]**|position: fixed; viewport positioning; staying in place; navigation bars; fixed headers. Viewport-fixed elements.|
|**[[7.5 Sticky Positioning]]**|position: sticky; scroll-based positioning; threshold; hybrid behavior; sticky headers. Scroll-dependent positioning.|
|**[[7.6 Z-Index & Stacking]]**|z-index; stacking context; stacking order; z-index rules; layering elements. Depth control.|
|**[[7.7 Centering Techniques]]**|Horizontal centering; vertical centering; flexbox centering; grid centering; absolute centering; modern methods. Element centering.|
|**[[7.8 Project: Modal & Dropdown]]**|Building modal overlay; dropdown menu; position absolute/fixed; z-index management; interactive components. Positioned components.|

### **[[08 Transforms & Transitions]]**

Master CSS transforms and transitions for smooth animations. Learn 2D/3D transforms, transition properties, and timing functions. Create hover effects, smooth state changes, and engaging interactions. Transforms and transitions bring interfaces to life.

|Topic|Focus & Purpose|
|---|---|
|**[[8.1 Transform Basics]]**|transform property; transform-origin; transform functions; 2D transforms; coordinate system. Element transformation.|
|**[[8.2 2D Transforms]]**|translate(); rotate(); scale(); skew(); matrix(); combining transforms; transformation effects. 2D manipulation.|
|**[[8.3 3D Transforms]]**|translate3d(); rotate3d(); perspective; transform-style; preserve-3d; 3D space. Three-dimensional effects.|
|**[[8.4 Transition Basics]]**|transition property; transition-property; transition-duration; transition-timing-function; transition-delay. Smooth changes.|
|**[[8.5 Timing Functions]]**|ease; linear; ease-in; ease-out; ease-in-out; cubic-bezier(); custom easing; animation curves. Motion curves.|
|**[[8.6 Transition Best Practices]]**|Performance; transform vs other properties; will-change; hardware acceleration; smooth animations. Optimized transitions.|
|**[[8.7 Interactive Effects]]**|Hover effects; focus states; button animations; card flips; micro-interactions; engaging UX. User feedback.|
|**[[8.8 Project: Animated Cards]]**|Building animated card gallery; hover transforms; transitions; 3D flips; smooth interactions. Interactive components.|

### **[[09 CSS Animations & Keyframes]]**

Master CSS animations with @keyframes for complex motion sequences. Learn animation properties, keyframe timing, and advanced animation techniques. Create loading spinners, attention grabbers, and sophisticated animations. Animations enable storytelling and brand expression.

|Topic|Focus & Purpose|
|---|---|
|**[[9.1 Keyframes Basics]]**|@keyframes rule; animation-name; from/to; percentage keyframes; defining animations. Animation sequences.|
|**[[9.2 Animation Properties]]**|animation-duration; animation-delay; animation-iteration-count; animation-direction; animation-fill-mode. Animation control.|
|**[[9.3 Animation Timing]]**|animation-timing-function; easing in animations; step(); cubic-bezier(); controlling pace. Animation curves.|
|**[[9.4 Animation Play State]]**|animation-play-state; pausing animations; running animations; interactive control; user-controlled animations. Playback control.|
|**[[9.5 Combining Animations]]**|Multiple animations; animation shorthand; sequencing; parallel animations; complex motion. Advanced animations.|
|**[[9.6 Performance Optimization]]**|transform and opacity; avoiding layout thrashing; GPU acceleration; will-change; performant animations. Smooth performance.|
|**[[9.7 Common Animation Patterns]]**|Loading spinners; fade effects; slide effects; bounce; pulse; shake; attention-grabbers. Reusable patterns.|
|**[[9.8 Project: Loading Animations]]**|Building loading indicators; spinner animations; skeleton screens; progress animations; engaging loaders. Production animations.|

### **[[10 Modern CSS Features]]**

Master cutting-edge CSS features from 2024-2025. Learn CSS nesting, :has() selector, container queries, cascade layers, and modern properties. Build with the latest CSS capabilities. Modern CSS features enable cleaner code and previously impossible layouts.

|Topic|Focus & Purpose|
|---|---|
|**[[10.1 CSS Nesting]]**|Native CSS nesting; & parent selector; nested rules; cleaner syntax; SCSS-like syntax in CSS. Modern syntax.|
|**[[10.2 :has() Selector]]**|Parent selector; relational pseudo-class; conditional styling; has() use cases; modern selection. Powerful selector.|
|**[[10.3 Container Queries]]**|@container rule; container-type; component-responsive; size-based queries; intrinsic design. Component responsiveness.|
|**[[10.4 Cascade Layers]]**|@layer rule; layer ordering; specificity management; organizing styles; cascade control. CSS architecture.|
|**[[10.5 :is() and :where()]]**|Specificity control; selector lists; grouping selectors; specificity differences; modern selectors. Advanced selection.|
|**[[10.6 accent-color]]**|Form control colors; accent-color property; native styling; checkbox/radio colors; modern forms. Native customization.|
|**[[10.7 aspect-ratio]]**|aspect-ratio property; maintaining proportions; responsive media; aspect control; modern sizing. Proportional sizing.|
|**[[10.8 Project: Modern Web App]]**|Building with modern CSS; nesting; :has(); container queries; cutting-edge features; future-proof code. Modern techniques.|

### **[[11 CSS Architecture & Methodologies]]**

Master organizing CSS for large projects. Learn BEM, SMACSS, OOCSS, and utility-first approaches. Understand CSS architecture, naming conventions, and maintainable code patterns. Proper architecture prevents CSS chaos and enables team collaboration.

|Topic|Focus & Purpose|
|---|---|
|**[[11.1 CSS Architecture Basics]]**|Code organization; file structure; naming conventions; scalability; maintainability; architectural principles. Foundation.|
|**[[11.2 BEM Methodology]]**|Block Element Modifier; naming system; component-based CSS; BEM syntax; avoiding specificity wars. Popular methodology.|
|**[[11.3 SMACSS]]**|Scalable and Modular Architecture; categorization; base, layout, module, state, theme; organizing rules. Architectural pattern.|
|**[[11.4 OOCSS]]**|Object-Oriented CSS; separation of structure and skin; separation of container and content; reusable objects. Reusability pattern.|
|**[[11.5 Utility-First CSS]]**|Utility classes; Tailwind approach; atomic CSS; composable utilities; rapid development. Modern approach.|
|**[[11.6 CSS Preprocessors]]**|Sass/SCSS; Less; variables; nesting; mixins; functions; partials; compilation. Extended CSS.|
|**[[11.7 PostCSS & Modern Tooling]]**|PostCSS; Autoprefixer; cssnano; modern CSS processing; build tools; optimization. Modern workflow.|
|**[[11.8 Project: Scalable Style System]]**|Building design system; component library; naming conventions; documentation; maintainable architecture. Production system.|

### **[[12 CSS Performance & Optimization]]**

Master CSS performance optimization. Learn render-blocking, critical CSS, minification, and performance best practices. Build fast-loading, performant stylesheets. CSS performance directly impacts Core Web Vitals, SEO, and user experience.

|Topic|Focus & Purpose|
|---|---|
|**[[12.1 Render Performance]]**|Critical rendering path; render-blocking CSS; CSSOM; painting; layout thrashing; reflow and repaint. Rendering optimization.|
|**[[12.2 Critical CSS]]**|Above-the-fold CSS; inline critical CSS; deferred loading; critical extraction; first paint optimization. Initial render.|
|**[[12.3 CSS Minification]]**|Minification; removing whitespace; shorthand properties; compression; build optimization. File size reduction.|
|**[[12.4 Selector Performance]]**|Efficient selectors; selector specificity cost; avoiding inefficient selectors; selector speed; best practices. Selector optimization.|
|**[[12.5 Font Loading]]**|font-display; FOUT; FOIT; font loading strategies; system fonts; web fonts optimization. Typography performance.|
|**[[12.6 Unused CSS]]**|Removing unused CSS; PurgeCSS; coverage tools; tree-shaking; bundle optimization. Reducing bloat.|
|**[[12.7 CSS Containment]]**|contain property; layout containment; paint containment; size containment; performance isolation. Advanced optimization.|
|**[[12.8 Project: Performance Audit]]**|Auditing CSS performance; Lighthouse; optimization techniques; measuring impact; production optimization. Performance improvement.|

### **[[13 Advanced Techniques]]**

Master advanced CSS techniques for professional development. Learn CSS shapes, filters, blend modes, clip-path, masks, and advanced visual effects. Create sophisticated designs and unique visual experiences. Advanced techniques enable creative expression and brand differentiation.

|Topic|Focus & Purpose|
|---|---|
|**[[13.1 CSS Filters]]**|filter property; blur(); brightness(); contrast(); grayscale(); hue-rotate(); saturate(); drop-shadow(). Visual effects.|
|**[[13.2 Blend Modes]]**|mix-blend-mode; background-blend-mode; blend mode types; overlay; multiply; screen; creative effects. Blending layers.|
|**[[13.3 Clip-Path & Masking]]**|clip-path; basic shapes; polygon(); CSS masking; mask-image; complex shapes. Shape manipulation.|
|**[[13.4 CSS Shapes]]**|shape-outside; circle(); ellipse(); polygon(); text wrapping; magazine layouts. Text flow control.|
|**[[13.5 Gradients Advanced]]**|Linear gradients; radial gradients; conic gradients; gradient patterns; multiple gradients; creative use. Advanced gradients.|
|**[[13.6 CSS Counters]]**|counter-reset; counter-increment; content; numbered lists; custom numbering; automated numbering. Automatic counters.|
|**[[13.7 CSS Math Functions]]**|calc(); min(); max(); clamp(); mathematical operations; responsive values; dynamic calculations. Computed values.|
|**[[13.8 Project: Creative Portfolio]]**|Building artistic portfolio; filters; blend modes; clip-path; advanced techniques; unique design. Creative application.|

### **[[14 CSS for Components]]**

Master building reusable UI components with CSS. Learn button systems, form styling, cards, navigation patterns, and component libraries. Build production-ready component systems. Component-based CSS enables scalable, maintainable design systems.

|Topic|Focus & Purpose|
|---|---|
|**[[14.1 Button Components]]**|Button styles; states; hover/active/disabled; sizing; variations; button systems. Interactive elements.|
|**[[14.2 Form Styling]]**|Input styling; select styling; checkbox/radio custom; form layout; validation states; accessible forms. Form components.|
|**[[14.3 Card Components]]**|Card patterns; card variations; media cards; pricing cards; hover effects; card grids. Content containers.|
|**[[14.4 Navigation Components]]**|Navbar patterns; dropdown menus; mega menus; hamburger menus; mobile navigation; navigation systems. Site navigation.|
|**[[14.5 Modal & Overlay Components]]**|Modal dialogs; overlays; backdrop; close buttons; accessibility; focus management. Dialog components.|
|**[[14.6 Tooltip & Popover Components]]**|Tooltips; popovers; positioning; arrows; CSS-only tooltips; informational UI. Contextual information.|
|**[[14.7 Tab & Accordion Components]]**|Tab systems; accordions; collapsible content; state management; interactive patterns. Content organization.|
|**[[14.8 Project: Component Library]]**|Building UI library; reusable components; documentation; variants; production components. Design system.|

### **[[15 CSS & Accessibility]]**

Master accessible CSS practices. Learn focus management, screen reader considerations, color contrast, reduced motion, and inclusive design. Build websites that work for everyone. Accessibility is both a legal requirement and moral imperative.

|Topic|Focus & Purpose|
|---|---|
|**[[15.1 Focus Management]]**|:focus styles; :focus-visible; focus indicators; keyboard navigation; focus order; visible focus. Keyboard users.|
|**[[15.2 Color & Contrast]]**|WCAG contrast ratios; color blindness; accessible color; contrast checking; text readability. Visual accessibility.|
|**[[15.3 Screen Reader Considerations]]**|Visually hidden content; sr-only class; screen reader-only text; hiding content; accessible hiding. Screen reader support.|
|**[[15.4 Reduced Motion]]**|prefers-reduced-motion; respecting user preferences; accessible animations; motion sensitivity. Motion accessibility.|
|**[[15.5 Accessible Forms]]**|Label association; error states; validation feedback; focus states; required indicators. Form accessibility.|
|**[[15.6 Skip Links]]**|Skip navigation; keyboard shortcuts; bypass blocks; main content links; navigation accessibility. Keyboard navigation.|
|**[[15.7 Accessible Components]]**|ARIA + CSS; role presentation; accessible modals; accessible dropdowns; inclusive components. Component accessibility.|
|**[[15.8 Project: Accessible Website]]**|Building fully accessible site; WCAG compliance; keyboard navigation; screen reader testing; inclusive design. Gold standard.|

### **[[16 Real-World Projects]]**

Master building production CSS projects. Learn complete project workflows from design to deployment. Build portfolio pieces across different industries and use cases. Real projects solidify understanding and create impressive portfolio work.

|Topic|Focus & Purpose|
|---|---|
|**[[16.1 Landing Page]]**|Hero section; features; testimonials; CTA; footer; responsive design; conversion-focused design. Marketing site.|
|**[[16.2 E-commerce Product Page]]**|Product showcase; image gallery; product details; add to cart; reviews; variations; shopping UI. Online store.|
|**[[16.3 Blog & Article Layout]]**|Article typography; reading experience; sidebar; related posts; comments; content-focused design. Publishing platform.|
|**[[16.4 Dashboard Interface]]**|Admin dashboard; data visualization; charts; tables; navigation; sidebar; responsive dashboard. Web application.|
|**[[16.5 Portfolio Website]]**|Project showcase; about section; skills; contact; responsive; personal branding; creative design. Personal website.|
|**[[16.6 SaaS Application UI]]**|Application interface; forms; data tables; settings; user profiles; modern UI patterns. Software interface.|
|**[[16.7 Restaurant Website]]**|Menu styling; gallery; reservations; location; hours; mobile-friendly; local business design. Business site.|
|**[[16.8 Complete Responsive Site]]**|Multi-page website; navigation; pages; consistent design; responsive; accessibility; SEO; production-ready. Full website.|
