# Nano Banana Pro Prompts

A Claude Code plugin with a skill for creating effective prompts for Google's **Nano Banana Pro** (Gemini 3 Pro Image) AI image generation and editing model.

## What This Skill Does

This skill provides comprehensive guidance for writing structured, effective prompts for Nano Banana Pro. It helps with:

- **Image Generation** - Creating images from scratch with proper structure
- **Outpainting** - Extending images beyond their borders
- **Inpainting** - Selective editing within images
- **Character Consistency** - Maintaining identity across multiple generations
- **Text Rendering** - Adding legible text to images
- **Style Transfer** - Applying artistic styles between images
- **Product Photography** - Commercial-quality product shots
- **Anime/Manga** - Japanese animation and comic styles
- **Infographics** - Data visualization and diagrams

## Installation

```bash
/plugin add github:markbrutx/nano-banana-pro-prompts
```


## Usage

Once installed, use the skill by invoking:

```
/nano-banana-pro-prompts
```

Or simply ask Claude Code to help you write prompts for Nano Banana Pro:

- "Help me write a prompt for Nano Banana Pro to create an anime character"
- "I need to extend this image to 16:9 wallpaper format using Nano Banana"
- "Write a prompt for product photography with Nano Banana Pro"

## Examples

### Outpainting Request
```
Extend this anime image beyond its original borders to a 16:9 widescreen wallpaper.
Keep character's design intact. Expand background naturally.
Output: 3840x2160, seamless integration.
```

### Character Consistency
```
Keep the person's facial features exactly the same as [Image1].
Change expression to happy, new pose: standing.
Place in coffee shop with warm lighting.
```

### Product Photography
```
Perfume bottle floating on dark water surface.
Golden hour lighting, scattered rose petals.
Camera: Low angle, shallow depth of field.
Style: High-end commercial photography.
```

## Key Principles

1. **Think Like a Creative Director** - Write intentional, structured prompts
2. **Avoid Tag Soup** - Don't use comma-separated keywords like "dog, cute, 4k"
3. **Use the 6-Element Formula**: Subject, Composition, Action, Setting, Style, Aspect Ratio
4. **Iterate, Don't Regenerate** - Refine with "Now change..." instead of starting over

## License

MIT License - see [LICENSE](LICENSE) for details.
