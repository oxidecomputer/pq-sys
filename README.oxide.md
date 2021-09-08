# Oxide fork of pq-sys

This is a fork of the [pq-sys crate](https://crates.io/crates/pq-sys).  The
canonical repo is [on GitHub](https://github.com/sgrif/pq-sys).  This fork is
used in [Omicron](https://github.com/oxidecomputer/omicron).

This fork exists to fix sgrif/pq-sys#36.  If a fix is integrated upstream and an
updated version of pq-sys released, we can delete this fork.  As of this
writing, the upstream "pq-sys" repo does not appear to be actively maintained.
There are several pull requests open for over a year from folks trying to use
it.  Some of these have no feedback from the maintainer.  That's why we created
this fork.

The branches in this fork that correspond with upstream branches (like "master")
should be kept in sync with upstream.  We don't want to put local changes on
these branches because that will make it harder to keep our own changes separate
and still sync up with upstream.

This fork contains branches:

- "oxide": the branch currently used by Omicron.  This includes our local
  changes.
- "issue-36": a branch used for upstream PR#37.  It contains only the relevant
  change, not the other local changes here (like this README).
