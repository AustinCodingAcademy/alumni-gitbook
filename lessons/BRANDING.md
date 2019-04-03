{% include "/includes/header.md" %}

# Branding

## Stop doing things no one is going to pay you to do

The first mistake new developers do when looking for a job is failing to actually
start. If you are not applying for a design job, do not spend time formatting your
resume or portfolio site. You should be able to get your personal brand up and
running within the class time today.

## Your personal brand

Your goal is to try to get your potential employers to say your name as many times
as possible. The best way to do that is to use your name as your brand.

- https://kevincolten.github.io
- https://austincodingacademy.com/hire/kevin-colten
- https://kevincolten.com
- https://kevincolten.com/KevinColten.pdf
- https://github.com/kevincolten
- https://linkedin.com/in/kevincolten
- https://en.gravatar.com/kevincolten

## Let's get to branding

We will create the resources we need in order to start the job search tonight.
If you are in the middle of creating a portfolio or resume page, I recommend setting
that aside for now and having these resources in place.

1. Update your linkedin, prettify your url => https://linkedin.com/in/kevincolten

2. Use your name as your GitHub username. Github will automatically fix it everywhere.

3. Create a [Gravatar](https://en.gravatar.com/)

4. Create a PDF, you can use [this](https://docs.google.com/document/d/1TP_k9JnO-DkgNijHRw8zun7NMzKekTTx5MCUpXrDfvU/edit?usp=sharing) as a baseline. Do not go over two pages.

5. [JSON Resume](https://jsonresume.org/): a [new resume standard](https://xkcd.com/927/)

   1. Create a new repo called `<username>.github.io`
   2. Pull down the empty repo
   3. Add a `package.json`: `npm init`
   4. Press enter a bunch of times
   5. Add a script to our `package.json`

      ```json
        "scripts": {
          "build": "resume export index.html --format html --theme flat_projects"
        }
      ```

   6. Add our dependencies: `npm install --save-dev github:kevincolten/jsonresume-theme-flat_projects#84491e5 github:kevincolten/resume-cli#b05d465`
   7. Create a file `resume.json` and replace the information [here](https://github.com/kevincolten/kevincolten.github.io/blob/master/resume.json) with your own.
   8. Run `yarn build`
   9. Put copy of PDF resume here.

6. Create your hire page on austincodingacademy.com

   1. Sign into GitHub
   2. Go To https://raw.githubusercontent.com/AustinCodingAcademy/austincodingacademy.com/preview/hire/kevin-colten.md and copy
   3. Paste into https://github.com/AustinCodingAcademy/austincodingacademy.com/new/preview/hire
   4. Replace data with your own
   5. Name the file `firstname-lastname.md`
   6. Click `Commit New File`

7. [Optional] Buy a custom domain => kevincolten.com

# Portfolio

## Projects

Our portfolio will be a combination of our different branded sites.

They will be listed with short descriptions and links on our four resumes

- LinkedIn
- GitHub
- Website
- ACA Hire Page

We should have at least two projects that are actively being worked on. These
projects must:

1. Have a hosted demo if it is a web app
1. Be styled with a CSS Framework
1. Have a descriptive README.md in the repo
1. Code must be linted
1. Code should be documented and commented
1. Hosted Project and master branch should have only complete features

{% include "/includes/footer.md" %}
