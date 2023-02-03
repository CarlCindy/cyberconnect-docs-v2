---
id: quick-setup
title: Quick Setup
slug: /how-to/build-badge-app/quick-setup
sidebar_label: Quick Setup
sidebar_position: 1
description: How to Build Badge app - Quick Setup
---

This guide will teach you how to create a social application where users can create on-chain badges that can be linked to an event. Once users have set up their profiles, they will be able to create badges for an event and attendees will have the ability to collect them by attending that event.

This is a basic example with the sole purpose of going over core features and highlighting how easy to implement them. Later on you can extrapolate and get creative with your project to create different use cases that would truly make your app stand out.

## Jump to

How to Build Badge app covers the following sections:

1. [Authentication](/how-to/build-badge-app/authentication)
2. [Create a Badge](/how-to/build-badge-app/create-a-badge)
3. [Collect a Badge](/how-to/build-badge-app/collect-a-badge)

## Prerequisites

The app you're about to build is using [Next.js](https://nextjs.org/). Make sure that you have installed [Node.js](https://nodejs.org/en/download/) on your computer and [MetaMask](https://metamask.io/) extension in your Chrome browser.

## Installation

Clone the repo [https://github.com/cyberconnecthq/cc-badge-app.git](https://github.com/cyberconnecthq/cc-badge-app.git) and run the following command in your terminal to install all the packages that are necessary to start the development server: `npm install` or `yarn install`.

## Set up env variables

In this demo we will be using [Pinata](https://www.pinata.cloud/) to pin our profile & badge metadata. If you don't already have a Pinata account, [signup and get your API keys here](https://docs.pinata.cloud/master).
Once you have your API key & secret, create a `.env` file (you can just copy the `.env.example`) and input your credentials:

```
PINATA_API_KEY="exampleapikey4a715f2cfb"
PINATA_API_SECRET="exampled1234567898f722249c231648ecbaea8968bc6ab4e762cdcea2dd8d335"
```

## Local Development

To start the local development server run the command `npm run dev` or `yarn dev` and open up the browser window http://localhost:3000. Most changes are reflected live without having to restart the server.

## Live demo

This is the link for the live version of the app you are about to build: [https://cc-badge-app.vercel.app/](https://cc-badge-app.vercel.app/)

Let's get started with building an application where users can issue and collect badges!
