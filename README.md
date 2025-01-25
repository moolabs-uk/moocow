# MOOCOW

Minimal Object-Oriented Community-Owned Workscape is the first project I started working on with GPT in 2022. The laughable idea is an all-in-one Linux server to handle most day-to-day Small Business processes.

Leveraging existing free packages where possible, the areas explored:

- **Inventory** (Stock/Sale Item, Asset, Supplier, Order)
- **Project** (Process, Task, Event, Action)
- **Schedule** (Appointment, Recurrence, Resource Planning)
- **Manage** (Employee, Customer, Contractor, Provider, Invoice)
- **Sale** (Medusa Product/Service, Storefront, POS)
- **Comms** (Contacts, Chat, Mailcow Mail/Calendar, Pushover Pings)

Everything is stored and handled as objects in TypeScript (website frontend) and Mongoose (database backend). These are referenced in the real-world using QR Codes, allowing for flexible code changes during development.
