# Gaming Arena — Modern Mobile Prototype

Updated prototype includes:

- Login / Register / Forgot Password OTP flow
- Home shows Free Fire only, then opens contest modes
- BR Solo, BR Duo, BR Squad, CS 1v1, CS 2v2, CS 3v3, CS Squad, Lone Wolf 1v1, Lone Wolf 2v2
- Live / Upcoming / Results per mode
- Tournament details, entry fee, per-kill prize, winning prize, slots, UID, slot selection and wallet check
- My Contests
- Wallet, deposit verification, withdrawal verification
- Notifications with tournament, join, wallet, withdrawal, slot and 10-minute reminder events
- Customer support
- Private Contest Chat for every joined match/tournament
- User can message the admin inside the specific contest thread
- Admin can open every contest thread, reply, send room ID/password, reminders and match instructions
- Admin dashboard for tournaments, users/joins, wallet requests, support, notifications and contest chats

Demo user:
- Email: user@example.com
- Password: 123456

Demo admin:
- Email: admin@gamingarena.local
- Password: admin123

This is a browser/PWA prototype using localStorage. Real authentication, server-side authorization, realtime chat, email OTP, and payment/withdrawal integrations require a backend and payment provider before production deployment.


## New Chart / Bracket panel
The user sees a Chart button for each joined contest. Each contest has Overview, Chart/Bracket, and Leaderboard views. The admin has a Charts / Brackets panel to update first-round matchups, scores, and match statuses; updates are saved and surfaced to users. The existing per-contest chat remains available alongside the new chart.
