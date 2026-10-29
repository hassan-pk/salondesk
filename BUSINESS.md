# SalonDesk business workflow

SalonDesk is an offline pilot for salons and barber shops using one computer. Configure the business and owner first. Each installation has its own records and backups.

## Modules

- **Clients:** names, contacts, addresses and preferences/notes.
- **Staff:** contacts, specialities and informational usual commission percentages.
- **Services:** categories, standard prices and typical durations.
- **Appointments:** client, staff member, main service, start/end times and booking status.
- **Service bills:** client, staff, optional appointment reference, dated service lines, amount collected and per-bill commission estimate.
- **Expenses:** operating costs recorded separately from client bills.

## First working day

1. Enter staff, services and clients.
2. Create appointments with an explicit start and end time. The app checks overlapping active appointments for the same staff member; choose a different time or staff member when occupied.
3. Follow Booked, Confirmed, In service and Completed statuses. Cancel unused bookings. Completion/cancellation releases the appointment resource.
4. Create a Service bill for an appointment or walk-in, choosing all services actually provided and their quantities. Link its appointment manually when appropriate.
5. Enter the amount collected and the commission percent agreed for that bill. Service lines calculate the total; commission is calculated from the full bill and entered percent. Collect later payments through the payment action rather than editing the paid amount.
6. Print the bill, record expenses and export a backup.

## Appointments and commissions

Appointment start/end must be entered explicitly. The service duration is a catalog aid; it does not auto-fill calendar slots. Staff availability covers overlapping appointments, not opening hours, leave, rooms, equipment or chairs. Completing an appointment does not automatically create its bill. Linking an appointment is a reference, not validation that every chosen service/staff field matches that booking.

Commission is an estimate on the bill total, not net profit, a payroll transfer or a proportion of actual cash collected. The staff's usual percent is informational: enter the intended percent on each bill. Review this estimate before paying staff and record actual payouts in the expense module; avoid recording the same payout twice. Finalize bill details before marking it Completed, since terminal records cannot be edited. Unpaid completed bills remain collectible.

## Current limits

No SMS reminders, memberships, prepaid package balances, product consumable inventory, salary/payroll engine, refunds or tax accounting. No automatic appointment-to-bill conversion or client-facing online booking. One local owner account and one computer; no staff-device synchronization. Keep independent backups.

This document describes the configured pilot, not unperformed production or hardware verification. Refer to repository verification notes for executed checks.
