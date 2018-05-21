---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Get Repositories Username Repo Slug Pullrequests
  description: |-
    Returns a paginated list of all pull requests on the specified
    repository. By default only open pull requests are returned. This can
    be controlled using the `state` query parameter. To retrieve pull
    requests that are in one of multiple states, repeat the `state`
    parameter for each individual state.

    This endpoint also supports filtering and sorting of the results. See
    [filtering and sorting](../../../../meta/filtering) for more details.
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pullrequests:
    get:
      summary: Get Repositories Username Repo Slug Pullrequests
      description: |-
        Returns a paginated list of all pull requests on the specified
        repository. By default only open pull requests are returned. This can
        be controlled using the `state` query parameter. To retrieve pull
        requests that are in one of multiple states, repeat the `state`
        parameter for each individual state.

        This endpoint also supports filtering and sorting of the results. See
        [filtering and sorting](../../../../meta/filtering) for more details.
      operationId: getRepositoriesUsernameRepoSlugPullrequests
      x-api-path-slug: repositoriesusernamerepo-slugpullrequests-get
      parameters:
      - in: path
        name: repo_slug
        description: 'This can either be the repository slug or the UUID of the repository,surrounded
          by curly-braces, for example: `{repository UUID}`'
      - in: query
        name: state
        description: Only return pull requests that are in this state
      - in: path
        name: username
        description: 'This can either be the username or the UUID of the user,surrounded
          by curly-braces, for example: `{user UUID}`'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pullrequests
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---