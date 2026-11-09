# Airya — preliminary App Privacy worksheet (not final answers)

Assess all actual data flowing through the native app, Supabase, hosting, logs and third-party services. Based on the current v4 source, **likely categories to disclose** include:

| Apple data type | Why | Likely purpose / linking |
|---|---|---|
| Contact Info → Name | Display name entered during onboarding | App Functionality; linked to identity |
| Contact Info → Email Address | Account authentication | App Functionality; linked |
| Identifiers → User ID | Supabase account identifier | App Functionality; linked |
| Location → Coarse Location | Self-reported city/service area, if treated as collection of location | App Functionality; linked; review Apple's classification |
| User Content → Other User Content | Job descriptions, comments and profiles | App Functionality; linked |
| User Content → Photos or Videos | Uploaded job photos | App Functionality; linked |
| User Content → Emails or Text Messages | In-app private message content (Apple includes non-SMS messaging) | App Functionality; linked |

Review whether IP addresses, diagnostics, device IDs, logs, product interaction, support requests or other data are received by Supabase or other processors. Confirm whether any data is used for tracking, advertising or analytics (do not guess). Confirm actual retention periods and deletion handling.

**Important:** Do NOT mark “Data Not Collected” without testing and auditing the full deployed stack. Do not claim end-to-end encryption of chat; Supabase server-side storage is not equivalent to E2E encryption.

Official Apple guide: https://developer.apple.com/app-store/app-privacy-details/
