---
icon: laptop-code
cover: ../.gitbook/assets/adp-electronic-communications.jpg
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: true
  pagination:
    visible: true
---

# Documenting API Endpoint Deprecation: the Art of Planning Ahead

As a freelance software technical writer, I usually spend between half and a third of my time to care for API documentation, depending on the project and the company I am working for.&#x20;

This can go from testing endpoints one by one to adjusting the endpoint classification in the documentation, enriching endpoint descriptions, renaming the endpoints to be understood by human beings, enriching parameter's descriptions, writing changelog posts, writing error messages, anticipating changes coming in the next version of the API, writing API guides, etc.

APIs are so critical to business growth those days, they usually evolve fast, which implies a constant stream of new endpoints to document as well as ancient endpoints being deprecated. Deprecating an endpoint means it will stop working in a close future, so the users need to be redirected to another way to perform the same task.&#x20;

### Why deprecate?

There are several reasons for deprecating endpoints, which include but are not limited to:

* [ ] **Technical debt**\
  Companies sometimes choose to strategically deprecate endpoints relying on an outdated structure, often for performances reasons. Dated systems can get harder and harder to properly maintain as time passes.&#x20;
* [ ] **Decrease in usage**\
  Sometimes a feature that used to be very much 'in demand' becomes less popular. It can come from clients 'churning' (turning to competitors), but also from the evolution of the market for specific needs. If an endpoint usage is significantly decreasing, it might be wise to decide to deprecate it to focus the resources on other endpoints providing more value.
* [ ] **Security issues**\
  Security protocols and techniques, including cryptographic algorithms, evolve quickly. Endpoints relying on dated protocols that are not considered 'safe' anymore might expose the API users to security risks, and should be deprecated to be replaced by more secure ones.
* [ ] **Performance reasons**\
  This can go along with technical debt issues. If requests are long to process, or the endpoint provides a full dataset in response instead of a specific set of data (or both), it is best to deprecate it to provide more specific, efficient options.
* [ ] **Business pivot**\
  Among the many reasons for deprecating endpoint is the rare - but possible - business pivot or strategical change of product, which brings a company to build new APIs entirely, or to repurpose some endpoints to perform some entirely new tasks.

{% hint style="info" %}
API stands for Application Programming Interface. Think of API as programs that take an input, and delivers an output (usually, as a JSON file to structure the data and make them readable by a machine). APIs allow systems to communicate with each other and are pretty much present behind all our phone apps, and web apps.&#x20;

For a very accessible guide explaining "What is an API?", I recommend visiting [this page](https://read.technically.dev/p/whats-an-api) on the site "Technically".
{% endhint %}

***

### The process of API deprecation

The decision of which endpoints to deprecate (and how to shape the new version of an API overall) comes from strategic discussions between - usually - product and technical teams, to find the right balance between user's needs and technical feasibility as well as overall business priorities. The evolution of an API is a collaborative effort. Deprecation are rarely discussed in isolation: they are part of the API roadmap and versioning plan, just like the introduction of new endpoints or changes to existing ones.

Every company has its own process, but it usually follows those general steps:

* [ ] **Strategic Prioritization**\
  Product & technical lead(s) craft the next version's priorities, to better balance user's needs with technical constraints and business goals.
* [ ] **Collaborative Design**\
  Once the priorities are clear, the roadmap is transferred to an API team, usually composed of senior technical profiles (engineers and architects) who define the structure and design guidelines. It is usually the stage where technical writers are involved, so we can start documenting the changes to come (_note that I have been asked before to prepare a deprecation notice within 24 hours before the actual deprecation, so anything can happen, but I would not recommend_).
* [ ] **Validation**\
  Depending on the criticality of the changes, the new API has to be approved by a technical board, and sometimes by executives as well. Legal can be involved too, if applicable.
* [ ] I**mplementation & Documentation**\
  That is when the actual changes are made to the API, that changes version (from 1.0 to 2.0 for instance). The chosen endpoints are deprecated, new ones might be added too. This is the perfect moment to update the API documentation, write migration guides, and craft deprecation notice pages and warning messages.
* [ ] **Communication**\
  As the release of the new version occurs, there should be emails sent to clients, as well as announcements (internal and external). A changelog should list all the changes and be easily accessible in the documentation.





