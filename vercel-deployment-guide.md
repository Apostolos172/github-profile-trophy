# [Vercel](https://vercel.com/) Deployment Guide

1. Create a Vercel project that imports from your GitHub fork.
2. Follow the steps that Vercel provides, making sure to:
	1. Set the root directory to `./`.
	2. Set the framework preset to `Other`.
	3. Generate two [GitHub PATs](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) with repo access enabled.
	4. Add two environmental variables `GITHUB_TOKEN1` and `GITHUB_TOKEN2` with the values of the GitHub PATs you generated.
3. All done!