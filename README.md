# HiveMQ Brand Guidelines Skill

This skill helps you apply HiveMQ's official brand guidelines to documents, presentations, and other materials.

## What This Skill Does

The skill provides comprehensive guidance on:
- **Colors**: Primary yellow (#FFC000), black, white, and accent teal (#037DA5)
- **Typography**: Arial font family with proper hierarchy
- **Logo Usage**: When and how to use the HiveMQ logo and bee logomark
- **Document Formatting**: Page layouts, headers, footers, tables, callouts
- **Presentation Design**: Slide templates, color schemes, master layouts
- **Brand Principles**: Modern, sleek, professional, and approachable design

## Quick Start

### For Documents (Word/DOCX)

**Example prompt:**
```
Create a white paper about IoT security with HiveMQ branding
```

The skill will automatically:
- Use US Letter page size with 1" margins
- Apply HiveMQ logo on cover page
- Use brand colors (yellow, black, white)
- Format with Arial typography
- Style tables with brand colors
- Include appropriate headers/footers

### For Presentations (PowerPoint/PPTX)

**Example prompt:**
```
Create a 10-slide pitch deck about HiveMQ Platform with our brand guidelines
```

The skill will:
- Create 16:9 slides
- Apply HiveMQ logo/logomark consistently
- Use brand color schemes (white, black, and yellow backgrounds)
- Format text with Arial
- Design charts with brand colors
- Follow slide best practices (minimal text, visual hierarchy)

## Key Brand Elements

### Colors
- **Primary**: Yellow (#FFC000), Black (#000000), White (#FFFFFF)
- **Accent**: Teal (#037DA5) - use sparingly

### Logo
- **Full horizontal logo**: Primary use
- **Full vertical logo**: Compact spaces
- **Bee logomark**: When HiveMQ context is established

### Typography
- **Typeface**: Arial
- **Headings**: Arial Bold (16pt, 14pt, 12pt)
- **Body**: Arial Regular (12pt)

## Usage Tips

1. **Always specify HiveMQ branding**: Include "with HiveMQ branding" or "apply HiveMQ brand guidelines" in your prompt

2. **Color restraint**: The skill knows to use yellow as the primary accent, not overwhelm with it

3. **Professional quality**: Outputs are designed for B2B enterprise use

4. **Variety in presentations**: Mix white, black, and yellow backgrounds across slides for visual interest

5. **Logo context**: The skill will use the full logo initially, then logomark for subsequent pages when appropriate

## Example Prompts

### Documents
```
Create a case study document with HiveMQ branding about a manufacturing IoT deployment
```

```
Make a one-page product sheet for HiveMQ Edge with our brand guidelines
```

```
Create a technical specification document using HiveMQ brand style
```

### Presentations
```
Create a conference presentation about MQTT best practices with HiveMQ branding
```

```
Design a quarterly business review deck following HiveMQ brand guidelines
```

```
Make a training presentation on HiveMQ Data Hub using our brand colors and logo
```

## Testing the Skill

The `evals` directory contains test cases you can use to validate the skill:

1. **eval-0**: Enterprise customer presentation
2. **eval-1**: White paper with HiveMQ branding
3. **eval-2**: One-page product sheet
4. **eval-3**: Quarterly business review template
5. **eval-4**: Technical documentation

To test:
```
Ask Claude to run the skill-creator in eval mode on one of these test cases
```

## What Makes This Different

This skill captures:
- Specific HiveMQ color values and usage rules
- Logo placement and clear space requirements
- Typography standards (Arial-based hierarchy)
- The shift from individual product logos to unified HiveMQ branding
- Balance of technical professionalism with approachable design
- Proper use of the iconic bee logomark

## Files Included

- `SKILL.md` - The complete brand guidelines for Claude
- `evals/evals.json` - Test cases for validation
- `README.md` - This file

## Official Resources

For the most current brand assets:
- **Brand Kit**: https://zeroheight.com/9c4326648/p/19a6ee-hivemq-brand-guidelines
- **Resources Page**: https://www.hivemq.com/company/hivemq-brand-resources/

## Customization

You can extend this skill by:
1. Adding more specific templates (e.g., specific document types)
2. Including additional eval cases for edge cases
3. Adding examples of good/bad brand applications
4. Creating sub-skills for specific document types

## Trademark Notice

All HiveMQ brand features including "HiveMQ", the HiveMQ Logo, and the bee logo are protected by applicable trademark, copyright and other intellectual property laws. Use in accordance with HiveMQ's trademark usage policy.

---

Created: February 2026
Based on: HiveMQ Brand Resources (https://www.hivemq.com/company/hivemq-brand-resources/)
