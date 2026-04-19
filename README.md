# Deploy to Cloudflare Pages
bun run build
bunx wrangler pages deploy dist --project-name astropage


# Deploy to Cloudflare Workers
bun run build
bunx wrangler deploy --project-name astropage