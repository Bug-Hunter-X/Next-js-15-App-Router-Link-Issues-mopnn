# Next.js 15 App Router Link Issue

This repository demonstrates a common issue encountered when migrating or working with Next.js 15's App Router and `next/link` component.  The issue is related to the App Router's different approach to routing compared to the Pages Router.

## Issue Description

The primary issue occurs when using `next/link` within pages managed by the App Router.  Standard usage may result in unexpected behavior, broken links, or incorrect client-side navigation. The root cause often relates to how routes are defined and handled by the new App Router architecture.