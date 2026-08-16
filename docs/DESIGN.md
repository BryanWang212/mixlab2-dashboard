---
design_system:
  name: "PRADA Fall/Winter 2013 Campaign"
  context: "Dane DeHaan Editorial Portrait"
  tokens:
    colors:
      primary:
        - name: "Deep Charcoal"
          hex: "#2C2E30"
          usage: "Main upper garment, defining shadow tones"
        - name: "Warm Olive"
          hex: "#89896C"
          usage: "Background backdrop, conveying industrial quietude"
        - name: "Muted Teal"
          hex: "#527877"
          usage: "Pattern accent in the floral/foliage print"
        - name: "Antique Gold"
          hex: "#C2A35E"
          usage: "Base color of patterned sleeves, contrast point"
        - name: "Graphite Stripe"
          hex: "#4A4D52"
          usage: "Pinstripe trouser tone"
        - name: "Dusty Sand"
          hex: "#AEA684"
          usage: "Footwear base"
        - name: "Brand White"
          hex: "#FFFFFF"
          usage: "Typography, primary brand contrast"
    typography:
      serif:
        - name: "PRADA Display Serif"
          weight: "Bold / High Contrast"
          letter_spacing: "Tight (0.02em)"
          case: "Uppercase"
          color: "Brand White"
          usage: "Main logo lockup"
      sans_serif:
        - name: "Informational Sans-Serif"
          weight: "Regular / Light"
          letter_spacing: "Moderate (0.05em)"
          case: "Sentence case"
          color: "Brand White"
          usage: "Campaign attribution copy"
    spacing:
      base_grid: 8
      margins:
        edge_padding: 16px
    shadows:
      depth_0:
        description: "Flat, no shadow. Built for raw, hard studio lighting."
      depth_1:
        description: "Subtle cast shadow on the floor under the stool, grounding the subject."
    borders:
      radius:
        base: 0px
        description: "Strictly rectilinear. No rounded corners on the chair or graphic elements to maintain an architectural rigidity."
---

# PRADA Fall/Winter 2013 Campaign Design System

## Overview (品牌与风格综述)
This design system captures the distinct visual identity of the PRADA Fall/Winter 2013 campaign, as exemplified by the Dane DeHaan portrait. The core philosophy is **"Tension between architectural rigidity and eccentric individuality."** 

The design does not rely on softness or luxury gloss; instead, it embraces a raw, cinematic, and slightly melancholy atmosphere. 
- **Silhouette:** Layered and slightly disheveled, emphasizing substance over form-fitting tailoring.
- **Mood:** Introspective, quiet, and intellectual—reminiscent of a 1970s indie film still.
- **Application:** When utilizing this system, focus on creating high-contrast, flat compositions where the texture of the material (heavy fabric, painted backdrop, matte leather) takes precedence over digital gradients.

## Colors (色彩)
The palette is desaturated and earth-bound, relying on natural pigments rather than neon or synthetic vibrancy. It uses color as a narrative tool to create a "moody narrative."
- **Primary Palette (Foundation):** *Deep Charcoal (#2C2E30)* and *Warm Olive (#89896C)*. These form the background and core garments, providing a stage of quiet stability.
- **Accent Palette (Personality):** *Antique Gold (#C2A35E)* and *Muted Teal (#527877)*. These colors appear exclusively together in the patterned sleeves of the garment. They act as a deliberate "disruption" to the monochrome outfit, signaling eccentricity.
- **Neutral:** *Brand White (#FFFFFF)* is reserved solely for the text overlay. It must be pure and opaque to ensure high legibility against the desaturated background.

## Typography (排版)
The typography acts as an architectural anchor, preventing the image from floating. 
- **Primary Lockup (PRADA):** Use a heavy, high-contrast Serif font in all-caps. The tracking should be extremely tight (almost touching), simulating an engraved metal plaque or an editorial header. It creates a stark, unyielding baseline for the composition.
- **Secondary Copy:** Use a clean, thin Sans-Serif for the attribution ("Dane DeHaan", "New York, November 2013"). This captures the utilitarian nature of the campaign—the information is presented factually, without ornamentation.

## Layout (布局与间距)
- **Composition:** Asymmetrical, heavily relying on the **"Rule of Thirds"**. The subject (Dane) sits slightly to the left, creating negative space on the right that accommodates the intersecting lines of his legs.
- **Verticality:** Strong vertical lines are prioritized: the legs of the stool, the pinstripes on the trousers, and the thick serif font of the logo all point the eye downwards or upwards, lending a sense of height and elongation.
- **Text Positioning:** The typography should act as a footer anchor. The logo is placed horizontally centered but vertically pushed to the lower third of the frame, acting as the ground layer of the design. Do not float text freely in the background; it must interact with the subject's physical positioning.

## Elevation & Depth (层级与深度)
This design specifically avoids deep digital layering (like drop shadows or heavy blurs). 
- **Flatness:** The visual hierarchy is established through **contrast and scale**, not through Z-index complexity. 
- **Lighting Depth:** Depth is achieved via "hard studio lighting." The subject and the stool cast a *single, sharp cast shadow* onto the backdrop floor. 
- **Implementation:** If simulating this effect digitally, use a hard, low-opacity black brush for shadows, rather than a soft Gaussian blur. The subject should feel physically present and weighty on the stool.

## Shapes (形状/圆角)
- **Rectilinear Philosophy:** The system rejects rounded corners. The stool, the text wrapping, and the structure of the set design rely purely on straight lines and 90-degree angles. 
- **Texture:** Rounded forms appear *only* organically (the curvature of the model's face, the rounded toe of the shoe). Therefore, UI elements or graphical boxes associated with this system *must* have `border-radius: 0px`.

## Components (组件详情)
1.  **The Canvas Backdrop:**
    - Visual texture: Matte, slightly mottled (simulated painted canvas).
    - Color: Warm Olive (#89896C).
    - Sharp intersection point where the wall meets the floor, kept dark and contrasting.
2.  **The Layered Garment:**
    - Outer layer: Solid, porous matte fabric (Deep Charcoal).
    - Inner layer (sleeves): High-contrast pattern print (Antique Gold base + Muted Teal foliage).
    - Note: The pattern should appear slightly "subdued" or faded to maintain the vintage/editorial feel.
3.  **The Anchor Stool:**
    - A minimal, dark brown/black, square-legged wooden stool. No cushions. It acts as a sculptural foundation.
4.  **Typography Overlay:**
    - Pure White (`#FFFFFF`).
    - Stacked vertically (Logo -> Spacer -> Attribution).

## Do's and Don'ts (最佳实践与禁忌)

**✅ Do's (遵循):**
- **Do** use high-negative-space compositions. Let the deep charcoal and olive tones breathe around the subject.
- **Do** ensure the brand typography is anchored to the lower third of the canvas.
- **Do** use hard, directional lighting to emphasize the texture of the fabric and the architectural lines of the set.
- **Do** apply the patterned sleeves (Antique Gold/Teal) sparingly; they are an accent, not the primary visual mass.
- **Do** maintain strict 90-degree corners on all physical set pieces and UI boxes.

**❌ Don'ts (禁忌):**
- **Don't** use bright, vibrant neon colors (magenta, bright cyan, electric yellow). The palette must remain desaturated and earthy.
- **Don't** use soft, glowing drop shadows or heavy gradient overlays. The aesthetic requires a flat, cinematic harshness.
- **Don't** use rounded corners on borders, frames, or furniture.
- **Don't** center-align the secondary attribution text (Dane DeHaan, etc.) if it disrupts the visual balance of the primary logo.
- **Don't** make the subject look overly cheerful or brightly lit; the mood must remain introspective, brooding, and reserved.