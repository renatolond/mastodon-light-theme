# Mastodon Light Theme
A dark-on-light theme for [Mastodon](joinmastodon.org).

## Setup

### Instance admins
1. Copy `mastodon_light.scss` and the `mastodon_light` folder in `app/javascript/styles`
2. Add the following line in `config/themes.yml`: `masto_light: styles/mastodon_light.scss`
3. Run `RAILS_ENV=production bundle exec rails assets:precompile`
4. Restart Mastodon

### Regular users
(assuming your instance admin installed the theme)
1. Go to your settings
2. Look for the `Site Theme` dropdown
3. Select the `masto_light` theme if available