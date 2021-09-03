# Oxide fork of pq-sys

This is a fork of the [pq-sys crate](https://crates.io/crates/pq-sys).  The
canonical repo is [on GitHub](https://github.com/sgrif/pq-sys).  As of this
writing, the upstream pq-sys repo does not appear to be actively maintained.  If
the fixes in this fork are integrated upstream and an updated version of pq-sys
is released, we should delete this fork.

This fork is used in [Omicron](https://github.com/oxidecomputer/omicron).

The branches in this fork that correspond with upstream branches (like "master")
should be kept in sync with upstream.  We don't want to put local changes on
these branches because that will make it harder to keep our own changes separate
and still sync up with upstream.

This fork contains branches:

- "oxide": the root of our local changes.  This branch contains this README and
  some GitHub actions to aid testing.
- "omicron": the branch currently used by omicron.
- "issue-36": a branch used for upstream PR#37.  This PR was abandoned.  The
  branch contains only the relevant change, not the other local changes here
  (like this README).
- "issue-36-metadata": a branch from "oxide" (so, with this README and other
  local changes) with an alternate fix for upstream issue #36.  This too was
  abandoned, though the approach may still be useful.
