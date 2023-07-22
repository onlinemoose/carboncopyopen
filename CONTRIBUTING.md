# Contributions to this project
For contributions to this project, please create a PR from feature branch, 

- We will review the changes
- Test it in development
- Promote to production

As of now we don't have a mock server's to test the changes locally, however you could mock the [store data](src\store\initialState.js) locally for dev/test.

# Install 

`npm i`

# Firebase Project Links

[Production](https://console.firebase.google.com/project/carboncopy-53bd1/overview)

[Development](https://console.firebase.google.com/project/carboncopy-4f14e/overview)

# Miro App Id

`Production`: 3074457362254861860

`Development`: 3074457352071726785

# Build and deploy to firebase server 

`Production`: npm run dist:production

`Development`: npm run dist:development

Note: Firebase access will be restricted only to project moderators