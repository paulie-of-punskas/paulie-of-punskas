## Labas / Hello / Hallo / Grüezi / Cześć

I am Paul, and currently am working as a programmer for one of pharmaceutical companies. In the past, I had worked in finance and insurance industries as well. I like Test-Driven Development.

I am using using this as a landing page and "single source of truth" of what I am currently working on or had worked on before. I consider it as a quasi portfolio. Some of the projects might be hosted on different code forge.

All the code, I had committed here or to [Codeberg](https://codeberg.org) was written by me, with no extra help. Yep, no generative "AI", believe it or not. LLMs are nice tools, that are really helpful, however, I noticed that I forget what I write, if I use only them for coding `-_-'`.

I take ownership of what I commit and build, however can't take responsibility (here) if something is used incorrectly.

## Why some repositories contain empty files?

I am a big fan of open source, however I cannot prevent generative "AI" companies from scraping my work, using it for training LLMs and then selling it back. That's why, I collaborate mostly on private code forge or on [Codeberg](https://codeberg.org/paulie-aus-punskas). 

## What I have been working on / Finished working

### Backend + frontend:
- [track_workout](https://github.com/paulie-of-punskas/java-track_workout) - a web application used for tracking my workouts. Containerized and deployed to Azure. Stack: 
  - Java 17
    - Spring Boot 3
    - JUnit
    - Maven
  - JavaScript
  - PostgreSQL

- [my-reads](https://github.com/paulie-of-punskas/my-reads) - a web application that is used for tracking books I am reading / have read. Main rationale behind it, was that I kept forgetting the exact quotes that author wrote and which I liked.
Stack:
  - Java 21
    - Spring Boot 3 (maybe 4, soon?)
    - Maven
  - PostgreSQL
  - TypeScript 

### Utilities
- [anon-repo-code](https://github.com/paulie-of-punskas/anon-repo-code) - a CLI tool, used for emptying file content, before they are pushed to privacy and non privacy oriented repos. Stack:
  - Golang, vanilla

- [scrape_and_post](https://github.com/paulie-of-punskas/scrape_and_post) - small tool, that scrapes given websites for price change, extracts data, appends it to a CSV file and publishes it as website. Thanks to it, I saved ~150 CHF. Stack:
  - Python 3
    - BeautifulSoup
    - Flask

### DevOps
- [get-lts-versions](https://github.com/paulie-of-punskas/get-lts-versions) - a GitHub Action used for fetching Long Term Support versions from [endoflife.date](https://endoflife.date/). Stack:
  - TypeScript
 
- [gha-costs](https://github.com/paulie-of-punskas/gha-costs) - CLI app used for monitoring costs of GitHub Actions runners, CI/CD pipelines.

- [gitops-tools](https://github.com/paulie-of-punskas/gitops-tools) - a set of git ops scripts or CLI:
  - setup-java (TypeScript): setting up Java environment combined with [get-lts-versions](https://github.com/paulie-of-punskas/get-lts-versions)
  - pr-check-sha (TypeScript): check if commmitted GitHub Actions yaml files contain SHA with a semver string
  - pre-push check (Golang, CLI): scrape committed files and check if they contain commented out code
