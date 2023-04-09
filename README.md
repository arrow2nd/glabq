# glabq

Clone GitLab repositories using fzf and ghq.

## Requirements

- jq
- [fzf](https://github.com/junegunn/fzf)
- [ghq](https://github.com/x-motemen/ghq)

## Usage

```sh
$ glabq --help

Clone GitLab repositories using fzf and ghq.

USAGE:
  glabq [command] [user or group id]

COMMANDS:
  user     Search user-owned repositories
  group    Search group-owned repositories

FLAGS:
  --help   Show this help

ENVIRONMENT VARIABLE:
  GLABQ_GITLAB_HOST     GitLab host name (default: gitlab.com)
  GLABQ_USE_HTTPS       Use HTTPS for Clone (default: false)
  GLABQ_DEFAULT_USER    ID to be used when userid is omitted
  GLABQ_DEFAULT_GROUP   ID to be used when groupid is omitted

EXAMPLES:
  glabq user arrow2nd
  glabq group gitlab-org
```

## Inspired by

- [kawarimidoll/gh-q](https://github.com/kawarimidoll/gh-q)
