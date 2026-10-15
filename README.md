# Haadhumaa's Little Universe ♡

A mobile-first React + Vite birthday scrapbook with a passcode gate, countdown, three missions, local photo previews, and local voice-note playback.

## Run it

1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL Vite prints.
4. Run `npm run build` to create a production build in `dist/`.

## Personalize before sharing

Edit `src/config.ts`:
- Change `passcode` (default: `HAADHUMAA19`).
- Update `letter`, mission question/options/answer, and memory captions.
- Change `birthdayISO` if the date/time changes.
- Add photos into `public/photos/` (e.g. `photo1.jpg`, `photo2.jpg`, `photo3.jpg`) and set their paths in `src/config.ts`.
- (Optional) Add a voice note audio file to `public/` and set `voiceNoteUrl` in `src/config.ts`.

The passcode is a fun gate, not strong security: the client-side source includes it. Do not put private or sensitive information in the site. Mission progress uses localStorage. Photos and voice notes bundled in `public/` are served with the website automatically. Visitors can also upload or replace photos locally on their own devices.

No cloud database is configured. The page uses Google Fonts when online, with local font fallbacks.
