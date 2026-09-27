# Platform Architecture

## Experience layers
1. Marketing: editorial landing page, manifesto, capabilities, showcase, services and coming soon.
2. Commerce: product pages, previews, pricing, licenses, wishlist, cart and checkout.
3. Customer workspace: projects, saved designs, blueprint, requests, orders, messages and account settings.
4. Creation layer: visual configuration and reference/design request intake.
5. Operations: admin catalog, quotes, customers, orders, deployments, analytics and lifecycle automations.
6. Private production: proprietary component library, build pipeline and deployment infrastructure.

## Routes
/, /showcase, /websites, /web-apps, /saas, /applications, /services, /coming-soon, /product/[slug], /custom, /request-design, /contact, /account/*, /checkout, /admin/*, /privacy, /terms, /licenses, /refund-policy.

## Design language
Premium, restrained, editorial, high-contrast, spacious and motion-led. Avoid generic SaaS gradients. Product imagery and live previews are the visual focus. Motion should be purposeful: reveal, transition, hover, preview and state feedback.

## Protected boundary
Public marketplace code may know product metadata and approved configuration schemas. It must not contain private source components, secrets, private storage credentials, build scripts or production-only asset URLs.
