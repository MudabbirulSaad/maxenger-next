# Opensource Messenger Clone:

Technologies used:

- Next.js 13
- NextAuth
- Pusher
- MongoDB
- Tailwind
- Prisma

</br>
Key Features:

- Real-time messaging using Pusher
- Message notifications and alerts
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with NextAuth
- Google, Github authentication integration
- File and image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings
- POST, GET, and DELETE routes in route handlers (app/api)
- fetch data in server React components by directly accessing the database
- Handling relations between Server and Child components in a real-time environment
- Creating and managing chat rooms and channels

</br>

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/mudabbirulsaad/maxenger-next.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
