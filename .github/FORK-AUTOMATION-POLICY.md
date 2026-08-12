# Fork automation policy

This `gho` branch intentionally carries no executable GitHub Actions workflow
files. Upstream workflow definitions remain owned by the upstream `main` mirror;
they are reviewed during an upstream-to-`gho` merge but are not copied into this
customization branch.

Repository-local validation therefore runs through the checked-in Make targets
and scripts. References to `.github/workflows/**` in retained upstream design or
historical documents describe the upstream repository, not active automation in
this fork.

This boundary is fork policy only. It does not establish JARVIS admission,
provider selection, deployment, activation, or native-authority transfer.
