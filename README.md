<div align="center">
  <a href="https://meetfaq.com?utm_source=github" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/github-20k/meetqa/assets/100117126/b1627f46-ab23-4a84-8a1f-e3c56d6411b0">
    <img alt="Novu Logo" src="https://github.com/github-20k/meetqa/assets/100117126/1f6c696c-d078-4e30-a8d6-bf503769059c" width="280"/>
  </picture>
  </a>
</div>

<br/>

<h1 align="center">Support Channels into a Public FAQ</h1>

<div align="center">
Not all of your customers are on your support channels.<br />
Extract your FAQ to make it available to everyone.
</div>

  <p align="center">
    <br />
    <a href="https://meetfaq.com/docs"><strong>Explore the docs »</strong></a>
  </p>

## ⭐️ Why MeetFAQ?

MeetFAQ connects to your support channels (At the moment Discord). <br />
It lets you take conversations and convert them into an FAQ with ChatGPT, later to be accessible via a public URL.<br />
You can also create an FAQ on your website directly with the system.

## ✨ Video Example

<div align="center">
  <video src="https://github.com/github-20k/meetqa/assets/100117126/caed6cdf-0582-4e90-aea6-e37081951c6e"></video>
</div>

## 🔌 Infrastructure

This is a monorepo built with NX

- `backend` - NestJS project manging all the API.
- `discord` - NestJS project of the Discord bot.
- `website` - NextJS project of the MeetFAQ dashboard and the customer website.
- `marketing` - NextJS project of the marketing website.

## ⚙️ Installation
1. Clone the project
2. Deploy a new Postgres database.
3. Copy `.env.example` to `.env` and fill in the variable.
4. Run `npm run update-prisma` to create the new schema.
5. Run `npm run dev` to start the project.

## 🍾 Contact me

Nevo - [nevo@gitroom.com](mailto:nevo@gitroom.com)
