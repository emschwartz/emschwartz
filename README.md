Hi 👋, I'm Evan Schwartz.

I'm an ideas person, aspiring inventor, and software engineer (Rust/Typescript).

When in a new environment, system, or company, I try to find what the most important problem is and then dive into working on it. My favorite thing is finding simple, clever solutions to apparently complex problems and then taking them from idea to reality. I also enjoy building community, giving presentations, and trying to explain ideas in ways that are easy to understand.

The three most significant projects I've worked on thus far are [Autometrics](#autometrics), [TurboVPB and Turbo Phonebank](#turbovpb--turbo-phonebank), and [Interledger](#interledger) (see below for the details, recorded presentations, and blog posts on each).

Outside of this, I spend time [reading](#reading) about political economy (among many other topics), running, cooking, sometimes making ceramics.


## Projects

### Autometrics

[Autometrics](https://github.com/autometrics-dev) is a set of open source libraries that make it easy to understand how code is performing in production. It enables developers to instrument functions with [Prometheus](https://prometheus.io) metrics to track the request rate, error rate, and latency of any function. The fun part is that they also insert links to live charts directly into each function's documentation so developers can jump directly from their editors to looking at the performance of their system in realtime (watch the demo [here](https://github.com/autometrics-dev)).

I came up with the initial idea for Autometrics while working at [Fiberplane](https://fiberplane.com) on how to make observability more accessible and appealing to developers. I built the first implementation in Rust ([autometrics-rs](https://github.com/autometrics-dev/autometrics-rs)) and have been collaborating with other developers inside and outside of the company to develop the concept further and create libraries in different programming languages.

#### Autometrics Videos
- [Introducing Autometrics (Apr 12, 2023)](https://youtu.be/Slnjt1TPDBo)

#### Autometrics Blog Posts

- [When can you add Prometheus labels without increasing cardinality? (Jul 12, 2023)](https://fiberplane.com/blog/when-can-you-add-prometheus-labels-without-increasing-cardinality)
- [Why are Prometheus queries hard? (Jul 4, 2023)](https://fiberplane.com/blog/why-are-prometheus-queries-hard)
- [autometrics-rs 0.5: Automatically connecting Prometheus metrics to traces (Jun 21, 2023)](https://fiberplane.com/blog/autometrics-rs-0-5-automatically-connecting-prometheus-metrics-to-traces)
- [autometrics-rs 0.4: Spot Commits That Introduce Errors or Slow Down Your Application (Apr 27, 2023)](https://fiberplane.com/blog/autometrics-rs-0-4-spot-commits-that-introduce-errors-or-slow-down-your-application)
- [Autometrics: a developer-first observability framework that writes queries for you (Apr 13, 2023)](https://fiberplane.com/blog/autometrics-a-developer-first-observability-framework-that-writes-queries-for-you)
- [The Case for Function-Level Metrics: An observability sweet spot that balances debuggability, cost, and ease of use (Apr 12, 2023)](https://fiberplane.com/blog/the-case-for-function-level-metrics)
- [autometrics-rs 0.3: Defining Service-Level Objectives (SLOs) in Rust Source Code (Mar 22, 2023)](https://fiberplane.com/blog/autometrics-rs-0-3-defining-service-level-objectives-in-rust-source-code)
- [An adventure with SLOs, generic Prometheus alerting rules, and complex PromQL queries (Mar 16, 2023)](https://fiberplane.com/blog/an-adventure-with-slos-generic-prometheus-alerting-rules-and-complex-promql-queries)


### TurboVPB & Turbo Phonebank

While taking time off in-between jobs, I got involved with the [Sunrise Movement](https://www.sunrisemovement.org/) doing phonebanking for climate-focused, progressive political candidates in the US. I was frustrated by how manual some of the phone calling platforms were and decided to build a browser extension, [TurboVPB](https://turbovpb.com), to speed up these calls.

I'm proud to say that TurboVPB has been used to place more than 5 million calls and send more than 500,000 text messages -- and counting.

Based on the experience of building this browser extension, I also built a standalone phonebanking platform called [Turbo Phonebank](https://turbophonebank.com) (using Typescript, Preact, Supabase, and Vercel). This has been used to contact more than 50,000+ people.

#### TurboVPB Videos

- [TurboVPB | Speed up phone banking with OpenVPB, VAN, and BlueVote -- Call and text with 2 clicks! (Oct 3, 2020)](https://youtu.be/B3QotZgtmF4)
- [TurboVPB | 2-Minute Setup (Oct 3, 2020)](https://youtu.be/TjR4veiOdvo)
- [TurboVPB | 2-Click Texting (Oct 3, 2020)](https://youtu.be/VXVqJ8py4FQ)

### Interledger

[Interledger](https://interledger.org) is a protocol for routing money across payment networks, akin to packet switching on the internet. While working at [Ripple](https://ripple.com), the then-CTO, Stefan Thomas, and I co-invented Interledger to enable interoperability between disparate financial networks and ledgers. I helped develop the [initial concept](https://interledger.org/interledger.pdf), [core protocols](https://github.com/interledger/rfcs), [reference implementation](https://github.com/interledgerjs) in Typescript, and then led the [reimplementation in Rust](https://github.com/interledger/interledger-rs). I currently serve on the board of the Interledger Foundation.

#### Interledger Presentations
- [State of the Interledger @ the Interledger Summit (Apr 5, 2019)](https://youtu.be/HTXLAM3PCUY)
- [Interledger in Rust Workshop @ the Interledger Summit (Apr 5, 2019)](https://youtu.be/m4t1EJPcxuA)
- [Interledger Protocol & Streaming Payments (May 16, 2018)](https://youtu.be/gqjXWI8Jyko)
- [Building with ILP (July 2016)](https://youtu.be/JCbuaAMYvrs)
- [How it [Interledger] Works (July 2016)](https://youtu.be/6sg62TAng1U)
- [Building the Internet of Payments with Interledger @ Epicenter Podcast (May 17, 2016)](https://youtu.be/izon3JJRs5w)
- [Content Micropayments (Feb 2016)](https://youtu.be/OIpgP7OaB-o)
- [Interledger Overview @ the 1st Interledger Workshop (Feb 2016)](https://youtu.be/UdCxrqP6w3I)

#### Interledger Blog Posts

- [Thoughts on Scaling Interledger Connectors: How I Learned to Stop Worrying and Love HTTP (Jan 23, 2019)](https://medium.com/interledger-blog/thoughts-on-scaling-interledger-connectors-7e3cad0dab7f)
- [Layer 3 Is for Interoperability: The Protocol Stack for the Internet of Value (Oct 30, 2018)](https://medium.com/xpring/layer-3-is-for-interoperability-ca387fa5f7e2)
- [Interledger: How to Interconnect All Blockchains and Value Networks (Oct 3, 2018)](https://medium.com/xpring/interledger-how-to-interconnect-all-blockchains-and-value-networks-74f432e64543)
- [STREAMing Money and Data Over ILP (May 18, 2018)](https://medium.com/interledger-blog/streaming-money-and-data-over-ilp-fabd76fc991e)
- [Simplifying Interledger: The Graveyard of Possible Protocol Features (Jan 29, 2018)](https://medium.com/interledger-blog/simplifying-interledger-the-graveyard-of-possible-protocol-features-b35bf67439be)
- [A Protocol for Interledger Payments (Original Whitepaper - Oct 6, 2015)](https://interledger.org/interledger.pdf)

## Other Presentations

- [Are We Web Yet? Our Journey to Axum [the Rust web framework] (May 24, 2022)](https://youtu.be/5l7WUXaaHzA)


## Other Writing

- [Getting Past “Ampersand-Driven Development” in Rust: A little mental model for ownership and borrowing (Mar 9, 2023)](https://fiberplane.com/blog/getting-past-ampersand-driven-development-in-rust)
- [Why we chose Jsonnet over WebAssembly for Fiberplane Templates (Jul 26, 2022)](https://fiberplane.com/blog/why-we-chose-jsonnet-over-webassembly)

## Reading

These are some of the books I've read that were particularly excellent, interesting, and/or perspective-altering (roughly in reverse chronological order of when I read them):

- _In the Garden of Beasts: Love, Terror, and an American Family in Hitler's Berlin_ - Erik Larson
- _Entangled Life: How Fungi Make Our Worlds, Change Our Minds, and Shape Our Futures_ - Merlin Sheldrake
- _The Mountains Sing_ - Nguyễn Phan Quế Mai
- _The World for Sale: Money, Power, and the Traders Who Barter the Earth's Resources_ - Javier Blas, Jack Farchy
- _Moneyland: Why Thieves And Crooks Now Rule The World And How To Take It Back_ - Oliver Bullough
- _The Three-Body Problem_ (series) - Cixin Liu
- _The Entrepreneurial State: Debunking public vs. private sector myths_ - Mariana Mazzucato
- _The Passions and the Interests: Political Arguments for Capitalism before Its Triumph_ - Albert O. Hirschman
