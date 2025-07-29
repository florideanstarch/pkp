# PKP

A personal blog on musings of two humans under the influence of LLMs and biology.

In a new Github Codespace (for an intialized repo) check that the latest `npm` is being used with `npm --version` (`node --version` should also be >22.0). Get the latest version of `npm` from `npm install -g npm@latest`.

Some useful commands:
- Check the page locally: `npx quartz build --serve`
- Publish to Github Pages: `npx quartz sync`

A `deploy.yml` rests in the `.github/workflows/` directory. This is has all the configuration for Github Pages. 

Don't forget to enable Github Actions in Settings > Pages > Build and deployment. 

Also, set Settings > Actions > Workflow Permissions to "Read and Write" and check the "Allow Github Actions to create and approve pull requests" box.

We have used [Quartz](https://quartz.jzhao.xyz/) to make this blog. Thanks Jacky Zhao!