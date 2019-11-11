# footsteps-app

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ffnplus%2Fproject-footsteps-app.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ffnplus%2Fproject-footsteps-app?ref=badge_shield)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/66839011f8424527bdf4a39b60ea6b4b)](https://www.codacy.com/manual/fnplus/footsteps-app?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=fnplus/footsteps-app&amp;utm_campaign=Badge_Grade)
[![CodeFactor](https://www.codefactor.io/repository/github/fnplus/footsteps-app/badge)](https://www.codefactor.io/repository/github/fnplus/footsteps-app)
[![Netlify Status](https://api.netlify.com/api/v1/badges/8e60385a-c75c-4b48-9d01-975f43285914/deploy-status)](https://app.netlify.com/sites/sharp-swanson-a61558/deploys)

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the starter.

    ```sh
    # create a new Gatsby site using the hello-world starter
    gatsby new footsteps-app https://github.com/fnplus/footsteps-app
    ```
1.  **Deploy Hasura graphql**

    [Deploy Hasura to Heroku](https://docs.hasura.io/1.0/graphql/manual/getting-started/heroku-simple.html)
    
    [Secure GraphQL endpoint](https://docs.hasura.io/1.0/graphql/manual/deployment/heroku/securing-graphql-endpoint.html#add-the-hasura-graphql-admin-secret-env-var)
    
    [Install Hasura CLI](https://docs.hasura.io/1.0/graphql/manual/hasura-cli/install-hasura-cli.html)
    
    [Download api migrations](https://github.com/fnplus/footsteps-app/raw/master/rle-api.zip)
    
    [Apply migrations to your instance](https://docs.hasura.io/1.0/graphql/manual/migrations/existing-database.html#step-6-apply-the-migrations-on-another-instance-of-graphql-engine)

1.  **Start developing.**
    create .env.development file and add your variables listed in .env.example
    Navigate into your new site’s directory and start it up.

    ```sh
    cd footsteps-app/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `footsteps-app` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)]()
