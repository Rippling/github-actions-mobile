# github-actions-mobile

Repository for GH actions shared between mobile repositories

<br />

## Avaiable Actions

**Note:** _click on action description to see inputs description._

<br />

### Git init `init-git`

<details>
  <summary>Configure git user so script would be able to read and write repositories if necessary</summary>

#### Inputs

- `ssh-private-key` private key with write access to repository
- `ssh-public-key` public key as above
- `git-user-email` Email to use in git client
- `git-user-name` User name to be displayed
</details>
<br />

### Prepare android `prepare-android`

<details>
<summary>Prepare android configuration for production app build</summary>

#### Inputs

- `keystore-string` GPG encrypted keystorefile
- `keystore-passphrase` Passphrase to decrypt keystorefile
- `keystore-alias` Keystore alias
- `keystore-password` Keystore file password
- `keystore-alias-password` Keystore alias password
- `maps-debug-key` Debug api key for google maps
- `maps-prod-key` Production api key for google maps
- `sentry-token` Sentry auth token
- `sentry-org-name` Sentry Organisation name
- `sentry-project-slug` Slug/Name of the project in sentry
</details>

<br />

### Prepare javascript `prepare-js`

<details>
<summary>Prepare mobile node modules, as well as webapp submodule</summary>

#### Inputs

none

</details>

<br />
