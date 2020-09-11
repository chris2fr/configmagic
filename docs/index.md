# ConfigMagic.com

[ConfigMagic.com](https://www.configmagic.com/) is a website for configuration management of all kinds.

Now where did I put that? What was that password again? Did I do that? ConfigMagic tries to answer these questions we ask ourselves, our providers, our coworkers and more. Ambitions of this website are to :

1. Document the architecture of deployed computer software and systems
2. Document where the passwords are and how to get to them (without storing the passwords or credentials themselves)
3. Isolate configuation information stores specific to each confguration grouping

I personally am not exactly sure how to o this, but my feeling is that as long as we put everything in one place, with one general approach shared by at least three people, we have something really powerful. 

## Current Approach

My thought to start this project is to have a Git Repository for each configuration grouping under ConfigMagic.com in addition to the core Git repository for ConfigMagic itself. For now, I will both put the common resources for ConfigMagic groupings and the congiuration of ConfigMagic.com itself in the same repositry (although, the config of ConfigMagic could be in its own Git Repository). This is based on covnention and less fancy tooling.

The ConfigMagic repository is here:  
[https://github.com/chris2fr/configmagic/](https://github.com/chris2fr/configmagic/)

Deployed MKDOCS to Ikoula server with webhook. Deployment tested.

## Hosted Configurations

These are configurations managed in some way.

### LesGrandsVoisins.com

The LesGrandsVoisins project is managed in the following repository.

[https://gitlab.com/lesgrandsvoisins/lgv/](https://gitlab.com/lesgrandsvoisins/lgv/)

It would be nice to have a MKDOCS webhook as well perhaps.

### Chris' Life

I, Chris Mann, manage my personal information here:

[https://pi.mann.fr](https://pi.mann.fr)

### CLient Michel Muszlak

Managed a few things that are documented here:  
https://www.mann.fr/en/company/extranet/mmuzslak/

### Volunteer Proposed Work for the ACParis.org

Documentation here:  
https://www.mann.fr/en/company/extranet/acparis-org/
