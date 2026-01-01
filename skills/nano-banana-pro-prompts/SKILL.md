---
name: nano-banana-pro-prompts
description: Guide for creating effective prompts for Google's Nano Banana Pro (Gemini 3 Pro Image) AI image generation and editing model. Use when user needs to write prompts for Nano Banana Pro for tasks like image generation, outpainting, inpainting, style transfer, character consistency, text rendering, infographics, product photography, anime/manga creation, or any image editing with Nano Banana.
---

# Nano Banana Pro Prompting Guide

Nano Banana Pro is Google's state-of-the-art image generation and editing model built on Gemini 3 Pro. It excels at text rendering, character consistency, reasoning-based generation, and up to 4K output.

## Core Principle: Think Like a Creative Director

Nano Banana Pro is a "Thinking" model — it understands intent, physics, and composition. **Do not use tag soups** (e.g., `dog, park, 4k, realistic`). Instead, write structured, intentional prompts.

## Prompt Structure Formula

Include these 6 elements for effective prompts:

1. **Subject**: Who/what is in the image (be specific)
2. **Composition**: Camera angle, framing (close-up, wide shot, low angle, POV)
3. **Action**: What is happening or the state of the scene
4. **Setting/Location**: Where the scene takes place
5. **Style**: Art type, aesthetic (realistic, anime, oil painting, product shot)
6. **Aspect Ratio**: Canvas size (16:9, 3:4, 1:1, etc.)

### Enhanced Details (Optional)

- **Camera/Lens**: f/1.8, 85mm portrait lens, shallow depth of field
- **Lighting**: Golden hour, dramatic shadows, soft diffused light
- **Text Rendering**: Exact text in quotes with placement and typography style
- **Reference Inputs**: Role of each input image (character, style, environment)

## Task-Specific Prompt Patterns

### Outpainting (Image Extension)

```
Extend [Image] beyond its original borders to [aspect ratio] composition.
Keep the main subject intact and centered/positioned at [position].
Generate new content that seamlessly matches:
- Original art style and color palette
- Lighting direction and atmosphere
- Visual consistency (linework, shading technique)
Output: [resolution], seamless integration.
```

### Character Consistency (Identity Locking)

```
Keep the person's facial features exactly the same as [Image1].
Change expression to [emotion] and pose to [action].
Place in [new environment] with [lighting style].
Maintain identity while changing [specific elements].
```

### Inpainting (Selective Editing)

```
In [Image], change only [specific element] to [new version].
Preserve everything else: lighting, shadows, surrounding objects.
Match the original style and color temperature.
```

### Text Rendering

```
Create [image type] with text "[exact text in quotes]".
Text placement: [position - top, center, bottom].
Typography: [font style - bold, serif, handwritten].
Text color: [color] on [background].
Language: [if multilingual].
```

### Product Photography

```
[Product description] in [setting/surface].
Lighting: [style - studio, natural, dramatic].
Background: [type - gradient, contextual, minimal].
Camera: [angle] with [depth of field].
Style: High-end commercial photography.
```

### Anime/Manga Style

```
[Character/scene description] in anime style.
Art style: [specific - cel-shaded, Ghibli-inspired, shonen].
Linework: [clean/sketchy], [line weight].
Color palette: [vibrant/muted/pastel].
Composition: [type - dynamic action, portrait, scenic].
```

### Infographics

```
Create [type] infographic titled "[title]".
Sections: [list main sections].
Visual style: [modern, retro, minimal].
Color palette: [colors].
Include: [icons, charts, data points].
Layout: [vertical/horizontal], evenly spaced.
Text must be legible and correctly spelled.
```

## Iterative Editing Strategy

Nano Banana Pro excels at conversational refinement. If result is 80% correct:

1. **Don't regenerate from scratch** — ask for specific changes
2. Use phrases like: "Now change...", "Add...", "Remove...", "Make the..."
3. Build complex images in stages:
   - Step 1: Basic composition
   - Step 2: Style adjustments
   - Step 3: Detail refinements

## Key Capabilities to Leverage

| Feature | How to Prompt |
|---------|---------------|
| 4K Output | "Output in 4K resolution (3840x2160)" |
| Multi-language Text | "Text in [language], correctly spelled" |
| Multi-image Fusion | Upload multiple images, specify role of each |
| Style Transfer | "Apply style/texture from [Image2] to [Image1]" |
| Camera Control | Specify lens, angle, focus, depth of field |

## Common Mistakes to Avoid

- Vague descriptions ("a nice landscape")
- Tag soup format ("dog, cute, 4k, realistic, detailed")
- Regenerating when minor edits would work
- Forgetting aspect ratio specification
- Not specifying text in quotes for text rendering

## Quick Reference Examples

See [references/prompt-examples.md](references/prompt-examples.md) for copy-paste prompt templates covering:
- Outpainting for wallpapers
- Product photography
- Character consistency
- Anime/manga creation
- Infographics and diagrams
- Style transfer
- Text-heavy designs
