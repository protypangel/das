# DAS (Dream Architectural System)
DAS allow you to launch a complexe architecture for tech company.

It's regroup :
* `docker` to be launch services
* `code` of each projects that's be launch too
* `test` which permits to dev to test concept or test a services

Each directory in DAS has his own repo !

# Clone this repo
```sh
# clone das
git clone https://https://github.com/protypangel/das.git
# get each sub repo of das
git submodule update --init --recursive
```

# Push
```sh
git add -A
git commit -m "message"
git push --recurse-submodules=on-demand
```