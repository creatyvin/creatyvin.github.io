# Manifesto 1000

A personal blog documenting a 14-year experiment: gathering 1,000 people who are changing the world by October 14, 2039.

**Live site:** [creatyvin.github.io/manifesto_1000](https://creatyvin.github.io/manifesto_1000/)

## About

This is not just a blog — it's a verifiable public record. Every thought, every edit, every revision is tracked through Git's version control.

In a future where content is increasingly generated, **provenance matters**. GitHub becomes proof of authentic thinking over time.

## Use as Template

Want to create your own blog like this?

1. **Fork this repository**
2. **Delete content:** Remove everything in `content/` folder
3. **Add your content:** Create your own pages and posts in `content/`
4. **Configure:** Edit `_config.yml` with your name, bio, and links
5. **Enable GitHub Pages:** Repository Settings → Pages → Branch: main

Your blog will be live at `https://YOUR-USERNAME.github.io/manifesto_1000/`

## Structure

```text
├── .theme/          # Template (don't modify)
├── content/         # Your content goes here
│   ├── en/          # English
│   ├── ru/          # Russian (optional)
│   └── images/
├── _config.yml      # Site configuration
└── _data/           # Navigation
```

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

## Features

- Light/Dark theme toggle
- Multilingual support (EN/RU)
- Mobile responsive
- Git history links on every page
- Clean, readable design

## License

MIT — Use freely, modify as needed.

---

*By [Dmytro Grepan](https://github.com/creatyvin)*
