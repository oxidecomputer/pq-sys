# Oxide fork of pq-sys

This is a fork of the [pq-sys crate](https://crates.io/crates/pq-sys).  The
canonical repo is [on GitHub](https://github.com/sgrif/pq-sys).  As of this
writing, the upstream pq-sys repo does not appear to be actively maintained.  If
the fixes in this fork are integrated upstream and an updated version of pq-sys
is released, we should delete this fork.

The branches in this fork are managed as described in [RFD
211](https://rfd.shared.oxide.computer/rfd/0211).  There is currently one
consumer, [Omicron](https://github.com/oxidecomputer/omicron), which uses the
"oxide/omicron" branch.

Other vestigial branches here include:

- "issue-36": a branch used for upstream PR#37.  This PR was abandoned.  The
  branch contains only the relevant change, not the other local changes here
  (like this README).
- "issue-36-metadata": a branch from "oxide" (so, with this README and other
  local changes) with an alternate fix for upstream issue #36.  This too was
  abandoned, though the approach may still be useful.
