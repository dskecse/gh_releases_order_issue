# Github releases order issue

A repo reproducing the Github releases order issue.

There's [a few tags][tags] created for this repo,
and here's the order of their creation (oldest to newest):

* July 16th
  * v0.1.0
  * v0.2.0
  * v1.0.0
  * v1.0.1
  * v0.2.1
  * v1.1.0
* July 17th
  * v1.2.0
  * v1.2.1
  * v0.2.2

As you can see [in the tags][tags] (or [releases][releases]),
same-day items are displayed in the correct semver order, but this order
is broken for items created on different days, here's how they're displayed now (first to last):

* v0.1.0
* v0.2.0
* v0.2.1
* v1.0.0
* v1.0.1
* v1.1.0
* v0.2.2
* v1.2.0
* v1.2.1

Here's an [issue I've raised](https://github.com/orgs/community/discussions/8226#discussioncomment-10070772)
with Github employees to help them address it.

[tags]:https://github.com/dskecse/gh_releases_order_issue/tags
[releases]:https://github.com/dskecse/gh_releases_order_issue/releases
