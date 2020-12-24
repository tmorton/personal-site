---
layout: post
title: The Full-Stack Center of Gravity
tags: []
---

New technology!  Write your entire webapp in the best language, without messing around in some other terrible environment.  I'm referring, of course, to [React server components](https://reactjs.org/blog/2020/12/21/data-fetching-with-react-server-components.html).  Or I'm referring to [Hotwire](https://hotwire.dev/).  Whether you love Javascript or hate it, you can be a "full-stack developer" and deliver a modern experience, in your preferred environment.  

Here's the thing: in 2021, there are three general ways to write a webapp, three ways to staff a webdev company, and three ways to approach a webdev career.  

But here's the important thing: all three are legitimate choices.  If you're breaking ground on a new app, company, or career, take your pick.  I'll add my opinions later.

But first, let's take a tour.

## Full Stack, Frontend Focus

In this world, we love Javascript (or Typescript).  As "full stack developers", we approach the application client-side first.  When server-side work is needed, we take responsibility for that as well.  We might write API endpoints with Node, or do server-side rendering for entire pages, but our native environment is the browser.

### Technology we like
- [Next.js](https://nextjs.org/) - especially its native support for server-side and compile-time rendering.
- [Deno](https://deno.land/) - making our server-side environment more browser-like
- [React server components](https://reactjs.org/blog/2020/12/21/data-fetching-with-react-server-components.html)

## Full Stack, Backend Focus

In this world, we're also "full stack developers", but we keep as much code server-side as possible.  Our preferred languages (Ruby, Python, etc) live on the server.  But we recognize that we're writing webapps, and a rich UX is required.  We prefer server-rendered markup, but sprinkles of Javascript and tricks like Turbolinks keep things snappy.

### Technology we like
- [Hotwire](https://hotwire.dev/) - the brand-new, integrated hotness for snappy server-rendered UI
- [Turbolinks](https://github.com/turbolinks/turbolinks) - the old trick to avoid full-page refresh
- [Phoenix LiveView](https://hexdocs.pm/phoenix_live_view/Phoenix.LiveView.html)

## Frontend / Backend Split

In this world, we're building separate apps: one (or more) on the client, and one (or more) on the server.  As developers, we focus on "front end" or "back end".  We might dabble in the other world, but mostly we specialize.  We expect our API to be a well-designed communication point between separate people or teams, and it may be reused by multiple clients.

### Technology we like
- GraphQL - an entire ecosystem of tools to decouple apps at the network boundary.
- [Swagger](https://swagger.io/) and other API documentation tools

# Parting thoughts

These are three approaches, but they aren't quite equivalent.  A hard frontend / backend split is powerful, but it comes with real communication challenges.  Most features will need changes on both sides of the API, so you'll need two specialists involved.  On the other hand, if you're supporting multiple clients and you need a stable API anyway, then it's reasonable to treat the web app as just another client.

So my general advice - to both companies and developers - is to stay "full stack" as long as you can, and draw an API boundary when you must.

When it comes to "front end" and "back end" focus - there are advantages to each, but it's mostly about aesthetics.  Each approach has its problems, but tools and techniques are filling in the gaps.

If you're an executive, go where your developers prefer.  If you're a junior developer, follow the best teachers and mentors.  And if you're like me - a mid-career developer with opinions - learn enough to appreciate both approaches.  
