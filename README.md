MeDB plugin for GitHub
======================

This plugin fetches user statistics from GitHub.

Configuration
=============

```
{
  "github": {
    "username": "your username here"
  }
}
```

Data
====

* `github`: general user stats
  * `public_repos`
  * `public_gists`
  * `followers`
  * `following`
  * `longest_streak`
  * `current_streak`
  * `contributions_year`: "Contributions in the last year" value from user page
  * `popular_repo_stars`: sum of stars from top 5 public repos (on user page)

* `github_stars`: star stats per repo (top 5 from user page only)
  * `repo`: repo name
  * `stars`: number of stars
