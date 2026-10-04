---
title: "Skip tests that pass on the current build: Re-run optimization in Cypress Cloud"
url: "https://www.cypress.io/blog/skip-tests-that-pass-on-the-current-build-re-run-optimization-in-cypress-cloud/"
date: "2026-10-01"
feed_url: "https://www.cypress.io/feed.xml"
---
When Cypress detects a CI rerun, it can now skip the work that already passed and run only what failed, so you get to green faster, burn fewer CI minutes, and record fewer billable test results. Re-runs with few failures can skip 99% or more of the tests that would have re-executed. It works out-of-the-box with common CI providers, and ships with overrides to customize the re-run behavior to your specific needs.
