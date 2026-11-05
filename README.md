# Free Christmas dinner timing calculator (UK, kilograms and Celsius, one HTML file)

Enter your turkey weight and the time you want to eat. You get a timeline that works backwards from serving time: when to start defrosting, when to take the turkey out of the fridge, when the oven goes on, when the turkey goes in and comes out, when it rests and is carved, and when each side dish starts. No sign-up, no server, no cookies, no build step: it is one `index.html` file, and nothing you type leaves your device.

**Use it now, no install:** download `index.html` and open it in any browser, or use the page version with the full guidance at [tchworks.co.uk/free/christmas-dinner-timing-calculator](https://www.tchworks.co.uk/free/christmas-dinner-timing-calculator/?utm_source=github&utm_medium=repo&utm_campaign=dinner-timing-repo).

## What it does

- Whole turkey or crown, weight in kg, fan or conventional oven, stuffing cooked separately or inside the bird.
- Turkey cooking times from published UK guidance (see below). Where sources differ it uses the longer figure.
- Defrost start time in the fridge (12 hours per kg), oven preheat, turkey in and out, rest under foil, carving, and optional side dishes: roast potatoes, parsnips, pigs in blankets, stuffing, Yorkshire puddings, sprouts, gravy, warm plates.
- Print button for a paper copy for the fridge door. Typed text is shown as text only, never run as code.

## The numbers

| Joint | Oven | Time |
|---|---|---|
| Whole turkey under 4.5 kg | 180C (160C fan) | 45 minutes per kg plus 20 minutes |
| Whole turkey 4.5 kg and over | 180C (160C fan) | 40 minutes per kg |
| Crown under 4 kg | 190C (170C fan) | 20 minutes per kg plus 70 minutes |
| Crown 4 kg and over | 190C (170C fan) | 20 minutes per kg plus 90 minutes |

The calculator adds 15 minutes of spare oven time (30 if stuffed inside), a 20-minute oven preheat, a 30-minute rest and a 10-minute carve. Those, and the start time of each side dish, are our own allowances, not official guidance. Change the `SIDES`, `PREHEAT` and `CARVE` values near the top of the script to suit your recipes.

Always check the pack label first and use a meat thermometer: 75C or more in the thickest part, no pink meat, clear juices. The Food Standards Agency also lists 70C held for 2 minutes. These are estimates and ovens vary. Not professional food safety advice.

Sources: [Food Standards Agency, Christmas food hygiene](https://www.gov.uk/government/publications/christmas-food-hygiene/christmas-food-hygiene), [BBC Good Food, foolproof turkey guide](https://www.bbcgoodfood.com/howto/guide/foolproof-turkey-guide) and [BBC Good Food, roast timer](https://www.bbcgoodfood.com/howto/guide/roast-timer). This project is not affiliated with either.

## Self-host

Put `index.html` on any static host (GitHub Pages, Netlify, a school or church intranet). There is nothing to configure.

## Licence

MIT. Made by [TCH Works](https://www.tchworks.co.uk/?utm_source=github&utm_medium=repo&utm_campaign=dinner-timing-repo), which also publishes [Christmas cards](https://www.tchworks.co.uk/cards/christmas/?utm_source=github&utm_medium=repo&utm_campaign=dinner-timing-repo), a free [Secret Santa generator](https://www.tchworks.co.uk/free/secret-santa-generator/?utm_source=github&utm_medium=repo&utm_campaign=dinner-timing-repo) and a printable [Christmas Dinner Countdown & Timing Planner](https://tchworks.gumroad.com/l/tdiitb?utm_source=github&utm_medium=repo&utm_campaign=dinner-timing-repo).
