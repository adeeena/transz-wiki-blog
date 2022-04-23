---
body_classes: 'title-center title-h1h2'
hide_git_sync_repo_link: false
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
content:
    items:
        - '@self.children'
    limit: 25
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: false
feed:
    limit: 10
hero_image: Banner.png
hero_classes: 'hero-large text-light parallax'
routable: true
visible: true
redirect_default_route: true
routes:
    default: /
---
