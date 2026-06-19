# perryazevedo.com

Personal site for Perry Azevedo — investor, entrepreneur, designer, engineer, and fly fishing guide.

Plain, self-contained HTML/CSS/JS. No build step, no framework, no backend.

## Structure

```
index.html        Homepage — hero, approach, "What I do" index, ethos, contact
portfolio.html    Selected design & code work (5 projects)
assets/           Images and (compressed) video
robots.txt
sitemap.xml
```

## Local preview

Any static server works, e.g.:

```bash
python3 -m http.server 4321
# open http://localhost:4321
```

## Deploy (GitHub Pages)

Pushed to the default branch and served via GitHub Pages. Custom domain configured
through the `CNAME` file + DNS (A records to GitHub Pages IPs, or a CNAME to the
`*.github.io` host for a subdomain).

## Notes

- Built from a high-fidelity design handoff; the DC prototype runtime was stripped
  and the Entrepreneurship toggle + scroll-reveal re-implemented as plain JS.
- Videos were re-encoded (H.264, CRF 27–28, audio stripped) to keep the repo light.
