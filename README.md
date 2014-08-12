# Panamax: Docker Management for Humans

[Panamax](http://panamax.io) is a containerized app creator with an open-source app marketplace hosted in GitHub. Panamax provides a friendly interface for users of Docker, Fleet & CoreOS. With Panamax, you can easily create, share, and deploy any containerized app no matter how complex it might be. Learn more at [Panamax.io](http://panamax.io) or browse the [Panamax Wiki](https://github.com/CenturyLinkLabs/panamax-ui/wiki).

# Panamax Contest Template Repo
[![Build Status](https://api.shippable.com/projects/53e29b2d4f881a8700879052/badge/master)](https://www.shippable.com/projects/53e29b2d4f881a8700879052)

Repo of the panamax template contest submissions. See: [panamax.io/contest](http://panamax.io/contest) for more information.

[Learn more about what we think makes a good image and template.](https://github.com/CenturyLinkLabs/panamax-ui/wiki/Panamax-Public-Templates)

## How to Submit a Contest Entry
1. Install Panamax using the directions from  http://panamax.io/get-panamax
2. Create the best template you can think of, using the guidelines listed in the documentation at  http://panamax.io/documentation
3. Fork Panamax Contest Template Repository from https://github.com/CenturyLinkLabs/panamax-contest-templates to your personal GitHub account
4. Press "Save as Template" for your new application and save your template to your forked panamax-contest-templates repository
5. Once your template is ready, go to GitHub and submit a pull request from your forked panamax-contest-templates repository, make sure to include any additional information in the comments of the pull request like how you are promoting it (urls to blog posts/twitter mentions/etc.).

## Validating your template
Once a Pull Request has been issued, the [Panamax Template Validator](https://github.com/CenturyLinkLabs/panamax-template-validator) will run a quick sanity check on new or changed *.pmx files. If you would like to run the validator locally, in advance, simple run ```rake``` from the root of the forked template repo.
