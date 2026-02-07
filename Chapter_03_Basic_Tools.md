---
layout: default
title: "3. Basic Tools"
nav_order: 4
---

# Chapter 3: Basic Tools & Techniques

Now that you know your way around the interface, let's start *doing* something. In this chapter, we will cover the fundamental tools you'll use in almost every project.

We'll focus on Moving, Selecting, Painting, and Erasing.

## 3.1 The Move Tool (V)

The most basic tool is the **Move Tool (V)**. It does exactly what it says: it moves things.

*   **Auto-Select:** In the Options Bar, there's a checkbox called "Auto-Select".
    *   *Checked:* Clicking on the canvas automatically selects the layer under your cursor.
    *   *Unchecked:* You must select the layer in the Layers Panel *before* you can move it.
    *   *Recommendation:* Keep it **unchecked** for now to avoid accidentally moving the wrong thing.
*   **Show Transform Controls:** Check this box to see bounding box handles (little squares) around your selected object, allowing you to resize or rotate it instantly.

## 3.2 Making Selections

Selections are how you tell Photoshop "I want to work on *this specific part* of the image, not the whole thing."

### Marquee Tools (M)
*   **Rectangular Marquee:** Click and drag to select a square or rectangle. Hold **Shift** to make a perfect square.
*   **Elliptical Marquee:** Click and drag to select a circle or oval. Hold **Shift** to make a perfect circle.

### Lasso Tools (L)
*   **Lasso Tool:** Freehand drawing selection. Great for rough selections.
*   **Polygonal Lasso Tool:** Click point-to-point to create straight-edged selections.
*   **Magnetic Lasso Tool:** Snaps to the edges of high-contrast objects.

### Quick Selection & Magic Wand (W)
*   **Quick Selection Tool:** Paint over an area, and Photoshop seemingly "magically" selects the object based on textures and edges.
*   **Magic Wand Tool:** Selects pixels of similar color with a Single Click. Good for solid backgrounds.

**Modifying Selections:**
*   **Add to Selection:** Hold **Shift** and use a selection tool.
*   **Subtract from Selection:** Hold **Alt** (Option on Mac) and use a selection tool.
*   **Deselect:** Press `Ctrl + D` (Cmd + D). Memorize this!

## 3.3 Painting with the Brush Tool (B)

The **Brush Tool (B)** is for painting color.

*   **Picking a Color:** Click the Foreground Color square at the bottom of the Tools Panel to open the Color Picker.
*   **Brush Size:** Use the `[` and `]` bracket keys to quickly resize your brush.
*   **Hardness:**
    *   *0% Hardness:* Soft, fuzzy edges (good for blending).
    *   *100% Hardness:* Crisp, sharp edges (good for drawing).

## 3.4 Erasing (and why you shouldn't)

The **Eraser Tool (E)** removes pixels permanently. When you erase, that information is gone forever.

**The Golden Rule of Photoshop:** destroy as little as possible.

Instead of erasing, professionals use **Layer Masks**. We will cover this in the very next chapter. But for now, just know that while the Eraser exists, it's often better to *hide* pixels than to *delete* them.

## 3.5 cropping and Resizing

Sometimes your canvas isn't the right shape.

*   **Crop Tool (C):** Click and drag the handles to trim your image.
    *   *Delete Cropped Pixels:* Uncheck this in the Options Bar! If you check it, anything you crop out is deleted. Unchecking it keeps the pixels there, just hidden outside the canvas.

---
**Next Up:** In Chapter 4, we tackle the most powerful concept in Photoshop: Layers and Masks. This is where the real magic happens.
