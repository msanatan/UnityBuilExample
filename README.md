# Unity Build Example

Sample project to prep for a game jam! The key thing is getting CI/CD so that I can build from GitHub straight to itch.io (and other destinations).

## Set up and notes

- Project is built with Unity 2021.24.1f1
- Default build targets are Linux, Windows, MacOS and WebGL
- You need to do a one time activation step to get the Unity license to work with CI/CD. See [this page](https://game.ci/docs/github/activation/) for details
- To build in Unity, you need to set up 3 secrets: `UNITY_LICENSE`, `UNITY_EMAIL` and `UNITY_PASSWORD`. See [this page](https://game.ci/docs/github/activation/) for details
- To deploy to itch.io, you need to set up 3 secrets: `BUTLER_CREDENTIALS`, `ITCH_GAME` and `ITCH_USER`. See [this page](https://itch.io/docs/butler/login.html) for details
