# Airya — App Store launch checklist

## App Store Connect
- [ ] Enroll in Apple Developer Program and accept latest agreements
- [ ] Create App ID in Apple Developer account, matching Xcode bundle ID
- [ ] Create new iOS app record at https://appstoreconnect.apple.com/
- [ ] Enter name, subtitle, promotional text, description, keywords and categories
- [ ] Add live Support URL and Privacy Policy URL (the enclosed HTML templates are NOT published)
- [ ] Add copyright owner and contact/review information
- [ ] Complete age rating and App Privacy questionnaires truthfully
- [ ] Complete content rights, encryption/export and other compliance questions
- [ ] Set pricing and availability; select appropriate geographic launch region
- [ ] Compile/test release build and upload through Xcode Organizer
- [ ] Attach uploaded build to version
- [ ] Capture actual app screenshots on iPhone; do not use concept mockups as if they were real screens
- [ ] Provide reviewer test accounts for resident and contractor

## App functionality / safety — MUST VERIFY BEFORE REVIEW
- [ ] In-app account deletion flow with backend user/content cleanup
- [ ] Report inappropriate posts/profiles/messages and block abusive users
- [ ] Moderation/response mechanism, content filtering, visible contact/support
- [ ] Privacy policy linked in-app, accurate disclosures and secure storage
- [ ] Confirm Supabase row-level access policies isolate private messages
- [ ] Verify email confirmation returns to installed app
- [ ] Confirm registration, homeowner/contractor onboarding, job photos, messages, comments and feed work with two real devices/accounts
- [ ] Disable/remove any unverifiable “verified”, “licensed”, “insured”, rating or background-check claim
- [ ] Final license/insurance disclaimer and community guidelines
- [ ] Check app build/device and support requirement for iPad (or disable if not supported)
- [ ] Test offline/error states and account sign-out

Apple sources:
- https://developer.apple.com/app-store/review/guidelines/
- https://developer.apple.com/support/offering-account-deletion-in-your-app/
- https://developer.apple.com/help/app-store-connect/reference/app-information/screenshot-specifications/
