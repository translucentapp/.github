[Translucent](https://www.translucent.app/) is the multi-entity accounting solution for SMBs.

## Background
- Translucent was founded by CEO Michael Wood, who had previously co-founded Dext/Recipt Bank, and is backed by some of the biggest names in the accounting space. 
- Launched in 2022, London-based Translucent has built a team of 32 people across Europe and has raised £2.7M pre-seed and [£5M seed](https://www.translucent.io/blog/seed).

## The problem
- Current SMB accounting systems are designed to hold the data of a single company in a single location. 
- Many SMB’s now operate multi-nationally, or have multiple entities, resulting in a company having to have many disparate copies of accounting systems - one company could be running 10+ different versions of their accounting software. 
- This results in fragmented, disconnected, and messy data, creating systemic issues, and leaves finance teams with time consuming workflows, and being overly reliant on tools like Excel to see all their data in one place.
- [Learn more](https://www.translucent.io/blog/The-Xero-Netsuite-Gap) about the problem multi-entity businesses face. 

## What we’re building
- Translucent is building the CFO Super-app to solve the everyday problems of multi-entity finance teams.
- Our solution integrates with existing accounting solutions, stores all the data in a single place, consolidates the data, and provides the toolset to enable collaboration around the data.
- Using the consolidated data, Translucent apps are tailored to multi-entity businesses. Finance teams can benefit from having multiple apps in one place, and using the same data. 
- Our list of apps is growing: [Search](https://www.translucent.io/search), [Group Reporting](https://www.translucent.io/group-reporting), [Live Sheets](https://www.translucent.io/live-sheets), [Financial Close](https://www.translucent.io/financial-close) and more to come.

## Stack stuff
- The Apps team is building a Next.js super-app running on Fly.io. We love Prisma, tRPC and have a growing component library of top-notch, accessible UI and UX. We use Postgres, Auth0 and other things that keep us productive.
- We're fully instrumented to understand how our app works (and doesn't) and are improving our internal testing and QA every week. We use Github Actions, Sentry and things like that, along with Prometheus and Grafana.
- The Platform team runs a mixed house of batchy stuff (Prefect on GKE), streaming stuff (Kafka), search indexes (Elastic) and lots of Pydantic and similar to validate models. Our goal is to scale and create incredible DX for our devs and response times for our users.
- Our APIs and data are on GKE, we replicate them with Airbyte and Snowflake. We're enabling top-notch internal BI processes, along with Data Science enrichment that we can feed back to our users.

## Join us
We're looking for exceptional people to join our team.

https://apply.workable.com/translucent/
