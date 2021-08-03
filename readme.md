[use this stack](https://github.com/new?stack=github/ghstack-nextjs-ghpages)

<img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg" alt="Hugo" width="100" height ="50"/>   <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/OCR-A_char_Plus_Sign.svg" alt="Hugo" width="50" height ="50"/>   <img src="./githubpages.png" alt="Azure" />

<p>
     <img src="https://assets.vercel.com/image/upload/v1607554385/repositories/next-js/next-logo.png" height="20">
    <img src="https://github.githubassets.com/images/modules/site/icons/footer/github-mark.svg" height="20">
    <b>Use this stack</b> to spin up a static website in seconds.
</p>


## Why should you use this stack?
You can spin up your own personal website in seconds. This stack uses nextjs to generate the contents. Next.js gives you the best developer experience with all the features you need for production: hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more. No config needed. Read more about [next.js](https://nextjs.org/learn)

The website is hosted in [Github Pages](https://pages.github.com/). 

The stack also sets up a proper Github CI/CD environment by taing care of the following things
1. Branch Naming convention - You can use any branch prefixed with "dev" as your development environment. 
2. Branch Protection Setting - Developers working on this branch can work freely and push changes without a PR and a code reviewer. This facilitates quick development. However the `master` Branch is protected and it needs a Pull request to merge with 2 reviewers approving it. The Reviewers should be defined in CODEOWNERS file.
3. Enable Security alerts - A workflow will be setup for you to enable Dependabot alerts to detect vulnerabilities.
4. CodeQL Security Analysis - Discover vulnerabilities across a codebase with CodeQL, our industry-leading semantic code analysis engine

## What are the inputs to pass while setting up the stack?
```
# This is needed for dependabot workflow
- NPM_PASSWORD

# created by github stacks to be used by sendgrid action
- SENDGRID_API_KEY

# You dont have to pass this. Azure OIDC app will set the secret 
- PROD_SPN_ID
```

#### Github apps installed with this stack
```Azure```

#### Version summary
```nextjs version (17.0.2)```

#### deployment to github pages
```
au
```

## How to setup local development server?
```
# to start a local development environment, and view in browser.
npm run dev
open http://localhost:3000 

# to run tests
npm test

# to generate a production build
npm run build
```

## Learn more 

### Nextjs
Learn more about [next.js](https://nextjs.org/learn) from the official tutorial.
Visit [https://nextjs.org/docs](https://nextjs.org/docs) to view the full documentation.

### Github Pages
Learn more about [Github Pages](https://pages.github.com/)

## Other Useful links

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- chaitanya sharma ([@phoenix24](https://twitter.com/phoenix24)) 
- atul malaviya ([@azooinmyluggage](https://twitter.com/azooinmyluggage))
- usha narayanabhatta ([@n-usha](https://twitter.com/n-usha))
- trilok ramakrishna ([@3loka](https://twitter.com/3loka))

