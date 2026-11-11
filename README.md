# StudyMate UK

A responsive student-support website built with self-contained HTML, CSS and JavaScript. It includes Home, About Us, Student Support, FAQs and Contact views, plus a clearly labelled demonstration contact form.

## Open the website

Open `index.html` in a modern browser. There is no package installation or build step.

For an HTTP preview with Python installed, run `python3 -m http.server 8000 --bind 127.0.0.1` in the repository folder and visit `http://127.0.0.1:8000`. Stop with Ctrl+C.

The previous `StudyMate UK.html` URL redirects to `index.html` and preserves the route fragment when JavaScript is enabled. The root filename makes the site usable on static hosts that look for `index.html`.

## Available views

Use `#home`, `#about`, `#support`, `#faqs` and `#contact` to open a view directly. The main navigation updates its current-page label and the document title. Route changes move focus to the main content.

## Community and contact details

The community URL is empty by design. Set the `COMMUNITY_URL` variable inside `index.html` only when the owner supplies a real invitation link. Until then, Join buttons lead to the contact view and display the availability notice.

The contact form is a demonstration. It does not send email, submit an enquiry or store the entered message. A real submission backend is a separate implementation decision. Contact details, testimonials and university partnerships are not invented by this template.

## Edit and verify

- Edit page content in the corresponding `v-*` view inside `index.html`.
- Edit colours and responsive styles in the inline CSS.
- Keep JavaScript enabled for view switching.
- Check all five navigation links, a direct-route reload, keyboard focus and phone-width layouts.
- Confirm the contact form still clearly reports that no enquiry has been sent.
- Keep both the canonical file and the small legacy redirect when maintaining old links.

No external runtime library or build tool is required. Any future hosted copy should use the access and privacy settings appropriate to its audience.
