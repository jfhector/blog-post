# How to design inclusively
The things we design include some people and exclude others.

Here's how to avoid locking out one billion people from the web and society.

## Introduction

### Some definitions

#### 'Inclusive Design' is a process

Inclusive Design is the process of actively considering the needs of people who are often excluded and marginalised, from the beginning of and throughout the design process. 
This is best achieved by designing with (rather than for) people who are excluded and marginalised.

#### 'Accessibility' is an outcome

Web accessibility means that websites and apps are easy to use for people in as many circumstances as possible, including people with impairments.

### The Web is inclusive by default

"The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect". Tim Berners Lee

HTML is designed to ensure that web content can be consumed in lots of different ways, be it visually or via a screen reader, using a mouse, a keyboard or a switch control.

Web browsers and operating systems themselves come with a wealth of accessibility features that most developers and designers don't know about. (eg. keyboard navigation, navigation by ).

All we need to do, is design with these features in mind, ensure that developers take advantage of them, and avoid putting barriers' in people's way.

### We've been putting barriers' in people's way

And yet, the large majority of most websites and apps get the basics of accessibility wrong.

US-based charity WebAIM ran their automated accessibility checks on the homepages of 1m most used websites across the world. Only about 20% of accessibility issues can be detected using such automated tests. And yet, they found on average XXXXXX issues per page.

Images alt
Colour contrast
Input names

### What we need to change

If we want a different result, we need:
* new thinking (Part 1)
* new practices (Part 2)

<!--  -->

## 1. New thinking

I've often heard that accessibility is important but not a priority on the roadmap. Or that accomodating people's disabilities or differences is an 'edge case'. Or that someone else (the client, the developer, the designer) needs to do something first, because we can think about accessibility.

#### New thinking #1: People with impairments are not an edge case

1 billion people in the world are disabled.

Just in the UK, 12.6m working-age adults are disabled. That's X% of the population, and as many people as live in London, Birmingham, Manchester,  ..... ... ... ..... .

Additionally, 5.4m people at any time in the UK have temporary disabilities. That's as many people as there are in Ireland and Northern Ireland.

According to the US Census Bureau, X% of those over 65 have a permanent impairment. And by 2050, 50% of the US population is expected to be over 50.

The latest report by the US Census Bureau states that 49.8% of adults over 65 have a disability or need some sort of basic assistance to get through the day.

So you're either disabled, or temporarily not disabled.

#### New thinking #2: Accessibility is not just for people with disabilities. It benefits everyone

Impairments can be permanent, temporary or situational.

For example:
* Being Deaf is a permanent hearing impairment. 
* An ear infection can mean having a temporary hearing impairment.
* Being in a loud pub is a situational hearing impairment if you're trying to make a phone call.

So when we make something work for people with permanent impairments, everyone with temporary or situation impairments also benefit.

For example, captions on videos are very useful for parents who want to watch movies without waking up their children, people in open plan offices or on the tube. 

Captions also help people who struggle to focus their attension for a long time, be it because they have ADHD, or because they're stressed or hyper because of caffeine.

In the same way, dropped kerbs ensure that wheelchair are not stuck, but also help people with prams, carrying heavy luggage or cyclists.

Ensuring that something is accessible generally benefits everyone.

#### New thinking #3: People with impairments are able. Until we disable them

There are different ways to think about disability:
* The **medical model of disability** says that people are disabled by their impairments or differences.
* The **social model of disability** says that people are disabled by barriers in society, not by their impairment or difference.

The medical model focuses on what is 'wrong' with the person. It implicitely assumes that people with impairments are not 'able'. 

The social model focus on what is wrong with the environment, and how it fails to accomodate people with impairments. It makes a distinction between 'having an impairment' and 'not being able to do something'.

In 1975, the UK Union of the Physically Impaired Against Segregation (UPIAS) claimed: "In our view it is society which disables physically impaired people. Disability is something imposed on top of our impairments by the way we are unnecessarily isolated and excluded from full participation in society."

The social model of disability shows us our true responsibility. 

As Jamie Knight, autistic accessibility specialist at the BBC said, “No one comes to our sites disabled. They come with impairments. We disable them".

#### New thinking #4: Accessibility is my responsibility

#### Reasonable adjustments are a legal requirement

I've often heard. "Accomodating the needs of people with disabilities is not within scope".

#### Inclusion and accessibility fall between the silos of design and development

I've often heard: "It's someone else's job. It's the developers' job to make sure that this is done well / to know this. Knowing this technical stuff isn't my job. I'm not / can't be expected to know this. It's the developers' job."

Developers don't know better.
Lack of knowledge by everyone.

Developers think that it's the designers' job
Designers think that it's the developers' job

Most accessibility problems require some technical knowledge to solve.
A lot of the accessibility guidelines and techniques are written in technical language.
Most product / UI / UX designers in the industry lack enough technical knowledge to think about these things effectively and confidently.
Their lack of technical knowledge gets in the way of designing inclusive user interfaces.
As a consequence, they put barriers' in people's way. Or fail to specify important design information to developers.

<!--  -->

## 2. New practices

### New practice #1: Learn about accessibility guidelines and good practices

Reading and studying the Web Content Accessibility Guidelines (WCAG) will make you a better designer.

You will learn:
* Specifically what it means for an interface to be accessible or inaccessible
* The most common design or development mistakes that make interfaces inacessible
* The a range of design and development techniques to ensure that interfaces are accessible

#### How to use the Web Content Accessibility Guidelines (WCAG)

There are 13 high-level guidelines, and 26 concrete success criteria under these. 

The success criteria are phrased to be as objective yet flexible as possible, and are referenced in laws and standards across the world. The success criteria are often quite technical and dry, hard to understand at first. The document itself can be very daunting.

But don't let that discourage you:
* Every technical term is clearly defined in a glossary
* Each success criterion has an 'Understanding' page written in plain language with plenty of examples.

### New practice #2: Who am I exclusing with this design?

Here are some considerations to include in your design, taken from the Web Content Accessibility Guidelines (WCAG).

#### Some things to think about, and design mistakes to avoid
(Checklist style)

* Accessible names (see 1.3.1 Info and relationships and 4.1.2 Name, role and value)
* Focus order (see 2.4.3 Focus order and 2.4.7 Focus visible)
* Heading structure (see 2.4.??)
* Areas (see. ??)
* Responsive layout considerations. No fixed heights. (see 1.4.4 Resize text and 1.4.10 Reflow content)
* Colour contrast. (see 1.4.3 Contrast and 1.4.11 Non-text Contrast)

### New practice #3: Specify accessibility in your design artefacts

You need to specify all the needed accessibility information in your designs.

Most developers don't know what needs to be done. And accessibility is a part of user experience. As a designer, you need to make decisions and communicate them to developers. Generally developers will only build what's explicitely included in the User Stories, Acceptance Criteria and design artefacts. If you don't include accessibility user experience in these artefacts, you can't expect that developers will fill in the blanks.

* Concretely what to do
* Concretely what to do
* Concretely what to do
* Concretely what to do
* Concretely what to do

(Mention web content authoring practices).

To learn how to do this and see examples, see HENNY SWAN LINK, and ANDREA ROSELLI LINK.

### New practice #4: Invite people who are not like you in the design process

##### Use inclusive persona

Bake the range of people and use cases into the brief, design thinking and every conversation about a piece of design.

Don't design for "normal" people in ideal situations.
Most people are not "normal". Most situations are not ideal.

Design with the diversity of human bodies, cognition and real life circumstances in mind.

Think about accessibility throughout the process.. "Who are we excluding?"

##### Do usability testing often, with a diverse range of people

Helpful for this:
Don't design just for people like you.
The problem with doing that, eg. with colour contrasts and legibility (eg. Cambridge vision curve).

Helpful for getting stakeholders to value accessibility and make decisions based on real people's experiences (rather than their own subjective preferences or predictions).

##### Design with people – not for people. Use experts

Most basic mistake.

"Nothing about me without me".

### New practice #5: Get technical skills

#### ie

Learn the technical materials (HTML and CSS in priority, and enough JavaScript to understand how a website works).

Don't worry about all the engineering tooling, frameworks of the day, etc. (Which is the most daunting part of getting started with web development, the biggest barrier).

It's like learning the materials (vs the tooling – see Lawson preso).

What you do want to learn:
- You need to know how your design will be implemented in HTML and CSS in very concrete terms

Things that you don't need to worry about when you get started:
- What CSS is supported in which browser
- Frameworks, engineering tooling, etc
- Learning JavaScript in depth

What you're not trying to achieve:
- Be able to replace a web developer, or do producton-grade code yourself

What you're trying to achive:
- Just enough so that you can think very clearly about design in a dynamic way
- Prototype using HTML and CSS and view your designs in web browsers directly (to complement your other design tools – some things can be done or thought about much quicker by opening up Google Dev Tools and doing something in the browser)
- Prototype with the real materials. Because prototyping helps you think and see
- Be intimately familiar with the materials you're designing with. (The only way to do this is to be intimately familiar with using them)
- Fill in the knowledge gap. This knowledge is missing
- Be a lot stronger in negotiations with developers and clients re. getting a good user experience delivered
- Break free of your design tools
  Your design tools are useful. But they are severely limiting your thinking.
  We review user interface design like we review art or posters. i.e. static things which purpose is primarily aesthetics and communication.
  It's a bad habit.
  Our design tools are not helping
  They make it very hard to think about (and remember) a lot of important potential solutions, and considerations. (Too easy to miss things – even if you're an experienced diligent designer).

#### How

Free resources:
- MDN docs
- MDN HTML, CSS and JavaScript tutorials
- A11y cast
- Udemy Google Accessibility
- Google Dev Fundamentals on accessibility
- A web for everyone?

## Conclusion: Change the culture around you

Exclusion is a habit.

We find lots of reasons not design and develop more inclusively.

But as designers we have a lot of power and influence. 

And digital exclusion is a habit that we are best placed to stop.

The task can seem daunting. But it quickly gets easier.

You get a lot of help, because everyone wants to see you succeed.

And it makes the job a lot more interesting and fulfilling.

(Krug quote).

This is about social justice, not charity.
