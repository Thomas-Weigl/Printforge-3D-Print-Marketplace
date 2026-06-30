# Project - Printforge (3D Printing Service - WebPage)

=> (Figma Project)[https://www.figma.com/files/team/1445765086307352728/project/309446497?fuid=1445765084239303309]

- Figma Prototype: [https://www.figma.com/proto/TIO3MgYAZPsxfDtEYHNxJN/Printforge?node-id=128-94&p=f&t=ERGHXRmcPHkmkA6y-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=128%3A94]
  - Link Password: MCI_Printforge

- documentation must be 10 to 20 pages long (without images)

## Documentation Contents

- description of the development process -> from idea to prototype to evaluation + conclusion
  -> screenshots of the prototype should be included in the documentation
- tools & technologies used for the prototype

## Used Tools

- GitHub for version control and collaboration -> define task for each team member, supply links to the documentation and the prototype, provide up to date photos
- chosen Figma as Design Tool for the prototype
- CoPilot image generation
- (planned to use Jira for organising the project)

## Notes - Idea

- were sure to make any kind of website -> 3D printing service was our final idea as website
- The platform is a flexible marketplace supporting two main use cases: purchasing ready-made 3D-printed products or downloading models for independent printing.
- This dual approach targets both non-technical users seeking ready-to-use products and experienced users with 3D printers who prefer self-printing for cost efficiency.
- The project emphasizes usability, accessibility, and clear interface design to provide an intuitive shopping experience for a broad audience.

- tried to legitimize every UI element by always giving a reason / explanation for their usage / changes

- immediately apply best practices from the lecture like laws for design or metrics to evaluate our UI for user-friendlyness and usability
  - also include friends and other people in the process and apply "user-driven" development and ask for immediate feedback

## Notes - Prototype (Figma)

### Initial (Paper) Sketches

- Aim: Clarify design decisions and outline future development steps.
- The work involves layout design, menu structure, filter functionality, product presentation, color schemes, and planning additional pages.

- Started with paper sketches for quick iteration of website layout and design.
- Defined main pages and their content: homepage, product page, checkout process, etc.
- Created initial design concepts:
  - Color schemes for buttons, backgrounds, etc.
  - Content structure on the homepage: categories, featured products.
  - Navigation menu design: categories, search bar, account/shopping cart icons.

#### General Page Layout

- Visual hierarchy with a large top section.
- Colorful images linking to subpages (e.g., Products, Blueprints), designed to be visually appealing and clickable.
- Text compartments with explanatory info, designed to be transparent or subtly integrated.
- Company images (generated via AI, e.g., employees, production) linking to pages like "About Us."
- Footer remains constant with essential links.

#### Ready-to-Buy Page and Menu Design

- Developed the **"Ready-to-Buy"** page with text and images (considering a background gradient, which is challenging to implement).
- Improved the top menu:
  - New design on the top right, appearing on subsequent pages.
  - Menu on the left for intuitive navigation, based on course insights.
  - Right side includes **Search**, **Profile**, **Shopping Cart**.
  - Potentially replacing the account icon with a shopping cart icon for better accessibility.
- The menu should be visible across relevant pages, including "Ready-to-Buy" and "Blueprints."

#### Landing Page

- Clear page structure with accessible navigation via buttons, images, footer, and top-right menu.
- Landing page accessible via main buttons, images, or footer.
- Top right contains the main navigation menu with all essential functions.
- Main content area:
  - Large, compressed section at the top with a clear structure.
  - Profile information or image, with explanation of design choices.
  - Two prominent buttons ("Ready-to-Buy" and "Blueprints") leading to main sections.

#### Product Detail Page

- Consideration for product detail pages with expandable animations.
- Use of images with transparent areas blending seamlessly.
- Consistent layout across pages, with variations in text and imagery.
- The background for product images typically in gray, with a preference for lighter tones if available.
- Product info displayed with name and price, with color variations (black or white text).
- Products displayed with a gray background, transparent overlay of product images.
- Product name and price shown below the image; text in black or white depending on design.
- Similar layouts used across "Ready-to-Buy" and "Blueprints" pages, with variations in content.

#### Blueprints Page

- **"Blueprints"** page layout mirrors "Ready-to-Buy" but with different text and images.
- Integration of the new top menu design on all relevant pages.

#### Navigation Menu

- Navigation menu:
  - Fixed at the bottom with three buttons.
  - Consider changing the icon at the top left (e.g., to a different symbol indicating menu state).
  - Clear indication of current page to users.

#### Future Steps and Technical Considerations

- Possible development of **"Help & Support," "FAQ," "Terms & Conditions"**; mostly text, so design may be minimal.
- **"About Us"** page to be created.
- **Customizer-Editor:**
  - Potential feature to allow color customization.
  - Time constraints may lead to skipping this feature.
  - Decision pending on whether to include color customization based on time and necessity.

### Figma Prototype

- try to use Fitts's Law for the design of the buttons and interactive elements (e.g. make the "Add to cart" button larger and more prominent) -> short calculation with a button element to show how we applied Fitts's Law (good with current bad response time of the prototype)

#### Progress Overview

- General progress:
  - Each page now has a functioning link to the shopping cart.
  - The shopping cart link works regardless of the screen size.
  - The My Profile Sign-In button functions; open question: what happens when the user is logged in.
  - The search bar can be expanded on every screen.
  - The progress includes removing the neighbor-gans (normal state), so they are now only expandable and collapsible.
  - The "mysterious ghost transition" has been resolved.

#### Filter Functionality

- Filter button toggles product images to compress and reveals a filter panel.
- Filter options include:
  - Product Type
  - Color
  - Price
  - Collections
  - Out-of-Stock
- Checkboxes allow users to include/exclude out-of-stock items.
- "Apply" button to confirm filters; toggling the filter panel on/off.
- Filter panel's appearance and disappearance are animated or toggled.

#### Open Tasks & Next Steps

- Filter Mechanic:
  - Various filtering options still need to be implemented.
  - Four options should be available depending on:
    - Whether the filter is open.
    - Whether a different view is active.
- Description and Funding Information:
  - Expand/collapse functions for both areas still to be implemented.

#### Additional Design & Structural Considerations

- Page Filament:
  - Similar to "Ready-to-Buy" and "Blueprint".
  - Only need to replace images.
  - Mechanics for filters and views need to be selected beforehand.
- Background Design:
  - Originally: White background with images (blueprints, ready-to-buy).
  - Options under consideration:
    - Make images transparent and enclose in a liquid-glass box.
    - Use a black background, as the glass effect looks best on dark.
  - Currently experimenting with different options.
- Liquid Glass Design:
  - Relatively complex to implement, involves stacking objects and cutting effects.
  - Uses variants:
    - Variants implemented on a single frame.
    - Not across multiple frames to keep things manageable.
  - The lower frame (variant 2) is a template:
    - Serves as a backup format.
    - Currently inactive, for future use if elements are deleted.

#### Functionality & Interaction Details

- Shopping Cart:
  - Works through a variable that adjusts the height based on screen size.
  - The shopping cart can be opened from the top.
  - Can be closed via an 'X' button at the top right, placed for quick access.
  - Can also be closed by swiping left, detected by an invisible rectangle.
  - price is calculated by multiplying the quantity with the price of the product, which is stored in a variable.
- Checkout:
  - Still needs to be implemented.
- Navigation & User Guidance:
  - Questions about practical navigation within the Figma prototype:
    - How to add products to the shopping cart?
  - Use techniques from previous sessions to facilitate testing and feedback.
- Page Switching & User Orientation:
  - Highlight the current page during navigation to provide clear orientation.

#### Design & User Interface Elements

- Navigation Bar:
  - Original plan: Create a separate design.
  - Decision: Use an example design to maximize clarity.
  - Aim: Provide maximum overview.
- Menu Button (Three Bars):
  - Function: Transforms into a cross when clicked to close.
  - Intuitiveness:
    - Cross is easier to understand for users.
    - Three bars are a common menu symbol.
  - Design considerations:
    - Two criteria:
      - The cross is intuitive.
      - The three bars are a standard symbol.
- Variable Storage:
  - Considering using variables to store menu state (expanded or collapsed).
  - Goal: Persist menu status across interactions.
- Liquid Glass Design:
  - Uses complex effects, stacking, and cutouts.
  - Variants are implemented on a single frame.
  - The inactive lower variant serves as a backup template.

#### Testing & Feedback Strategy

- After completion of the basic layout:
  - The prototype will be reviewed by:
    - Mother
    - Friend
    - Possibly grandmother (Oma)
  - Target groups:
    - Young audiences
    - Middle-aged audiences
    - Older audiences
- Feedback Collection:
  - Method still undecided.
  - Feedback will be gathered from family, friends, and later from the actual user group.
- Evaluation:
  - Results will be analyzed after testing.
  - Focus on documenting what was done.

#### User Guidance & Page Navigation

- Questions about how users will practically navigate:
  - How to add an order?
  - How to add products to the shopping cart?
- Use techniques learned previously to facilitate testing and feedback.
- When switching pages, the current page will be highlighted for clarity.

### General Design Decisions

#### General Design Philosophy and Layout

- Based on the rough paper design plan
- Decided to place key elements in the center and lower parts of the layout
- Chose not to mention the Ready-to-Buy and Blueprint links in the footer since they are already visible on the landing page
- Focused on highlighting the initial distinction between offers to emphasize differences
- Included an "About Us" section in the footer to build trust by showcasing the team
- Company is visually represented as being in a green, natural environment to create a positive image
- A button in the footer allows users to view more information

#### Header Design and Navigation

- Logo centered, also functions as a button to return to the landing page (similar to online shops)
- Search bar included for increased flexibility, especially helpful for older users
- Profile login accessible
- Shopping cart: remains visible, does not open in a new window to avoid confusion, can be closed easily by clicking a cross or the left side
- Users can close the shopping cart at any time, maintaining clear awareness of their current location

#### Menu Design

- Initial idea was a separate overlay screen for the menu with an image or short video (e.g., moving printhead)
- This idea was discarded; instead, the menu remains as an overlay
- Documented design considerations and alternatives, including the possibility of adding media

#### Consistent Page Layout and Style

- All pages (e.g., landing page, Ready-to-Buy, Blueprint) share a uniform layout
- Consistent use of images, texts, headings, and subheadings
- Design style: Apple-like, black-and-white, liquid-glass aesthetic
- Uniform arrangement of filters and views; only product content varies

#### Filters and Button Interactions

- Filters are collapsible, revealing various options when opened
- Filter functionality has not been implemented due to complexity and numerous options
- Buttons feature hover and pressed animations (some still pending implementation)
- User feedback is being incorporated into button animation and interaction design
- View size can be adjusted for older (larger) or younger (smaller) users, with future adjustable settings

#### Product Overview and Navigation

- Added an arrow under products to indicate clickable areas
- Users are advised that clicking on images also opens product details
- Buttons in the Ready-to-Buy and Blueprint sections include links to product detail pages (only for one product on each page for now, but can be easily expanded -> also needed for evaluation)

-> ...

#### Product Detail Page

- Consistent header with a large image, which can be swapped later
- Color options presented in gray circles; selecting a color updates the product image
- Functionality to add products to the shopping cart, with quantity adjustment
- "Further Informations" section can be expanded or collapsed
- Reviews button scrolls down to reviews section, possibly with animation
- Reviews displayed in the familiar Liquid-Glass style
- User feedback included, e.g., a comment from persona Lars Bytecraft
- Review section may include animations

#### Additional Features and Content

- FAQ and Terms & Conditions are not planned for implementation
- Sign-in page: no search, profile, or shopping cart buttons included, as deemed unnecessary
- Sign-in menu shows status message "You are in my profile" (placeholder)
- Profile creation is only indicated with a placeholder; full implementation is optional
- Navigation between pages is handled via the menu bar (switching feature)
- Approximate completion: around 80% of the prototype is finished
- Remaining tasks include designing the filament section and polishing details

## Notes - Evaluation & Conclusion

### Pre-Evaluation Planning

- made a clear plan for the evaluation and conclusion steps (see "Evaluation" in exec_plan.md)
- evaluation will be conducted using the Figma prototype and an online survey (e.g. Google Forms) with quantitative and qualitative questions
- links to the Figma prototype and the online survey will be included in the documentation and the presentation slides

- evaluation will focus on the navigation bar, shopping cart, profile page, font size, color scheme, and overall design
- participants will be asked to complete specific tasks related to these design elements and functionalities, and then answer questions about their experience

### Evaluation Execution

- provided slides with QR-Code to access the online survey during the evaluation presentation
- link to the FIGMA prototype was directly in the survey, so participants could easily access it and complete the tasks while answering the questions
- we explained what we considered from the proposals and recommendation from the initial project presentation question round

### Conclusion & Next Steps

- calculated median, mean, and standard deviation for the quantitative questions to analyze the results
- documented the results in a clear and concise way using tables and graphs
- wrote a conclusion based on the results, identifying which design elements and functionalities were well received and which need improvement -> already changed some design before the final presentation based on the feedback from the evaluation
- outlined next steps for improving the design and improved questioning
