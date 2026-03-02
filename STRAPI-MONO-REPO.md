<p align="center">
  <a href="https://strapi.io/#gh-light-mode-only">
    <img src="https://strapi.io/assets/strapi-logo-dark.svg" width="318px" alt="Strapi logo" />
  </a>
  <a href="https://strapi.io/#gh-dark-mode-only">
    <img src="https://strapi.io/assets/strapi-logo-light.svg" width="318px" alt="Strapi logo" />
  </a>
</p>

<h3 align="center">Open-source headless CMS, self-hosted or Cloud you're in control.</h3>
<p align="center">The leading open-source headless CMS, 100% JavaScript/TypeScript, flexible and fully customizable.</p>
<p align="center"><a href="https://docs.strapi.io">Docs</a> · <a href="https://strapi.io/cloud">Strapi Cloud</a> · <a href="https://feedback.strapi.io">Roadmap</a> · <a href="https://discord.strapi.io">Discord</a> · <a href="https://github.com/strapi/strapi/discussions">Discussions</a></p>

<p align="center">
  <a href="https://www.npmjs.org/package/@strapi/strapi">
    <img src="https://img.shields.io/npm/v/@strapi/strapi/latest.svg" alt="NPM Version" />
  </a>
  <a href="https://github.com/strapi/strapi/actions/workflows/tests.yml">
    <img src="https://github.com/strapi/strapi/actions/workflows/tests.yml/badge.svg?branch=main" alt="Tests" />
  </a>
  <a href="https://discord.strapi.io">
    <img src="https://img.shields.io/discord/811989166782021633?label=Discord" alt="Strapi on Discord" />
  </a>
  <a href="https://github.com/strapi/strapi/actions/workflows/nightly.yml">
    <img src="https://github.com/strapi/strapi/actions/workflows/nightly.yml/badge.svg" alt="Strapi Nightly Release Build Status" />
  </a>
</p>

<br>

Strapi is an open-source, self-hosted headless CMS that lets developers build content APIs fast while giving content creators a friendly editing interface. Define your content models and Strapi generates a full API, ready to consume from any frontend, mobile app, or IoT device.

- Design content structures visually with the [**Content-Type Builder**](https://docs.strapi.io/cms/features/content-type-builder), no code required
- Auto-generated [**REST**](https://docs.strapi.io/cms/api/rest) & [**GraphQL**](https://docs.strapi.io/cms/plugins/graphql) APIs for every content type
- Granular [**Roles & Permissions**](https://docs.strapi.io/cms/features/users-permissions) out of the box
- Built-in [**Media Library**](https://docs.strapi.io/cms/features/media-library), [**Internationalization (i18n)**](https://docs.strapi.io/cms/features/internationalization), and [**Draft & Publish**](https://docs.strapi.io/cms/features/draft-and-publish)
- First-class **TypeScript** support with flexible database options (SQLite, PostgreSQL, MySQL, MariaDB)
- Extensible [**plugin system**](https://docs.strapi.io/cms/plugins) and customizable admin dashboard

> Explore all features at **[strapi.io/features](https://strapi.io/features)**

## Getting Started

<a href="https://docs.strapi.io/developer-docs/latest/getting-started/quick-start.html" target="_blank">Read the Getting Started tutorial</a> or follow the steps below:

### ⏳ Installation

Use the **Quickstart** command below to create a new Strapi project instantly:

- We recommend using **yarn** to create a Strapi project.
  [View yarn installation docs](https://yarnpkg.com/lang/en/docs/install/).

**yarn**
```bash
yarn create strapi my-project
```

**npx**
```bash
npx create-strapi@latest my-project
```

**pnpm**
```bash
pnpm create strapi@latest my-project
```

This command generates a brand new project with the default features (authentication, permissions, content management, content type builder & file upload).

> Full installation options (including TypeScript, `--quickstart`, etc.) in the **[CLI installation docs](https://docs.strapi.io/cms/installation/cli#creating-a-strapi-project)**

### Requirements

> Hardware & software requirements (OS, Node.js, databases) at **[Requirements docs](https://docs.strapi.io/cms/deployment#hardware-and-software-requirements)**

## Docker

Strapi doesn't ship official Docker images, so you build your own from your project. The fastest way to get started is with the community CLI tool:

```bash
npx @strapi-community/dockerize@latest
```

This generates a `Dockerfile` and `docker-compose.yml` tailored to your project. See the [strapi-tool-dockerize](https://github.com/strapi-community/strapi-tool-dockerize) repo for more details.

> Dockerfiles, Docker Compose examples, production builds at **[Docker installation docs](https://docs.strapi.io/cms/installation/docker)**

## Deploy to Strapi Cloud

The fastest way to go from local to production. Strapi Cloud is the official managed hosting platform with zero DevOps, a built-in database, media library, and CDN.

> [**Deploy now**](https://cloud.strapi.io)

## LaunchPad

The official demo template combining Strapi with Next.js to get you started quickly.

> [**LaunchPad template**](https://github.com/strapi/LaunchPad)

## Strapi AI

Strapi AI is the built-in intelligence layer that automates repetitive tasks across the CMS, from content modeling to media metadata to translations. Generate schemas from natural language, Figma, or frontend code. Auto-generate alt text and captions on upload. Auto-translate content across all your locales on save. Available on the Growth plan.

> Full details on Strapi AI at **[strapi.io/ai](https://strapi.io/ai)**

## Repositories

| Repository | Description |
|------------|-------------|
| [**strapi/strapi**](https://github.com/strapi/strapi) | Core monorepo, the CMS itself |
| [**strapi/design-system**](https://github.com/strapi/design-system) | Strapi Design System, React component library |
| [**strapi/LaunchPad**](https://github.com/strapi/LaunchPad) | Demo app: Strapi + Next.js |

## Contributing

Strapi is community-built and open source. There are many ways to get involved:

- **[Discord](https://discord.strapi.io)**: Chat with the community and core team
- **[Discussions](https://github.com/strapi/strapi/discussions)**: Ask questions, share projects, get feedback
- **[Community Content](https://github.com/strapi/community-content)**: Showcase, tutorials, starters, and templates
- **[Contributing Guide](https://contributor.strapi.io/)**: How to contribute code, docs, and translations

New to open source? Check out [How to Contribute to Open Source](https://opensource.guide/).

## Community support

For general help using Strapi, please refer to [the official Strapi documentation](https://docs.strapi.io). For additional help, you can use one of these channels to ask a question:

- [Discord](https://discord.strapi.io) (For live discussion with the Community and Strapi team)
- [GitHub](https://github.com/strapi/strapi) (Bug reports, Contributions)
- [GitHub Discussions](https://github.com/strapi/strapi/discussions) (Questions and Discussions)
- [Feedback section](https://feedback.strapi.io) (Roadmap, Feature requests)
- [Twitter](https://twitter.com/strapijs) (Get the news fast)
- [YouTube Channel](https://www.youtube.com/strapi) (Learn from Video Tutorials)

## Migration

Follow our [migration guides](https://docs.strapi.io/developer-docs/latest/update-migration-guides/migration-guides.html) on the documentation to keep your projects up-to-date.

## Roadmap

Check out our [roadmap](https://feedback.strapi.io) to get informed of the latest features released and the upcoming ones. You may also give us insights and vote for a specific feature.

## Documentation

See our dedicated [repository](https://github.com/strapi/documentation) for the Strapi documentation, or view our documentation live:

- [Developer docs](https://docs.strapi.io/developer-docs/latest/getting-started/introduction.html)
- [User guide](https://docs.strapi.io/user-docs/latest/getting-started/introduction.html)
- [Cloud guide](https://docs.strapi.io/cloud/intro)

## Try live demo

See for yourself what's under the hood by getting access to a [hosted Strapi project](https://strapi.io/demo) with sample data.

## Security

If you discover a security issue, please report it responsibly. See our [Security Policy](https://github.com/strapi/strapi/blob/develop/SECURITY.md) for our disclosure process and contact info.

## About Strapi

- **[Company Handbook](https://handbook.strapi.io)**: Our values, how we work, and more
- **[About Us](https://strapi.io/about-us)**: The story of Strapi

[Contact us](https://strapi.io/contact)

## Support Strapi

If Strapi is useful to you, give us a star:

- **[Star us on GitHub](https://github.com/strapi/strapi)**: It helps more than you think!

## Thanks to All Contributors

Thank you to everyone who has contributed code, reported issues, and helped shape Strapi.

[![Strapi contributors](https://contrib.rocks/image?repo=strapi/strapi&max=400&columns=20)](https://github.com/strapi/strapi/graphs/contributors)

## License

See the [LICENSE](./LICENSE) file for licensing information.

---

[Website](https://strapi.io) · [Docs](https://docs.strapi.io) · [Blog](https://strapi.io/blog) · [Twitter](https://twitter.com/strapijs) · [LinkedIn](https://www.linkedin.com/company/strapi/)
