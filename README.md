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
2. Select "Deploy from branch" and gh-pages as branch
3. Set Custom domain

    a. Set domain name url in repo settings such as: https://www.necmettinceylan.com/

    b. Add record to domain settings such as: 

    | Host  | Type | Data
    | ------------- | ------------- | ------------- |
    | www  | CNAME | \<gh-username>.github.io

    