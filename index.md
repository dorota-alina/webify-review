---
title: "My ideas for improving the Webify documentation"
menuTitle: "Webify improvements"
description: "Review the attached documentation and identify the ways in which it can be improved. The documentation is for a fictional web hosting platform. You are
provided with a welcome page and an excerpt from the technical documentation on “Split Testing”."
author: Dorota Wojcik
date: 2022-06-29
---

## Welcome page

### Layout & structure

* Get rid of the plaintext layout. A doc welcome page needs to be simple, transparent, accessible, or even catchy for the user.
* Replace the existing structure with a page consisting of a few major entry points (thumbnails / cards) representing crucial Webify categories from the user's perspective. The entry points can represent use cases, user's journeys, usage scenarios, specific operations, etc. The entry points need to be labelled with short speaking headings and supported with some nice graphics.
* At the top of the page, there's a perfect place for a stressed name/ title of the whole thing with one or two short sentences next to it, summing up the mission and idea behind the Webify doc website.

### Visuals

* It's up to UX/UI folks how to make it attractive and user-friendly.
* They can use photos, images, animations, sky is the limit here.
* Use thumbnails / cards for the entry points.
* Provide a banner at the top of the page with the tile and the page mission / synopsis / manifesto or similar.

### Language & style

* Minimize the plaintext.
* Make entry points' labels concise and speaking.
* Inside each entry points (thumbnails / cards), below the label, provide short info why the user would enter this specific doc area.
* Don't get too formal or official. Use user-friendly expressions or even user's jargon.
* Use the **bold** font for any UI elements and the `code` font for any code-originated strings.

### Technical content

No need for that on a welcome page - minimize it to the labels and their intros inside thumbnails / cards.

#### Proposed thumbnails

* Why Webify (*here, I'd include all the highlights that are actually there in the original Welcome page*)
* Getting started
* API
* Etc

### Interactivity

Provide links to

* Any documentation sets that could be of interest to the user
* Webify social media
* Webify portal
* Webify demo / sandbox
* Webify trial
* Webify GitHub

## SEO

* Don't use complex fancy words or phrases.
* Promote use of key words and expressions related to Webify and its functions.
* Shape all the textual content keeping in mind what the user might use Webify for.

## Split testing

### Layout & structure

Here are the sections I'd include in the document:

1. *Overview* - explain what this document covers and what the user will learn
2. *About Split Testing* - explain the purpose of this feature, what it's good for, how it's useful for you as a user
3. *Prerequisites* / *Before you start* - list what you need to use the feature, e.g.
   * Active Webify account
   * Git configured
4. *How it works* - explain what the feature does and how it's done
5. *Limitations* / *Restrictions* - list how the use of the feature is restricted
6. *Run a branch-based test*

   1. Provide clear steps representing specific actions that the user needs to take to operate the feature,e.g.
   2. Whenever possible, provide expected results, either descriptive or as screenshots.
   3. If needed, use *NOTE*s for providing additional information related to specific steps).

   *Example*

#### Set up your branches

      1. Deploy from a connected Git repository.
      2. Enable branch deploys.

      ***RESULT*** You have a new branch deployed in addition to your production branch.

#### Run the first test

      1. Go to the **Split Testing** tab of [your site dashboard](url) to start your first test.
      2. Choose the branches you want to perform the test with.
      3. Assign the percentage of traffic you want to send to each branch.
      4. Select **Start Test**.

      ***RESULT*** Traffic to your site is split according to the percentages you set.

      ***NOTE*** If you change the percentages, you automatically adjust the split of the traffic.

7. *Track visitors' behaviours* - provide the user with instructions on how they can use Split Testing to to track visitors across different versions of
your site. Include three alternative ways:

   1. Client-side analytics with GA
   2. Client-side analytics with Segment
   3. Client-side analytics with code injection

1. *Follow up* - provide links to docs covering ideas for next possible actions that the user might want to take.
2. *Learn more* - provide links to any other resources on Spilt Testing, client-side analytics, or the subject of this document.
3. *Related articles* - provide links to resources covering some related topics that could be of interest to the user.

### Visuals

* It's up to UX/UI folks how to make it attractive and user-friendly.
* They can use photos, images, animations, sky is the limit here.
* Use thumbnails / cards for the entry points.
* Provide a banner at the top of the page with the tile and the page mission / synopsis / manifesto or similar.

### Language & style

* Use the sentence case for headings and titles.
* Don't get too formal or official. Use user-friendly expressions or even user's jargon.
* Use the **bold** font for any UI elements and the `code` font for any code-originated strings.

### Technical content

### Interactivity

Provide links to

* Any documentation sets that could be of interest to the user
* Webify social media
* Webify portal
* Webify demo / sandbox
* Webify trial
* Webify GitHub

## SEO

* Don't use complex fancy words or phrases.
* Promote use of key words and expressions related to Split Testing and its functions.
* Shape all the textual content keeping in mind what the user might use Split Testing for.
