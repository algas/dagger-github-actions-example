# dagger-github-actions-example

[Dagger](https://dagger.io/) example for github actions

## How to setup your dagger for github actions

1. [install dagger](https://docs.dagger.io/1200/local-dev)
2. make your github repository  
`gh repo create`
3. write a [cue file](./helloworld.cue)
4. setup dagger (generates `cue.mod/`)  
`dagger project init && dagger project update`
5. write a [github workflow file](./.github/workflows/helloworld.yml)
6. commit and push (includes `cue.mod`)  
`git commit -a && git push origin main`
7. visit your github repo and check the [action result](https://github.com/algas/dagger-github-actions-example/actions)
