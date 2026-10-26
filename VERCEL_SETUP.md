# Deploy Peer2Peer to Vercel

Peer2Peer runs as a static site and stores accounts, profiles, mentor assignments, and chats in the current browser's `localStorage`. It does not connect to Neon or need a database or API functions.

## Deploy

Import this repository into Vercel with the project root selected. The root contains `index.html`, `script.js`, `style.css`, `package.json`, and `vercel.json`. No build command or output directory is required. Deploy the latest commit after changing these files.

## Demo admin

Register in the browser using `yusuf.daniel@binus.ac.id` to enable the admin panel. The admin can designate student mentors and assign mentors to students. This is a local demo only: email ownership is not verified, and browser storage cannot securely protect admin access.

## Data limitations

- Data is available only in the browser and website origin where it was created. Other users and devices do not share accounts, profiles, assignments, or chats.
- Clearing that browser's site data removes its Peer2Peer data.
- Neon is not deleted or changed, but this version no longer reads or writes to it.
- Existing accounts in Neon are not copied into browser storage. Register again in each browser for this demo.
- Use a hosted database and server-side authentication for shared or real student records.
- Support requests open a prefilled email to `yusuf.daniel@binus.ac.id` in the user's email application.
