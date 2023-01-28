# steebe

A revamping of Steve Bass’ personal site, using Gatsby.

### Release Notes
- `1.0.0`: Bootstrapping Gatsby
   - Basic tweaks to the default styles and mechanisms leveraged to get a site off the ground, in the way I want it 
     to look
- `1.1.0`: Upgrading Gatsby to 5.5, and its supporting libraries accordingly
   - [Upgrade guide](https://www.gatsbyjs.com/docs/reference/release-notes/migrating-from-v4-to-v5/)
   - [MDX Plugin Upgrade](https://www.gatsbyjs.com/plugins/gatsby-plugin-mdx/)
   - [Important hack for MDX](https://paulie.dev/posts/2022/09/mdx-2-breaking-changes-and-gatsby-plugin-mdx-v4-slug/)
      - Additional workaround: {mdx.slug}.tsx --> {mdx.fields__slug}.tsx 

### Diary

After many months since switching to Gatsby from a [pure HTML site](https://github.com/steebe/site-archive) with a
basic sibling [Jekyll blog](https://github.com/steebe/steebe.github.io), I decided to keep my React chops up by giving
Gatsby a try. I have been fortunate enough to have received some experience with Next.js. First on a side project, and
then at work. My experience with Vercel's baby exposed me to the overarching JavaScript/TypeScript community more than I
appreciated at the time, and I built a fairly foundational awareness of the alternative and up-and-coming frameworks and
tools such as Gatsby and Svelte.

I was aware of Gatsby's potential. Raw power, fueled by GraphQL and a ferocious community. Power that promised a simple
development experience for a complex and capable result: a static site on steroids.

Perhaps it was my stellar experience working with Next.js that got my hopes up for Gatsby, but I was shocked at a few 
attributes I noticed out of the gate:
- Complex
   - The docs to get things off the ground were (at the time, with Gatsby v4) absolutely massive. Nothing was simple.
- Scattered
   - For a framework that claims to offer so much, its functionality sure seemed to not be in one place. Plugins galore 
power this beast.
- Ever breaking
  - Each major release (and yes, I understand the point of marking  a release as "major", thank you) contains massive
breaking changes. The more plugins you use for functionality that's core to Gatsby, the longer it will take to address
such changes.
- Not my job
  - I've encountered a few scenarios, mostly within the "getting started" guides or upgrade guides, in which the author
of the guide offered no tangible understanding to a step or workaround, and rather linked to a library or listed steps
provided by a community developer. Obviously, that's how the realm of programming gets things done in general (on top of
existing solutions), it just feels lazy that a guide would be a place where an author cops out.


### Technologies
- Gatsby
- Node.js