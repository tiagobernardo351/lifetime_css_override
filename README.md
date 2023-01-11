# lifetime_css_override

This project is to contain some CSS that will override a fix some issues in the LifeTime tool of an OutSystems platform installation.

I use the Chrome extension "User JavaScript and CSS", 
https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en, 
as a way to inject CSS and Javascript into web pages, but we can use whatever other tool/extension accomplishes the same goal.

The pattern URL that this CSS and Javascript should be applied to is (configured in a rule inside the Chrome extesion):

**com/lifetime**

This will, for example, match the following URLs:
- www.server-dev.outsystemscloud.com/lifetime
- www.server-lt.outsystemsenterprise.com/lifetime
