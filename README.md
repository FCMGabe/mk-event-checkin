# Event QR Check-In

Org: All (FC / CoK / MK). Public check-in page for Jotform event registrations.

- `?form=<form ID>` – guest check-in page for that event
- `?form=<form ID>&sign=1` – printable QR sign for that event
- no parameters – staff tool: paste a form link, get its sign

A form takes part only if it has hidden fields labeled "Checked In" and "Check-In Time".
The page calls a Google Apps Script that marks the matching Jotform registration as checked in.
No data or keys are stored here.
