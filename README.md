Meet **eppz! Disqus exporter**, a simple plugin that post process a
WordPress export file to include avatars for Disqus import. Works only
if SSO is enabled in your Disqus account.

It grabs avatar urls (if any) from Gravatar each time it arrives to a
comment author email in the WXR file, then adds an entry to the WXR that
**creates Disqus SSO user** upon importing the resulting file in Disqus admin.

As it comes without a single line of error handling, I'm not intended to
support this repository. Please help yourself, and look into the code if
some issue raised.
