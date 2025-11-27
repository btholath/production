==========================================================================
Deployment of Flask API from IDE to Vercel
==========================================================================
(venv) bijut@b:~/aws_apps/production/API$ vercel login
Vercel CLI 48.11.0

  Visit https://vercel.com/oauth/device?user_code=GDBQ-SGLD

  Congratulations! You are now signed in.

  To deploy something, run `vercel`.

  💡 To deploy every commit automatically,
  connect a Git Repository (vercel.link/git (https://vercel.link/git)).
(venv) bijut@b:~/aws_apps/production/API$ vercel
Vercel CLI 48.11.0
? Set up and deploy “~/aws_apps/production/API”? yes
? Which scope should contain your project? Biju's projects
? Link to existing project? no
? What’s your project’s name? (api)
(venv) bijut@b:~/aws_apps/production/API$ vercel .
Vercel CLI 48.11.0
? Set up and deploy “~/aws_apps/production/API”? yes
? Which scope should contain your project? Biju's projects
? Link to existing project? no
? What’s your project’s name? api
? In which directory is your code located? ./
? Do you want to change additional project settings? no
🔗  Linked to bijus-projects-71507ffb/api (created .vercel and added it to .gitignore)
? Would you like to pull environment variables now? no
🔍  Inspect: https://vercel.com/bijus-projects-71507ffb/api/5peZvRXJ42mmMJcTRbjj3JKRYC9M [894ms]
✅  Production: https://api-ixezhd064-bijus-projects-71507ffb.vercel.app [11s]
📝  Deployed to production. Run `vercel --prod` to overwrite later (https://vercel.link/2F).
💡  To change the domain or build command, go to https://vercel.com/bijus-projects-71507ffb/api/settings
❗️  Due to `builds` existing in your configuration file, the Build and Development Settings defined in your Project Settings will not apply. Learn More: https://vercel.link/unused-build-settings
(venv) bijut@b:~/aws_apps/production/API$
==========================================================================
