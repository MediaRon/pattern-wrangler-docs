---
description: Preview patterns on the frontend
---

# Pattern Previews

The built-in Patterns post type in WordPress doesn't have a frontend preview by default.

With Pattern Wrangler, you can launch a preview from the Patterns screen, or from the block editor. Pattern Wrangler does its best to match your theme when displaying the pattern and is compatible with Full-site Editing (Block) themes.

### Frontend Pattern Previews

The Patterns Preview Screen can be accessed from All Patterns >  and a Click on any of the Patterns on the All Patterns Screen.

Here, you can see what a Pattern will look like on the front end of your site when inserted into a page or post.

<figure><img src="../.gitbook/assets/The Pattern Wrangler Preview Screen.png" alt="Preview a Pattern From the Pattern Wrangler Screen"><figcaption><p>Preview a Pattern From the Pattern Wrangler Screen</p></figcaption></figure>

For those not using block themes, authoring patterns involves a lot of trial and error in coordinating the block editor's appearance with the actual frontend appearance.

The default pattern experience doesn't provide a preview, so we've built one in. It also works well with block themes.

Behind the scenes, we're loading most of the theme's styles, but trying to preserve the pattern's layout and structure. It should provide a close approximation of how a pattern will behave when inserted or displayed on your site.

For security reasons, only those with `publish_posts` permissions can preview patterns.
