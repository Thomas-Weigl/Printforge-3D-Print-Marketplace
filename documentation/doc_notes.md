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

- Brief explanation of current work on the Figma prototype, focusing on pages **"Ready-to-Buy"** and **"Blueprints"**.
- Aim: Clarify design decisions and outline future development steps.
- The work involves layout design, menu structure, filter functionality, product presentation, color schemes, and planning additional pages.

- Started with paper sketches for quick iteration of website layout and design.
- Defined main pages and their content: homepage, product page, checkout process, etc.
- Created initial design concepts:
  - Color schemes for buttons, backgrounds, etc.
  - Content structure on the homepage: categories, featured products.
  - Navigation menu design: categories, search bar, account/shopping cart icons.
- Considered replacing the account icon with a shopping cart icon for easier access.

#### Design Changes and Additions

- Developed the **"Ready-to-Buy"** page with text and images (considering a background gradient, which is challenging to implement).
- Improved the top menu:
  - New design on the top right, appearing on subsequent pages.
  - Menu on the left for intuitive navigation, based on course insights.
  - Right side includes **Search**, **Profile**, **Shopping Cart**.
  - Potentially replacing the account icon with a shopping cart icon for better accessibility.
- The menu should be visible across relevant pages, including "Ready-to-Buy" and "Blueprints."

#### Structure and Layout

- Clear page structure with accessible navigation via buttons, images, footer, and top-right menu.
- Landing page accessible via main buttons, images, or footer.
- Top right contains the main navigation menu with all essential functions.
- Main content area:
  - Large, compressed section at the top with a clear structure.
  - Profile information or image, with explanation of design choices.
  - Two prominent buttons ("Ready-to-Buy" and "Blueprints") leading to main sections.

#### Main Compartments and Navigation

- Visual hierarchy with a large top section.
- Colorful images linking to subpages (e.g., Products, Blueprints), designed to be visually appealing and clickable.
- Text compartments with explanatory info, designed to be transparent or subtly integrated.
- Company images (generated via AI, e.g., employees, production) linking to pages like "About Us."
- Footer remains constant with essential links.

#### Design and Visual Elements

- Consideration for product detail pages with expandable animations.
- Use of images with transparent areas blending seamlessly.
- Consistent layout across pages, with variations in text and imagery.
- The background for product images typically in gray, with a preference for lighter tones if available.
- Product info displayed with name and price, with color variations (black or white text).

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

#### Product Presentation

- Products displayed with a gray background, transparent overlay of product images.
- Product name and price shown below the image; text in black or white depending on design.
- Similar layouts used across "Ready-to-Buy" and "Blueprints" pages, with variations in content.

#### Additional Page Details

- **"Blueprints"** page layout mirrors "Ready-to-Buy" but with different text and images.
- Integration of the new top menu design on all relevant pages.
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

#### After Completion of the Basic Layout

- This version will be reviewed by different people:
  - Mother
  - Friend
  - Possibly grandmother (Oma)
- The goal is to cover the target groups: young and middle-aged audiences.

#### Feedback Strategy

- Consider how to gather feedback.
- Feedback will be collected from acquaintances (family and friends) and later from the actual user group.
- The exact method of collecting feedback is still undecided.

#### Navigation Within the Prototype

- Questions about practical navigation in the FIGMA prototype need to be addressed:
  - Example: How to add an order?
  - Example: How to add products to the shopping cart?
- The team will handle these tasks.
- Use the techniques learned in the last session to facilitate testing and feedback.

#### Evaluation of the Testing

- After testing, the results will be analyzed.
- The main focus is to document what was done.

#### Color Scheme

- Used exclusively black and white.
- For all other elements, mainly work with opacity (transparency).

#### Navigation Bar

- Original plan: Create a separate design for the navigation bar.
- Decision: Instead, use an example design (example one) to maximize clarity.
- Design choice based on the desire to provide maximum overview.

#### Design Guidelines

- Based on Apple's Liquid Glass design.
- Aim: Maintain a consistent, modern look with glass-like effects.

#### Page Switching and User Guidance

- When switching pages, the current page is highlighted to indicate control.
- Goal: Provide clear orientation for users.

#### Menu Button (Three Bars)

- Function: When clicked, the menu transforms into a cross to close.
- Intuitiveness: The cross is easier for normal users to understand.
- The three bars are a common symbol for menus, even if the cross is more intuitive.
- Insights:
  - Two criteria in design:
    - The cross is intuitive.
    - Three bars are a standard menu symbol.

#### Variable Storage

- Considering using variables to store the state (expanded or not).
- Goal: Persistently save the menu's status.

#### Liquid Glass Design

- Relatively complex to implement.
- Uses various effects.
- Involves stacking two objects and cutting effects.
- Working with variants:
  - Variants were implemented on a single frame.
  - Not on multiple frames to keep things manageable.
- The lower frame (variant 2) is only a template:
  - Currently has no active role.
  - Serves as a backup for formats in case elements are deleted.

#### Background Design

- Original specification: White background with images (as in blueprints and ready-to-buy).
- Current status: Uncertain whether this still fits well.
- Considerations:
  - Make images transparent.
  - Enclose images with a liquid-glass box.
  - Alternatively: Use a black background, as the glass design looks best on black.
- Currently experimenting and testing different options.

#### Additional Notes

- Need to familiarize with variable handling.
- Objective: Determine which information should be stored.

## Notes - Evaluation & Conclusion

- made a clear plan for the evaluation and conclusion steps (see "Evaluation" in exec_plan.md)
- evaluation will be conducted using the Figma prototype and an online survey (e.g. Google Forms) with quantitative and qualitative questions
- links to the Figma prototype and the online survey will be included in the documentation and the presentation slides
