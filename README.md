# Furry Friends — website preview

Pet grooming in Jumeirah Village Circle, Dubai. One page, English and Arabic. Customers pick where, pet, service, day and time, and WhatsApp opens with the booking written for them; Radd replies and confirms.

- Edit `src.html`, then `python3 build.py 971563334114` (the shop's WhatsApp number) to make `index.html`.
- Photos in `photos/` (Unsplash, free to use): `c_*` are pets cut out of their backgrounds (Apple Vision), `p_*` are normal photos. Swap in the shop's own photos when we have them.
- Reviews are real Google reviews of Furry Friends JVC (4.3★, 340 reviews, Oct 2026), shortened. Update the numbers in `src.html` now and then.
- Opening hours (`HOURS` in `src.html`) are 9 AM – 6 PM from Fresha; Google says 11 AM – 8:30 PM. Confirm with the owner.
- `?wa=9715XXXXXXXX` tries another WhatsApp number without rebuilding; `?lang=ar` opens in Arabic.
- Remove the `noindex` line in `src.html` when this becomes the shop's real site.
