# Altratech Outreach HQ

The password-protected dashboard website for the Altratech outreach crew.

This repo only holds the page. It contains no data. When you open the site, it asks for
your password and then reads the crew's live data from the private
`arnomoller/Altratech-outreach` repo using a GitHub token that is stored on your device,
encrypted with that password.

The page is built from `site/app.html` in the outreach repo (`python site/build.py`).
Copy the built `site/index.html` here to update it.
