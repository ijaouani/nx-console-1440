# How this repo has been build ?

1. Create a node devcontainer
2. Create a nx workspace with the following configuration :

```
node ➜ /workspaces/nx-console-1440 $ npx create-nx-workspace@latest
Need to install the following packages:
  create-nx-workspace@15.5.1
Ok to proceed? (y) y

 >  NX   Let's create a new workspace [https://nx.dev/getting-started/intro]

✔ Choose what to create                 · package-based
✔ Repository name                       · test
✔ Enable distributed caching to make your CI faster · No

 >  NX   Nx is creating your v15.5.1 workspace.

   To make sure the command works reliably in all environments, and that the preset is applied correctly,
   Nx will run "npm install" several times. Please wait.

✔ Installing dependencies with npm
✔ Nx has successfully created the workspace: test.

 >  NX   Directory is already under version control. Skipping initialization of git.


 ————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————


 >  NX   First time using Nx? Check out this interactive Nx tutorial.

   https://nx.dev/core-tutorial/01-create-blog
   ```
