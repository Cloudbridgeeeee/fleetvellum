# FleetVellum

**Financial intelligence for every fleet.** Vehicle cost tracking for fleet managers.

- Founder and CEO: Kingsley Eze
- Co-founder and CTO: Temitope Ajayi

## Structure

- `index.html`: the marketing page, built on the TasteSkill kit (`public/assets`) with a dealt hero, palette, type and moments. Design rules: `design.md`, `layout.md`, `product.md`.
- `demo/` and `src/demo`: the React demo workspace (overview, records with search and filters, a review queue with approve and decline, an audit log kept in localStorage).
- `privacy.html`, `terms.html`, `docs/architecture.md`, `vercel.json`.

```bash
npm install
npm run dev
npm run build
npm test
```

The demo runs on fixed data in the browser; no AI service is called.
