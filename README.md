# Kaching Subscriptions Integrations

### Klaviyo Templates

Located in `Klaviyo/templates/`, this collection includes responsive HTML email templates for common subscription lifecycle events:

#### Billing Events

- **`billing_attempt_success.html`** - Sent when a billing attempt succeeds
- **`billing_attempt_failure.html`** - Sent when a billing attempt fails

#### Subscription Management

- **`subscription_contract_create.html`** - Triggered when a new subscription is created
- **`subscription_contract_activate.html`** - Sent when a subscription is activated
- **`subscription_contract_pause.html`** - Triggered when a subscription is paused
- **`subscription_contract_cancel.html`** - Sent when a subscription is cancelled

#### Order Management

- **`order_skipped.html`** - Triggered when a subscription order is skipped
- **`order_unskipped.html`** - Sent when a skipped order is unskipped

## Template Features

All templates include:

- **Responsive Design** - Optimized for mobile and desktop viewing
- **Cross-Client Compatibility** - Tested with major email clients including Outlook, Gmail, Apple Mail
- **Retina-Ready** - High-resolution display support
- **Conditional Comments** - Special handling for Microsoft Office email clients
- **Clean HTML Structure** - Semantic markup with inline styles for maximum compatibility

## Usage

### With Klaviyo

1. Navigate to your Klaviyo account
2. Go to **Email Templates** section
3. Create a new template or edit an existing one
4. Copy the HTML content from the desired template file
5. Paste into Klaviyo's HTML editor
6. Customize the template variables and branding as needed
7. Test the template with sample data
8. Assign the template to the appropriate flow or campaign

### Customization

These templates use standard email HTML patterns and can be customized by:

- Modifying inline styles for colors, fonts, and spacing
- Updating placeholder text and variable names
- Adding or removing content sections
- Adjusting responsive breakpoints in the media queries

## Template Structure

Each template follows a consistent structure:

```
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta tags for email client compatibility -->
    <!-- Inline and embedded CSS styles -->
  </head>
  <body>
    <!-- Email content with tables for layout -->
  </body>
</html>
```

## Best Practices

- Always test templates across multiple email clients before deployment
- Use Klaviyo's preview and testing features to verify variable substitution
- Keep email file sizes reasonable for faster loading
- Ensure all links include proper tracking parameters
- Test on both mobile and desktop devices
