# Ondrej Holub — Personal Website & Blog

My personal website and blog, built with static HTML and CSS.

## Local preview

Open `index.html` in a browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this project to your GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: personal website and blog"
   git branch -M main
   git remote add origin https://github.com/OndrejHolub/Blog.git
   git push -u origin main
   ```

2. In your GitHub repo: **Settings** → **Pages** → **Source** → select **Deploy from a branch**
3. Choose branch **main** and folder **/ (root)**
4. Save. Your site will be live at `https://ondrejholub.github.io/Blog/`

## Adding new blog posts

1. Create a new HTML file in `blog/posts/` (e.g. `my-post.html`)
2. Copy the structure from `blog/posts/welcome.html`
3. Add the post to `blog/index.html` and `index.html` in the Recent Posts section

## Structure

```
Blog/
├── index.html          # Homepage
├── about.html          # About page
├── blog/
│   ├── index.html      # Blog listing
│   └── posts/          # Individual blog posts
├── css/
│   └── style.css       # Styles
└── README.md
```
