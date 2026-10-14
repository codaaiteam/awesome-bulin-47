# Prompt recipe: clean 9:16 portrait (step 1)

**Goal:** turn one front-facing selfie into a clean, well-lit vertical portrait that *looks exactly like the person* — so the next step (scene replacement) stays recognizable.

Works with any image-to-image / editing model (nano-banana, Flux Kontext, GPT-Image, SDXL img2img, etc.).

## Input
- One clear, front-facing photo of the person's face.

## Prompt

```
A clean, natural portrait of the same person from the uploaded photo,
vertical 9:16 framing, head and shoulders, neutral modern street background,
soft even lighting, sharp focus on the face, photorealistic.

No sunglasses, no hat, no costume, no heavy makeup — face fully visible and
clearly recognizable as the person in the uploaded photo. Keep the exact same
facial features, identity, skin tone, hairstyle and age. Do not beautify or
change the face.
```

## Why these rules

- **Face lock** (keep the exact same features) is the #1 factor in whether the final video looks like *you*. Models love to "improve" faces — explicitly forbid it.
- **No sunglasses / costume**: anything covering the face defeats the whole point. Let the scene supply the vibe.
- **9:16** so step 2 doesn't have to crop.

> Prefer a done-for-you version? [bulin47viralvideo.com](https://bulin47viralvideo.com) runs this portrait step automatically before building your video.
