---
name: admin-panel-kit
description: Build a login-gated admin panel with dashboard, products, orders, and settings for a store or brand site.
---

# Admin Panel Kit

Use this skill when the user wants an admin dashboard or internal management area.

## What to do
- check the stack and auth setup
- build a clear login flow if the app does not already have one
- include only the admin pages the user actually needs
- default to dashboard, products, and orders
- keep the UI functional and clean rather than decorative

## Required behavior
- show login errors clearly
- redirect to dashboard on success
- use tables for products and orders
- allow stock changes and status updates where relevant
- keep the admin area visually distinct but aligned with the brand

## Important
- do not pretend fake auth is real auth
- do not add extra admin pages unless the user asks for them
- prefer clarity and speed over visual flourish
