---
title: CLIPS Rules
aliases:
  - Home
---

This is a blank Quartz installation.
See the [documentation](https://quartz.jzhao.xyz) for how to get started.

#### Set up steps

* #todo  Edit `quartz/quartz.config.ts` to change title and base url:

```typescript
const config: QuartzConfig = {
  configuration: {
    pageTitle: "Site Template",  <---- title
    enableSPA: true,
    enablePopovers: true,
    analytics: null,
    locale: "en-US",
    baseUrl: "hello.nickmain.com/obsidian-quartz-template", <---- base url
```

* #todo  Edit `title` property of this page.
* #todo  Edit Footer.tsx to change site URL
* #todo  Enable Github Pages via Actions on Github web.