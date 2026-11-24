# Laravel Dating Script

Dating Pro is a modern online dating platform built with PHP 8.3, Laravel 13, Livewire 4 and Tailwind CSS 4, sold with full source code by Coderobotics. Members register, complete an onboarding wizard, upload photos and find people through a swipe deck with pass, like, super like, rewind and boost, plus filtered search, a nearby map, profile visitors and favorites. A mutual like creates a match, and messaging unlocks only after a match. Chat runs in real time with typing indicators, online status and read receipts, using Laravel Reverb by default or Pusher, Ably or polling. Owners earn revenue from premium plans and credit packs paid through Stripe, PayPal or Razorpay. Members spend credits on super likes, boosts and gifts. A custom admin panel covers members, photo moderation, reports, payments, plans, gifts, CMS pages and site settings. Dating Pro also includes a versioned JWT REST API for mobile apps, an installable PWA with web push notifications, privacy controls such as incognito mode and hidden distance, and OpenStreetMap, Google Maps or Mapbox support. It suits entrepreneurs, agencies and developers launching their own dating or matchmaking service.

<img src="https://www.coderobotics.com/frontend/assets/icon/laravel_dating_php_script.jpg">

Dating Pro is a modern dating platform built with Laravel 13 and Livewire 4. Members sign up, build a profile, and swipe, search or browse a nearby map to find people. A mutual like creates a match and unlocks realtime chat. Premium plans and credit packs earn you revenue, and a custom admin panel, a JWT REST API for mobile apps and an installable PWA come built in.

Dating Pro – Online Dating Website, Swipe & Match App with Realtime Chat
Building a dating platform means solving many hard problems at once: swipe discovery, matching, live chat, photo moderation, location search, payments and a backend for mobile apps. Dating Pro handles all of them in one Laravel codebase. Members swipe, match and chat in real time, and they can message only after a mutual like, so they only receive messages from people they matched with. Premium plans and credit packs paid through Stripe, PayPal or Razorpay let you earn from day one. Because you get the full source code, you can launch your own branded dating site or app. 

What You Get
 
Accounts & Onboarding – Registration, login, password reset, an onboarding wizard and a full profile editor.
Photos & Moderation – Up to 9 photos per member, with optional admin approval before photos go live.
Privacy & Safety – Incognito mode, hide distance, and block and report tools.
Swipe Deck – Pass, like, super like, rewind and boost from one swipe screen.
Search, Nearby & Visitors – Search with filters, a nearby-members map, profile visitors and favorites.
Matching – A mutual like creates a match; messaging unlocks only after a match.
Realtime Chat – Live messaging with typing indicators, online status and read receipts.
Premium Plans & Credits – Premium plans and credit packs through Stripe, PayPal or Razorpay. Credits pay for super likes, boosts and gifts.
Free-Tier Limits – Set daily likes (25) and super likes (1) for free members, and the credit cost of super likes (5) and 30-minute boosts (25).
Notifications – In-app, realtime and browser push notifications.
Admin Panel – Dashboard, members, photo moderation, reports, payments, plans, credit packs, gifts, interests, CMS pages and site settings.
REST API for Mobile Apps – A versioned /api/v1 API with JWT authentication and rotating refresh tokens. It covers auth, profile, photos, discovery, reactions, matches, chat, billing, notifications and push.
Installable PWA – Installable app, offline page and web push using VAPID keys.
Maps – OpenStreetMap by default, with Google Maps or Mapbox selectable in admin.
Switchable Realtime – Laravel Reverb by default, with Pusher, Ably or polling selectable in admin.
Reliable Payments – Webhooks for every gateway. A payment is credited only once, even when both the redirect and the webhook confirm it.

Why This Platform?

Most dating software is a closed, hosted service with monthly fees. With Dating Pro you get the complete source code, so you own the product, the members and the revenue.

One codebase for the website, the PWA and a mobile app backend
Messaging only after a mutual match, so members don't get unwanted messages
Payment gateways, map provider and realtime driver switchable from admin
Most settings managed in the admin panel, with secrets stored encrypted
Premium time and credits built in from day one
Includes feature and API tests

Perfect For
 
Entrepreneurs launching their own dating or matchmaking business
Niche dating communities (local, religious, interest-based, age-based)
Agencies building dating sites or apps for clients
Mobile developers who need a ready-made backend and API for a dating app
Startups that want a working dating MVP fast
Developers who want a modern Laravel + Livewire codebase to extend

Tech Stack
 
PHP 8.3
Laravel 13
Livewire 4
Alpine.js
Tailwind CSS 4
Vite
MySQL 8 / MariaDB 10.4+
Laravel Reverb (Pusher / Ably / polling optional)
Stripe, PayPal, Razorpay
JWT (firebase/php-jwt)
Web Push (minishlink/web-push)
OpenStreetMap / Google Maps / Mapbox

Prerequisites
 
PHP 8.3 with extensions: pdo_mysql, gd, openssl, mbstring, bcmath, curl
Composer 2
Node.js 20+ and npm
MySQL 8 or MariaDB 10.4+
A cron job running every minute (php artisan schedule:run)
HTTPS on a public domain (required for PWA install and push notifications)
Supervisor to keep Laravel Reverb running, or a Pusher / Ably account

Frequently Asked Questions - Dating Pro
 
What is Dating Pro?
Dating Pro is a complete online dating platform built with Laravel 13 and Livewire 4. Members create profiles, swipe and search to find people, match with a mutual like, and chat in real time. It includes premium plans, credits, a custom admin panel, a REST API for mobile apps and an installable PWA.
How does matching work?
When two members like each other, a match is created. Messaging unlocks only after a match, so members only receive messages from people they matched with.
What discovery features are included?
A swipe deck with pass, like, super like, rewind and boost; search with filters; a map of nearby members; profile visitors; and favorites.
What does the realtime chat include?
Live messaging with typing indicators, online status and read receipts. Laravel Reverb is the default. You can switch to Pusher, Ably or polling, which needs no extra server, in Admin ? Settings ? Realtime.
How do I earn money with Dating Pro?
Sell premium plans and credit packs through Stripe, PayPal or Razorpay. Members spend credits on super likes, boosts and gifts. Free members get daily limits on likes and super likes, which you can change in admin.
Do premium plans renew automatically?
No. Premium plans are one-time payments that add premium time to a member's account. A daily task expires memberships when their time ends.
Can a payment be credited twice?
No. Fulfilment is idempotent, so a payment confirmed by both the return redirect and the gateway webhook is credited only once.
What privacy and safety tools do members get?
Incognito mode, the option to hide their distance, and tools to block and report other members. Admins can moderate photos and review reports from the admin panel.
What can I manage in the admin panel?
The /admin panel includes a dashboard, members, photo moderation, reports, payments, plans, credit packs, gifts, interests, CMS pages and site settings. Most settings are stored in the database, and secrets are stored encrypted.
Can I build a mobile app on top of Dating Pro?
Yes. It includes a versioned REST API at /api/v1 with JWT authentication and rotating refresh tokens. It covers registration and login, profile, photos, discovery, reactions, matches, chat, billing, notifications and push.
Does it work as a mobile app without the app stores?
Yes. Dating Pro is an installable PWA with an offline page and browser push notifications. Installing it and receiving push notifications both require HTTPS.
Which map providers are supported?
OpenStreetMap by default, with no API key needed. You can switch to Google Maps or Mapbox in admin.
What are the server requirements?
PHP 8.3 with the pdo_mysql, gd, openssl, mbstring, bcmath and curl extensions; Composer 2; Node.js 20+ and npm; MySQL 8 or MariaDB 10.4+; and a cron job that runs every minute. A live site also needs HTTPS and either Supervisor to keep Reverb running or a Pusher/Ably account.
Is there demo data to explore the features?
Yes. Outside production, the database seeder creates demo members plus an admin account and a member account, so you can try every feature right away. Delete the demo data before going live.
Is the source code encrypted?
No. You get the complete source code with no encryption and no domain limitations.
How soon will I receive the source code after payment?
On working days (Monday–Friday), we send the download link within 2–4 hours. On weekends (Saturday–Sunday), delivery takes 4–8 hours.
Do you provide installation and support?
You get unlimited email support and free updates for one year. Installation is not free; it costs $5 to $10, depending on the software's complexity.
Can I use Dating Pro for multiple clients or resell it?
A regular license allows use in a single project, for personal or commercial purposes, by you or for a client. You may not resell the item or distribute its source files.

More details & download link:
https://www.coderobotics.com/product/laravel-dating-script
