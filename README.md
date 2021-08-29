# gitea-github-theme
An opinionated GitHub-based theme for Gitea

Created and tested with Gitea v1.15.
The theme might work with future versions though Gitea devs might change some CSS classes in the meantime and things might potentially look odd - just try yourself :)

I might update the theme over time to fix oversights and other issues - no guarantee though.
## Installation

1. If you do not have admin access to a Gitea instance, you can use the [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne/related) browser extension and use the CSS provided in this repo for the Gitea URL
2. If you are an admin and want to make this theme available to all users:
   1. Put `theme-github.css` into `$GITEA_PUBLIC/public/css/theme-github.css` where `$GITEA_PUBLIC` is the "CustomPath" of your instance reported by `gitea help`.
   2. Add `github` to the comma-separated list in the setting `THEMES` in `app.ini`
   3. Now users can select this theme in their settings under "account"
   4. (optional) If you want to make this theme the default of your instance, set it in `DEFAULT_THEME` in `app.ini`

## Changes to default Gitea theme

- Aligned primary green, grey, red and blue colors with GitHub
- Aligned `border-radius` with GitHub
- Related theme by removing a lot of hover colors and dominant button background-colors
- Aligned markup background to GitHub's value
