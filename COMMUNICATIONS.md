# Recommended Communications Guide

This is a recommended communications guide. It attempts to distill a
set of communications best practices to help the Haskell Stack
community. The guidelines here are recommendations, and non-binding on
anyone. The guidelines are themselves guided by past experience, but
in following with these guidelines, this document will avoid calling
out specific events or individuals.

These guidelines may (or may not!) be useful for people outside of the
Haskell Stack community. Anyone is of course free to follow these
guidelines. This project itself is open source, and therefore any
documents may be forked, modified, and reshared at will. Furthermore,
if any others would like to discuss usage of these guidelines in other
contexts, please feel free to reach out via a Github issue or personal
email.

## Goals

This document is intended to:

* For those looking for advice, help them improve their communications
* Help the community have better discussions of sensitive technical topics
* Encourage a healthy form of discussion, avoiding a situation where
  we're afraid to have any technical disagreement

## Prior art

Some related documents I've written in the past are tangentially
related:

* [Effective Ways to Get Help from Maintainers](https://www.snoyman.com/blog/2017/10/effective-ways-help-from-maintainers)
* [How to send me a pull request](https://www.snoyman.com/blog/2017/06/how-to-send-me-a-pull-request)
* [Maintainer communication](https://github.com/commercialhaskell/commercialhaskell/blob/master/guide/maintainer-communication.md)
* [Guide to open source maintenance](https://github.com/commercialhaskell/commercialhaskell/blob/master/guide/open-source-maintenance.md)

## Principles

The following are principles I recommend. If you disagree with these,
would like to propose changes to the wording, or would like to propose
others, feel free to open an issue or pull request on this repository.

### Don't take it personally

We often become personally invested in our software. We dedicate huge
amounts of time, both personal and professional, to making it
succeed. It can sometimes be difficult to hear criticism of this
software.

However, technical discussions will ultimately include some such
criticism. Don't take it personally! Many of the points below try to
help this become a reality.

### Don't make it personal

A corollary to the above: don't _make_ it personal. When discussing a
technical topic, there is rare&mdash;if ever&mdash;good reason to
implicate negative attributes to the author. Indicating that the
author is unintelligent, implying nefarious motives, or similar
comments brings the discussion down from technical to personal.

_If_ the other side in a discussion makes it personal, my
recommendation: immediately point it out as such, with a link to this
section.

### Respect privacy

Some topics are best discussed publicly. Others may be well handled
privately. If you believe you are in the latter category, send a
private message requesting the other side participate privately. If
agreed to, somewhat obviously, **do not** violate that agreement!

That said, private communications can be used as a method of private
attacks and intimidation. As such, communications can only reasonably
be considered private if both sides agree.

### Avoid ad hominems

Do not discredit someone's technical work or discussions based on who
made the comment or did the work. This can come in many different
forms:

* **BAD** Their previous work is shoddy, so this work must be shoddy.
* **BAD** They are part of an organization/company/committee,
  therefore they are inherently biased and cannot be listened to.
* **BAD** They are seen as friendly with someone else, therefore they
  are inherently biased.

A related topic is the pattern of behavior argument. "Person X has
done A, B, and C, therefore D must have a similar motivation." That's
_also_ not appropriate for public discussion.

There's no way to prevent these associations from forming in your
mind. If you decide to analyze someone's technical work or public
statements more closely because you see their associations, so be
it. But it is inappropriate to discredit their work simply based on
these prejudices.

Find a technical issue to discuss, or leave the matter alone.

### Encourage healthy discussion

We _want_ open, healthy discussion around our projects. Since this is
about Stack: user feedback has dramatically improved Stack over the
years. Even negative feedback from non-users has in many cases helped
Stack improve. These are good things worth discussing.

Do not try to shut down or avoid a healthy discussion.

### Debate technical merits

Discussions should be about the technical merits of a
project. However, the definition of technical merits is in fact quite
broad, including:

* Performance
* Reliability
* Maintainability
* Ease of use
* Marketability

I believe that last one may be a surprise to many. I want to make the
argument for that specifically. The best software is useless (by
definition) if no one uses it. Making an argument for a feature so
that it is easier to encourage the use of some software is perfectly
valid.

That said, keep these discussions as objective as possible.

### Avoid partisanship

This document is written for the Stack community. As [the initial
proposal](https://www.snoyman.com/blog/2018/11/proposal-stack-coc)
mentions, this in itself is not ideal, since it is somewhat
divisive. Allow me to backtrack that divisiveness here a bit: we
should _not_ be trying to establish a separate Stack community that
does not integrate with other projects.

Much of how Stack has been designed is in fact along these lines:

* The Stackage project is separate, and is usable by both Nix and (to
  some extent) cabal-install
* Hackage remains the upstream repository
* Cabal remains the underlying build system

Broadening this a bit: I (Michael) am one of the original authors of
Stack. I'm also the original author of Yesod and Conduit. It is
absolutely vital that Stack treat other web frameworks (like Servant)
or streaming data libraries (like Pipes or Streaming) as first class
citizens, in exactly the same way as Yesod or Conduit.

Said another way: a decision to opt in to one piece of the toolchain
should be orthogonal to any other decisions.

### Respect others' time

This is covered in depth in the "prior art" links above. Most people
are interacting with the Stack community in their free time. Companies
that support development of tooling are spending funds they could be
using for non-community activities. We should respect these
contributions.

On the other hand, for users and consumers of the technology, we
should wherever possible try to make life as easy as we can. Avoid
blocking people if you can. Recognize differences in goals and see if
they can be addressed. Be aware that it may _not_ be possible to
address these differences. Be explicit about your intentions so people
can make decisions on how they wish to proceed with achieving their
goals.

### Avoid derailing discussions

Keep discussions on topic. If there's an issue about X, do not
unnecessarily raise Y. Do not rehash previous arguments. Do not open
copious issues to rehash previous arguments. If there is an inherent
disagreement, accept that that disagreement exists, and do not attempt
to force others to comply with your viewpoint.

### Don't demand changes from others

These guidelines are non binding. No one has the right to point at
them and demand that some arbitrary other person comply with
them. That is not the purpose of this document. This rule extends: you
cannot demand that others behave in a way you want, or perform
technical activities you want them to.

That said, similarly, you are under no obligation to engage in an
environment you are not comfortable. If a discussion has been handled
in a manner which you're not happy with, feel free to either disengage
completely, or explain that you're stepping away, possibly with a link
to this section.

If you feel comfortable with doing so, in some cases a private message
to the other party can help resolve a situation you're unhappy
with. They may be unaware that you're uncomfortable. They may be more
sensitive to your feelings if expressed privately and calmly. Again,
you may not _demand_ such a change, but a polite request is
reasonable.
