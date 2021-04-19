# Open Source, Flexible Static Site and SPA Hosting

Welcome to Netliblox! This is a very work in progress project intended for the following:

- Get your HTML, JS, and other static assets on the internet following all best practices (minifying, SSL, and so on)
- Hook your website up to a dynamic backend like serverless functions, your pods in Kubernetes, or your app on VMs
  - Managing and maintaining this app is out of scope, but you should be able to connect to it from your site easily and reliably
- Build and test your static site without setting up CI/CD

## Motivation

There are many products and technologies on the market today that do magical things, but nothing does everything of course. Without spending weeks researching and prototyping on each platform, it's usually hard (if not impossible) to determine where the gaps are.

We recognize that these technologies are amazing and are building Netliblox on top of them. If a technology is strong at doing X but not Y, Netliblox will just do Y and integrate with it to do X. Further, this project aims to be as componentized and extensible as possible, so that you can (a) integrate with the technologies you already have (even if Netliblox doesn't officially support it!) and (b) add the project (or part of it!) to your stack without rewriting everything.

## Status

Nothing is built yet. We're doing README-driven development at the moment :smile:
