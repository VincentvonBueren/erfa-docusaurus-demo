---
title: 🚀 Tutorial with ipt Docs
description: A hands-on intro for internal developers.
keywords: [ipt, documentation, docusaurus, getting started, markdown]
tags: [internal, tutorial]
---

# 🧪 Create Your Own Page

Let’s get hands-on. You’ll now **create your very own doc page** in the tutorial section — from scratch!

### 📂 1. Create a New Folder

Inside the root folder, create a new folder with a high number to place it **last** in the sidebar, for example:

```

docs/99-your-page/

```

Inside that folder, create an `index.md` file.

---

### 📝 2. Add Content in `index.md`

Write your page in Markdown with:

- A main title
- A short paragraph
- A subheading

Example content:

```md
---
title: My Awesome Page
description: This is a test page created in the tutorial.
---

# 🚀 My Awesome Page

Welcome to my custom tutorial page.  
Let’s learn how to make things look great!

## 🔍 A Closer Look

This section contains an image and a styled table.
```

---

### 🖼️ 3. Upload and Embed an Image

Place your image in:

```
static/img/my-screenshot.png
```

Then embed it in your page:

```md
![A screenshot of my app](/img/my-screenshot.png)
```

---

### 📊 4. Add a Table Using HTML

Use raw HTML for flexibility and styling:

```html
<table class="customTable">
  <thead>
    <tr>
      <th>Feature</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Markdown Support</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Custom Styling</td>
      <td>✅</td>
    </tr>
  </tbody>
</table>
```

---

### 🎨 5. Style the Table Header

Create a `styles.module.css` file next to your `index.md`:

```
docs/tutorial/99-your-page/styles.module.css
```

Add this CSS:

```css
.customTable thead {
  background-color: #dceefb;
  color: #003366;
  font-weight: bold;
}
```

Import the style in `index.md`:

```mdx
import styles from './styles.module.css';
```

Done! Your table header now has a nice background color 🎨

**Great job with finishing the tutorial!!!**

Check out the other sites in the sidebar, to learn more about Docusaurus and Markdown!
