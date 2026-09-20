---
title: "Cypress Cloud: Test Replay now masks sensitive form inputs by default"
url: "https://www.cypress.io/blog/ctest-replay-now-masks-sensitive-form-inputs-by-default/"
date: "2026-09-18"
feed_url: "https://www.cypress.io/feed.xml"
---
Starting today, Test Replay replaces the values of sensitive form fields (passwords and payment details) with asterisks before it captures the DOM before any Test Replay data is uploaded to Cypress Cloud. It's on by default for every Cypress Cloud project. This follows the same principle as network data redaction in Test Replay: keep sensitive values out of captured artifacts, without giving up the overall debugging experience of Test Replay in Cypress Cloud.
