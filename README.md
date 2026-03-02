# Strapi

### 🚀 The leading open-source headless CMS — 100% JavaScript/TypeScript, fully customizable and developer-first.

[Docs](https://docs.strapi.io) · [Strapi Cloud](https://strapi.io/cloud) · [Roadmap](https://feedback.strapi.io) · [Discord](https://discord.strapi.io) · [Forum](https://forum.strapi.io)

[![GitHub stars](https://img.shields.io/github/stars/strapi/strapi?style=flat&logo=github&colorB=7B2BFC)](https://github.com/strapi/strapi/stargazers)
[![npm version](https://img.shields.io/npm/v/@strapi/strapi.svg?style=flat&colorB=7B2BFC)](https://www.npmjs.com/package/@strapi/strapi)
[![npm downloads](https://img.shields.io/npm/dm/@strapi/strapi.svg?style=flat&colorB=7B2BFC)](https://www.npmjs.com/package/@strapi/strapi)
[![License](https://img.shields.io/badge/license-SEE%20LICENSE-7B2BFC.svg)](https://github.com/strapi/strapi/blob/main/LICENSE)
[![Discord](https://img.shields.io/discord/811989166782021633?label=Discord&logo=discord&colorB=7B2BFC&logoColor=white)](https://discord.strapi.io)

---

Strapi's story started on GitHub on October 1, 2015. Since that first commit, 36,000+ others followed, more than 9,400 pull requests have been merged, and the project has earned 70K+ GitHub stars 🤯 The majority of [milestones associated pull requests](https://github.com/strapi/strapi/milestones) come from the Strapi community and we can't be more proud of it 🙏

We strive every day to create the best Open-Source and Self-Hosted Headless CMS to allow Developers as well as Content Creators to Unleash Content 💪

---

## ⚡ Quick Start

Get a Strapi project running in seconds:

**npx**
```bash
npx create-strapi@latest my-project
```

**pnpm**
```bash
pnpm create strapi@latest my-project
```

**yarn**
```bash
yarn create strapi my-project
```

> 📖 Full installation options (including TypeScript, `--quickstart`, etc.) → **[Installation — CLI docs](https://docs.strapi.io/cms/installation/cli#creating-a-strapi-project)**

---

## 🐳 Docker

Strapi doesn't ship official Docker images — you build your own from your project. The fastest way to get started is with the community CLI tool:

```bash
npx @strapi-community/dockerize@latest
```

This generates a `Dockerfile` and `docker-compose.yml` tailored to your project. Or you can write your own Dockerfile using the templates in the docs. See the [strapi-tool-dockerize](https://github.com/strapi-community/strapi-tool-dockerize) repo for more details.

> 📖 Dockerfiles, Docker Compose examples, production builds → **[Docker installation docs](https://docs.strapi.io/cms/installation/docker)**

---

## ☁️ Deploy to Strapi Cloud

The fastest way to go from local to production. Strapi Cloud is the official managed hosting platform — zero DevOps, built-in database, media library and CDN.

**One-click deploy from your dashboard:**

> [**Deploy now →**](https://cloud.strapi.io)

**Or use the Strapi Deploy CLI:**

```bash
npx strapi deploy
```

> 🚀 Want a head start? Try **[LaunchPad](https://github.com/strapi/LaunchPad)** — the official Strapi + Next.js demo app, ready to deploy in one click.
>
> 📖 Deployment guides (AWS, Azure, DigitalOcean, self-hosted) → **[Deployment docs](https://docs.strapi.io/cms/deployment)**
>
> Hardware & software requirements → **[Requirements](https://docs.strapi.io/cms/deployment#hardware-and-software-requirements)**

---

## ✨ Features

| Feature | Description | Docs |
|---------|-------------|------|
| **Content-Type Builder** | Build your data structure visually — no code required | [Docs →](https://docs.strapi.io/cms/features/content-type-builder) |
| **Content Manager** | Create, edit, draft and publish any content | [Docs →](https://docs.strapi.io/cms/features/content-manager) |
| **REST & GraphQL APIs** | Auto-generated, fully customizable APIs | [REST →](https://docs.strapi.io/cms/api/rest) · [GraphQL →](https://docs.strapi.io/cms/api/graphql) |
| **Roles & Permissions** | Fine-grained access control for admins and end-users | [Docs →](https://docs.strapi.io/cms/features/users-permissions) |
| **Media Library** | Upload, organize and transform images, videos and files | [Docs →](https://docs.strapi.io/cms/features/media-library) |
| **Internationalization (i18n)** | Manage content in multiple locales | [Docs →](https://docs.strapi.io/cms/features/internationalization) |
| **Draft & Publish** | Stage content before going live | [Docs →](https://docs.strapi.io/cms/features/draft-and-publish) |
| **Custom Plugins** | Extend Strapi with your own plugins or install from the marketplace | [Docs →](https://docs.strapi.io/cms/plugins) |
| **TypeScript Support** | First-class TypeScript support out of the box | [Docs →](https://docs.strapi.io/cms/typescript) |
| **Database Flexibility** | SQLite, PostgreSQL, MySQL, MariaDB | [Docs →](https://docs.strapi.io/cms/configurations/database) |
| **Live Preview** | See content changes in real time as you edit, right in the admin panel | [Docs →](https://docs.strapi.io/cms/features/preview) |
| **Customizable Dashboard** | Drag-and-drop homepage widgets tailored to your workflow | [Docs →](https://docs.strapi.io/cms/features/homepage) |

---

## 🤖 Strapi AI

Strapi AI is the built-in intelligence layer that automates repetitive tasks across the CMS — from content modeling to translations. Available on the Growth plan.

- **AI Content-Type Builder** — Describe your project in plain language, upload a Figma file, or point to an existing frontend app, and Strapi AI generates Collection Types, Single Types, Components, and relationships for you. Hours of manual schema work reduced to minutes. [Learn more →](https://strapi.io/blog/introducing-strapi-ai)
- **AI Media Library** — Automatically generates alt text and captions on image upload, in bulk. Fully editable, enabled by default. Better accessibility and SEO with zero extra effort. [Learn more →](https://strapi.io/blog/strapi-ai-is-now-generally-available)
- **AI Translations** — Edit and save in your default locale, and Strapi AI auto-translates all other locales — including dynamic zones and blocks. Launch new markets in hours, not weeks. [Learn more →](https://strapi.io/blog/shipping-faster-with-strapi-ai-translations-and-more-homepage-customizations)

> 📖 Full details on Strapi AI → **[Strapi AI docs](https://docs.strapi.io/cms/features/strapi-ai)**

---

<!-- TODO: [TO DISCUSS] Architecture diagram
Consider including a cleaner version of the architecture overview:
https://delicate-dawn-ac25646e6d.media.strapiapp.com/Strapi_Architecture_0f03d820f5.png
-->

## 🏗️ Repositories

| Repository | Description |
|------------|-------------|
| [**strapi/strapi**](https://github.com/strapi/strapi) | Core monorepo — the CMS itself |
| [**strapi/parts**](https://github.com/strapi/parts) | Strapi Design System — React component library |
| [**strapi/strapi-docker**](https://github.com/strapi/strapi-docker) | Official Docker images |
| [**strapi/LaunchPad**](https://github.com/strapi/LaunchPad) | Demo app — Strapi + Next.js |
| [**strapi/rfcs**](https://github.com/strapi/rfcs) | Request For Comments — help shape the future of Strapi |

<!-- TODO: [TO DISCUSS] Examples repository
Consider adding an /examples directory similar to:
https://github.com/payloadcms/payload/tree/main/examples
-->

[Browse all repositories →](https://github.com/orgs/strapi/repositories)

---

## 🤝 Community & Contributing

Strapi is built in the open by a diverse global community. There are many ways to get involved:

- **[Discord](https://discord.strapi.io)** — Chat with the community and core team
- **[Forum](https://forum.strapi.io/)** — Ask questions, share projects, get feedback
- **[Community Content](https://github.com/strapi/community-content)** — Showcase, tutorials, starters, and templates
- **[Awesome Strapi](https://github.com/strapi/awesome-strapi)** — Curated list of community resources
- **[Contributing Guide](https://contributor.strapi.io/)** — How to contribute code, docs, and translations

New to open source? Check out [How to Contribute to Open Source](https://opensource.guide/).

<!-- TODO: [TO DISCUSS] Community Org & Partner Program
Add a CTA for the Strapi Community Organization and/or Partner Program here?
-->

<!-- TODO: [TO DISCUSS] "Made with Strapi" badge
Offer a badge option for projects built with Strapi, e.g.:
[![Made with Strapi](https://img.shields.io/badge/Made%20with-Strapi-7B2BFC.svg)](https://strapi.io)
-->

---

## 🔐 Security

<!-- TODO: [TO DISCUSS] SECURITY.md & reporting process
Consider adding:
- Link to SECURITY.md with responsible disclosure policy
- Security contact email (e.g., security@strapi.io)
- Instructions for reporting vulnerabilities
-->

If you discover a security issue, please report it responsibly. See [SECURITY.md](./SECURITY.md) for our disclosure policy.

---

## 😃 We're Hiring

Strapi is a limitless product built in the open by a diverse and vibrant team from around the world.

- **[Careers](https://strapi.io/careers)** — Open positions
- **[Company Handbook](https://handbook.strapi.io)** — Our values, how we work, and more
- **[About Us](https://strapi.io/about-us)** — The Story of Strapi

[Contact us →](https://strapi.io/contact)

---

## ⭐ Support Strapi

If Strapi is helping you build something great, show some love:

- **[⭐ Star us on GitHub](https://github.com/strapi/strapi)** — it helps more than you think!

<!-- TODO: [TO DISCUSS] GitHub Sponsors
- **[❤️ Sponsor the project](https://github.com/sponsors/strapi)** — help sustain the open-source mission
-->

---

## 🙏 Thanks to All Contributors

None of this would be possible without our amazing community. Thank you to everyone who has contributed code, reported issues, and helped shape Strapi into what it is today.

[![Strapi contributors](https://contrib.rocks/image?repo=strapi/strapi&max=400&columns=20)](https://github.com/strapi/strapi/graphs/contributors)

---

[Website](https://strapi.io) · [Docs](https://docs.strapi.io) · [Blog](https://strapi.io/blog) · [Twitter](https://twitter.com/strapijs) · [LinkedIn](https://www.linkedin.com/company/strapi/)