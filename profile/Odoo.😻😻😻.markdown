# Weekly Release Cycle

![](https://github.com/user-attachments/assets/4ec1d334-8d30-4ebe-a5e6-d62d79082edb)

Every week we prepare a new release.
Technically, it starts with a **branch** named like `release-w33` — the candidate for week 33.
This release branch aggregates multiple development branches, typically named `w33-xxx-yyy-zzz`.

But let’s go deeper.


## Development

It begins with a copy of the project (our Oval Office).
On this copy, fixes and upgrades are built, tested, and reviewed. Once both technical and functional checks are approved, the work moves into the `release-w33` branch. At this stage, it’s a polished candidate, but not yet production.


## Staging

With the help of **odoo.sh** tools, we can create a staging environment out of any branch (for example, `release-w33`).
Staging is the rehearsal room — the final stage where all new features of the weekly sprint are tested together and approved.


## Production

And then comes the performance.
With the **magic button** of GitHub and Odoo.sh, we apply the upgrade smoothly, securely, and efficiently. What once took weeks or even months in the early days of business IT systems now happens in minutes — thanks to scientific progress in computing, and to the carefully designed release management routine of **VS Consulting Group**.


## Hotfix

But life always calls for a backup plan.
If something goes wrong, or an urgent issue must be solved immediately, we bypass the weekly rhythm.
A **HOTFIX branch** is created (`HOTFIX-xxx`) and deployed to production with the highest priority possible.

# Thank You 🌿

The journey through mirrors, copies, branches, and releases is only the beginning.
Every rhythm needs a partner, and every map needs a crew.
We’ll be glad to guide your project into its next horizon.

📬 [Get in touch with us](https://www.vs-consulting-company.com/contact/): +32 (0) 794.526.307
