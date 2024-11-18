---
date: '2024-11-18T16:05:04+11:00'
draft: true
title: 'SUI Design System'
ShowReadingTime: true
ShowPostNavLinks: true
cover:
  image: ""
  # can also paste direct link from external site
  # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
  alt: "Live asset mapping for BlueCats"
  caption: "<text>"
  relative: false # To use relative path for cover image, used in hugo Page-bundles
---

## Improving the usability of the design system shared across SiteMinder products

---
### Roles

- Systems Designer
- Product management (UI/UX, Figma migration)
- Developer handoff (HTML/CSS)

---
### The Challenge

Coming into an established team and existing design system at SiteMinder with a fresh set of eyes, one of my tasks was to identify areas of the design workflow that could be improved. The existing system was created in Sketch and included other 3rd party tools in order to maintain the design, development, and review process. Sketch and the extra tools were leading to inefficiencies in the speed and consistency between visual design and development. My task was to identify and remove these roadblocks whilst continuing to maintain an ever growing design system.

---
### The Audit

I ran retrospective sessions with the designers in order to identify the problems they were facing and what they wanted from the design system.

IMG BE HERE

From that session three main problem areas were identified:

#### 1. The existing symbol structure and software

It led to many separate but similar symbols and made it difficult for designers to locate choose the correct one to use in their designs.

#### 2. External version control application

We ran a git style version control for our design files. It took up a lot of system resources and slowed down the responsiveness of the files themselves. Worst of all when some designers tried to revert back to a previous commit, the application did not produce a workable file.

#### 3. Clarifying design components during handoff

This last issue related to the flexibility of the design components in Sketch and how it negatively impacted the design-to-development handoff process.

---
### The Research & Actions

From these findings I looked at other, more established design systems, design programs, and blog articles to find out how others have tackled these issues previously.

IMG BE HERE

This information led me to research Figma as a design tool to solve the design component duplication and the version control performance issue. I had previous experience in Figma and some of the designers were already experimenting with it so we were able to run a pilot program of the design system for their projects.

The main way that Figma is able to solve issue **1 & 3** is the flexibility of a component and the ability to have component variants. This combined with the nesting of symbols allowed us to simplify component management on the design side, it also gave designers using the components a clear choice as to which component they should go with. When parts of the component were not fit for purpose, designers are able to remove these elements without detaching it from the parent component, which made the handoff process easier as the developers were then able to inspect the layers and see the link to the base component.

Figma also indirectly helped us to solve **issue 2** regarding version control as well. Since our existing application did not work when it was required and designers felt that it took up too much system resources to run, having a cloud design program made version control much easier. Designers are now able to use the version history controls in Figma in order to see and revert back to previous versions when needed. The drawback is that these controls are not as fine grained compared to our existing application, but it was good enough for our current workflow.

---
### Results & Takeaways

A design system is meant to help maintain design consistency, be a central repository of information for designers and developers, and help maintain an efficient design workflow. It is important to establish a consistent feedback loop from stakeholders in order to improve and rectify issues as the system grows.
After the switch from Sketch to Figma we ran Q&A sessions with the design team in order to help them get familiar with the new program. We also implemented monthly design system updates as well as a change-log inside the design file itself so that users are able to see the latest developments and if it will impact their design files.
