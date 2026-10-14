# Prompt recipe: replace the performer (step 2)

**Goal:** drop *your* portrait into the Bulin 47 scene as the lead performer, while keeping everything else — crowd, camera, choreography, and the original audio — untouched.

Works with any **character-replacement / motion-transfer video model** that accepts a reference image + a reference video (Wan, Runway Act-One-style, Kling motion, etc.).

## Inputs
- **Reference image:** your clean 9:16 portrait from [step 1](clean-portrait.md).
- **Reference video:** a short clip (≈8–10s, vertical) of the Bulin 47 scene.

## Prompt

```
Replace only the central performer in the reference video with the person
from the reference image. Keep the same face and identity as the reference
image throughout.

Preserve everything else exactly: the crowd, the background, the club/street
setting, the camera movement, the lighting, the timing, and the original
choreography and shoulder-bounce motion. Keep the original audio. Do not
change the scene, do not add text, do not alter other people in the frame.

Vertical 9:16, photorealistic, consistent identity across all frames.
```

## Settings that matter

| Setting | Recommended |
|---|---|
| Aspect ratio | `9:16` (vertical / adaptive) |
| Resolution | `480p` → `720p` → `1080p` (higher = cleaner face) |
| Duration | match the reference clip (~9s) |
| Audio | **on** (keep the original sound) |

## Notes

- **Identity consistency** is the hard part — a single clean reference portrait usually beats a multi-pose sheet.
- Keep it **lyric-free**: recreate the *video*, don't reproduce the song's copyrighted lyrics.
- Only use footage and photos you have the right to use. Mark your posts as AI-generated.

> Don't want to source a clip or tune a model? [bulin47viralvideo.com](https://bulin47viralvideo.com) does both steps end-to-end — one photo in, a watermark-free 1080p video out.
