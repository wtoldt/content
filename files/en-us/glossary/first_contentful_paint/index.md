---
title: First Contentful Paint (FCP)
slug: Glossary/First_contentful_paint
page-type: glossary-definition
---

{{GlossarySidebar}}

**First Contentful Paint** (FCP) is when the browser renders the first bit of content from the DOM, providing the first feedback to the user that the page is actually loading. The question "Is it happening?" is "yes" when the first contentful paint completes.

_The First Contentful Paint_ timestamp is when the browser first rendered any text, image (including background images), video, canvas that had been drawn into, or non-empty SVG. This excludes any content of iframes, but includes text with pending webfonts. This is the first time users could start consuming page content.

## See also

- [`PerformancePaintTiming`](/en-US/docs/Web/API/PerformancePaintTiming)
- Related glossary terms:
  - {{Glossary("First Paint")}}
  - {{Glossary("Largest Contentful Paint")}}
  - {{Glossary("First Meaningful Paint")}}
- [First Contentful Paint](https://web.dev/articles/fcp) at web.dev
