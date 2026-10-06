# Trio public website

Static consumer-facing website, published by GitHub Pages from `master` at
<https://scasimir2021.github.io/trio-website/>. It is marketing content, not the
tenant application backend or an engine gateway.

The October 2026 product direction is a customer workspace for apps,
conversations, and ongoing work, backed by a privately operated Trio engine.
GPU capacity and the three-machine topology belong in operator docs, not the
customer setup flow. Public copy distinguishes existing guided setup from
planned browser onboarding, additional capacity, and expanded workflows.

`index.html`, `styles.css`, and `app.js` have no build step or external runtime
dependencies. Preview with `python -m http.server 8766 --bind 127.0.0.1` and
check JavaScript with `node --check app.js`.

The workspace preview is explicitly illustrative. It makes no backend calls.
The page retains the previously published $0/$49/$199 prices; confirm any
commercial changes with the operator. The former `steven@trio.local` mail link
was not deliverable publicly. Until a public address is supplied, the contact
action opens a GitHub issue inquiry; it does not submit or send anything itself.

Before publishing: check mobile and desktop layouts, navigation, keyboard tab
controls, FAQ details, section links, and the contact destination. Avoid blanket
privacy, isolation, autonomy, review, or performance guarantees. Do not publish
internal hostnames, addresses, ports, credentials, customer records, or private
benchmark answers.
