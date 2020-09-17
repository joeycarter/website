# Website

My personal website, powered by [Hugo](https://gohugo.io) and the [Para-Minimal](https://github.com/joeycarter/para-minimal) theme.

---

<p style="text-align: center;">
joeycarter.github.io
</p>

---

## Testing and Deploying

Build the website with Hugo (this places the complete website in the `public` directory) and start the Hugo server to preview the site in a web browser:

```bash
$ hugo
$ hugo server
```

Check the output for the `localhost` path; this is normally http://localhost:1313/. Open the link in a web browser to preview the website. The server should watch for local changes by default and automatically update the site.

When ready, publish the site to github.com/joeycarter/joeycarter.github.io by committing and pushing the changes. The `public` directory is set up as a `git` submodule for this repository. The live version will update after a few minutes. For convenience, use the `deploy.sh` script to automatically commit and publish the website:

```bash
$ ./deploy.sh
```
