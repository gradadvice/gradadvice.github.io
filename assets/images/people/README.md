# Profile Images

This directory contains profile images for people listed in the PhD Advice Hub.

## Image Guidelines

### File Naming
- Use the same filename as the person's markdown file in `_people/`
- Example: For `ilias_stog.md`, use `ilias_stog.jpg` or `ilias_stog.png`

### Image Specifications
- **Format**: JPG or PNG preferred
- **Dimensions**: 400x400 pixels minimum (square aspect ratio)
- **Size**: Keep under 500KB for optimal loading
- **Background**: Professional headshot with clean background

### How to Add a Profile Image

1. **Prepare your image**:
   - Crop to square aspect ratio
   - Ensure good lighting and professional appearance
   - Resize to at least 400x400 pixels

2. **Add the image file**:
   - Place it in this directory (`assets/images/people/`)
   - Name it matching your profile file (e.g., `ilias_stog.jpg`)

3. **Update your profile**:
   - Add `image: /assets/images/people/your_filename.jpg` to your front matter
   - The image will automatically display on your profile page and in the people directory

### Example Front Matter

```yaml
---
layout: page
title: Your Name
name: Your Name
position: PhD Student (Year X)
institution: Your University
field: Your Field
email: your.email@example.com
image: /assets/images/people/your_filename.jpg
---
```

### Placeholder Image

If you don't have a profile image yet, you can:
- Leave the `image:` field out of your front matter
- Use a placeholder service temporarily
- The profile will display without an image until you add one

## Privacy Note

Only upload images you have permission to use and are comfortable sharing publicly.
