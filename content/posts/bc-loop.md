---
date: '2024-11-18T16:05:36+11:00'
draft: true
title: 'Bc Loop'
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

# Scanning & Asset Association App
A companion app for an industrial track & trace location platform

## Areas:

- Research & developing user personas
- Taskflow creation (whimsical)
- Wireframing & UI (whimsical & XD)
- Prototyping & user testing (XD)
- Developer hand-off (XD & Zeplin)

## Overview

As BlueCats expands it’s RTLS (real time location service) product offering to other industries the company focused its effort into creating a white-label app that help operators connect assets in the real world to the BlueCats Loop Platform.
This business problem stems from the users’ need to quickly assign and attach a beacon/tag to the asset they wish to track. This app will be provided to existing customers who is using an interim solution and new customers as well. In order to reduce the dev time this app needs to have flexibility in mind – being able to easily adapt to different scanning workflows with minimal design/dev effort.
Discovery

After the initial brief, several flowcharts were create to map out the user journey and tasks they had to undertake, how they could succeed, fail and what happens when they fail:

From the flowcharts above we then went into wireframes to assess the components required, combining those scenarios into an app layout:

---
## Prototype & Testing

From the behavioural patterns gathered and initial task flow sketches we moved to creating interactive prototypes in XD. A technological constraint we came up against in this project was the use of the Xamarin Forms library as a base as we needed to create an app that can be deployed on both Android and iOS without rewriting the code – the good side is the devs only needs to work on one project for both versions, but we lose some native features or have to build those from scratch.
 
Luckily Grial Kit offered a good starting point to learn from to see what has been achieved with the library on both design and development terms. We tailored some aspects of the UI and interactions in order to reduce the development time.
 
We then went ahead to create all the possible paths a user could take:

---
## Challenges

Bringing existing workflows into a white-label app design can create some unique difficulties, one such example is we only had support for associating between 1 tag with 1 object but later found out the need to support:
- Many-to-1 associations
- Mass removal of associations

Thankfully our app structure was robust enough to handle these workflows with minimal changes. In order to overcome this workflow issue we took inspiration from Instagram, Google Lens, and the bar code scanner on the Amazon app. Our solution was to add a task switcher in the Scan Mode, similar to how you switch Instagram Live filters in order to keep the workflow and structure consistent to what has already been designed.

---
## Conclusion

There has been general positive user feedback since the release of the app to internal and external test users. From their usage and comments we are continually making improvements and incorporating other workflows based on the functionalities that are being added to the Loop Platform.

