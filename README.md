# RAK

Random acts of Kindness (RAK) is a mobile-first web application where trusted organisations and charities can create wish lists of items for prospective donors. Each year charities receive donations that do not meet their specific needs or campaign goals, resulting in millions of dollars&#39; worth of goods going to waste each year. Fundamentally, RAK&#39;s goal is to streamline the process of donating goods whilst minimising waste.

**Key features/User stories:**

**Donors**

- can create accounts.
- have account authentication.
- can follow organisations.
- have a public list of projects.
- can filter projects by radius, donation type, events, and categories.

**Organizations**

- verified organisations can create an account and build a profile.
- profiles include branding elements, projects, and mission statement.
- organizations can create projects.
- organizations can create events i.e. Napa Fire.
- organisations can add/update/delete entries.
- organization accounts are verified via their EIN using the Guidestar API.

**Stretch goals:**

- Sign-in with Facebook/Google.
- Secure payment (Stripe, Square, Paypal).

**Contributors:**

 Quynh Nguyen, Lorraine Hemenway, Youssef Kholeif, Maria-Luisa Ramos, Sarah Caplan



**System Configuration:**

- Ruby/Rails version: Ruby 2.3.3, rails Rails 5.1.4 
- System dependencies 
- Configuration 
- Database creation :  
- Database initialization 
- How to run the test suite 
- Services (job queues, cache servers, search engines, etc.) 
- Deployment instructions

## Deploy from Command Line
> Download and Install the Heroku CLI with homebrew

`$ brew install heroku/brew/heroku`

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

`$ heroku login`
 
If you already have the repository cloned on your local machine, pull latest commits from development branch first.

`git pull origin development`

*or*

If you do not have it, clone the repository. Use Git to clone rak-backend's source code to your local machine.


`$ heroku git:clone -a rak-frontend`

`$ cd rak-backend`

Deploy your changes to Heroku

`$ git push heroku development:master`

*NOTE:* The command above will deploy the development branch on git to the master branch on Hreoku.

To view logs in the terminal, run

`$ heroku logs -t --app rak-frontend`
