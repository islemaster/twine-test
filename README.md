# Twine Test

[Play online](https://islemaster.github.io/twine-test)

## About

Started a repo to try out out Em Lazer-Walker's [introduction to Twine development](https://dev.to/lazerwalker/a-modern-developer-s-workflow-for-twine-4imp) and building with [Tweego](https://www.motoslave.net/tweego/). This is just some experiments for now.

## Local development

1. Clone the repository
2. Install [Tweego](https://www.motoslave.net/tweego/)
3. Copy [Chapbook](https://klembot.github.io/chapbook/) 1.2.0 (included in this repo as the `storyformats/chapbook-1` directory) into your Tweego install, over the Chapbook 1.0.0 it includes by default.
4. Build locally with `tweego`.

   ```
   tweego -o example.html example.twee
   ```

   Open the output example.html in the browser to try it out.
5. Automatically rebuild on save with `--watch`.

   ```
   tweego -o example.html --watch example.twee
   ```

   You'll still have to reload the browser.
