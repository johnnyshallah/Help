# PayPal Payment Integration

This userbot now supports processing payments and donations via PayPal. To enable this functionality, you need to configure the following environment variables:

*   **`PAYPAL_CLIENT_ID`**: Your PayPal Client ID.
*   **`PAYPAL_CLIENT_SECRET`**: Your PayPal Client Secret. This is sensitive information and should be kept secure.
*   **`PAYPAL_MODE`**: The mode for PayPal transactions. This can be set to `sandbox` for testing purposes or `live` for actual transactions.

You can obtain your `PAYPAL_CLIENT_ID` and `PAYPAL_CLIENT_SECRET` from your PayPal Developer account dashboard.

The specific Telegram commands for initiating payments or donations (e.g., `/pay` or `/donate`) will be detailed in the userbot's own documentation or help commands. This repository primarily focuses on the deployment and setup of the bot. Ensure your userbot's code is updated to utilize these PayPal environment variables for the payment features.
