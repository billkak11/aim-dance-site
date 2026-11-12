# AIM Dance — Modern Astro Rebuild

Modern rebuild of Art In Motion Dance Center using the live WordPress site as the content and brand reference.

## Included
- Modern responsive homepage using original AIM photography
- AIM burgundy / blush / black brand system
- Melville + Commack contact details and parent portal links
- Programs: Recreational Dance, Competition Team, Genres, Summer Programs, Birthday Parties, Kickline Technique
- 2026–2027 schedule graphics from the live media library
- 2026–2027 calendar graphic
- Full current 20-person staff roster, with recovered staff portraits where available
- Current events content from the existing Claude project
- Legacy/live URL coverage for `/team/`, `/calendars/`, `/testimonial/`, `/upcoming-events/`, and `/programs/genres/`

## Local development
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```
Output is generated in `dist/`.

## Cloudflare Pages
Use:
- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`

Push the project to the GitHub repository connected to Cloudflare Pages/Workers and allow the deployment to rebuild.

## Media
The original WordPress upload archive contained thousands of generated thumbnail variants. The rebuild carries the original AIM assets actually used by the new pages rather than copying every duplicate WordPress thumbnail into Git.

Deployment refresh - November 4, 2026
