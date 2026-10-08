# La Rueda Films Productions — Company website

Website for **La Rueda Films Productions**, an audiovisual production company based in Ciudad Real, Spain: direction, cinematography, drone, editing and color.

Static, bilingual (Spanish / English) site designed and built from scratch: structure, UI/UX, copy layout, front-end code and deployment plan.

> *Sitio web estático y bilingüe (ES/EN) de la productora audiovisual La Rueda Films Productions. Estado: borrador.*

**Status:** draft, in progress.
**Planned domain:** laruedafilmsproductions.com

## Sections

| Section | Purpose |
|---|---|
| Hero | Brand line and call to action |
| Servicios | What the company offers |
| Certificaciones | Certified training in digital marketing, artificial intelligence and data analysis, linked to the public LinkedIn credentials |
| Trabajos | Reel cards, each linking to a video on the company's YouTube channel |
| Equipo | Team profiles with downloadable CVs (PDF) |
| Contacto | Contact details and social links |

## Features

- **ES / EN toggle**, with the chosen language remembered between visits.
- **Reel cards with poster images** linking to YouTube.
- **Downloadable CVs** (PDF) for each team member.
- **Introductory brand ident** video.
- **SEO basics:** page title and meta description.
- **Responsive layout** using a consistent typographic system (Antonio, Figtree and JetBrains Mono via Google Fonts).

## Tech stack

- HTML5, CSS3 and vanilla JavaScript (no framework, no runtime dependencies).
- Google Fonts.
- Images optimized as separate JPG files.

## Project structure

```
laruedafilms-web-borrador/
├── index.html
├── ident.mp4        # brand ident
├── img/             # logos, reel posters, section images
└── cv/              # team CVs (PDF)
```

## Deployment plan

- **Hosting:** Cloudflare Pages.
- **DNS:** migrate the domain from WordPress.com nameservers to Cloudflare, with HTTPS.
- **Next steps:** Google Search Console, structured data (JSON-LD) and Google Business Profile once the company is fully settled in Spain.

## Roadmap

- Connect the final domain and publish.
- Add structured data and sitemap.
- Add remaining reel links and client testimonials.
- Optimize the ident video for faster first load.

## License

© La Rueda Films Productions. All rights reserved. The code is published for reference; images, videos and text are not licensed for reuse.
