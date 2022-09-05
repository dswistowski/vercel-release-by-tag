# Example how release to [vercel.com](http://vercel.com) production with tagging 

For easy releases with tagging to vercel:

1. Create a `production` branch
2. Configure `vercel` to deploy from `production` branch
3. Add GitHub action to deploy to `production` branch on tag push, by pushing to `production` branch

This example repo is released to [https://vercel-release-by-tag.vercel.app/](https://vercel-release-by-tag.vercel.app/) after tagging, 
every change to master is released to [https://staging-vercel-release-by-tag.vercel.app/](https://staging-vercel-release-by-tag.vercel.app/)

# Create T3 App

This is an app bootstrapped according to the [init.tips](https://init.tips) stack, also known as the T3-Stack.

