# live preview
"[**Live Demo**](https://havel-eta.vercel.app)"
# <img src="https://img.icons8.com/color/344/discord.png" width="40" alt="Fullstack Discord Clone"> Fullstack Discord like app

## Project Overview

A comprehensive guide to building a full-fledged Discord clone using Next.js 13, React, Socket.io, Prisma, Tailwind, and postgreSQL.

## Features

* <img src="https://img.icons8.com/color/344/chat.png" width="20" alt="Chat"> Real-time messaging using Socket.io
* <img src=""> Send attachments as messages using UploadThing
* <img src="https://img.icons8.com/color/344/edit.png" width="20" alt="Edit"> Delete & Edit messages in real time for all users

VIDEO TUTORIAL](https://www.youtube.com/watch?v=ZbX4Ok9YX94)

Features:

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

## Tech Stack

* Next.js 13
* React
* Socket.io
* Prisma
* Tailwind
* postgresql
  

## Prerequisites

* Node version 18.x.x

## Getting Started

```bash
git clone https://github.com/AntonioErdeljac/next13-discord-clone.git
```
```shell
npm install
```
Setup .env file

Create a new file named .env in the root directory and add the following variables:
Makefile
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=your_sign_in_url
NEXT_PUBLIC_CLERK_SIGN_UP_URL=your_sign_up_url
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=your_after_sign_in_url
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=your_after_sign_up_url

DATABASE_URL=your_database_url

UPLOADTHING_SECRET=your_uploadthing_secret
UPLOADTHING_APP_ID=your_uploadthing_app_id

LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
NEXT_PUBLIC_LIVEKIT_URL=your_livekit_url
```
Add MySQL Database (NEON.TECH)
```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```
## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

# discord-typescript
