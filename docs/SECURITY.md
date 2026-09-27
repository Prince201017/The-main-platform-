# Security and Source Protection

- Keep production repositories private.
- Never commit secrets, service-role keys, payment secrets or private asset credentials.
- Use server-side authorization for protected operations.
- Apply Supabase RLS to customer-owned records.
- Separate public product metadata from private implementation details.
- Generate short-lived signed URLs for protected downloads where needed.
- Deliver finished websites through a private build/deployment pipeline rather than exposing the component repository.
- Log administrative actions.
- Provide account deletion/export and consent controls appropriate to the data collected.

Important: frontend HTML/CSS/JS delivered to a browser cannot be made completely invisible. Source protection focuses on proprietary repositories, private build infrastructure, server-side logic and non-public assets.
