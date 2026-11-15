# Image Generation Prompts for Vishal & Poonam Wedding Website

Use these with your preferred image generation model (Midjourney, DALL-E, Ideogram, etc.).

---

## 1. Watercolor Couple Portrait (Main Website Image)

> **Prompt:**
> A beautiful soft watercolor painting of a young Indian couple in traditional wedding attire. The woman wears a vibrant pink and magenta Banarasi silk saree with golden zari border, she has long flowing black hair, a delicate nose ring, and a silver necklace, smiling warmly. The man wears a crisp white kurta, has short dark hair and light stubble. They stand close together, shoulders touching, looking at the camera with warm expressions. Surrounded by marigold flowers and soft golden light. Painted in a loose, romantic watercolor style with visible brushstrokes, warm tones of saffron, gold, crimson and rose. Cream/ivory paper background bleeding through the paint. No harsh edges, everything dissolves into the paper at the borders. Vertical portrait orientation, 3:4 aspect ratio.

**Negative prompt (if supported):** photorealistic, digital art, hard edges, dark background, western clothing, cartoon, anime

**Settings:** Aspect ratio 3:4 (portrait), high quality, artistic style

---

## 2. Social Sharing Preview Image (OG Image)

> **Prompt:**
> An elegant wedding invitation graphic in warm Indian style. Cream and ivory textured background with subtle gold filigree patterns. Text area in the center reading "Vishal & Poonam" in flowing calligraphy. Decorative marigold garland border at the top. Small traditional Indian motifs — a paisley, a diya lamp, and scattered rose petals. Color palette of deep maroon, warm gold, saffron orange, and cream. Landscape orientation, 1200x630 pixels, clean and readable at small size. Watercolor wash texture on the background.

**Settings:** Aspect ratio 1200:630 (or 16:9), high quality

---

## 3. Envelope Background Texture (Optional)

> **Prompt:**
> A seamless ornamental Indian pattern in warm gold tones on a deep saffron background. Subtle paisley and mandala motifs in slightly lighter gold. Traditional Mughal-inspired floral border elements. Luxurious silk-like texture. Elegant and understated, not too busy. Top-down flat view suitable for use as an envelope or card texture. Square format.

**Settings:** Aspect ratio 1:1, tileable/seamless if possible

---

## 4. Decorative Border/Frame Element (Optional)

> **Prompt:**
> A decorative Indian wedding invitation border frame in watercolor style. Marigold garlands draped along the top, with delicate golden vines and leaves curving down the sides. Small traditional bells (ghungroo) hanging from the garland. A few red rose petals scattered at the corners. Painted in warm watercolor tones — saffron yellow, deep gold, crimson red, and soft pink. Transparent/white background (PNG-style). Ornate but not cluttered. Vertical portrait orientation.

**Settings:** Aspect ratio 3:4, transparent background if supported

---

## How to Use

1. **Prompt #1** is the most important — it replaces the current couple photo on the website. Generate it, save as `couple.webp` or `couple.jpg`, and replace the existing `couple.jpg` in the website folder.

2. **Prompt #2** creates the social sharing preview that shows up when the link is shared on WhatsApp, Instagram, etc. Save as `preview.jpg` (1200x630px).

3. **Prompts #3 and #4** are optional decorative elements you can incorporate if desired.

## Tips for Best Results
- Upload the real couple photo (Image 3) as a reference when using Prompt #1
- For Midjourney, add `--style raw --v 6.1` for more natural results
- For DALL-E, specify "watercolor painting" emphasis
- Generate 3-4 variations and pick the one that captures the couple's likeness best
