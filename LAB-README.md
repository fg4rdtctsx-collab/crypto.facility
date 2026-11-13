# Crypto Facility — isolated UI training lab

This branch is not the published website. Do not merge it into main or enable Pages publishing for it.

- Original page layout and wording retained as explicitly fictional training examples.
- Purple #3A0CA3, near-black #050505 and white.
- Existing logo on refresh and for 1.2 seconds before a local mock checkout.
- Persistent training notice; all wallet results, earnings, activity and reviews are fictional.
- No real invoice, payment, account activation, email or analytics write.
- Browser connections, external frames and form submissions are blocked by Content Security Policy; fetch calls use fixtures.
- No CNAME file or publishing workflow on this branch. GitHub Pages remains configured for main.

## Run locally

Download this branch and run python3 -m http.server 8000 --bind 127.0.0.1 in its folder. Open http://127.0.0.1:8000/index.html. Do not enter real personal or payment information.

index.html contains the bundled training overlay and original demonstration UI. mock-checkout.html is a local simulated destination, not OxaPay.
