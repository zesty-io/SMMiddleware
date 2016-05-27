# SMiddleware
A middleware framework to manage abstracted sales and marketing software connections, integrations, and operations.

From website to ERP, CRM, ESP, internal custom systems, or any network endpoint.
From ERP, CRM, ESP, internal custom systems, or any network endpoint to website.

Whatever is needed, this is the layer where decisions are made without bastardizing marketing software that powers websites. 

## Smiddleware Benefits
- Marketing gains agility by not losing updating abilities or control of their presentation to over modification.
- Marketing software does not gain new security vulnerabilities through modification.
- Operations are abstracted and become more manageable
- IT gains control of the nuts and bolts without needed to know how to modify hundreds of different 

## Making the transition to Smiddleware
**Marketing Implementers**
When creating integrations, do not modify the codebase you are building websites in. Use network requests and software hooks to process captured data.

**Software writers**
Start writing hooks into operations on your software. This starts with form posting. Even though implementers can post data with javascript, if you can provide hooks that fire on events, reliability increases.

## Why PHP
PHP was decided as the codebase language because
- Wordpress is largest adopted software that is bastardized into frankenstein middleware, and it is written in PHP.
- PHP is the most common amongst budding marketing implementers/developers (Wordpress, Drupal, Joomla, etc.)
- PHP is open source, has a large community, and plenty of integrations hooks.

## Open-source
Please feel free to express your ideas or extend this codebase. This codebase is a mindset, not an end all. Ultimately you can maintain your own Smiddleware on any language you are comfortable with.
