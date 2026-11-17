# Al Ferdous — Vision Correction Landing Page

صفحة هبوط «رحلة مختلفة لرؤية أوضح» لمركز الفردوس للعيون. بتتفتح من الـQR في المركز، ومعمولة للموبايل أولًا، بالعربي ومن اليمين للشمال.

## Current stage
Direction draft (branch `journey-v2`): full-width video with Arabic captions, animated boarding pass on first scroll, and the first station on a journey line that fills as you scroll. Remaining stations, «عن الفردوس» and the booking form come after approval.

## Structure
- `index.html`: the whole site (HTML + CSS + JS, no build step)
- `media/`: video, poster and background images

## Run locally
Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Still dummy
- `media/intro.mp4`, `media/poster.jpg`: replace with the center's real video and cover
- `media/ph-*.jpg`: photos taken from the brand guidelines; replace with photos from the center when available
- Contact details and the «عن الفردوس» text in `index.html`
- Booking form: see the `TODO` in `index.html` to connect it to WhatsApp, email or a CRM
