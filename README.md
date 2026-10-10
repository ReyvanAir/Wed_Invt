# Kimberly & Joel — Wedding Invitation

A responsive Indonesian wedding invitation with a burgundy and ivory design, the couple's photo, a countdown, ceremony and reception details, optional music, and an RSVP message preview.

## Preview

Open `index.html` in a browser. No build step is required. Keep the `assets` folder beside it.

For a local server, run `python -m http.server 8000` in this folder and open http://localhost:8000.

## Personalize

Edit the `INVITATION` settings near the bottom of `index.html`:

- `date`: the template currently retains 12 December 2026 at 08:00 WIB (UTC+07:00).
- `ceremonyTime` and `receptionTime`: event schedules.
- `ceremony` and `reception`: real venue names, addresses, and HTTPS map links.
- `whatsapp`: the recipient's international phone number, without a plus sign or spaces.

Until a WhatsApp number is supplied, RSVP prepares a message that guests can copy. When configured, it opens a WhatsApp draft for the guest to send. Responses are not stored in a database.

The photo is stored locally in `assets/kimberly-joel.png`. Fonts load from Google Fonts. The music is extracted from the supplied video and stored in `assets/wedding-music.mp3`. Guests can play or pause it using the music button; playback loops.

## Files

- `index.html` — complete page, styles, and interactions.
- `assets/kimberly-joel.png` — supplied wedding photo.

Live website: https://reyvanair.github.io/Wed_Invt/

GitHub Pages publishes the root of the main branch. Push changes to main to update the website.
