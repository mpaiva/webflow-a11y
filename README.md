# webflow-a11y
Notes from my study on using Webflow as a tool for accessible prototyping.

## Getting Started
The goal of this study is to identify a tool designers can use to create accessible prototypes. This is part of the "shift-left" effort, where we bring accessibility testing as early as possible in the design process.  

### What is Webflow?
Webflow is a SaaS application that allows designers to build responsive websites with browser-based visual editing software. While designers use the tool, Webflow automatically generates HTML, CSS, and JavaScript. 

### Why Webflow?
During our discovery to identify a rapid prototyping tool that would allow designers to testing with users that rely on assistive technologies, Webflow was the only tool that gave the ability to test with screen readers, by setting landmark regions/roles and applying ARIA attributes when needed.

## Design Challenge
The goal of this study is to create a Accessible Job Listing site, where screen reader users will have a better than usual experience in the following cases:
- Wayfinding - Navigate to search without many impediments
- Search - Find a specific job posting
- Apply - Submit resume and application

### Webflow Challenges
In order for Webflow to succeed in this study, it is expected to support the following:
- Skip-links
- Named anchor links
- ARIA Landmark Roles: 
  - banner
  - form
  - region
  - search
  - navigation
  - main
- ARIA Widget Attributes
  - aria-label
  - aria-placeholder
- ARIA Relationship Attributes
  - aria-labeledby
  - aria-describedby
- ARIA Live Region Attributes
  - aria-live
  - aria-busy


## Expected Outcome
Testing the output on a screen reader is our end goal for this study, before presenting our findings to a screen reader users.

For testing with assistive technologies, it will be required to publish the prototype on a public server and test with one of the following screen readers:
- Voiceover
- NVDA
- Jaws

---

# Please contribute
Please submit any questions or feedback at our [issues page](https://github.com/mpaiva/webflow-a11y/issues/new).
