# MailMe - send templated mails

This is a clone/fork of [Netlify's MailMe
repository](https://github.com/netlify/mailme). That one is no longer
maintained, but this one is as it's an important dependency to
[GoTrue](https://github.com/supabase/gotrue) the software behind [Supabase
Auth](https://supabase.com/auth).

MailMe is meant to deliver transaction mails with a template that can be loaded
from a URL. If no template is present from the URL it will fall back to a default
template.

This makes it easy to deploy your mail templates to a CDN (with Netlify) and have
an easy workflow to work with the mails and preview them directly in the browser.

