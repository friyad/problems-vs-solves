# 1. Amplify is not installing on npm >@6 verson
- We have to use `npm install -g @aws-amplify/cli --unsafe-perm=true` instead of using only `npm install -g @aws-amplify/cli`.
- The `--unsafe-perm=true` flag is used to override the default behavior of npm when it runs scripts as a specific user (typically, the user who owns the npm process).
