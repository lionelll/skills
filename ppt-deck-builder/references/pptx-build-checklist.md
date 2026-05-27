# PPTX Build Checklist

## Before Building

- Confirm aspect ratio, usually 16:9.
- Confirm output language.
- Confirm page count or infer a reasonable range.
- Confirm whether the user needs editable PPTX, PDF, image preview, HTML preview, or speaker notes.
- Gather brand assets if required: logo, colors, font, screenshots, product images.

## Recommended Build Flow

1. Create slide plan.
2. Write visible slide text and notes.
3. Define visual system.
4. Build editable PPTX using the available presentation tooling.
5. Render or inspect the deck.
6. Fix overflow, alignment, contrast, and missing assets.
7. Deliver final file with a short change summary.

## Verification

Check:

- File opens.
- Slide count matches plan.
- Text is not clipped.
- Notes are present when requested.
- Images and charts render.
- Fonts and colors are consistent.
- Charts have readable labels.
- Tables fit the slide.
- Final slide has a clear action or takeaway.

## JSON-Like Structure

Use this internal structure when converting content into a deck:

```json
{
  "metadata": {
    "title": "",
    "audience": "",
    "goal": "",
    "style": "",
    "aspect_ratio": "16:9"
  },
  "slides": [
    {
      "number": 1,
      "type": "cover",
      "title": "",
      "message": "",
      "visible_content": [],
      "visual": "",
      "notes": ""
    }
  ]
}
```

The structure is a planning aid, not a required final format.
