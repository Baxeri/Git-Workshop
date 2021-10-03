If you fail a git push you normally would just try to run it like this:
git push --force
But in fact, it's better to force push like this:
git push --force-with-lease
This way it's less likely you break something in your repo when trying to
force it.
