# Shop Phi

Shop Phi is the commerce layer for the Infinity network: a product discovery, comparison and storefront system that can turn a search or collected Quant into useful shopping paths without making commerce the identity of the user.

## Purpose

Shop Phi connects products, sellers, brands, specifications, media, availability and price observations to the same topic-first architecture used elsewhere in the network. A search can begin as research and become shoppable when appropriate, while keeping the original subject and its related Quants intact.

## Core model

- **Product cards** — title, image, description, seller/source, current observed price and canonical destination.
- **Shop Quants** — product and commerce relationships can attach to a Quant without replacing the original research object.
- **Comparisons** — equivalent products can be grouped by meaningful attributes rather than advertising position alone.
- **Collections** — a user can deliberately collect products or subjects and later use those choices as seeds.
- **Portable plugin** — other Infinity sites should be able to request Shop Phi results instead of rebuilding commerce logic.
- **Source transparency** — price, availability and seller claims should retain their source and observation time.

## Planned flow

`search / collected Quant -> related products -> product cards -> compare -> seller -> optional collect/share`

Shop Phi should distinguish editorial/research results from paid placements. Sponsored inventory must be labeled, and payment must not silently rewrite the underlying Quant relationships.

## Integration

Shop Phi is intended to interoperate with Quants for topic relationships, the unified wallet/ledger for permitted reward accounting, News Phi for commerce-related current stories, and Monitor Phi for runtime/deployment services.

## Status

Architecture repository. Features described as planned are targets until corresponding implementation is present and tested.
