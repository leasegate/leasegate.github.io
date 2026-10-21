# leasegate.github.io

The site at [leasegate.github.io](https://leasegate.github.io): one page for the organisation and one subpage per product (`gitgate/`, `sshgate/`, `bwgate/`, `cdpgate/`, `leasegate/`).

Each gate's update file lives on its own subpage, at `<gate>/update/<gate>.json`, and is written by that gate's release script after the release assets exist. There is deliberately no placeholder: an update file that names a version with no release would make "Check for updates" download a 404.
