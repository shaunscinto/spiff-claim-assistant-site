# Pip Website

Static public website for Stripe account activation and customer-facing product information.

Pages:

- `index.html` - product and pricing page
- `download.html` - installer access page
- `support.html` - support contact
- `refund.html` - refund and cancellation policy
- `privacy.html` - privacy policy
- `terms.html` - terms of service

Before publishing:

- Replace `support@charliesystems.net` if another support mailbox should be used.
- Checkout buttons point to the hosted license server buy page:
  `https://spiff-license-prod.jollydesert-2af4bbca.westus2.azurecontainerapps.io/buy`
- Replace the download page copy or link when the production installer is ready.

Custom domain:

- `CNAME` is set to `charliesystems.net` for GitHub Pages-style hosting.
- Set up `support@charliesystems.net` email forwarding or a real mailbox before using it in Stripe.
