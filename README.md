# FlavAI 🚢 (formerly Code Review GPT)

[![NPM][npm_badge]][npm]
[![Contributors][contributors_badge]][contributors]
[![Pulse][pulse_badge]][pulse]
[![License][license_badge]][license]
[![Twitter][twitter_badge]][twitter]

## Helps you ship faster

FlavAI uses Large Language Models to review code in your CI/CD pipeline. It should pick up on common issues such as:

- Exposed secrets
- Slow or inefficient code
- Potential bugs or unhandled edge cases

It can also be run locally in your command line to review staged files.

```bash
npx FlavAI review
```

## Demo

https://github.com/mattzcarey/FlavAI/assets/77928207/92029baf-f691-465f-8d15-e1363fcb808e

## Ethos 💭

- Beautiful CLI tool written in typescript and bun
- Vertically integrated into your CI/CD pipeline
- Functions as a human code reviewer, using a small set of optimised tools
- Acts as a [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) client for integration with external tools such as browser use, infrastructure deployments, observability monitoring.

## Setup Instructions 💫

See the [setup instructions](docs/setup.md) for more docs on how to set up FlavAI in your CI/CD pipeline and use it locally.

## Development 🔧

1. Clone the repository:

   ```shell
   git clone https://github.com/mattzcarey/FlavAI.git
   cd FlavAI
   ```

2. Install dependencies (we use bun but you can use npm or pnpm if you prefer):

   ```shell
   bun i
   ```

3. Set up the API key:
   - Rename the `.env.example` file to `.env`.
   - Open the `.env` file and replace `YOUR_API_KEY` with your actual OPENAI API key.

4. Run the application:

```shell
bun start
```

See the package.json file for all the npm commands you can run.

5. Make a PR 🎉

We use [release-please](https://github.com/googleapis/release-please) on this project. If you want to create a new release from your PR, please make sure your PR title follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format. The release-please bot will automatically create a new release for you when your PR is merged.

- fix: which represents bug fixes, and correlates to a patch version.
- feat: which represents a new feature, and correlates to a SemVer minor.
- feat!:, or fix!:, refactor!:, etc., which represent a breaking change (indicated by the !) and will result in a major version.

## Contributors 🙏

Thanks to our wonderful contributors!

<a href="https://github.com/mattzcarey/FlavAI/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mattzcarey/FlavAI" />
</a>

## Roadmap 🌏

Have a look at the [discussion tab](https://github.com/mattzcarey/FlavAI/discussions) for the latest chat and ideas. I am actively working on the items in [todo.md](todo.md).

## Sponsors ❤️

<a href="https://www.quivr.app/">
    <img src="https://github.com/mattzcarey/FlavAI/assets/77928207/30361248-3159-4535-8efb-b114989ae886" alt="quivr logo" width="150" height="150">
</a>

<a href="https://www.aleios.com/">
    <img src="https://github.com/mattzcarey/FlavAI/assets/77928207/a47c2460-b866-433f-a4c9-efb5737d4fed" alt="aleios logo" width="150" height="150">
</a>

## Star History ⭐️

[![Star History Chart](https://api.star-history.com/svg?repos=mattzcarey/FlavAI&type=Date)](https://star-history.com/#mattzcarey/FlavAI&Date)

<!-- Badges -->

[npm]: https://www.npmjs.com/package/FlavAI
[npm_badge]: https://img.shields.io/npm/dm/FlavAI.svg
[license]: https://opensource.org/licenses/MIT
[license_badge]: https://img.shields.io/github/license/mattzcarey/FlavAI.svg?color=blue&style=flat-square&ghcache=unused
[contributors]: https://github.com/mattzcarey/FlavAI/graphs/contributors
[contributors_badge]: https://img.shields.io/github/contributors/mattzcarey/FlavAI
[pulse]: https://github.com/mattzcarey/FlavAI/pulse
[pulse_badge]: https://img.shields.io/github/commit-activity/m/mattzcarey/FlavAI
[twitter]: https://twitter.com/intent/follow?screen_name=mattzcarey
[twitter_badge]: https://img.shields.io/twitter/follow/mattzcarey?style=social&logo=twitter
