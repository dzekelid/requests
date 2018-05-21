---
name: Bitbucket
x-slug: bitbucket
description: Code against the Bitbucket API to automate simple tasks, embed Bitbucket
  data into your own site, build mobile or desktop apps, or even add custom UI add-ons
  into Bitbucket itself using the Connect framework.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: Requests
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests
  x-api-slug: bitbucket
  description: |-
    Returns a paginated list of all pull requests on the specified
    repository. By default only open pull requests are returned. This can
    be controlled using the `state` query parameter. To retrieve pull
    requests that are in one of multiple states, repeat the `state`
    parameter for each individual state.

    This endpoint also supports filtering and sorting of the results. See
    [filtering and sorting](../../../../meta/filtering) for more details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests
  tags: Repositories, Username, Repo, Slug, Pullrequests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequests-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests
  tags: Repositories, Username, Repo, Slug, Pullrequests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequests-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequests-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Pullrequests
  x-api-slug: bitbucket
  description: Post repositories username repo slug pullrequests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests
  tags: Repositories, Username, Repo, Slug, Pullrequests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequests-post-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Activity
  x-api-slug: bitbucket
  description: |-
    Returns a paginated list of the pull request's activity log.

    This includes comments that were made by the reviewers, updates and
    approvals.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/activity
  tags: Repositories, Username, Repo, Slug, Pullrequests, Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestsactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestsactivity-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Activity
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests activity
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/activity
  tags: Repositories, Username, Repo, Slug, Pullrequests, Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestsactivity-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestsactivity-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request
  x-api-slug: bitbucket
  description: Get repositories username repo slug pullrequests pull request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-id-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-id-parameters-openapi.md
- name: Bitbucket Update Repositories Username Repo Slug Pullrequests Pull Request
  x-api-slug: bitbucket
  description: |-
    Mutates the specified pull request.

    This can be used to change the pull request's branches or description.

    Only open pull requests can be mutated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-id-put-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Activity
  x-api-slug: bitbucket
  description: |-
    Returns a paginated list of the pull request's activity log.

    This includes comments that were made by the reviewers, updates and
    approvals.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/activity
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idactivity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idactivity-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Activity
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  activity
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/activity
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Activity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idactivity-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idactivity-parameters-openapi.md
- name: Bitbucket Delete Repositories Username Repo Slug Pullrequests Pull Request  Approve
  x-api-slug: bitbucket
  description: Delete repositories username repo slug pullrequests pull request  approve
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/approve
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Approve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-delete-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Approve
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  approve
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/approve
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Approve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Pullrequests Pull Request  Approve
  x-api-slug: bitbucket
  description: Post repositories username repo slug pullrequests pull request  approve
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/approve
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Approve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idapprove-post-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Comments
  x-api-slug: bitbucket
  description: |-
    Returns a paginated list of the pull request's comments.

    This includes both global, inline comments and replies.

    The default sorting is oldest to newest and can be overridden with
    the `sort` query parameter.

    This endpoint also supports filtering and sorting of the results. See
    [filtering and sorting](../../../../../../meta/filtering) for more
    details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/comments
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcomments-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Comments
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  comments
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/comments
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcomments-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcomments-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Comments
    Comment
  x-api-slug: bitbucket
  description: Get repositories username repo slug pullrequests pull request  comments
    comment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Comments,
    Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommentscomment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommentscomment-id-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Comments
    Comment
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  comments
    comment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/comments/{comment_id}
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Comments,
    Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommentscomment-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommentscomment-id-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Commits
  x-api-slug: bitbucket
  description: |-
    Returns a paginated list of the pull request's commits.

    These are the commits that are being merged into the destination
    branch when the pull requests gets accepted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/commits
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Commits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommits-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Commits
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  commits
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/commits
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Commits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommits-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idcommits-parameters-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Decline
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  decline
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/decline
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddecline-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddecline-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Pullrequests Pull Request  Decline
  x-api-slug: bitbucket
  description: Post repositories username repo slug pullrequests pull request  decline
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/decline
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddecline-post-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Diff
  x-api-slug: bitbucket
  description: Get repositories username repo slug pullrequests pull request  diff
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/diff
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Diff
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddiff-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddiff-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Diff
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  diff
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/diff
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Diff
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddiff-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-iddiff-parameters-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Merge
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  merge
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/merge
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Merge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idmerge-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idmerge-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Pullrequests Pull Request  Merge
  x-api-slug: bitbucket
  description: Post repositories username repo slug pullrequests pull request  merge
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/merge
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Merge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idmerge-post-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Patch
  x-api-slug: bitbucket
  description: Get repositories username repo slug pullrequests pull request  patch
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/patch
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Patch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idpatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idpatch-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Patch
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  patch
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/patch
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Patch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idpatch-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idpatch-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pullrequests Pull Request  Statuses
  x-api-slug: bitbucket
  description: Get repositories username repo slug pullrequests pull request  statuses
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/statuses
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Statuses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idstatuses-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Pullrequests Pull Request  Statuses
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug pullrequests pull request  statuses
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pullrequests/{pull_request_id}/statuses
  tags: Repositories, Username, Repo, Slug, Pullrequests, Pull, Request, , Statuses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idstatuses-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/repositoriesusernamerepo-slugpullrequestspull-request-idstatuses-parameters-openapi.md
- name: Bitbucket
  x-api-slug: bitbucket
  description: Code against the Bitbucket API to automate simple tasks, embed Bitbucket
    data into your own site, build mobile or desktop apps, or even add custom UI add-ons
    into Bitbucket itself using the Connect framework.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/bitbucket-logo.png
  humanURL: https://bitbucket.org/
  baseURL: https://api.bitbucket.org//2.0
  tags: Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/requests/master/_listings/bitbucket/openapi.md
x-common:
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---