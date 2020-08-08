# schutzbot

This repository contains work-in-progress intended to be used by Schutzbot in
their endeavors to support osbuild and related development.

## snapshot

This script takes a snapshot of a distribution. RPM caches are shared between
snapshots, but nevertheless, they do grow large. In the order of 200GB per
distribution.
