# ALU VISTA - Images Guide

This guide will help you add images to your website.

## How to Add Images

### Step 1: Upload Your Images
1. Go to the `images` folder in this repository
2. Click on "Add file" → "Upload files"
3. Upload your image files (e.g., sample.jpg, logo.png, product1.jpg)

### Step 2: Use Images in Your Files

#### In Markdown Files (like this README.md):

```markdown
![Image Description](images/sample.jpg)
```

#### In HTML Files (like index.html):

```html
<img src="images/sample.jpg" alt="Image Description" />
```

## Sample Image Examples

Below are examples showing how to display images. After you upload your images, they will appear here:

### Sample Image 1
<!-- CHANGE 'sample.jpg' to your actual image filename -->
![Sample Image](images/sample.jpg)

### Sample Image 2
<!-- CHANGE 'sample2.jpg' to your actual image filename -->
![Another Sample](images/sample2.jpg)

### Product Image Example
<!-- CHANGE 'product.jpg' to your actual product image filename -->
![Product Image](images/product.jpg)

## Notes for Beginners:
- Image filenames should not have spaces (use hyphens or underscores instead)
  - ✅ Good: `my-product.jpg`, `window_sample.jpg`
  - ❌ Bad: `my product.jpg`
- Supported formats: JPG, PNG, GIF, SVG
- Keep image file sizes reasonable (under 5MB per image)
- Always add descriptive alt text for accessibility

## Quick Reference:

**Markdown syntax:**
```
![Alt Text](images/your-image-name.jpg)
```

**HTML syntax:**
```
<img src="images/your-image-name.jpg" alt="Alt Text" />
```

Replace `your-image-name.jpg` with your actual filename!
