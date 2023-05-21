---
theme: ./
favicon: 'https://cdn.jsdelivr.net/gh/jcalixte/static/tucano.svg'
---

# Tucano

Slides for joyful presentation

<p>
  Press <kbd>space</kbd> for next page <carbon:arrow-right />
</p>

---
layout: intro
---

# Intro

<Toc />

---
layout: two-cols
---

# The build-in layouts

- center,
- cover,
- default,
- end,
- fact,
- full,
- image-left,
- image-right,
- image,

::right::

<br>
<br>
<br>

- iframe-left,
- iframe-right,
- iframe,
- intro,
- none,
- quote,
- section,
- statement,
- two-cols,

---

# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features

- **Text-based** - focus on the content with Markdown, and then style them later
- **Themable** - theme can be shared and used with npm packages
- **Developer Friendly** - code highlighting, live coding with autocompletion
- **Interactive** - embedding Vue components to enhance your expressions
- **Recording** - built-in recording and camera view
- **Portable** - export into PDF, PNGs, or even a hostable SPA
- **Hackable** - anything possible on a webpage

Read more about [Why Slidev?](https://sli.dev/guide/why)

---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel

## Keyboard Shortcuts

|   Shortcut  |  Description   |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

---
layout: image-left
image: 'https://source.unsplash.com/collection/9657233/1920x1080'
---

# Image left

Use code snippets and get the highlighting directly!

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)

  return true
}
```

---
layout: image-right
image: 'https://source.unsplash.com/collection/9530167/1920x1080'
---

# Image right

---
layout: center
---

# Learn More

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
