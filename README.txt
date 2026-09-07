DOOR DNA AI V40 — CLOUDFLARE WORKERS AI

This build removes the OpenAI image-generation dependency and uses Cloudflare Workers AI.
Image model: @cf/black-forest-labs/flux-2-klein-9b

Cloudflare setup:
1) Import this repository/project as the existing Worker.
2) Deploy using wrangler.jsonc.
3) The AI binding is declared as binding name AI.
4) No OPENAI_API_KEY is required for image generation.

The frontend remains the V39 Luxury Royal Black + Gold experience.
Supplier names, prices, contracts and payments in the prototype remain DEMO until real integrations are added.
