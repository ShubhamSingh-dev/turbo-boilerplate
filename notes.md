# Steps to create this project

### level 1 :

1. Initialized an empty turborepo
2. Deleted the docs app
3. added http-server , ws-server folder
4. added package.json in both the places
5. Added tsconfig.json in both the pieces, and imported it from @repo/typescript—config/base.json
6. Added @repo/typescript-config as a dependency in both ws-server and http-server

7. Added a build, dev and start script to both the projects
8. Update the turbo-config in both the projects (optional)
9. Initialize a http server , Initialize a websocket server