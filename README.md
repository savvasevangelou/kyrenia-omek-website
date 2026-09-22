# ΟΜΕΚ Κερύνειας

Website for the Ομοσπονδία Συνδέσμων Γονέων Μέσης Εκπαίδευσης Επαρχίας Κερύνειας
(Federation of Secondary Education Parents' Associations of Kyrenia District),
hosted as a static site with GitHub Pages. Bilingual: Greek / English.

**Live site:** https://savvasevangelou.github.io/kyrenia-omek-website/
**Contact:** omkeryneias@gmail.com

## Structure

- `index.html` — the whole site (single page)
- `kyrenia-castle.jpg`, `kyrenia-limani.jpg` — hero photos
- `crest-header.png`, `crest-footer.png` — federation crest (dark/light variants), also used as the favicon
- `map.jpg` — map graphic used in the About section

## Updating the site

Edit `index.html` (or the images), then:

```
git add .
git commit -m "describe your change"
git push
```

GitHub Pages rebuilds automatically after each push to `main`, usually live within a minute or two.
