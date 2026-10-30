# Petronas ($PETRONAS)

A Solana memecoin launchpad with a 2000s internet look, set in a pixel penthouse computer room on the top floor, looking out over a night city.

Petronas is just the project's name. This is an independent memecoin project with no affiliation with, endorsement by or connection to any company, brand or organisation of that name.

## Deploy
The site is a single `index.html` with no folders and no build step. Drop it into a GitHub repo or Vercel.

## Settings
Open `index.html` and find `CONFIG` near the top of the script:

```js
var CONFIG={xUrl:'',xHandle:'',ca:'',buyUrl:''};
```

- `xUrl` / `xHandle`: your X link and @handle
- `ca`: the contract address. Until it's set, the page says "CA posted on X at launch".
- `buyUrl`: your buy link

## How Petronas works
- **Call the elevator (launch):** launching is free, with no dev wallet, and the site pays the launch fee. The coin's elevator rides up for 5 to 30 minutes, and anyone can board with up to 2 SOL per wallet. At the top floor, one transaction launches the coin and buys it for everyone aboard at one price.
- **Floors:** every coin lives on a floor, one floor per $2K of market cap, up to floor 99. Graduated coins get the penthouse (PH). The building directory sorts coins into In the elevator, Rising floors, Lobby and Penthouse.
- **Rent (fees):** 40% buys back the coin and burns it ("lights out"), 35% buys back and burns $PETRONAS, and 25% goes to the building fund.
- **Lights out:** each coin burns at a random moment 15 to 25 minutes after its last burn, with a receipt. The concierge log lists every burn.
- **Penthouse of the Week:** every Sunday, the graduated coin that burned the most is featured, and the building fund pays for its boosts that week.
- **Doorbell:** watch coins to get a pop-up when they burn. **House rules:** all the rules in one place.
- **Landing page:** a live elevator floor indicator, a skyline.exe stats window, a concierge sticky note and a detailed penthouse scene. The city lights up whenever a burn lands.

These mechanics are planned. Everything shown before launch is a labelled sample or simulation.
