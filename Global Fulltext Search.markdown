# GlitchCat Stance on Global Fulltext Search

This document comprises the current stance of the GlitchCat
  ([glitch.cat.family](https://glitch.cat.family)) moderation team with
  respect to “global” fulltext search on those instances with which we
  federate.
It is recommended reading for admins of instances we communicate with,
  as well as GlitchCat users.

## Context

By default, Mastodon only allows fulltext searching on posts that a
  user has interacted with.

Some instances have recently decided to remove that limitation.
This document comprises our policy with respect to those instances.

## Our Axiom

The GlitchCat policy with respect to post discoverability can be summed
  up as follows :—

> The agency of post authors to determine the capabilities of their
>   posts is **more important** than the desires of other users on the
>   network to consume or interact with their content.

“Capabilities” here means both interaction capabilities—whether a post
  can be boosted, for example—and discovery capabilities, like whether
  a post appears in the public timelines or in search.
We believe that post authors should be the final arbiters of these
  decisions, for two reasons :—

01. Ethically, **it is the correct position.**
    Prioritizing discovery mechanisms over author intention is the same
      as treating authors as a product to be consumed rather than
      people to be respected.
    Doing so would be antithetical to our mission as a social platform.

02. Socio‐technologically, **antagonism between post authors and
      discovery mechanisms harms the experience of everyone.**
    It leads to self·censorship and workarounds which damage important
      user capabilities, like post filtering, which depend on agreement
      by post authors to distribute the contents of their posts in an
      algorithm‐friendly way.

## Problems with “Global” Fulltext Search

Adhering to the above axiom means that GlitchCat **cannot support
  a global fulltext search on the fediverse as it exists today.**
The specific problems we have identified are as follows :—

01. The existing precedent on the fediverse is for fulltext search to
      be disabled for posts a user has not already interacted with.
    We believe this **must** be maintained as the default behaviour for
      all posts which have not explicitly indicated otherwise.

02. Existing mechanisms for opting into search indexing, for example by
      search engines, do not federate and cannot be used to indicate
      support for a global fulltext search on other instances.

03. The precedent on Mastodon is for capabilities to be specified on a
      per‐post, not per‐user (and certainly not per‐instance), level.
    No mechanism for federating support for fulltext search on a
      per‐post level exists, and nor has any been proposed.

04. All existing implementations of global fulltext search that we
      know of blatantly ignore the above points, and no known
      proponent has made any effort at addressing them.

## Policy Regarding Instances Implementing Global Fulltext Search

We will, at minimum, *silence* instances implementing a global fulltext
  search, to ensure that we do not receive unwanted interaction from
  them as a consequence of our posts being accessible through these
  means.

**We ask that instance admins running instances that implement a global
  fulltext search notify us, so that we can apply the appropriate
  silence.**
If you are an admin of an instance implementing a global fulltext
  search and you do not notify us (because you do not want to be
  silenced), understand that we will interpret this as a challenge to
  our sovereignty to moderate our instance as we see fit, and as
  disaffirming the rights and agency of our users.

## Exceptions to the Above Policy

 +  **The above remarks apply only to *global* fulltext search**
      (across the whole known network).
    You are free to implement fulltext search across local statuses if
      you wish.

 +  **The above remarks do not apply to single·user instances.**
    (We moderate single·user instances with the assumption that their
      owners have database access, so global fulltext search has always
      been a possibility for them.
    We will suspend any single·user instance which abuses this
      privilege.)
