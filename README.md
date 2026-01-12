# Illinois English Learners Gap Analysis

Interactive data visualization showing proficiency gaps between overall students and English learners in Illinois schools.

## Files in this Repository

- `index.html` - Main HTML file (42 KB)
- `education_data.json` - Data file (1.7 MB)

## Setup Instructions for GitHub Pages

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com
   - Click "Sign up"

2. **Create a new repository**
   - Click the "+" icon in top right
   - Select "New repository"
   - Name it something like: `illinois-el-gap`
   - Make it **Public**
   - Click "Create repository"

3. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop both `index.html` and `education_data.json`
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section (left sidebar)
   - Under "Source", select "main" branch
   - Click "Save"

5. **Get your URL**
   - Wait 1-2 minutes for deployment
   - Your site will be at: `https://[your-username].github.io/illinois-el-gap/`

## Embedding in Your CMS

Once hosted, embed in your CMS using an iframe:

```html
<iframe 
    src="https://[your-username].github.io/illinois-el-gap/" 
    width="100%" 
    height="1400px" 
    frameborder="0"
    style="border: none; max-width: 1000px; margin: 0 auto; display: block;">
</iframe>
```

Replace `[your-username]` with your actual GitHub username.

## Updating the Data

To update the visualization:
1. Generate new `education_data.json` file
2. Go to your GitHub repository
3. Click on `education_data.json`
4. Click the pencil icon (Edit)
5. Paste new content
6. Click "Commit changes"

Changes appear immediately!

## Data Source

2025 Illinois State Report Card data comparing overall student performance to English Learners.
