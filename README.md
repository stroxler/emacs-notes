# Emacs Notes

This will be a collection of Markdown and probably eventually
org-mode notes on using emacs.

## Why?

I used to use spacemacs, and for around 2 years have been almost all VSCode
because that's what my company's tooling uses. But I want to start using
emacs again some of the time for a few reasons:
- I want to be more ready for open-source and side project work than I
  currently am, I've gotten lazy about dev setup.
- For some open-source work I do at my job, the VSCode setup isn't helpful.
  I'd like to have an alternative to that.
- I'm very interested in some personal studies that would pretty much
  require emacs: some ocaml studies where emacs is the best debugger and also
  Agda and Coq.
- I found spacemacs was helpful but prevented me from really learning emacs
  well, it was too magic. A few recent discoveries have made me think it's
  worth trying again:
  - The System Crafters youtube channel has awesome getting started videos,
    including bootstrapping an evil-oriented environment manually and learning
    elisp.
  - Doom emacs looks to me like it may have most of the advantages of
    spacemacs (a large preset config with good defaults for vim users), but
    be written in a lighter weight way that leads to faster load times and
    makes customizing more emacs-like than the unusual spacemacs setup.
    is easier

## What is here?

Mostly unstructured notes of various kinds, I might try to
collect them into something nicer someday (but probably not).
* The [getting-started](getting-started.org) doc talks about
  navigating a bare emacs install.
  * basic file and other control commands, color theme
  * basic navigation - a big issue for me as a vim user!
  * basic editing, including a minimal discussion of mark and point
