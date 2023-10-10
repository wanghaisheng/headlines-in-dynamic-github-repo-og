support github profile and repo url


https://vercel.com/docs/functions/edge-functions/og-image-generation

https://metatags.io/?url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%2FRnIQChBqdFZPjL-cMJIAog
https://vercel.com/docs/functions/edge-functions/og-image-generation/og-image-examples#using-an-external-dynamic-image

如果把它当做一个打水印的工具，用户输入自己的url，添加 盗版必究 ，由xxx赞助发布等等呢 放置引流二维码



## deployed url


https://og.cool/github.com/wanghaisheng/headlines-in-dynamic-github-repo-og


https://headlines-in-dynamic-github-repo-og.vercel.app/github.com/wanghaisheng/headlines-in-dynamic-github-repo-og



## Introduction

**OG.cool** is a demo that shows you how you can display headlines directly inside your news article's OG image. Powered by [`@vercel/og`](https://vercel.com/docs/functions/edge-functions/og-image-generation).

Read the guide to learn more about how you can implement your own version: https://vercel.com/guides/displaying-article-headlines-in-social-previews

## How it works

To try out **OG.cool**, all you need to do is replace the `https://` (or `https://www.`) portion of the news article's URL with `https://og.cool/`.

Example:

- Original URL: https://www.nytimes.com/2023/08/23/climate/ocean-warming-fish.html
- **OG.cool** URL: https://og.cool/nytimes.com/2023/08/23/climate/ocean-warming-fish.html

The **OG.cool** URL will still redirect to the destination URL when a user clicks on it, but for bots like `TwitterBot` or `SlackBot`, they'll be shown an OG image with a nice headline in it (refer [Examples](#examples) section).

**OG.cool** currently supports the following publications:

- New York Times
- Wired
- Techcrunch
- github
- other

## Examples

### New York Times

![image](https://github.com/steven-tey/og/assets/28986134/fd79bf14-cab1-4989-a5bb-74146fa43485)

Try it for yourself: https://og.cool/nytimes.com/2023/08/23/climate/ocean-warming-fish.html ([OG image preview](https://dub.co/tools/metatags?url=https%3A%2F%2Fog.cool%2Fnytimes.com%2F2023%2F08%2F23%2Fclimate%2Focean-warming-fish.html))

### Wired

![image](https://github.com/steven-tey/og/assets/28986134/7de03193-05e0-4ee1-bb3a-45c12ed70cf7)

Try it for yourself: https://og.cool/wired.com/story/adhd-adderall-video-games-endeavorrx/ ([OG image preview](https://dub.co/tools/metatags?url=https%3A%2F%2Fog.cool%2Fwired.com%2Fstory%2Fadhd-adderall-video-games-endeavorrx%2F))
