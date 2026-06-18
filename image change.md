# Nano Banana 2 — Style Transfer Prompt (Identity-Locked)

**How to use:** Upload two images in Google AI Studio.
- **Image 1 = Wardrobe + background swatch ONLY** (the outfit, background, lighting you want — NOT a body or a person to copy)
- **Image 2 = The real person** (the one and only person in the output — face AND body stay exactly as they are)

> ⚠️ Adjust the **bolded outfit and build descriptions** in the prompt below to match your own two photos.

Then paste the prompt below.

---

## ✦ The Prompt

> You are editing **Image 2**. The person in Image 2 is the ONLY person in the result. Keep them completely — same face AND same body — and change ONLY their **clothing, background, and lighting** to match **Image 1**.
>
> **Image 1 is a wardrobe-and-background swatch only.** Do not take any part of Image 1's person — not their body, not their build, not their frame, not their face. Image 1 exists only to show what outfit, background, and lighting to use.
>
> **Keep 100% from Image 2 (the real person) — unchanged:**
> - **The full body and build.** This man is larger and heavier-set, with a broad frame, a full round face, fuller cheeks, and a thicker neck. Keep him at exactly that size and shape. Do NOT make him slimmer, narrower, lighter, or more athletic. His width, weight, neck thickness, shoulder width, and round face must stay identical to Image 2.
> - **The entire face**, exactly as in Image 2: facial structure, eyes, nose, mouth, lips, cheeks, eyebrows, jawline, chin, and the **glasses** and **beard**. Do not beautify, slim, or reshape the face.
> - The same skin tone, hair (style, length, color), and overall head shape.
>
> **Take ONLY these from Image 1 (the swatch):**
> - **Outfit:** dress the Image 2 person in the same **charcoal / dark-grey business suit, white dress shirt, and maroon (burgundy) tie**. The suit must be tailored to fit his real, larger body — drape the fabric over his actual broad frame. Do NOT shrink his body to fit a slim suit.
> - **Background:** the same neutral grey studio gradient.
> - **Lighting & color grading:** the same professional studio lighting and tone.
> - **Pose (optional):** you may use the arms-crossed, slightly-turned orientation — but bend *his own larger arms and body* into that position. Never substitute the reference's thinner arms or torso.
>
> **Hard rules — most important first:**
> 1. The man's body and face MUST stay the size and shape of Image 2. **If the result looks thinner or smaller than Image 2, it is wrong.**
> 2. Do not merge, blend, or average the two people. Image 1's body has zero influence on the output.
> 3. Keep the glasses, beard, and full face from Image 2.
>
> **Final result:** A photorealistic professional corporate headshot of the *exact* person from Image 2 — same heavy-set build, same full round face, same beard and glasses — now wearing the grey suit, white shirt, and maroon tie on a grey studio background, lit and graded like Image 1. He must be instantly recognizable as the same individual, **at his true body size**, with no slimming or reshaping.
>
> Render in sharp, high resolution with natural, realistic detail.

---

## ✦ Follow-up fixes (if the first result is off)

- **Face changed too much:**
  *"The face changed too much — regenerate keeping the face pixel-for-pixel identical to Image 2, only changing the outfit, background, and pose."*

- **Features look off (eyes, nose, mouth, etc.):**
  *"The eyes / nose / mouth / cheeks don't match — reproduce each facial feature exactly as in Image 2 so it is clearly the same person."*

- **Body got replaced with the reference's body (looks thin / cartoon-like / like someone else):**
  *"You replaced the body with the body from Image 1 — that is wrong. Keep ONLY the pose direction from Image 1. The body must be the real body of the person in Image 2: same width, same thickness, same build. Re-pose that exact body, do not reshape or slim it."*

- **Neck or body proportions changed:**
  *"Keep the neck, throat, and body proportions identical to Image 2 — same neck thickness, same body width, length, and build on both sides. Do not slim or reshape."*

- **Wrong outfit color:**
  Name the exact color, e.g. *"emerald-green shimmering satin"* or *"rose-gold radiant fabric."*

- **Wrong crop/zoom:**
  *"Match the framing of Image 1 exactly — same crop from [chest / waist / knees], same camera distance."*

- **Background not matching:**
  *"Replace the background with the exact gradient and color tone from Image 1."*

---

## ✦ Tips

- **The body-slimming problem is the hard part.** When the swatch person (Image 1) is much thinner than the real person (Image 2), the model wants to average the two. The fix is framing: never say "transfer from Image 1" — say "keep the Image 2 person, only change clothes/background." That's why this prompt is written subject-first.
- **Describe your real build in words.** The model can't be trusted to just "see" it. Stating "larger, heavier-set, broad frame, full round face" does more than any "keep the body" instruction alone.
- **Consider dropping the arms-crossed pose** if slimming persists. The crossed-arms pose is the strongest thing dragging in the thin reference frame. A simple straight-on or hands-relaxed pose preserves your real build far more reliably.
- Nano Banana 2 responds best to **concrete visual instructions**, not role-play setups.
- Generate a few times; pick the best and refine with a short follow-up rather than rewriting the whole prompt.



