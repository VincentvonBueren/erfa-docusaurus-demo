---
title: Getting Started
description: Learn how to run, edit, and contribute to the ipt Documentation using Docusaurus. A hands-on intro for internal developers.
keywords: [ipt, documentation, tutorial, getting started, markdown]
tags: [internal, how-to, onboarding, tutorial]
---

import useBaseUrl from '@docusaurus/useBaseUrl';

# Welcome to the **ipt Docs Developer Guide**!

This short guide will walk you through setting up the site locally, editing content, and starting your tutorial journey.

---

## ✍️ How to Edit Docs

Docusaurus uses Markdown (`.md` and `.mdx`) for documentation pages. Most docs are under the `docs/` folder.

To add or edit a doc:

1. Navigate to the appropriate subfolder inside `docs/`.
2. Create or update `.md` or `.mdx` files.
3. When your Docusaurus server is running you will directly see the changes.
   If not --> Run `npm run start` to preview your changes locally.

You can use regular Markdown, but also include **React components**, **HTML**, and custom **styles**.

---

## 🚧 Activating the Tutorial

We’ve included a hidden `_tutorial/` folder with example content.

To activate it, you must remove the `_` (Docusaurus simply ignores \_):

```bash
mv _tutorial tutorial
```

This will make the tutorial sidebar appear in the UI! Now, complete the tutorial.

---

That’s it for now!
Check out the next tutorial step and start customizing.

Happy documenting 💙
