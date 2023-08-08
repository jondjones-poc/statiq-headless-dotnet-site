# Statiq Headless SSG WIth Netlify Demo Site - By Jon D Jones 💥

Example of how to use Statiq .NET static-site generation with markdown files and host it on Netlify

## Installation

Clone the repo.  This site makes use of the default Statiq theme, which you can find [here](https://github.com/statiqdev/CleanBlog/tree/9a1d228c5a05dff89094beb249887aabc6d24eb4).

The theme is added as a GitSubmodule and lives within the `theme` folder.  You can see the submodule reference in `.gitmodules`.  You will need to pull the files from the sub-module before the site will work.  You can do that usign this command:

```
git submodule update --init --recursive
```

After you have the files you can build the site using:

```
dotnet run
```

You can then access the site locally using:

```
http://localhost:5080/
```

## 👻 Live Site URL, Github & Status 👺

You can see and access this site using these details:

- [Github](https://github.com/jondjones-poc/statiq-headless-dotnet-site)

- [Website on Netlify](https://statiq-headless-site.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/80387042-fd8d-4044-964d-7b32c61b669a/deploy-status)](https://app.netlify.com/sites/statiq-headless-site/deploys)

## 🔗 Useful Documentation

- [Statiq website](https://www.statiq.dev/)
