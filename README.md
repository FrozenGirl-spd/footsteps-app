# Footsteps

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ffnplus%2Fproject-footsteps-app.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ffnplus%2Fproject-footsteps-app?ref=badge_shield)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/66839011f8424527bdf4a39b60ea6b4b)](https://www.codacy.com/manual/fnplus/footsteps-app?utm_source=github.com&utm_medium=referral&utm_content=fnplus/footsteps-app&utm_campaign=Badge_Grade)
[![CodeFactor](https://www.codefactor.io/repository/github/fnplus/footsteps-app/badge)](https://www.codefactor.io/repository/github/fnplus/footsteps-app)
[![Netlify Status](https://api.netlify.com/api/v1/badges/8e60385a-c75c-4b48-9d01-975f43285914/deploy-status)](https://app.netlify.com/sites/sharp-swanson-a61558/deploys)

## 🚀 Quick start

1. **Install the Gatsby CLI.**

   ```shell
   npm install -g gatsby-cli
   ```

2. **Fork & Clone the repo**

   ```shell
   git clone https://github.com/[yourname]/footsteps-app
   ```

3. **Install node dependencies**

   Use the Gatsby CLI to create a new site, specifying the starter.

   ```shell
   cd footsteps-app/
   npm install
   ```

4. **Add Credentials to .env**

   Create `.env.development` file and add your variables listed in `.env.example`

   Use the below credentials for testing purposes

   ```shell
   GATSBY_HASURA_GRAPHQL_URL=http://rle-test.herokuapp.com/v1/graphql
   GATSBY_HASURA_GRAPHQL_ADMIN_SECRET=!footstepstest!
   GATSBY_FIREBASE_API_KEY=AIzaSyCfv2UcXCifCqmo6PhpdjKajVcpP_8Al9M
   GATSBY_FIREBASE_AUTH_DOMAIN=fnplus-rle-test.firebaseapp.com
   GATSBY_FIREBASE_DATABASE_URL=https://fnplus-rle-test.firebaseio.com
   GATSBY_FIREBASE_PROJECT_ID=fnplus-rle-test
   GATSBY_FIREBASE_STORAGE_BUCKET=fnplus-rle-test.appspot.com
   GATSBY_FIREBASE_MESSAGING_SENDER_ID=1042822146411
   GATSBY_FIREBASE_APP_ID=1:1042822146411:web:d09d2baa58dd82ff49842e
   GATSBY_GOOGLE_TRACKING_ID=UA-154496987-1
   ```
   
   For access to the Firebase project, please fill [this](https://airtable.com/shrOevwzFNas0wis3) form.
   
   For access to the testing DB, use [this](https://rle-test.herokuapp.com/console/login) link & enter '!footstepstest!' as the password.

5. **Start developing.**
   Navigate into your new site’s directory and start it up.

   ```sh
   gatsby develop
   ```

6. **Open the source code and start editing!**

   Your site is now running at `http://localhost:8000`!

   _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

   Open the `footsteps-app` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## 🎓 Learning Gatsby

Full documentation for Gatsby lives [on the website](https://gatsbyjs.org/).

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples head [to our documentation](https://gatsbyjs.org/docs/).** In particular, check out the “<i>Guides</i>”, “<i>API Reference</i>”, and “<i>Advanced Tutorials</i>” sections in the sidebar.

We welcome suggestions for improving our docs. See the [“how to contribute”](https://gatsbyjs.org/contributing/how-to-contribute/) documentation for more details.

**Start Learning Gatsby: [Follow the Tutorial](https://gatsbyjs.org/tutorial/) · [Read the Docs](https://gatsbyjs.org/docs/)**

## :memo: License

Licensed under the [GPL v3 License](./LICENSE).

## 💜 Thanks

Thanks to our many contributors and to [Netlify](https://www.netlify.com/) for hosting [footsteps.dev](https://footsteps.dev) and our example sites.
