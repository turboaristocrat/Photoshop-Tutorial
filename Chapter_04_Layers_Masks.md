---
layout: default
title: "4. Layers & Masks"
nav_order: 5
---

# Chapter 4: Layers & Masks – The Heart of Photoshop

If you only learn one thing about Photoshop, learn Layers. Layers are what separate Photoshop from simpler paint programs. They allow you to work non-destructively, meaning you can change one part of an image without ruining the rest.

## 4.1 Understanding Layers

Imagine a stack of transparent acetate sheets. You can paint on one sheet, place a photo on another, and add text on a third. looking down through the stack, you see a composite image.

**The Layers Panel:**
*   **Background Layer:** The bottom-most layer. Usually locked. If you erase on it, it turns to the background color, not transparent.
*   **New Layer Button (+):** Creates a fresh, empty transparent layer on top of the selected layer.
*   **Delete Layer (Trash Can):** Deletes the selected layer.
*   **Eye Icon:** Toggles visibility on/off. Hiding a layer is often better than deleting it!

**Layer Types:**
1.  **Pixel Layers:** Standard layers containing painted pixels or photos.
2.  **Type Layers:** Text. These remain editable (you can fix typos) until you "rasterize" them.
3.  **Adjustment Layers:** Special layers that change color or tone of layers below them (e.g., Black & White, Curves). They don't contain pixels themselves.
4.  **Shape Layers:** Vector shapes like rectangles and circles.

## 4.2 Managing Layers

As you work, you'll accumulate many layers. Staying organized is key.

*   **Renaming:** Double-click the layer name to rename it (e.g., "Sky," "Subject," "Retouching"). Do this early and often!
*   **Grouping:** Select multiple layers (Shift-click) and press `Ctrl + G` (Cmd + G) to put them in a folder.
*   **Moving:** Drag layers up or down in the panel to change their stacking order. Top layers cover bottom layers.

## 4.3 Blending Modes

At the top of the Layers Panel is a dropdown menu that says "Normal." This is the **Blending Mode**.

Changing this changes how the selected layer interacts with the layers below it.

**Common Blending Modes:**
*   **Multiply:** Darkens the image. Great for shadows or removing white backgrounds.
*   **Screen:** Lightens the image. Great for adding light effects or removing black backgrounds.
*   **Overlay:** Adds contrast. Makes lights lighter and darks darker.
*   **Color:** Changes the color without affecting brightness (great for recoloring objects).

## 4.4 Introduction to Layer Masks

Remember the Eraser Tool? Forget it. **Layer Masks** are the professional way to hide parts of a layer.

**Why Masks are Better than Erasing:**
*   **Reversible:** If you erase too much with the Eraser, you have to Undo. If you hide too much with a Mask, you just paint it back.
*   **Non-Destructive:** The original pixels remain untouched.

**How to Use a Mask:**
1.  Select a layer.
2.  Click the **Add Layer Mask** button (rectangle with a circle) at the bottom of the Layers Panel. A white thumbnail appears next to your layer thumbnail.
3.  **White Reveals, Black Conceals.**
    *   Paint with **Black** on the mask to **hide** parts of the layer.
    *   Paint with **White** on the mask to **show** parts of the layer.
    *   Paint with **Gray** for partial transparency.

**Exercise:**
Open a photo. Add a mask. Paint with black to see the layer disappear. Switch to white and paint it back. Once you grasp this concept, you've unlocked 90% of Photoshop's power.

---
**Next Up:** In Chapter 5, we'll look at how to make your photos pop with Adjustments and Filters.
