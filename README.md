.yml file include, Events, Jobs, Runners, Steps, Actions

for example event on: `push` can trigger the yml file when pushing new code ..

jobs:
    super-lint: (name of the job)
        name: Lint code base
        runs-on: ubuntu-latest (runs the container for you) <super lint will run on ubuntu-latest>
        steps:
            - name: checkout code
              uses: actions/checkout@v2 

            - name: checkout code
            - uses: actions/checkout@v2 

Github Actions looks for workflows inside the following repo:
    .github/workflows

smoke test: does the app run without crashing? 

source: https://www.youtube.com/watch?v=mFFXuXjVgkU 