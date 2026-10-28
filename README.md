# Muhammad Faaiz portfolio

Static site. No build step needed.

Files:
- index.html  : the whole portfolio
- vercel.json : Vercel settings (sends the referrer header YouTube needs to play embedded videos)

## Deploy on Vercel (GitHub)
1. Create a new GitHub repository and upload these files to it.
2. Go to vercel.com, sign in, click Add New > Project and import the repository.
3. Leave Framework Preset as "Other", leave Build Command and Output Directory empty, then click Deploy.

## Deploy on Vercel (command line)
1. Install Node.js, then open a terminal in this folder.
2. Run: npx vercel
3. Answer the prompts (accept defaults), then run: npx vercel --prod

## Add or change videos
Open index.html and edit the LINKS list near the bottom.
