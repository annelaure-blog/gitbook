---
icon: code
layout: editorial
---

# "Readme Refactored": A Peek at the New Features for Documenting APIs in 2025

## <mark style="color:purple;">What is Readme.com?</mark>

[Readme.com](https://readme.com/) is one of the most popular CMS out there to build developer portals. It features interactive API references, guides, recipes, changelogs and more.&#x20;

It is very easy to use for non-technical people (everything can be set up and edited from a quite straightforward back-office space), and provides a few interesting features such as:

* [x] an interactive API Spec display (where users can perform live tests),
* [x] a built-in glossary,&#x20;
* [x] a search function,&#x20;
* [x] a "suggest edit" feature,
* [x] a solid versioning tool,&#x20;
* [x] a reusable content feature, etc.

I have used Readme for about half of the projects I have worked on as a freelance technical writer, and for most companies I find it to be a very good fit to manage large groups of users, multiple projects, as well as massive amounts of pages and big API specs in one back-office.

Yet, Readme was not - so far - made for docs-as-code processes. It did not allow synchronizing with GitHub, so all edits had to be made through the back-office itself (where sometimes people struggle to log into), and there was no simple option to have a back-up on GitHub or to download the documentation's content all at once.&#x20;

Good news, Readme.com announced a bunch of new exciting featured to come in 2025, which I look forward to having available for my clients, and for me in my daily tasks.&#x20;

It is called "Readme Refactored", and below is a breakdown of the most exciting changes to come.

***

## <mark style="color:purple;">A peek at Readme new features</mark>

{% embed url="https://www.youtube.com/watch?v=CIhJ1uWyLhk" %}

While not thrilled by the use of a live animal to perform this awkward announcement ceremony, I was by the following features.

***

### <mark style="color:purple;">Editing & Viewing from the same interface</mark>

All changes can now be done from one single interface (instead of having to go back and forth between the back-office and the front). This means the switch is easy and fast, whether you need to quickly fix a typo or edit a full section of the page. It can all happen in the same tab.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>The "View mode"</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p>The "Edit" mode</p></figcaption></figure>

***

### <mark style="color:purple;">MdX Editor</mark>

The editor is now MdX instead of Markdown, which means we can now incorporate interactive components in the content of pages such as cards, interactive tabs, etc.&#x20;

Readme were kind enough to provide three built-in components: accordion, cards, columns and tabs - but we can add custom ones too. Those add a bit of visual and interactive diversity to the content of the pages that were - so far - pretty basic.&#x20;

<div align="center"><figure><img src="../.gitbook/assets/image (2) (1).png" alt="" width="278"><figcaption><p>The MdX components in Readme Refactored</p></figcaption></figure></div>

I am already excited to redo all the introductory / overview pages of all the sections of the docs, using the clickable cards to make navigation a little more sexy than just a bullet point list.&#x20;

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p>The accordion, cards and tabs interactive mdX components</p></figcaption></figure>

Columns are a nice addition too to format pages in a more diverse way. Tabs will make it easier to display language-dependent technical information or code snippets. I like using accordion for troubleshooting tips or specific instructions for a sub-use-case, without adding too much length to the main content.

***

### <mark style="color:purple;">Synchronization with GitHub</mark>

One very exciting news is the possibility to soon be able to **connect with a GitHub account** and to synchronize with it. From what I have seen in the video launch, it will be possible to edit in Readme and to automatically update the content on GitHub, and the other way around as well.&#x20;

This is great to provide flexibility: technical people usually prefer to edit through GitHub, so now they have the option.&#x20;

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption><p>The Git Connection beta feature</p></figcaption></figure>

It is also great for back-up, because to be honest, I never felt comfortable relying 100% on Readme for all our technical content. If their server was to be down tomorrow, most of my client's would be in deep trouble (and so would I).

***

### <mark style="color:purple;">Open API Spec Embedded Editor</mark>

This one is probably my favorite, as it will make my life a lot easier and improve the quality of the API documentation presented in Readme.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>The Open API Spec editor feature (image taken from the video above <br>as I could not find this feature in the current demo version of Readme Refactored)</p></figcaption></figure>

One common challenge for API documentation is to adjust the Open API Spec produced by the technical teams for documentation purposes. This can be done through scripts, and/or manual editing (_I, for instance, like to adjust the endpoint names to be proper "human-readable" names and not just the endpoint URLs - which requires adding a "summary" field to the spec - which some of my client R\&D teams couldn't do, so I had to manually adjust all the endpoints in the spec)_, but in any case once the spec has more than twenty endpoints, and is updated frequently, it becomes a lot to handle.

Having the Open API spec on one side of the screen and the documentation interface on the other while being able to edit both is just going to be a great way to help, for heavy maintenance as much as quick fixes.&#x20;

Also, this means having full control over our own version of the spec dedicated to documentation :tada: that we can iterate from.

***

### <mark style="color:purple;">Embedded API keys & variables</mark>

There will be the possibility to have variables and security scheme imported from the Open API spec, but also to add custom variables like there are in [Postman collections](https://learning.postman.com/docs/sending-requests/variables/variables/). This is a great add to make the interactive documentation even more personalized for users, especially as API keys can be pre-populated with specific sets of variables.

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p>The "Personalized Docs" feature</p></figcaption></figure>

***

### <mark style="color:purple;">Detailed API Usage Analytics</mark>

Last, but not least, there will be a much more detailed way to track user's usage of the API in the doc called "My Developers". This looks like a promising tool to gain detailed insights into technical user's behavior, including the "`Time to 200`", "`Error rate`", and the Top (most tested) endpoints.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>The "My Developers" new feature allows for in-depth analytics about API usage in the doc</p></figcaption></figure>

This concludes our first tour of the coming features for 2025 (there are more presented in the video but I chose to focus on the ones I will most likely be using in the context of my work).

I look forward to testing them all on concrete projects. Stay tuned for updates and use cases on this blog. :thumbsup:
