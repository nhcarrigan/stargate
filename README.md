# Discord bot using Stargate

<table border="0">
  <tr>
    <td align="center">
      Stargate is a data gateway deployed between client applications and a database. It's built with extensibility as a first-class citizen and makes it easy to use a database for any application workload by adding plugin support for new APIs, data types, and access methods.
      For more information about how to use Stargate, visit <a href="https://stargate.io/">Stargate.io</a>
    </td>
    <td align="center">
      YouTube video of Stargate
      <a href="http://www.youtube.com/watch?v=2ltVf2EscmM">
        <img src="http://img.youtube.com/vi/2ltVf2EscmM/0.jpg" alt="YouTube thumbmnail for Stargate" />
      </a>
    </td>
  </tr>
</table>

## Phase 1

### Goals

A video tutorial on how to use Stargate serverless

Features:

- CRUD usage of Stargate
- Discord Bot (bio, social links, timezone)
- 5-10mins edited video

### Challenges

- Cassandra is associated with being "scary"
- People using what they are used to even if the wrong tool for the job
- People use what they hear most for example Mongo or an equivalent in the frontend space React

### Storytelling

- That it is not anymore difficult than similar alternatives
- Simple and quick to use at hackathons and build prototypes
- Scalable so that enterprise projects can use it too
- Serverless is an affordable option for everyone (also has a free tier)
- Stargate is open source and can grow and scale with the project

### Problem

- Awareness of Stargate
- Cassandra scares people, usually perceived as being "difficult" or "hard"
- Educating people on the benefits of using Stargate

### Solution

- Short / concise video (5-10mins)
- 1min social teaser video
- Include what is Stargate serverless
- Build a simple Discord bot, to get/set user details and read/write to DB using Stargate serverless (bio, socials)

### Vision

- Easily digestible content
- More projects on Github using Stargate
- Clear and engaging message
- Lowering the barrier to entry
- Low cost of usage
- Community excited about it

### Impact

- Evergreen content
- Searchable content
- Consise / digestible content for everyone to get started
- Community building their own projects with Stargate serverless

![DataStax Discord Bot v0.1](https://user-images.githubusercontent.com/624760/110018509-416c3200-7d1f-11eb-8f1b-444557401906.png)

## Technologies Used 

- [DiscordJS](https://discordjs.guide) with Typescript
- [Stargate](http://stargate.io)

## Quickstart

1. fork the project
1. clone project `git clone https://github.com/<YOUR-USERNAME>/stargate`
1. navigate into the project `cd stargate`
1. `cp .env.example .env`
1. add the respective env-vars to the .env file
  - [generating Discord bot token](https://discordjs.guide/preparations/setting-up-a-bot-application.html#keeping-your-token-safe)
  - [making AUTH token for Stargate](https://stargate.io/docs/stargate/1.0/developers-guide/authnz.html#_generate_an_auth_token)
1. install dependencies `npm install`
1. install husky helpers `npm run prepare`

## Docs

- [Project board v0.1](https://github.com/eddiejaoude/stargate/projects/1) of `to do`, `in progress`, `done`
- How to edit project [Labels](docs/labels.md)
