# www.adventuity.co.za

The Adventuity Floodline website, published with GitHub Pages at **https://www.adventuity.co.za**
(the bare domain adventuity.co.za forwards here).

- `.github/workflows/publish.yml` copies the Floodline files from
  [Katiso0623/adventuity-hub](https://github.com/Katiso0623/adventuity-hub) (`floodline/`) every 30 minutes, commits them here
  when they changed, and publishes. A push to this repository, or Actions → Publish www.adventuity.co.za → Run workflow,
  publishes straight away. So the Floodline files can be updated in adventuity-hub; this copy follows automatically.
- Settings → Pages: source GitHub Actions, custom domain www.adventuity.co.za, HTTPS enforced.
  DNS at Afrihost: `www` CNAME `katiso0623.github.io` and the four GitHub A records on adventuity.co.za.
  The domain is verified on the Katiso0623 account.
- The learner and tutor portal is a separate site: https://learn.adventuity.co.za (repository adventuity-hub).
