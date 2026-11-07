# Security policy

This policy applies to every repository in the magnetite-browser organisation
that does not carry its own `SECURITY.md`.

## Reporting a vulnerability

Report it privately, not in a public issue, through the repository's
"Report a vulnerability" page (Security tab, Advisories), or by mail to
[security@magnetitebrowser.org](mailto:security@magnetitebrowser.org).

Please include the affected repository and part, the commit you tested, steps
to reproduce, and the impact. We will acknowledge the report, keep you updated,
and credit you in the fix unless you prefer not to be named. Please give us a
reasonable time to fix the issue before you disclose it.

## Scope

In scope is Magnetite's own code: the browser, the `magnetite-sync` server and
its protocol, the Arc importer and the website.

Chromium and CEF bugs belong upstream
([Chromium](https://issues.chromium.org),
[CEF](https://github.com/chromiumembedded/cef/issues)). Magnetite pins a CEF
version, so upstream fixes reach Magnetite when we update CEF. Tell us if a
release we pin is affected.
