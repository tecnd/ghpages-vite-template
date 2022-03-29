# ghpages-vite-template
Template with the basic Vite/React project and a GitHub action to build and deploy the site to GHPages. By default, force-commits the dist directory to the gh-pages branch and clobbers whatever was there.

Make sure to change the base path in `vite.config.js` to the name of your repo, since GHPages are hosted at `<user>.github.io/<repo>`. For example, this template is available at <https://tecnd.github.io/ghpages-vite-template/>.
