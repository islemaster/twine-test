# Twine Test

[Play online](https://islemaster.github.io/twine-test)

## About

Started a repo to try out out Em Lazer-Walker's [introduction to Twine development](https://dev.to/lazerwalker/a-modern-developer-s-workflow-for-twine-4imp) and building with [Tweego](https://www.motoslave.net/tweego/). This is just some experiments for now.

## Local development

1. Clone the repository
2. Install [Tweego](https://www.motoslave.net/tweego/)
3. Copy [Chapbook](https://klembot.github.io/chapbook/) 1.2.0 (included in this repo as the `storyformats/chapbook-1` directory) into your Tweego install, over the Chapbook 1.0.0 it includes by default.
4. Start local test builds that will auto-rebuild on save with `--test` and `--watch`.

   ```
   tweego -o example.html --watch --test example.twee
   ```

   Open the generated example.html file in your browser to try it out. You'll have to reload your browser after you make changes to the story.
