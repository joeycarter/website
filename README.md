# Website

My personal website, powered by [Hugo](https://gohugo.io) and the [Para-Minimal](https://github.com/joeycarter/para-minimal) theme.

---

<p align="center">
<a href="https://joeycarter.github.io/" target="_blank" rel="noopener noreferrer">joeycarter.github.io</a>
</p>

---

## Add a New Blog Post

From the project root directory, run:

```console
$ hugo new post/<post-name>.md
```

The new blog post template file will be created under `content/post/`. Change `'draft: true'` to `'draft: false'` in the file header before publishing the final version.

## Testing and Deploying

Build the website with Hugo (this places the complete website in the `public` directory) and start the Hugo server to preview the site in a web browser:

```console
$ hugo
$ hugo server
```

Check the output for the `localhost` path; this is normally http://localhost:1313/. Open the link in a web browser to preview the website. The server should watch for local changes by default and automatically update the site.

When ready, publish the site to github.com/joeycarter/joeycarter.github.io by committing and pushing the changes. The `public` directory is set up as a `git` submodule for this repository. The live version will update after a few minutes. For convenience, use the `deploy.sh` script to automatically commit and publish the website:

```console
$ ./deploy.sh
```
