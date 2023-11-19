# 1. Amplify is not installing on the npm >@6 version
We have to use this command instead of using only `npm install -g @aws-amplify/cli`.
```
npm install -g @aws-amplify/cli --unsafe-perm=true
```
- The `--unsafe-perm=true` flag is used to override the default behavior of npm when it runs scripts as a specific user (typically, the user who owns the npm process).
