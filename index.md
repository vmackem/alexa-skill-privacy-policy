# Privacy Policy for Sunderland Bin Day Alexa Skill

**Last Updated:** February 25, 2026

## Introduction

This privacy policy explains how the Sunderland Bin Day Alexa skill ("the Skill") collects, uses, and protects your information.

## Information We Collect

The Skill collects only the following information necessary to provide bin collection services:

- **Postcode**: Either automatically detected from your Alexa device address settings (with your permission) or manually provided by you through voice commands
- **Reminder Preferences**: Whether you have enabled or disabled bin day reminders
- **Last Reminder Refresh Date**: When reminders were last updated (to keep them current)

## How We Collect Information

- **Device Address**: If you grant permission, the Skill may access your device address to automatically detect your postcode
- **Voice Input**: You can manually provide your postcode by speaking it to the Skill
- **Preference Storage**: Your choices about reminders are saved for your convenience

## How We Use Your Information

We use your information solely to:
- Provide bin collection dates for your postcode
- Send you reminders about upcoming bin collections (if you enable this feature)
- Automatically update your postcode if you move house and update your device address

## Data Storage

- Your postcode and preferences are stored securely in Amazon DynamoDB
- Data is encrypted at rest using AWS KMS encryption
- No personally identifiable information (name, email, phone number, full address) is collected or stored
- Only your postcode is retained, which covers approximately 15 addresses and cannot uniquely identify you

## Data Sharing

We do **not** share, sell, or transfer your information to any third parties.

The Skill queries publicly available bin collection data from Sunderland City Council's website to provide you with collection dates.

## Data Retention

- Your postcode is stored indefinitely while you use the Skill
- Bin collection data is cached for 24 hours and automatically refreshed
- Reminders are automatically updated every 7 days

## Your Rights

You have the right to:
- **Access**: View what data we have stored by checking your reminder settings
- **Delete**: Remove all your data by disabling the Skill in your Alexa app
- **Update**: Change your postcode at any time by saying "my postcode is [new postcode]"
- **Revoke Permissions**: Remove device address access through the Alexa app settings

## Children's Privacy

This Skill is not directed at children under 13 years of age. We do not knowingly collect information from children.

## Data Security

We implement appropriate technical and organizational measures to protect your information:
- AWS DynamoDB with KMS encryption at rest
- Secure HTTPS connections for all API calls
- No storage of unnecessary personal information
- Regular security reviews and updates

## Changes to This Privacy Policy

We may update this privacy policy from time to time. The "Last Updated" date at the top of this page indicates when the policy was last revised.

## Geographic Scope

This Skill is designed for residents of Sunderland, UK, and uses Sunderland City Council's public bin collection data.

## Contact Information

If you have questions about this privacy policy or how we handle your data, please contact:

**Email**: dowen93to98@hotmail.com

## Compliance

This Skill complies with:
- UK Data Protection Act 2018
- General Data Protection Regulation (GDPR)
- Amazon Alexa Skills Kit Developer Agreement
- Amazon's Privacy Requirements for Skills

## Third-Party Services

The Skill uses the following third-party services:
- **Amazon Web Services (AWS)**: For hosting and data storage (Lambda, DynamoDB, API Gateway)
- **Amazon Alexa**: Voice interface platform

These services have their own privacy policies and terms of service.

## Your Consent

By enabling and using this Skill, you consent to the collection and use of information as described in this privacy policy.

---

**Effective Date**: February 25, 2026

This privacy policy is provided in compliance with Amazon Alexa Skills certification requirements.
