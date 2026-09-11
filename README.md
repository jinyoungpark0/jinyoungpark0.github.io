# Personal website — ready to deploy

Everything is filled in from your CV, including cv.pdf. Nothing is required before publishing. Optional: add a photo (`<img>` in the header) and any DOIs I omitted for older papers.

## Deploy on GitHub Pages (free)

```bash
# from this folder
git init && git add . && git commit -m "personal site"
# create a repo named  <username>.github.io  on github.com, then:
git remote add origin git@github.com:<username>/<username>.github.io.git
git push -u origin main
```

Live at `https://<username>.github.io` within minutes. To update later: edit, commit, push.

## Custom domain (optional, ~$12/yr)

Buy a domain (e.g. jinyoungpark.com), add it under repo Settings → Pages → Custom domain, and point the registrar's DNS at GitHub's A records. Worth doing before the job market — it goes on your CV, biosketch, and talk slides.

## Design notes

Single file, no build step, one Google Font (Newsreader). The pine-green rule beside the header is the identity element — change `--pine` in `:root` to retheme. Citations use hanging indents with your name emphasized; publication entries follow your CV's grouping.

## Replacing the photo

`portrait.jpg` is the retouched version of the photo you sent (white balance corrected,
softened background, 4:5 crop). To swap it, save any new image as `portrait.jpg` in this
folder — ideally around 880x1100, framed on head and shoulders. Nothing in index.html
needs to change.

A plain wall in indirect daylight will beat any amount of editing. Many departments will
take a headshot for postdocs on request.
