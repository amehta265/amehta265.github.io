# ankitmehta.dev — personal site

Personal research portfolio. Single self-contained `index.html`, no build step
and no dependencies. Served by GitHub Pages.

**Ankit Mehta** — M.S. Robotics, Georgia Institute of Technology.
Safe manipulation near the human body, planning under uncertainty, multi-agent
coordination.

- [amehta318@gatech.edu](mailto:amehta318@gatech.edu)
- [LinkedIn](https://www.linkedin.com/in/ankit-h-mehta/)
- [Google Scholar](https://scholar.google.com/citations?user=VQWRzKwAAAAJ&hl=en)

## Layout

```
index.html          the whole site — markup, styles and scripts
assets/img/         headshot, logos, figures, photographs
assets/video/       compressed demo clips
assets/slides/      research decks as PDF
```

## Local preview

Open `index.html` in a browser. That's it.

## Editing

The colour palette is six CSS variables at the top of `index.html`, with three
alternate schemes commented directly beneath them.

To add a section, copy an `<article class="entry">` block, then add a matching
`<li>` to `nav ol` and give the new `<section>` an `id`. The scroll-spy picks it
up automatically.
