# discord-blockchain

Build Discord Web 3.0

## Tech Stack

- Gun.js - Decenteralized Database Node
- Context API - To manage the State
- Sanity - Storing Users and Channels
- NextJS - To build the APP
- Meta Mask - Authentication
- Sanity - Backend Database
- GROQ (Graph-Relational Object Queries) - A declarative query language
- Versel - Deployment

## Directories Details

- Client

  - cd client
  - npx create-next-app .

- Server

  - cd server
  - npm i -g yarn
  - yarn init
    - question name (server): discord-gun-node
    - question version (1.0.0):
    - question description:
    - question entry point (index.js): server.js
    - question repository url:
    - question author:
    - question license (MIT):
    - question private:

- Studio

  - cd studio
  - Setup Sanity (https://www.sanity.io/cleverprogrammer)
    npm install -g @sanity/cli
    sanity init --coupon cleverprogrammer
    - Login using Email
    - Enter Project Name
    - Select Project Template - (Clean project with no predefined schema)
    - Enter

- Parent Dir
  - setup Vercel
    - install vercel CLI - npm i -g vercel
    - versel
      Vercel CLI 24.0.0
      > > No existing credentials found. Please log in:
      > > Log in to Vercel email
      > > Enter your email address: bhopalsinghsis@gmail.com
      > > We sent an email to bhopalsinghsis@gmail.com. Please follow the steps provided inside it and make sure the security code matches Unusual Sponge.
      > > Success! Email authentication complete for bhopalsinghsis@gmail.com
      > > ? Set up and deploy “~/git-repos/discord-blockchain”? [Y/n] y
      > > ? Which scope do you want to deploy to? Bhopal Singh
      > > ? Link to existing project? [y/N] n
      > > ? What’s your project’s name? discord-blockchain
      > > ? In which directory is your code located? ./client
      > > No framework detected. Default Project Settings:
      - Build Command: `npm run vercel-build` or `npm run build`
      - Output Directory: `public` if it exists, or `.`
      - Development Command: None
        ? Want to override the settings? [y/N] n
        🔗 Linked to bhopals/discord-blockchain (created .vercel and added it to .gitignore)
        🔍 Inspect: https://vercel.com/bhopals/discord-blockchain/GdqwgGnMKxCo3fEsSPFGzfssSCvA [1s]
        ✅ Production: https://discord-blockchain-khaki.vercel.app [copied to clipboard] [38s]
        📝 Deployed to production. Run `vercel --prod` to overwrite later (https://vercel.link/2F).
        💡 To change the domain or build command, go to https://vercel.com/bhopals/discord-blockchain/settings
