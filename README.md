# Encyclopedia

This repository is intended to serve as a reference point for various tools, libraries, articles, cli commands, and other miscellaneous things that I've found helpful in my career or am interested in learning about or using.

## .NET

- .NET Foundation Projects (https://dotnetfoundation.org/projects/)
- ApiEndpoints (https://github.com/ardalis/ApiEndpoints/)
- AutoMoq (https://github.com/darrencauthon/AutoMoq/)
- Brighter (https://github.com/BrighterCommand/Brighter/)
- CliFx (https://github.com/Tyrrrz/CliFx/)
- CliWrap (https://github.com/Tyrrrz/CliWrap/)
- Compare .NET Objects (https://github.com/GregFinzer/Compare-Net-Objects/)
- Coravel (https://github.com/jamesmh/coravel/)
- Cupboard (https://github.com/cupboard-project/cupboard/)
- Discord.NET (https://github.com/discord-net/Discord.Net/)
- EF Core (https://github.com/dotnet/efcore/)
- FastEndpoints (https://github.com/dj-nitehawk/FastEndpoints/)
- FluentValidation (https://github.com/FluentValidation/FluentValidation/)
- HangFire (https://github.com/HangfireIO/Hangfire/)
- HashIds (https://github.com/ullmark/hashids.net/)
- Hot Chocolate (https://github.com/ChilliCream/hotchocolate/)
- Mass Transit (https://github.com/MassTransit/MassTransit/)
- NServiceBus (https://particular.net/nservicebus/)
- Polly (https://github.com/App-vNext/Polly/)
- Refit (https://github.com/reactiveui/refit/)
- Scrutor (https://github.com/khellang/Scrutor/)
- Serilog (https://github.com/serilog/serilog/)
- Spectre.Console (https://github.com/spectreconsole/spectre.console/)
- Yarp (https://github.com/microsoft/reverse-proxy/)

### Testing

- AutoFixture (https://github.com/AutoFixture/)
- BenchmarkDotNet (https://github.com/dotnet/BenchmarkDotNet/)
- Bogus (https://github.com/bchavez/Bogus/)
- Fixie (https://github.com/fixie/fixie/)
- FluentAssertions (https://github.com/fluentassertions/fluentassertions/)
- Moq (https://github.com/moq/moq/)
- NBomber (https://github.com/PragmaticFlow/NBomber/)
- NSubstitute (https://github.com/nsubstitute/NSubstitute/)
- Respawn (https://github.com/jbogard/Respawn/)
- Shouldly (https://github.com/shouldly/shouldly/)
- WireMock (https://github.com/WireMock-Net/WireMock.Net/)
- xUnit (https://github.com/xunit/xunit/)

## Frontend

- Bun (https://bun.sh/)
- Classnames (https://github.com/JedWatson/classnames/)
- Dexie (https://github.com/dexie/Dexie.js/)
- Formik (https://github.com/formium/formik/)
- Framer Motion (https://github.com/framer/motion/)
- Headless UI (https://github.com/tailwindlabs/headlessui/)
- React Developer Tools (https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi/)
- React-Query (https://github.com/tannerlinsley/react-query/)
- React Router (https://github.com/remix-run/react-router/)
- React Spinners (https://github.com/davidhu2000/react-spinners/)
- React-Spring (https://github.com/pmndrs/react-spring/)
- Redux (https://github.com/reduxjs/react-redux/)
- Remix Auth (https://github.com/sergiodxa/remix-auth/)
- SWR (https://github.com/vercel/swr)
- Tauri (https://github.com/tauri-apps/tauri/)
- Tailwind (https://tailwindcss.com/)
- Zod (https://github.com/colinhacks/zod/)

### Frameworks

- Create React App (https://create-react-app.dev/)
- Next (https://nextjs.org/)
- Remix (https://remix.run/)

### Learning

- A11y Project (https://www.a11yproject.com/)
- Kent C. Dodd's Epic React Course (https://epicreact.dev/)
- Kent C. Dodd's Testing JavaScript Course (https://testingjavascript.com/)

### Testing

- Cypress (https://github.com/cypress-io/cypress/)
- Jest (https://github.com/facebook/jest/)
- MirageJS (https://github.com/miragejs/miragejs/)
- Mock Service Worker (https://github.com/mswjs/msw/)
- Playwright (https://playwright.dev/)
- React Testing Library (https://testing-library.com/)
- Testing Playground (https://testing-playground.com/)

## Node

- Deno (https://github.com/denoland/deno/)
- Electron (https://www.electronjs.org/)
- Esbuild (https://github.com/evanw/esbuild/)
- Prisma (https://www.prisma.io/)
- Swc (https://swc.rs/)

## JavaScript

- Pheno (https://github.com/suchipi/pheno/)
- XState (https://github.com/statelyai/xstate/)

## Tools

- Event Store (https://www.eventstore.com/)
- PlanetScale (https://planetscale.com/)
- Seq (https://datalust.co/seq/)
- SonarQube (https://www.sonarqube.org/)

## Infrastructure

- Auth0 (https://auth0.com/)
- Clerk (https://clerk.dev/docs/get-started/remix/)
- Cloudflare Pages (https://pages.cloudflare.com/)
- Cloudflare Workers (https://workers.cloudflare.com/)
- Liveblocks (https://liveblocks.io/)
- Terraform (https://www.terraform.io/)
- Vault (https://github.com/hashicorp/vault/)

## Miscellaneous

- Apihouse (https://apihouse.vercel.app/)
- Blobmaker (https://www.blobmaker.app/)
- Conventional Commits (https://www.conventionalcommits.org/)
- David Fowler's Standard .NET Project Structure (https://gist.github.com/davidfowl/ed7564297c61fe9ab814/)
- Dbml (https://www.dbml.org/home/)
- Excalidraw (https://excalidraw.com/)
- Get Waves (https://getwaves.io/)
- Haikei (https://app.haikei.app/)
- Pact (https://docs.pact.io/)
- Readme.so (https://readme.so/)
- Roadmap.sh (https://roadmap.sh/)
- unDraw (https://undraw.co/)

## Git

How do I unstage files?\
`git restore --staged .`

How do I discard local changes to files?\
`git checkout .`

How do I discard newly added unstaged files?\
`git clean -f`

How do I discard newly added unstaged files and directories?\
`git clean -fd`

How do I discard all untracked files and directories?\
`git clean -fdX`

How do I remove a file from the working tree?\
`git update-index --skip-worktree <file_name>`\
`git update-index --no-skip-worktree <file_name>`

## Blogs

- Kent C. Dodds (https://kentcdodds.com/blog/)
- Mark Seemann (https://blog.ploeh.dk/)
- Nick Chapsas (https://www.youtube.com/channel/UCrkPsvLGln62OMZRO6K-llg/)
- The Morning Brew (https://blog.cwa.me.uk/)
- Vladimir Khorikov (https://enterprisecraftsmanship.com/)
