# Consentio Consent Mode - Google Tag Manager Template

Official Google Tag Manager template for [Consentio](https://consentio.it) - GDPR compliant consent management platform.

## Features

- **Google Consent Mode v2** - Full support for the latest Consent Mode API
- **GDPR Compliant** - All consent types denied by default
- **Multi-language** - Italian, English, German, French, Spanish
- **Advanced Options** - URL Passthrough and Ads Data Redaction support

## Installation

### From Community Template Gallery (Recommended)

1. In Google Tag Manager, go to **Templates** > **Search Gallery**
2. Search for "Consentio Consent Mode"
3. Click **Add to workspace**

### Manual Import

1. Download `template.tpl` from this repository
2. In GTM, go to **Templates** > **New**
3. Click the three dots menu > **Import**
4. Select the downloaded file

## Configuration

1. Create a new **Tag** using the Consentio Consent Mode template
2. Enter your **Script Key** (available at [consentio.it](https://consentio.it))
3. Set the trigger to **Consent Initialization - All Pages**
4. Publish your container

## Parameters

| Parameter | Description | Default |
|-----------|-------------|---------|
| Script Key | Your Consentio domain key | Required |
| Language | Banner language (auto, it, en, de, fr, es) | auto |
| Analytics Storage | Default consent for analytics | denied |
| Ad Storage | Default consent for advertising | denied |
| Ad User Data | Default consent for ad user data | denied |
| Ad Personalization | Default consent for ad personalization | denied |
| Wait for Update | Milliseconds to wait for consent update | 500 |
| URL Passthrough | Pass URL parameters when ad_storage is denied | false |
| Ads Data Redaction | Redact ads data when ad_storage is denied | false |

## Support

- Documentation: [https://consentio.it/docs/gtm](https://consentio.it/docs/gtm)
- Issues: Use the GitHub Issues tab
- Email: support@consentio.it

## License

Apache License 2.0 - See [LICENSE](LICENSE) file for details.

---

Made with care by [Consentio](https://consentio.it)
