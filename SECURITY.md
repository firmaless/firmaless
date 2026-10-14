# Security

FirmaLess handles documents and signatures, so we take security and privacy reports seriously.

## Reporting a problem

**Please do not open a public issue.** Use GitHub's private reporting instead: on this repository, open the **Security** tab and choose **Report a vulnerability**. Only the maintainers can read what you send.

Useful to include:

- what you found and why it matters;
- the steps to reproduce it, with the browser and operating system you used;
- whether a document, a signature or anything derived from them could leave the device because of it.

Do not include real documents or signatures. A made-up PDF shows the problem just as well.

## What we especially want to hear about

- Any way for a document, a signature, a file name or page content to leave the device.
- Any way around the isolation of the part of the app that opens documents: its content security policy, its sandboxed frame, or the messages it exchanges with the rest of the site.
- Anything that lets another website read or change signatures saved in the browser.

## What to expect

We will confirm that we received your report, tell you what we found, and tell you when a fix is released. Please give us a reasonable time to fix a problem before making it public.
