# webpack-dev-server-hmr-issue

## Reproduction Instructions

1. `yarn`

2. `yarn dev`

3. Navigate to http://localhost:8080 in your browser

4. Edit text in `src/index.js`

5. Observe full page reload

6. Exit dev server

7. `yarn patch` to add `devServer: { liveReload: false }` to `preact-cli` config

8. `yarn dev`

9. Edit text in `src/index.js`

10. Observe HMR
