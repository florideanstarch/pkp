# PKP

A personal blog on musings of two humans under the influence of LLMs and biology.

In a new Github Codespace (for an intialized repo) check that the latest `npm` is being used with `npm --version` (`node --version` should also be >22.0).

If not, get the latest version of `npm` using `npm install -g npm@latest`.

Then run `npm i`.

Now you can:
- Check the page locally: `npx quartz build --serve`, or
- Publish it on Github Pages: `npx quartz sync`

A `deploy.yml` rests in the `.github/workflows/` directory. This is has all the configuration for Github Pages. 

Don't forget to enable Github Actions in Settings > Pages > Build and deployment. 

Also, set Settings > Actions > Workflow Permissions to "Read and Write" and check the "Allow Github Actions to create and approve pull requests" box.

We have used [Quartz](https://quartz.jzhao.xyz/) to make this this work. Thanks Jacky Zhao!

Check out the blog [here](https://florideanstarch.github.io/pkp/).