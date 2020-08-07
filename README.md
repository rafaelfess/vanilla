<p align="center">
  <img width="150" src="https://github.com/undefinedbuddy/vanilla/blob/master/res/logo.svg" />
</p>
<h1 align="center">Vanilla</h1>
<p align="center">
  <i>A fast, elegant and unopinionated framework</i>
</p>

Vanilla is a framework for building instant web applications. It's fast.

## Features

- It is JIT-compiled, can run in browsers, Node, Deno, GraalVM and even Rhino.
- Hassle-free, no build tools required. No webpack or Parcel. Not even Rollup.
- Vanilla is so easy, it does not even require any specialized documentation.
- It has a larger community than any framework. In fact, more than any **programming language**.
- Does not attempt to create a whole new environment for developers. They just use it.
- Unlike mainstream frameworks/libraries, it does not _attempt_ to support browsers and engines. Instead, browsers and engines strive to support it.
- Supports [cross-framework components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) that are easy to debug.
- ES Modules is built-in and works great with HTTP 2.
- Tweakable routing with the [History](https://developer.mozilla.org/en-US/docs/Web/API/History_API) API.
- Powerful `fetch` API, so you don't need `axios` or other alternatives.
- Built-in CSS-in-JS support, although I advise against it. SSR support too.
- Built-in `map`, `filter`, `reduce`, `forEach` for FRP, so you won't need bloated RxJS observables and operations.
- Strong object APIs for creating, assigning, freezing, defining properties, and more.
- Runtime object reflection with the Reflect API.

## History

**Vanilla** was actually built in 1995 and supports event-driven, functional, imperative and even object-oriented programming. That is why it is not opinionated.

**Vanilla** was so primitive in its early days, that jQuery was created. After some time, frameworks flooded userland.

**Vanilla** eventually became powerful and started shipping powerful features. No complex tooling. No countless hours of debugging. No loopholes for complex systems.

## Framework Comparisons

### React

**React** is bloated. A typical application ships megabytes of JavaScript to the browser. Asynchronous rendering via prioritization is still a pain (and [hazardous](https://reactjs.org/blog/2018/11/27/react-16-roadmap.html#react-16x-q2-2019-the-one-with-concurrent-mode)).

**React** is pushing towards functional purity with minimal side effects, a goal they haven't realized till today.

**React** developers, meanwhile, are more interested in [Algebraic Effects](https://overreacted.io/algebraic-effects-for-the-rest-of-us/) and [making `setInterval` declarative](https://overreacted.io/making-setinterval-declarative-with-react-hooks/).

### Vue

**Vue** is a popular and overrated rip-off of React. Not much of a difference.

### Angular

**Angular**?

### Svelte

Rich said [Svelte is a programming language](https://gist.github.com/Rich-Harris/0f910048478c2a6505d1c32185b61934). Did I mention we were making _JavaScript_ framework comparisons?

If the future of bundlers is _no bundlers_, I'm sure we can agree that the future of frameworks is no frameworks.

### Preact

Vanilla has what they call a zero-cost abstraction system. That means no runtime (**0kb**). In large applications, even those few extra bytes count. With slower network, it just gets worse.

## Installation

This is the best part. You don't install it, you just start writing!

## Contributing

You don't contribute. Vanilla is stable.

## Credits

Brendan Eich (for designing the first draft).
