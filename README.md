# MkDocs-Material-How-to

Ref: 

[Material documentation](https://squidfunk.github.io/mkdocs-material/getting-started/)

# Start MkDocs Website

1. Install the Library

    pip install mkdocs-material

2. Init MkDocs 

    mkdocs new .

3. Minimal Configs

    site_name: My site
    site_url: https://mydomain.org/mysite
    theme:
        name: material

4. Serve to Verify if it Works

    mkdocs serve

5. Build to Static Website

    mkdocs build

# Publish to Github

1. Activate CI using Github Actions
