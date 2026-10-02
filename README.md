# AI Visibility Tracker

AI Visibility Tracker is a skills-only plugin maintained by **Khadin Akbar**. It helps content teams use AI citation evidence to plan and prioritize work: measure whether AI-search answers cite a domain or specific pages, compare matching saved checks, and produce a content action plan.

Its three skills are `ai-visibility-tracker`, `visibility-trends`, and `visibility-action-plan`. They use the independently installed official Apify CLI and [Khadin Akbar's AI Search Visibility Tracker Actor](https://apify.com/khadinakbar/ai-search-visibility-tracker) through the user's Apify account. This is a productivity workflow for content research, report preparation and task prioritization.

## Requirements and use

Running a check requires a host with local command execution and internet access, the official Apify CLI, jq and a user-controlled Apify account. A chat surface without command execution can analyze supplied results or prepare a plan. Third-party usage charges apply under the user's Apify agreement; the skills package supplies no credits or AI-provider account.

Authenticate through the official Apify CLI's login flow in your own terminal. Never paste an API token into chat. Authorize the scope and spending limit before starting a billable run. Use public business information, such as your domain and general industry questions; do not submit personal, confidential or customer data.

The plugin bundles no executable scripts, server, MCP connection, hooks or dependencies. It adds no automatic telemetry or recurring schedule. Results and run records are handled by Apify and local exports by your host environment.

## What the results mean

The Actor reports domain and page citations, citation-list position, content gaps and competing domains. These are sampled API observations, not guaranteed rankings across consumer AI apps. Missing and diagnostic responses are unknown. Trends require matching domains, platforms and question panels, and a content recommendation does not establish causation or guarantee a visibility gain.

## Product information

- [Privacy notice](PRIVACY.md)
- [Terms of use](TERMS.md)
- [Support and issue reporting](SUPPORT.md)

This repository publishes product documentation. It does not include the plugin's skill source or the Actor's server source. Directory availability is subject to the relevant platform's review; preparation or validation does not imply an approved listing.
