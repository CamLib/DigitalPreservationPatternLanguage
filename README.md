# Digital Preservation Pattern Language

## A set of patterns to describe Digital Preservation.

The patterns I have produced here provide a description of the domain of Digital Preservation, i.e. the ways in which digital materials (most commonly computer files) can be sourced, brought under control, and then have their usefulness maintained, potentially in perpetuity.

The idea to create a pattern language came about as part of the Polonsky Digital Preservation Project at Cambridge University Library and The Bodleian Library at Oxford University; see http://www.dpoc.ac.uk for more details about the project. 

One of the first things I did when I joined the project was to go in search of a pattern language in the hope that I could use it to get up to speed with what Digital Preservation is, and what tasks are involved in preserving digital materials. However, it became clear that, while there is a tremendous amount of expertise and knowledge in the Digital Preservation domain, nobody seems to have had the time to encode this knowledge in a re-usable set of patterns yet. However, as part of the project is to come up with Digital Preservation policies, training materials and sets of requirements for Digital Preservation systems, our project provides an opportunity to try and put a pattern language together.

There's a blog post about the idea of [developing a Digital Preservation pattern language](http://www.dpoc.ac.uk/2016/11/11/digital-preservation-pattern-language/) on the DPOC website which explains the thinking behind this idea in more detail, but the fundamental purpose is to **try and describe as much of the Digital Preservation domain as possible in plain English**. As with a lot of technical domains, there's a lot of jargon, and that can cause frustrating (and expensive) misunderstandings.

## Why is it in GitHub?

The idea behind putting the Digital Preservation Pattern Language in GitHub is to keep the files that constitute the pattern language as light-weight as possible, and to try and encourage people to use it and adapt it to their own needs. To that end:

1. All the patterns are written in [simple markdown](https://guides.github.com/features/mastering-markdown/) - I'm trying to stick to the core markdown, too, rather than using anything specific to GitHub.
2. Because they're in GitHub, I can create versions and release them like normal code. So, until I've reached a point where there's a useable set of patterns in place, I'll keep everything on the Development branch, and then make major changes to the pattern language on that branch post the first release, too.
3. I'd like to encourage people to create their own forks and create pull requests to contribute them back. I want this to be a collaborative effort as the Pattern Language should be a resource for a whole community to use to describe their domain, not just one person's ideas.
4. I'm actually (reasonably) new to the Digital Preservation domain (aside from some *very* rusty digitisation experience), so I'm not actually expecting much of the content to be 'right' - in fact, I'd like to use this as an opportunity for the Digital Preservation community to tell me where my thinking is going astray. As such, I encourage people to make free and copious use of the [Issues List](https://github.com/CamLib/DigitalPreservationPatternLanguage/issues), and / or to fork the whole set of patterns and re-do them in their own image (with a Pull Request at the end, obviously).

## What's a pattern language?

My [blog post on the Polonsky project website] (http://www.dpoc.ac.uk/2016/11/11/digital-preservation-pattern-language/) describes pattern languages in more detail (and links to some even more detailed descriptions), but the shortest way to describe a *pattern* is to quote one of the two books which are credited with inventing the concept: *A Pattern Language - towns, buildings, construction* by Christopher Alexander et al. This describes patterns like so:

>The elements of this [architectural] language are entities called patterns. Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.

So the point is that I'm not trying to be proscriptive about 'how to do Digital Preservation' - I'm trying to come up with a playbook of *potential* responses to particular Digital Preservation situations. Plus, as noted above, I *really* don't claim to have the 'correct' answers (as if such things were even possible). So if a particular pattern fails to ring true for you, why not try one of two things:

1. Add an issue about your, er, issue, to the [repo's Issues List](https://github.com/CamLib/DigitalPreservationPatternLanguage/issues).
2. Fork this repo, re-write the pattern so it fits how you would describe the situation, and then generate a Pull Request to suggest the changes.

I'll consider all serious suggestions seriously. And as soon as people start to make major contributions, I am open to the idea of giving them permission to contribute to this repository directly.
