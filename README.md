Don't run these with -j it's used internally.

There's a lot to build, expect it to take a while esp if you don't have many cores. Maybe 10mins with 32 cores?

Clone with the following, probably need ssh keys set up.

git clone --recursive <url>

make build-ukl-app
make launch-ukl-app
