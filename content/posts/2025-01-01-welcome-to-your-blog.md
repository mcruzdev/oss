---
title: "Welcome to Your New Blog!"
date: 2025-01-01 10:00:00 +0000
tags: [blogging, roq, getting-started]
description: "Learn how to use this Roq blog template and start writing your own posts. This guide covers everything from basic formatting to advanced features."
toc: true
---

## Getting Started

Welcome! This is a sample post to help you get started with your new blog. You can edit or delete this post and start writing your own content.

Posts are written in **Markdown** (or [Asciidoc](https://iamroq.com/docs/plugins/#plugin-asciidoc)), a simple formatting language that's easy to learn. This post demonstrates various features you can use in your articles.

## Markdown Formatting

### Headings

You can create headings using the `#` symbol:

```markdown
# Heading 1
## Heading 2
### Heading 3
```

### Text Formatting

Make text **bold** with `**bold**` or _italic_ with `*italic*`. You can also combine them: **_bold and italic_**.

Create [links](https://example.com) with `[text](url)`.

### Lists

**Unordered lists:**
- Item one
- Item two
- Item three

**Ordered lists:**
1. First item
2. Second item
3. Third item

### Code Blocks

Inline code uses backticks: `const example = true;`

Code blocks use triple backticks:

```javascript
function greet(name) {
  console.log(`Hello, $\{name}!`);
}

greet('World');
```


### Blockquotes

> "The only way to do great work is to love what you do."
> — Steve Jobs

### Images

```markdown
![Alt text](/path/to/image.jpg)
```

### Tables

| Feature | Supported |
|---------|-----------|
| Markdown | ✅ |
| Syntax Highlighting | ✅ |
| Responsive Design | ✅ |

## Blog Features

### Tags

This post uses tags: `blogging`, `roq`, `getting-started`. Tags help organize your content and improve SEO.

### Excerpts

The `excerpt` in the front matter appears in article lists and meta descriptions. Keep it concise and compelling!

### Table of Contents

Notice the TOC at the top? It's generated from the `toc` section in the front matter or automatically if `toc: true`. 

### Previous/Next Navigation

Navigation links to previous and next posts appear at the bottom of each article.

## Writing Your First Post

1. **Create a new file** in `posts/` directory
2. **Name it** following the format: `YYYY-MM-DD-title.md`
3. **Add front matter** (see below)
4. **Write your content** in Markdown

### Example Front Matter

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-01-15 10:00:00 +0000
tags: [tag1, tag2, tag3]
description: "Brief description for previews"
---
```

## Tips for Great Blog Posts

1. **Write compelling titles** - Your title is the first thing readers see
2. **Use headings** - Break up your content for better readability
3. **Add code examples** - Show, don't just tell
4. **Include images** - Visual content increases engagement
5. **Optimize for SEO** - Use relevant tags and write good excerpts
6. **Be consistent** - Regular posting keeps readers coming back
7. **Edit ruthlessly** - Clear, concise writing is better than verbose prose

## Next Steps

- Delete this sample post
- Delete or update the sample posts in `posts/`
- Customize your `about.md` page
- Write your first real post!

## Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [Roq Documentation](https://iamroq.com/docs/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)

Happy blogging! 🎉

---

**Pro Tip:** Keep this post as a reference for Markdown formatting, or delete it once you're comfortable with the syntax.

