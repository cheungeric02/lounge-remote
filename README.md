# Lounge Remote

Phone remote for the [Lounge](https://github.com/cheungeric02/lounge) Android TV home screen.
Live at https://cheungeric02.github.io/lounge-remote/ (GitHub Pages, main branch root).

- Single-file app: `index.html`. `?demo=1` runs a fake TV backend (use it for testing; never write the live DB).
- `APP_VERSION` in index.html MUST equal the sw.js cache number (`loungeremote-vN`). Bump both and add a `PATCH_NOTES` entry on every change.
- Pairing word list lives in the lounge repo (`remote/words.txt`, must equal `WordList.kt`).
- The old URLs cheungeric02.github.io/lounge/remote/ and /lounge/app/ redirect here (kept in the lounge repo CI).
