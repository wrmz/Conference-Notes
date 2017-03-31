# Design Systems: Accounting for Quantity and Scalability

__Speakers__:

- Amy Vainieri, Senior Designer at [Taoti Creative](http://www.taoti.com/)
- Courtney Clark, Managing Director of User Experience at [Forum One](https://forumone.com/)

## Takeaways

- Wireframes still come first - build the system around that
- Invest time to create a design system for faster development
- Design systems help everyone in the process get their work done

---

### Design Systems

> When a technology matures, design moves to the foreground because the underlying machinery has been commoditized.
> \- John Maeda

### How to Know You Need a Design System

If your site has 20+ button styles, you're doing something wrong.

You ned a design system if your project

- Contains overly inconsistent site elements
- Will evolve and grow over time
- Has high turnover or project-sharing

### What is a Design System

A design system is a time investment upfront allowing for fast development later in the project.

As an analogy, Taco Bell as a _food system_ with a core set of ingredients (8). They use those 8 ingredients to create 50+ menu options, which is smart for fast food. Then they rely on marketing magic to create a new product regularly.

What are our core ingredients for a design system?

1. Basics
    * Colors
    * Pattern Use
    * Icons
    * Branding
    * Typography
2. Elements
    * Buttons
        * 3 sizes, 3 styles
    * Forms, fields & submits
3. Building Blocks
    * Stat boxes
    * Calls to action
    * Quotes
    * Image galleries
    * Share bars
    * Teasers
    * Flavor and variation
    * Listing styles
    * System starts taking shape (what do articles/posts look like?)
4. Pages
    * Putting things together and making it work
    * Mixing and matching

### Extending the System

If a project evolves and styles change or new elements are needed, you may need to extend the design system. When doing this there are 3 questions you need to ask:

1. What already exists?
2. What is the significance?
3. How will it be used again in the future?

You need to _guard_ what you created, or it will unravel quickly.

### Extending Users to the System

Share the system with others. This allows the new members or those already working on the project to become familiar with and adopt rapidly to producing quick and quality work with what you've produced. When sharing it, you should have the reasons available for the decisions that were made so backtracking doesn't happen.

### Why Use a Design System

Frame your system around investment. If you invest the time in the beginning, pages will get built in 5 minutes later.

Design systems provide:

- [X] Scalability
    * You can build pages very quickly once a system is in place
- [X] Consistency
    * You get a unified user experience
- [X] Efficiency & Teamwork
    * Everyone can work on the site with a common understanding
    * Designers and developers alike can build the site much faster

### Getting Started

![Investment](https://s3.amazonaws.com/resources.sketch.cloud/private/4db442e4-8394-4fc5-8ff5-5e4a9b840f46.png?AWSAccessKeyId=AKIAIS7X2P6WUKGTP2GA&Expires=1491240457&Signature=bv9LNW0CUwy6DwzWYh5uzmAfBgM%3D)

The design system benefits User Experience, Development, Design & Branding, Governance, Project Management & Business Development.

- Be consistent
    - Files, layers & variables consistently named
- Be organized
- Document
- Communicate
- Code
    - Get to code as quickly as you can
    - The faster you get building blocks into code, the faster you can see what it will look like and get it finalized
- Decide on the afterlife / final version
    - And communicate this once decided!
- You have bigger fish to fry - either you have more important things to do (or just more things to do)

## How We Apply It

We've been trying to get better at wireframing, mocking up and prototyping, but this really gives us a framework around which we can base our strategy. It's especially important for Sheetz as a whole to apply a design system so that all of our microsites, and products align and feel cohesive. What's really great about using a design system, is that this is the __perfect__ format for Brand to weigh in and work together with us without harming the integrity of our goals, infrastructure, or wireframes. At the same time, we would gain less friction in designing our projects because of the power we can supply Brand with in having a say with the system.

At some point, we'll need to upgrade our site to angular 2. This will be cause for some rewriting because it's a different (but way better and maintainable) beast. It will be fast in completing because we already have all the work done, it just needs worded differently in the code basically. But while we're at it, we ought to consider creating a design system together with Brand based on what we already have.

We could then have a `json` file or some global sheet based on our system which can be modified as necessary and committed, so that when a style needs to change - a brand designer, UI designer or developer could perform it (so long as the change is communicated, necessary and agreed upon).