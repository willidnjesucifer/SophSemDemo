# 🎨 Artist Portfolio Website Guide (VS Code Version)

Welcome! This template helps you build and publish your own artist portfolio website using:

- HTML (website structure)
- Tailwind CSS (visual styling)
- GitHub Pages (free web hosting)
- Visual Studio Code (editing software)

---

# 📦 Before You Start

## Create GitHub Account

👉 https://github.com

# 📁 Understanding Your Website Folder

Your entire website lives inside one folder.
SOPHSEMDEMO/
│
├── index.html (homepage + gallery)
├── projects/
│ └── project-template.html (Copy this to make new projects)
│
├── images/
│ └── image files
└── README.md

## Preview Your Website While Editing

    1. In Finder or Windows Explorer, navigate to your file folder
    2. Right click on index.html
    3. 'Open with' the browser of your choice (Chrome, Safari, Firefox etc)

    Your website will open in your browser and automatically update when you save changes.

## Adding Your Artwork

    1. Add Images
        Images should be jpeg, png, or webm file format.
        Images should be no more than 2000px on the longest edge.
        Place your artwork image files inside:
            images/

    2. Use The Image In HTML
        Replace placeholder: images/placeholder.jpg
        With:
        images/<my-artwork.jpg>

## Important Image Rules

    Do NOT use spaces in file names
        ✅ Good
        video-installation.jpg
        ❌ Bad
        Video Installation FINAL.jpg

## Adding New Projects

    1. Duplicate Project Template
        Right click: project-template.html > Copy > Paste

    2. Rename file:
        project-new-title.html

    3. Edit Project Page
        Update:
        Project title
        Images
        Description
        Project information

    4. Add Project To Homepage Gallery
        Open: index.html
        Find project card block and duplicate it.
        Update the link:
            href="projects/project-new-title.html"

    5. Changing Fonts
        1. Research fonts you like on google fonts. Choose no more than two fonts (one for headers and one for body copy)
        👉 https://fonts.google.com

        2. Copy Embed Code
            Google Fonts provides code like:
            <link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">
                                                                ^note the font name
        3. Paste inside <head> in:
        - index.html
        - project pages

        4. Apply Font
        Replace: <body class="font-sans">
        With:<body class="font-[Inter]">

## Changing Colors

Tailwind uses simple color classes.
Examples:
bg-white
bg-gray-100
text-black
text-blue-600

Explore colors here:
👉 https://tailwindcss.com/docs/colors

## Publishing Your Website

    1. Create GitHub Repository
    - select the source control button in VSCode
    - select 'initialize repository'
    - Write message that describes your changes:
        "Initial portfolio upload"
    - Click 'Commit'
    - Click 'Publish Branch'
    - Login to Github if needed

    2. Publish Website
    - Navigate to github.com and login
    - Navigate to your repository
    - Settings > Pages
            - Source > Deploy from Branch
            - Branch > Main > Save
    Github will gerate a url for your project
    https://yourusername.github.io/your-repository

## Updating Your Website Later

Whenever you make changes:

    1. Save files in VS Code
    2. Write a comment & commit changes
    3. Push to GitHub
    4. Your site updates automatically.

🆘 Troubleshooting

Images Not Showing
Check: - File exists inside images folder - Spelling matches exactly - Path is correct

Page Link Broken
Check: - File exists inside projects folder - Matches filename exactly. - Path is correct
