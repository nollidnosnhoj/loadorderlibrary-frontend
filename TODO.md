# Lists

-   [x] Upload form
-   [x] Edit form
-   [x] Ampersand in game name is breaking URL (probably just wrap game names in `encodeURIComponent()`)
-   [x] Metadata for embeds
-   Triple check iframe security stuff
-   [x] Comparisons

# User

-   [x] Generating/deleting API tokens
-   2FA

# General

-   Content security policy for the frontend itself.
-   Double check cache control and other related things for perf/etc

# API

-   [x] Need to move over the scheduled tasks for deleting expired lists and orphaned files from existing phinocio/loadorderlibrary repo.
-   [ ] Complete review of token permissions on API (half done)
-   [x] Move APIToken stuff to a specific API Token controller

# TO FIX:

-   Text reflow issues on thinner mobile devices
-   [x] No logo for non-list-specific embeds
-   [x] Verison and game name need to be split onto different lines in list view


# MISC:

- [ ] search feature (after redesign is live)
- [ ] API Docs
- [ ] Admin game add/delete page
- [ ] Admin user management page (verify/delete)
- [ ] Simple stats page (num lists, num files, etc)
- [ ] Go through and make div/article/section tags more consistent in use
- [x] Text overflow issues for long strings with no whitespace
- [ ] User avatars (maybe)
- [ ] More error pages (maybe make it just one generic top level instead of custom per route?)
- [ ] Transparency page
- [ ] Ensure pages have proper titles
- [ ] Ensure pages have proper embeds for discord/twitter/fb
