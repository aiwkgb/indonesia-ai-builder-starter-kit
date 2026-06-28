# Example Blueprint — Simple Order Follow-up App

This is a fictional example. It does not use real business data.

## Project level

L2 — MVP / Micro Product

## Product summary

A simple web app for a small service business to track customers, orders, and manual follow-up status.

## Target user

Non-technical business owner or admin who currently tracks orders in chat, notebook, or spreadsheet.

## Problem

The owner forgets which customers need follow-up, which orders are done, and which orders are still waiting.

## MVP scope

Must-have:

- Add customer
- Add order
- Set order status
- Add follow-up note
- See dashboard summary

## Out of scope

Do not build yet:

- WhatsApp API automation
- Payment gateway
- Mobile native app
- Multi-branch support
- Advanced analytics

## User flow

1. Admin opens dashboard.
2. Admin adds a customer.
3. Admin creates an order.
4. Admin updates status: new, in progress, done, follow-up needed.
5. Admin checks the follow-up list.

## Screen map

- Dashboard
- Customer list
- Customer detail
- Add/edit order
- Follow-up board
- Settings

## Data model

| Entity | Fields |
| --- | --- |
| Customer | id, name, phone_placeholder, notes |
| Order | id, customer_id, title, status, due_date, notes |
| FollowUp | id, order_id, note, next_action_date |

## Suggested stack

- Beginner prototype: Lovable or Bolt
- Code refinement: Cursor or Codex
- Backend: Supabase only if login/database is needed
- Deploy: Vercel

## Build phases

1. Static dashboard UI
2. Local data or simple mock data
3. Customer/order CRUD
4. Follow-up board
5. Empty states and validation
6. Deploy demo with fake data

## AI prompt starter

```text
Build a simple order follow-up dashboard for a fictional service business.
Use fake demo data only.
Include customer list, order list, status tags, and follow-up board.
Do not add payment, WhatsApp API, or authentication yet.
Explain how to run and verify the app.
```

## Resume point

Last done: blueprint created.  
Next action: build static dashboard UI with fake data.  
Do not do yet: WhatsApp API, payment, real customer data.
