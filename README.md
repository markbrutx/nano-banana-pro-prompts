# Nano Banana Pro Prompts Plugin for Claude Code

A Claude Code plugin with a skill for creating effective prompts for Google's **Nano Banana Pro** (Gemini 3 Pro Image) AI image generation and editing model.

## Features

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

### Option 1: Install via Claude Code CLI

```bash
claude plugin install github:markbrutx/nano-banana-pro-prompts
```

### Option 2: Clone to plugins directory

```bash
cd ~/.claude/plugins
git clone https://github.com/markbrutx/nano-banana-pro-prompts.git
```

### Option 3: Local installation (for development)

```bash
claude plugin install /path/to/nano-banana-pro-prompts
```

## Usage

Once installed, Claude Code will automatically use this skill when you:

- Ask about creating prompts for Nano Banana Pro
- Request help with image generation, outpainting, inpainting
- Want to create anime/manga style images
- Need product photography prompts
- Work with text rendering in images

### Example Prompts

```
Help me write a prompt for Nano Banana Pro to create an anime character
```

```
I need to extend this image to 16:9 wallpaper format using Nano Banana
```

```
Write a prompt for product photography with Nano Banana Pro
```

## Plugin Structure

```
nano-banana-pro-prompts/
├── .claude-plugin/
│   ├── marketplace.json
│   └── plugin.json
├── skills/
│   └── nano-banana-pro-prompts/
│       ├── SKILL.md
│       └── references/
│           └── prompt-examples.md
├── README.md
├── LICENSE
└── .gitignore
```

## Key Principles

1. **Think Like a Creative Director** - Write intentional, structured prompts
2. **Avoid Tag Soup** - Don't use comma-separated keywords like "dog, cute, 4k"
3. **Use the 6-Element Formula**: Subject, Composition, Action, Setting, Style, Aspect Ratio
4. **Iterate, Don't Regenerate** - Refine with "Now change..." instead of starting over

## Resources

- [Google AI Studio](https://aistudio.google.com/)
- [Gemini API Documentation](https://ai.google.dev/docs)

## License

MIT License - see [LICENSE](LICENSE) file for details.
