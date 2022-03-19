# GitHub Dramas

> Collection of dramas on GitHub (and else where)
> 
> Last update: 18 March 2022

## 2022

[March 16, 2022 | Controversial | Politics] [vue-cli](https://github.com/vuejs/vue-cli) [node-ipc](https://github.com/RIAEvangelist/node-ipc) - vue-cli dependency on node-ipc potentially overwrites user files
* Main issue on vue-cli to warn users about the impact: https://github.com/vuejs/vue-cli/issues/7054
* Original issue (some comments deleted or edited by RIAEvangelist): https://github.com/RIAEvangelist/node-ipc/issues/233
  * Commit that contains overwite logic: https://github.com/RIAEvangelist/peacenotwar/blob/5b72bd82cae6f555983a2e04821a54027a774269/index.js#L16-L29
  * Repo for the overwrite code (`protestware`): https://github.com/RIAEvangelist/peacenotwar
* snyk vulnerability alert blogpost: https://snyk.io/blog/peacenotwar-malicious-npm-node-ipc-package-vulnerability/
* HN discussion: https://news.ycombinator.com/item?id=30717382

[Jan 8, 2022 | Breaking] [colors.js Zalgo](https://github.com/Marak/colors.js) - colors.js author Marak breaking colors.js intentionally 
* Original issue (posted by author): https://github.com/Marak/colors.js/issues/285
* Commit: https://github.com/Marak/colors.js/commit/074a0f8ed0c31c35d13d28632bd8a049ff136fb6#diff-92bbac9a308cd5fcf9db165841f2d90ce981baddcb2b1e26cfff170929af3bd1R18

[Jan 5, 2022 | Breaking] [faker.js emptied](https://github.com/Marak/faker.js) - faker.js author Marak emptying faker.js intentionally 
* Empty repo: https://github.com/Marak/faker.js
* Community org faker-js fork: https://github.com/faker-js/faker.js
* Marak's GitHub account suspended after he erased his faker project: https://twitter.com/marak/status/1479200803948830724
  * HN discussion: https://news.ycombinator.com/item?id=29837473

## 2021

[Nov 4, 2021] [Malicious Takeover] [veged/coa](https://github.com/veged/coa) (Command-Option-Argument) - Malicious owner takeover of npm package
* Original issue: https://github.com/veged/coa/issues/99
* cnpm fix: https://github.com/cnpm/bug-versions/pull/157

[Jan 6, 2021 | Controversial] [The ESM move](https://github.com/sindresorhus/meta/discussions/15) - sindresorhus migrating pacakges to ESM 
* Original discussion: https://github.com/sindresorhus/meta/discussions/15
* ES Modules are terrible, actually
  * https://gist.github.com/joepie91/bca2fda868c1e8b2c2caf76af7dfcad3

[May 23, 2021 | Politics] [graphiql](https://github.com/graphql/graphiql) - Political stance
* Original commit: https://github.com/graphql/graphiql/commit/7d0b7d477195ee240e0e9ac800a00d17eb91bac4
 * MR: https://github.com/graphql/graphiql/pull/1860
 * Follow up MRs:
   * https://github.com/graphql/graphiql/pull/1867
   * https://github.com/graphql/graphiql/pull/1868
   * https://github.com/graphql/graphiql/pull/1870
 * Follw up issues:
   * https://github.com/graphql/graphiql/issues/1862
   * https://github.com/graphql/graphiql/issues/1865

[May 10, 2021 | Politics] [babel](https://github.com/babel/babel) - Funding disputes
* Original blogpost: [Babel is used by millions, so why are we running out of money?](https://babeljs.io/blog/2021/05/10/funding-update.html)
* Response by Sebastian (creator of Babel): https://twitter.com/sebmck/status/1392019586833387522
  * Response to Sebastian by Evan You(creator of Vue.js): https://twitter.com/youyuxi/status/1392088730438090756
* HN thread: https://news.ycombinator.com/item?id=27114718

## 2020

[Dec 28, 2020 | Bug] [cinnamon-screensaver](https://github.com/linuxmint/cinnamon-screensaver) - Screensaver lock by-pass via the virtual keyboard 
* Original issue: https://github.com/linuxmint/cinnamon-screensaver/issues/354

[Jun 20, 2020 | Malicious Takeover] [The Great Suspender](https://github.com/greatsuspender/thegreatsuspender) - Malicious owner takeover of Chrome extension
* Original owner takeover issue: https://github.com/greatsuspender/thegreatsuspender/issues/1175
* Malicious accusation: https://github.com/greatsuspender/thegreatsuspender/issues/1263
* HN thread: https://news.ycombinator.com/item?id=25846504

## 2019

[Oct 17, 2019 | Politics] [GitLab](https://gitlab.com/gitlab-com/www-gitlab-com) - Hiring exclusion of certain geographical regions
* Original issue: https://gitlab.com/gitlab-com/www-gitlab-com/issues/5555 (seems to be deleted, 404 now)
* Merge request: https://gitlab.com/gitlab-com/www-gitlab-com/-/merge_requests/32606
* Update blog post: https://about.gitlab.com/blog/2019/11/12/update-on-hiring/

[Feb 3, 2019 | Breaking] [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) - Terser v3.16.0 breaks webpack 
* Original issue: https://github.com/webpack-contrib/terser-webpack-plugin/issues/66
* PR to fix: https://github.com/terser-js/terser/pull/254
* Other issues:
  * https://github.com/webpack/webpack/issues/8694
  * https://github.com/facebook/create-react-app/issues/6334

## 2018

[Nov 21, 2018] [Malicious Takeover] [event-stream](https://github.com/dominictarr/event-stream) - Malicious owner takeover of npm package
* Original issue: https://github.com/dominictarr/event-stream/issues/116

[Jun 20, 2018 | Breaking] [docker.github.io](https://github.com/docker/docker.github.io) - Cannot download Docker CE without logging in 
* Original issue: https://github.com/docker/docker.github.io/issues/6910

[Aug 29, 2018 | Politics] [lerna](https://github.com/lerna/lerna) - License exclusion of certain companies
* Original PR: https://github.com/lerna/lerna/pull/1616
* Reverted via: https://github.com/lerna/lerna/pull/1633

[Sep 8, 2018 | Politics] [redis](https://github.com/antirez/redis) - Controversial terminology & wording
* Original issue: https://github.com/antirez/redis/issues/5335

---

## More dramas

HN-ratio
> Hacker News ranked by Comment/Score ratio

https://paradite.github.io/hn-ratio/
* GitHub: https://github.com/paradite/hn-ratio

## Prior arts and their issues

https://github.com/nikolas/github-drama
* No categorization or context on the drama, just links
* [Not being maintained actively](https://github.com/nikolas/github-drama/pulls)

---

PRs and issues welcomed.

If you viewing this on GitHub or any git hosting platforms, note that you are viewing a mirror. The sole source of truth resides in Zhu Liang's mind.
