========================================================
  SIMMONS MORTGAGE — WEBSITE STARTER
  "Your mortgage BFF"
========================================================

This is the first draft of your website. It's a fast, mobile-friendly
static site (plain HTML/CSS — no logins, no monthly software), ready to
deploy on Netlify just like the CG Public House site.

--------------------------------------------------------
WHAT'S IN HERE
--------------------------------------------------------
  index.html ....... the whole website (one page, scrolls through
                     Hero → About → Loan Options → How It Works → Contact)
  privacy.html ..... a starter privacy policy (compliance should review)
  styles.css ....... all the styling (black & white brand)
  favicon.svg ...... the little "S" browser-tab icon
  README-FOR-STEF.txt ... this file

--------------------------------------------------------
WHAT I STILL NEED FROM YOU  (the site works without these,
but it'll look and read much better once we add them)
--------------------------------------------------------
1. LOGO — the actual file didn't come through in the message.
   Send the PNG/SVG and I'll swap the text "Simmons" logo for it.

2. HEADSHOT — DONE. Pulled Stef's professional headshot (stef.jpg) from
   the Sam's Saloon site; it's now in the hero. If you have a higher-res
   version than 500x500, send it and I'll swap it for extra sharpness.

3. COMPLIANCE / DISCLOSURES — DONE. Barrett Financial has greenlit the
   site.
   - Legal Disclaimer page (legal.html): Barrett's published language.
   - Privacy Policy page (privacy.html): Barrett's published language.
   - Footer carries NMLS #1607894 (Stef) and #181106 (Barrett),
     licensed states, Equal Housing Opportunity, and NMLS Consumer
     Access link.
   (If Barrett ever supplies an official Equal Housing Opportunity logo
   image to use instead of the current mark, send it and I'll swap it.)

4. LOAN PRODUCTS — I listed the common ones (Conventional, FHA, VA,
   USDA, Jumbo, Refinance). Confirm which you actually want featured.

5. GOOGLE REVIEWS LINK — you asked how to send it: open your Google
   Business Profile, hit "Get more reviews" / "Share review form," and
   copy that link. Send it and I'll add a reviews section + a
   "Leave a review" button.

6. OPTIONAL EXTRAS you left blank (all optional): office hours,
   FAQs, testimonials, "areas served," and realtor/title partners.

DOMAIN: www.callmyfriendstef.com (confirmed). It's set as the site's
canonical URL and is in the sitemap. When you deploy on Netlify, add
this as the custom domain (Netlify → Domain settings) and it'll issue
the free HTTPS certificate automatically.

--------------------------------------------------------
THINGS ALREADY WIRED UP FROM YOUR ANSWERS
--------------------------------------------------------
  • Phone:   (503) 481-7866  (click-to-call + text)
  • Email:   simmons@barrettfinancial.com
  • Office:  6 N Everett Street, Kennewick, WA 99336
  • Apply:   your my1003app.com application link (all "Apply" buttons)
  • Book:    calendly.com/steftalks (all "Book a Call" buttons)
  • Tagline: "Your mortgage BFF."
  • Bio:     your paragraph, used on the About section
  • NMLS:    #1607894 (you) and #181106 (Barrett) in the footer
  • States:  OR, WA, ID, AZ, TX, WY shown throughout

--------------------------------------------------------
HOW THE CONTACT FORM WORKS  (get messages to your email)
--------------------------------------------------------
The contact form uses Netlify Forms (same as the restaurant site).
After submitting, visitors see a friendly "Thanks!" page (thanks.html).

To make messages land in your inbox:
  1. Deploy the site on Netlify (connect this GitHub repo).
  2. Netlify auto-detects the form.
  3. Netlify dashboard -> your site -> Forms -> Form notifications
     -> Add notification -> Email notification.
  4. Recipient: simmons@barrettfinancial.com  -> Save.
All submissions are also stored in the Netlify dashboard as a backup.
(This only works once the site is LIVE on Netlify -- not from the
local preview file.)

BOOKING A CALL: the "Book a Call" buttons go to Calendly
(calendly.com/steftalks). Calendly emails you directly -- just make
sure the email on your Calendly account is the one you want alerts at,
and connect your Google Calendar so booked calls show up automatically.

--------------------------------------------------------
GET A QUOTE PAGE  (get-a-quote.html)
--------------------------------------------------------
New page with two lead-capture tools, both powered by Netlify Forms:
  1. "Request a rate quote" -- borrower fills in loan details.
  2. "Beat my Loan Estimate" -- borrower UPLOADS their current Loan
     Estimate (PDF or photo) for Stef to review.
Both email you the same way as the contact form once notifications
are set up (Netlify -> Forms -> add email notification for the
"rate-quote" and "beat-estimate" forms, not just "contact").
Uploaded files appear with each submission in the Netlify dashboard.
Note: Netlify's free tier caps form submissions/uploads per month;
if volume gets high, bump the Netlify plan.
Both forms carry "this is not a loan application" disclaimers. Since
they collect borrower info, it's worth a quick heads-up to Barrett
compliance that these lead forms exist.

--------------------------------------------------------
GOOGLE REVIEWS WIDGET (Elfsight)
--------------------------------------------------------
The "What clients are saying" section uses an Elfsight Google Reviews
widget (your live 5.0 / 31 reviews, auto-updating). It's already
embedded in the site. To manage it (change layout, colors, how many
reviews show), log in at elfsight.com and edit that widget -- changes
apply automatically, no code needed.

--------------------------------------------------------
DEPLOYING / GOING LIVE (quick version)
--------------------------------------------------------
  1. Netlify.com -> Add new site -> Import from GitHub -> pick this repo.
  2. Build command: (leave blank)   Publish directory: .
     (A netlify.toml in the repo already sets this.)
  3. After it deploys, add the custom domain www.callmyfriendstef.com
     (Netlify -> Domain settings) -- free HTTPS is automatic.
  4. Set up the form email notification (see above).

--------------------------------------------------------
TO PREVIEW IT
--------------------------------------------------------
Just double-click index.html to open it in your browser. Everything
works locally except the contact form (that only sends once it's live
on Netlify).
