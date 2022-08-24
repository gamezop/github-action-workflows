## Collection of reusable workflows

### ci-elixir-push

- Inputs:
    - mix-env
    - mix-app-name
    - img-name
    - github-run-id
    - path-docker-file

- Secrets:
    - DOCKER_HUB_USERNAME
    - DOCKER_HUB_ACCESS_TOKEN
    - GO_MODULES_GITHUB_TOKEN

- Outputs:
    - app-tag

NOTE: [Using outputs from a reusable workflow](https://docs.github.com/en/actions/using-workflows/reusing-workflows#using-outputs-from-a-reusable-workflow)



build-test

main, docker-push-dev return app-id?
*.*.* docker-push-prd return app-id?