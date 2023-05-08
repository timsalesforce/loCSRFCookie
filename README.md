# W-13146437 - Signature - Case# 44506381 - Robert Half International - "Bad Message 431 - reason: Request Header Fields too Large " on Visualforce Page

## Repro

1. Clone this repo and deploy to an org
2. Login and make sure you are in the "Lightning Console" app
3. Create a few Accounts
4. Check the Cookie header for the vf domain

You should see multiple ERIC_PROD CSRF cookies with different tokens in the names.

