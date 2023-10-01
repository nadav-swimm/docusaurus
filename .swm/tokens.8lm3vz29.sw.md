---
title: Tokens
---
&nbsp;

<SwmToken path="/examples/classic/src/components/HomepageFeatures/index.js" pos="7:4:10" line-data="    title: &#39;Easy to Use&#39;,">`'Easy to Use'`</SwmToken>

<SwmToken path="/examples/classic/src/components/HomepageFeatures/index.js" pos="41:6:10" line-data="      &lt;div className=&quot;text--center&quot;&gt;">`"text--center"`</SwmToken>

<SwmToken path="/examples/classic/src/components/HomepageFeatures/index.js" pos="12:5:9" line-data="        used to get your web site up and running quickly.">`get your web`</SwmToken>

&nbsp;

<SwmToken path="/website/src/utils/jsUtils.ts" pos="10:29:32" line-data="  return arrays.reduce((a, b) =&gt; a.filter((c) =&gt; !b.includes(c)));">`includes(c)`</SwmToken>

<SwmSnippet path="/website/src/utils/jsUtils.ts" line="7">

---

&nbsp;

```typescript

// Inspired by https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore#_difference
export function difference<T>(...arrays: T[][]): T[] {
  return arrays.reduce((a, b) => a.filter((c) => !b.includes(c)));
```

---

</SwmSnippet>

&nbsp;

<SwmSnippet path="/examples/classic/src/components/HomepageFeatures/index.js" line="5">

---

&nbsp;

```javascript
const FeatureList = [
  {
    title: 'Easy to Use',
    Svg: require('@site/static/img/undraw_docusaurus_mountain.svg').default,
    description: (
      <>
        Docusaurus was designed from the ground up to be easily installed and
        used to get your web site up and running quickly.
      </>
    ),
```

---

</SwmSnippet>

<SwmMeta repo-id="Z2l0aHViJTNBJTNBZG9jdXNhdXJ1cyUzQSUzQW5hZGF2LXN3aW1t" repo-name="docusaurus"><sup>Powered by [Swimm](http://localhost:5001/)</sup></SwmMeta>
