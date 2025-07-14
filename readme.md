# DAS (Dream Architectural System)
DAS allow you to launch a complexe architecture for tech company.

It's regroup :
* `docker` :
  * Allow to launch needed containers (gitlab / gitlab's postgresql / verdaccio)
  * Create services from `services-custom`
* `services-custom`:
  * Custom services like storybook
* `test` which permits to dev to test concept or test a services

**Each directory in DAS has his own repo !**

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

# Dev on verdaccio
You can use `Dev Containers` vsc's extension to modify the verdaccio's pluggins.

To reboot the container :
`docker compose -p alif -f docker\compose\docker-compose.yml --profile manual restart verdaccio`

