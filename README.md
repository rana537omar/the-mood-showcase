<p align="center"><img src="media/banner.png" alt="The Mood: event ticketing with discovery, checkout, QR e-tickets, an organizer console and door check-in" width="100%"></p>

# The Mood

**A complete event ticketing platform for concerts, comedy, conferences and nights out.** Buyers find an event, pay by card and get QR e-tickets on their phone in under a minute. Organizers run everything from one console: events and ticket types, sales and refunds, promo codes, a box office for door and phone sales, and a door check-in screen that works on any phone or laptop.

> **This is a product showcase.** The Mood software and its source code are proprietary and are **not** included in this repository. See [License](#license).

**Showcase website:** https://rana537omar.github.io/the-mood-showcase/

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20The%20Mood%20ticketing%20app%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## Demo video

<p align="center"><a href="https://rana537omar.github.io/the-mood-showcase/#demo"><img src="media/video-poster.png" alt="Watch the 2-minute The Mood demo" width="100%"></a></p>

A walkthrough of just under 2 minutes, in 1080p. It shows a buyer finding an event, applying a promo code, paying and getting QR e-tickets. Then it moves to the organizer console: the dashboard, events and attendees, a box-office sale, the door check-in scan (and a caught second scan), promo codes and the payment settings. **[Watch it on the showcase website](https://rana537omar.github.io/the-mood-showcase/#demo)**.

## Features

### For buyers
- **Event discovery**: search plus category, date and city filters, featured events, and "selling fast" / "sold out" badges.
- **Event pages with a live price quote**: ticket types, per-order limits, promo codes, the service fee and the total, all updated as you choose.
- **Fair checkout**: tickets are **held** for 10 minutes (configurable) while the buyer pays, so two people can never buy the last seat.
- **Real card payments** through **Stripe** or **Paymob** (cards, Apple Pay / Google Pay, mobile wallets and local methods in Egypt, the UAE, Saudi Arabia and Oman).
- **QR e-tickets**: one per attendee, with a name on each ticket (editable until check-in). Buyers can print them, save them as PDF or add the event to their calendar.
- **"Find my tickets"** by email and order number, and a waitlist when an event sells out.

### For organizers
- **Dashboard**: ticket sales, tickets sold, orders, check-in rate and fees compared with the previous period. It also has a daily sales chart, the split between sales channels, top events, upcoming events and the latest orders.
- **Events**: draft → publish, edit, duplicate, cancel (refunds every order and prepares an email to each buyer). You can set a cover photo or colour theme, mark events as featured and cap venue capacity across ticket types.
- **Ticket types**: price, quantity, min / max per order, sales windows, and hidden types for guest lists and crew.
- **Orders**: search and filters, and a full history for each order. Refunds void the tickets and put the seats back on sale. You can also resend tickets and edit buyer details.
- **Box office**: sell at the door or by phone (cash, card or transfer) or issue complimentary tickets, and print them on the spot.
- **Attendees**: search, manual check-in and undo, rename, CSV export.
- **Promo codes**: percent or fixed amount, for one event or all events, with usage caps and validity dates.
- **Outbox** with every confirmation, refund, cancellation and waitlist email, ready to connect to your mail provider. Team roles (Admin, Organizer, Door staff) and settings: brand, currency, time zone, service fee, hold time.

### At the door
- Works with USB / Bluetooth barcode scanners, typed codes, and the phone camera where the browser has a built-in QR reader.
- A big **green / amber / red** result: admitted, or already checked in (when and by whom). Wrong-event, refunded, unpaid and unknown tickets also show clearly.
- Guest search by name, email or order number, per-ticket-type progress, and counts that refresh every few seconds across every door.
- Each ticket is admitted **once**, even if two doors scan it at the same moment.

### Built to run
- One small server with its own database: the only outside services are your payment provider and, when you connect one, your email sender.
- Encrypted payment keys, signed payment webhooks with automatic refunds, protected sign-in, and security headers.
- Brand-ready: logo, colours, black e-tickets and a built-in library of cover photos.

## Screenshots

| | |
|---|---|
| ![Home page](media/home.png) **Home**: search and featured events. | ![Upcoming events](media/events.png) **Upcoming events** with category and date filters. |
| ![Event page](media/event.png) **Event page**: ticket types and a live quote with a promo code applied. | ![Checkout](media/checkout.png) **Checkout**: tickets held while the buyer pays. |
| ![Order confirmation](media/confirmation.png) **Confirmation**: the order and its e-tickets, straight after payment. | ![E-tickets](media/tickets.png) **E-tickets**: one QR code per attendee. |
| ![Organizer dashboard](media/dashboard.png) **Dashboard**: sales, tickets, check-ins and the daily sales chart. | ![Events in the console](media/events-console.png) **Events**: sales, capacity and status for every event. |
| ![Event overview](media/event-overview.png) **Event overview**: sales and check-ins for one event. | ![Ticket types](media/ticket-types.png) **Ticket types**: prices, quantities, limits and sales windows. |
| ![Attendees](media/attendees.png) **Attendees**: search, check in by hand, export. | ![Box office](media/box-office.png) **Box office**: door and phone sales, or comps. |
| ![Orders](media/orders.png) **Orders**: search and filter every order. | ![Order detail](media/order-detail.png) **Order detail**: tickets, payment, buyer, history and emails. |
| ![Door check-in](media/checkin.png) **Door check-in**: green means let them in. | ![Promo codes](media/promo-codes.png) **Promo codes** with limits, dates and per-event rules. |
| ![Payment settings](media/payments.png) **Payments**: Stripe, Paymob or test mode. | ![Event editor](media/event-form.png) **Event editor** with the cover photo library. |

<p align="center"><img src="media/phones.png" alt="The event page, a QR e-ticket and the door check-in screen on phones" width="80%"></p>

All names, events, orders and figures in these screenshots and the video are fictional demo data.

## Get the full system

Want The Mood for your venue or events company, a live demo, or the complete source code? Message me on WhatsApp: **+20 120 856 2225**.

<p align="center"><a href="https://wa.me/201208562225?text=Hello%2C%20I%20saw%20The%20Mood%20ticketing%20app%20and%20I%20would%20like%20to%20get%20the%20full%20system%20and%20the%20source%20code."><img src="media/whatsapp-button.svg" alt="Get the full system and source code: chat on WhatsApp, +20 120 856 2225" width="380"></a></p>

## License

**Copyright © 2026 Rana Omar. All rights reserved.** The text, screenshots, images and video in this repository are shared for viewing only. No license is granted to copy, reuse, modify, republish or use them, or The Mood software they show, for any personal or commercial purpose. See [LICENSE](LICENSE).
