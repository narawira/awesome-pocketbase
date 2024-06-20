# Awesome PocketBase [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [PocketBase](https://pocketbase.io) resources.

PocketBase is a powerful open-source backend designed to simplify application development. It integrates an embedded SQLite database, enabling efficient data management and storage. With real-time subscriptions, PocketBase ensures that your application can handle dynamic data updates seamlessly. Including secure user authentication and authorization out of the box.

Furthermore, PocketBase offers a straightforward REST-like API, allowing for easy interaction with the backend from various client applications.

## Contents

- [Official Packages](#official-packages)
- [Docker](#docker)
- [Hosting](#hosting)
- [Showcases](#showcases)
- [C#](#c)
- [D](#d)
- [Dart](#dart)
- [Go](#go)
- [HTMX](#htmx)
- [JavaScript/TypeScript](#javascripttypescript)
	- [React](#react)
	- [Remix](#remix)
	- [Svelte](#svelte)
	- [Vue](#vue)
	- [Node.js](#nodejs)
- [Kotlin](#kotlin)
- [PHP](#php)
- [Python](#python)
- [Rust](#rust)
- [Swift](#swift)
- [Tools/Plugin](#toolsplugin)
	- [Extended Go](#extended-go)
	- [Extended SQLite](#extended-sqlite)
	- [TypeScript](#typescript)
	- [Other](#other)

## Official Packages

| Name | Description | Homepage | License |
|-----------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------|------------|
| PocketBase | PocketBase is an open source Go backend, consisting of embedded database (SQLite) with realtime subscriptions, built-in files and users management, convenient Admin dashboard UI, and simple REST-ish API. | [GitHub](https://github.com/pocketbase/pocketbase) | MIT |
| JavaScript SDK | Browser and Node.js SDK for interacting with the PocketBase API. | [GitHub](https://github.com/pocketbase/js-sdk) | MIT |
| Dart SDK | Multi-platform SDK for interacting with the PocketBase Web API. | [GitHub](https://github.com/pocketbase/dart-sdk) | MIT |

## Docker

| Name | Description  | Homepage | License |
|----------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Docker Setup | Docker setup supporting multiple architectures. | [GitHub](https://github.com/muchobien/pocketbase-docker) | - |
| Docker Image | Docker images supporting multiple architectures. | [GitHub](https://github.com/kdpuvvadi/pocketbase) | MIT |
| Docker Setup | Pocketbase in the form of Docker container. Just for my personal scenario, but maybe can inspire others. | [GitHub](https://github.com/sonyarianto/pocketbase-docker) | MIT |
| Docker Image ARM/AMD | Unofficial Pocketbase docker images for ARM & AMD. | [GitHub](https://github.com/coollabsio/pocketbase) | - |

## Hosting

| Name | Description  | Homepage | License |
|----------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| PocketHost | PocketHost is the multi-user, multi-tenant PocketBase server. Run hundreds, even thousands, of PocketBase instances at the same time on a single server or a global network. | [GitHub](https://github.com/pockethost/pockethost) | MIT |
| DigitalOcean | Guide to deploy in a Droplet. | [GitHub](https://github.com/pocketbase/pocketbase/discussions/512) | - |
| Fly.io | Guide to deploy for free on Fly.io. | [GitHub](https://github.com/pocketbase/pocketbase/discussions/537) | - |
| LocalXpose | Allow public access to a localhost instance. | [Homepage](https://localxpose.io/docs/tutorials/expose-pocketbase-backend) | - |
| BlazedCloud | Mobile client for minimalistic cloud hosting provider. | [GitHub](https://github.com/TheRedSpy15/blazedcloud) | MIT |

## Showcases

| Name | Description | Homepage | License |
|----------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Demo | This demo effectively shows how Marmot with PocketBase + Fly.io can be pushed closer to the edge. | [GitHub](https://github.com/maxpert/marmot-pocketbase-flyio) | - |
| E-Course | A self-hosted SPA to simplify course creation and management. | [GitHub](https://github.com/Ilyas-Codes/eCourse) | MIT |
| FireShip Demo | Build a basic note-taking app with Next.js 13 and Pocketbase. | [GitHub](https://github.com/fireship-io/next13-pocketbase-demo) | - |
| FireShip PocketChat | A basic realtime chat app demo with Pocketbase & Svelte. | [GitHub](https://github.com/fireship-io/pocketchat-tutorial) | - |
| Flutter Chat App | Chat app using PocketBase in Flutter. | [GitHub](https://github.com/rohitsangwan01/flutter_pocketbase_chat) | - |
| HTMX | Demo on how to use Pocketbase as a framework (With TEMPL and HTMX). | [Homepage](https://github.com/gobeli/pocketbase-htmx) | MIT |
| JustJot | A keyboard-first note-taking PWA. [Frontend](https://github.com/JunoNgx/justjot-frontend) [Backend](https://github.com/JunoNgx/justjot-backend) | [Homepage](https://justjot.app) | MIT |
| Next.js Starter | My Next.js (without app directory) Boilerplate with Pocketbase Backend. | [GitHub](https://github.com/ChristianSeelemann/nextjs-with-pocketbase) | - |
| Nomad Ops | A simple operator for nomad which reconciles the running jobs in comparison to git repos. | [GitHub](https://github.com/nomad-ops/nomad-ops) | MIT |
| oAuth Demo | React-based oAuth demo. | [GitHub](https://github.com/rajesh6161/pocketbase-oauth-demo) | - |
| Presentator | Presentator is free and open source design feedback and presentation platform. | [GitHub](https://github.com/presentator/presentator) | BSD-3-Clause |
| Realtime Blog | React-based real-time blog demo.  | [GitHub](https://github.com/rajesh6161/pbRealtimeBlog) | - |
| Share Me | An image and video hosting platform for your server, with rich embed support and API. | [GitHub](https://github.com/Dan6erbond/share-me) | MIT |
| Showcase | Full stack application built with SvelteKit & PocketBase. | [GitHub](https://github.com/huntabyte/showcase) | - |
| SvelteKit Auth | Demonstrates how to integrate PocketBase with SvelteKit 1.0. The project includes login and registration pages, as well as examples of how to retrieve the current user. | [GitHub](https://github.com/jianyuan/pocketbase-sveltekit-auth) | MIT |
| ToDo App | React-based To-Do demo app. | [GitHub](https://github.com/rajesh6161/pocketbaseTodo) | - |
| UpSnap | A simple wake on lan web app written with SvelteKit, Go and PocketBase. | [GitHub](https://github.com/seriousm4x/UpSnap) | MIT |
| Vimsnake | A real-time WASM game where Vim commands are used as controller inputs. | [GitHub](https://github.com/patmood/vim_snake) | - |

## C#

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| C# SDK | Unofficial PocketBase client for C#. | [GitHub](https://github.com/PRCV1/pocketbase-csharp-sdk) | MIT |
| C# SDK (+ORM) | Unofficial PocketBase client with ORM to manage your PocketBase Application. | [GitHub](https://github.com/iluvadev/PocketBaseClient-csharp) | MIT |

## D

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client | PocketBase client wrapper for D with automatic serialization and deserialization to/from JSON. | [GitHub](https://github.com/Hax-io/libpb) | LGPL-3.0 |

## Dart

| Name | Description | Homepage | License |
|------------------------------------|----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| PocketBase Drift | A PocketBase client cached with Drift. | [GitHub](https://github.com/rodydavis/pocketbase_drift) | Apache-2.0 |
| Dart Generator | Generate type-safe client SDKs for use in local SQLite, JSON or GraphQL resolvers. | [GitHub](https://github.com/rodydavis/pocketbase_dart_generator) | Apache-2.0 |
| PocketBase Server Flutter | A Flutter plugin to run PocketBase server directly from Android/iOS. | [GitHub](https://github.com/rohitsangwan01/pocketbase_server_flutter) | MIT |

## Go

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client | Unofficial PocketBase client for Go. | [GitHub](https://github.com/r--w/pocketbase) | MIT |

## HTMX

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Chat App | A simple chat application built with HTMx, JavaScript, and the PocketBase API, styled using Tailwind CSS. | [GitHub](https://github.com/valiantlynx/htmx-chat) | - |

## JavaScript/TypeScript

JavaScript and typescript ecosystem.

### React

| Name | Description | Homepage | License |
|--------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| PocketBase React | Unofficial React SDK (React, React Native, Expo) for interacting with the PocketBase JavaScript SDK. | [GitHub](https://github.com/tobicrain/pocketbase-react) | MIT |
| PocketBase Next.js Template | PocketBase Next.js Template with server & browser client using cookies. | [GitHub](https://github.com/tsensei/nextjs-pocketbase-starter-template) | MIT |

### Remix

| Name | Description | Homepage | License |
|--------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| PocketBase Remix | Example app with complete server side registration and authentication flow (including OAuth), using Remix and PocketBase. | [GitHub](https://github.com/ausminternet/remix-pocketbase-starter) | MIT |

### Svelte

| Name | Description | Homepage | License |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Svelte Query | TanStack Query wrappers around PocketBase for Svelte and SvelteKit that update the query cache in real-time. | [GitHub](https://github.com/goknsh/svelte-query-pocketbase) | MIT |
| SvelteKit Auth  | Sample implementation reference for setting up authentication using SvelteKit. | [GitHub](https://github.com/danawoodman/sveltekit-auth-example) | - |
| SvelteKit PocketBase Auth | Demonstrates how to integrate PocketBase with SvelteKit, including login and registration pages. | [GitHub](https://github.com/jianyuan/pocketbase-sveltekit-auth) | MIT |
| SvelteKit Shortener | An open-source URL Shortener written in SvelteKit with PocketBase. | [GitHub](https://github.com/GermanHeim/svelte-shortener) | MIT |
| SvelteKit Starter | A starter kit showing how to use customized PocketBase as a backend to SvelteKit frontend. | [GitHub](https://github.com/spinspire/pocketbase-sveltekit-starter) | MIT |
| SvelteKit Static | Minimalist template with configured authorization featuring a single Docker image for deploying.  | [GitHub](https://github.com/Egor-S/pocketbase-sveltekit-static) | MIT |
| SvelteKit Stripe | KitBase is a starter template geared towards quickly spinning up projects using PocketBase and Stripe.  | [GitHub](https://github.com/kevmodrome/kitbase) | MIT |

### Vue

| Name | Description | Homepage | License |
|---------------------------------|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Vue 3 + Vite Starter Kit | A starter kit for Vue 3 + Vite + PocketBase.  | [GitHub](https://github.com/StefanVDWeide/pocketbase-vue) | - |
| Quasar Starter Kit | Quasar framework starter kit for PocketBase.  | [GitHub](https://github.com/aaronblondeau/pocketbase_quasar_starter) | - |
| PocketNuxt | A Nuxt3 PocketBase starter that builds into a single binary. | [GitHub](https://github.com/j-wil/pocket-nuxt) | - |

### Node.js

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| gobot | PocketBase as an npm package. CLI and API. | [GitHub](https://github.com/benallfree/gobot) | - |

## Kotlin

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client  | Unofficial PocketBase client for Kotlin. | [GitHub](https://github.com/agrevster/pocketbase-kotlin) | MIT |

## PHP

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client | Unofficial PocketBase client for PHP. | [GitHub](https://github.com/mkay-development/pocketbase-php-sdk) | - |

## Python

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Python (Sync) | Unofficial PocketBase client for Python (Sync). | [GitHub](https://github.com/vaphes/pocketbase) | MIT |
| Python (Async) | Unofficial PocketBase client for Python (Async). | [GitHub](https://github.com/thijsmie/pocketbase) | MIT |

## Rust

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client | Unofficial PocketBase client for Rust. | [GitHub](https://github.com/sreedevk/pocketbase-sdk-rust) | MIT |

## Swift

| Name | Description | Homepage | License |
|-------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Client | A simple Swift client for PocketBase. | [GitHub](https://github.com/zz129869523/PocketBase) | - |

## Tools/Plugin

Here's another tools or plugin that related to the PocketBase or can be used with-in pocketbase.

### Extended Go

| Name | Description | Homepage | License |
|------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Telegram Auth | Add Telegram authentication (Widget button and WebApp). | [GitHub](https://github.com/iamelevich/pocketbase-plugin-telegram-auth) | MIT |
| Ngrok  | Expose local PocketBase to the internet with ngrok. | [GitHub](https://github.com/iamelevich/pocketbase-plugin-ngrok) | MIT |
| Proxy  | Proxy requests to another host, useful for separate server frontends. | [GitHub](https://github.com/iamelevich/pocketbase-plugin-proxy) | MIT |

### Extended SQLite

| Name  | Description | Homepage | License |
|-----------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Marmot | A distributed SQLite replicator.  | [GitHub](https://github.com/maxpert/marmot) | MIT |
| Litestream | Streaming SQLite replication. | [Homepage](https://github.com/benbjohnson/litestream) | Apache-2.0 |
| PocketBase & Litestream Starter | Template showing Litestream running with PocketBase. | [GitHub](https://github.com/TylerSustare/pocketbase-framework-litestream) | - |
| PocketBase & Litestream Docker | Docker example of PocketBase saving/restoring from Litestream. | [GitHub](https://github.com/bscott/pocketbase-litestream/) | Apache-2.0 |

### TypeScript

| Name  | Description | Homepage | License |
|-----------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Hooks Starter Kit | Build PocketBase JavaScript hooks using TypeScript. | [GitHub](https://github.com/benallfree/ts-pb-hooks-starter) | - |
| PocketBase Typegen | Generate TypeScript types from the SQLite db file. | [GitHub](https://github.com/patmood/pocketbase-typegen) | - |
| PocketBase TS | A simplified PocketBase SDK to ease the developer experience. | [GitHub](https://github.com/Solaris9/pocketbase-ts) | MIT |
| Typed PocketBase | Generate types from your PocketBase instance for type-safe queries. | [GitHub](https://github.com/david-plugge/typed-pocketbase) | MIT |

### Other

| Name  | Description | Homepage | License |
|-----------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| PocketBase Filter (PBF) | Library for serializing and deserializing PocketBase filter syntax. | [GitHub](https://github.com/nedpals/pbf) | MIT |
| PocketBase GPT | A GPT with all of PocketBase's documentation uploaded for more accurate and up-to-date answers. | [Homepage](https://chat.openai.com/g/g-Owo2FBp4K-pocketbase-gpt) | MIT |
| PocketBase Import | PocketBase data import tools for CSV and JSON files made using PocketBase JS SDK. | [GitHub](https://github.com/michal-kapala/pocketbase-import) | MIT |
| PocketBase Mobile | Frameworks for running PocketBase from mobile. | [GitHub](https://github.com/rohitsangwan01/pocketbase_mobile) | MIT |
| Pocketbase Queue | Type-safe queue for background tasks using PocketBase.  | [GitHub](https://github.com/joseferben/pocketbase-queue) | MIT |
| PocketBase Stripe | Integration for Stripe subscriptions. | [GitHub](https://github.com/mrwyndham/pocketbase-stripe) | MIT |
| PocketBase Templates | Collection of PocketBase schemas to quickly get started. | [GitHub](https://github.com/Pocket-Space/pocketbase-templates) | MIT |
| PocketBase UML | Generates UML diagrams based on PocketBase databases. | [Homepage](https://pocketbase-uml.github.io/) | MIT |
| PocketBlocks | Integration between Openblocks and Pocketbase. | [GitHub](https://github.com/internoapp/pocketblocks) | AGPL-3.0 |
| PostgreBase | Fork of PocketBase, but replacing the sqlite with CockroachDB and PostgreSQL. | [GitHub](https://github.com/zhenruyan/postgrebase) | MIT |
