---
layout: people
background: /assets/images/kaist.jpg
title: Jaehwang Jung (정재황)
excerpt: "Jaehwang Jung's website"
---

{%- assign person_id = "jaehwang.jung" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl }}/assets/images/people/jaehwang.jung.jpg" alt="{{ person.name }}">

I am a **PhD student at [Concurrency and Parallelism Laboratory]({{ site.url }}), [KAIST School of Computing](https://cs.kaist.ac.kr)**.
I have been working on design and verification of algorithms for concurrency.
Specifically, I am interested in memory management algorithms for non-blocking concurrency and separation logics for weak memory models.

{% include person_contact.md person_id=person_id %}

{% include person_education.md person_id=person_id %}


#### Publications

{% include publications.md author_id=person_id submitted=true %}

#### Experiences

- Intern, Runtime Verification Inc., May, 2018 - August, 2018, January, 2019 - February 2019.

  (topic: [verification of ethereum smart contracts](https://github.com/runtimeverification/verified-smart-contracts))
