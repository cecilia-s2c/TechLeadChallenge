# Welcome!
I'm very excited to see you've come until here. This challenge is built with the intention of knowing how you solve everyday tasks of this role, as commented during the interviews, although the code does not figure as the greatest of my activities it is important to have experience and knowledge
If you have any question, comment, whatever, please let me know.

## Prepare environment

Create a PGP key.

Use PGP to send an encrypted message to cecilia@safe2choose.org with your public PGP key attached. The public key you need for cecilia@safe2choose.org can be found here https://mega.nz/#!LNoVCDrK!FWnL-nPmo4XDuFpfFERPWerAYcxVcZUtFf2YaXw12fg

Create a Github account. For privacy and security reasons, create a new Github account just for these exercises

Fork and clone this repository.


## Step 1: Code review

Review the code into the "Step1" folder for security vulnerabilities. This Meteor project is meant to keep track of the number of times each user clicks on the button on the client. The count per user is recorded in two places: On the Meteor server that the app is connected to. On a server located at secure.safe2choose.org (this server does not actually exist).

Only the counts of users who have signed in with Twitter need to be securely stored. The count of users who are not logged in is irrelevant.

Deliverable: Create a README file with explanations of the vulnerabilities you are able to find. For extra points, correct the source code to fix those issues. When finished, commit your changes and push to your own repositorie and create a pull request to merge your changes with the original repo (mine).


## Step 2: Wordpress customization

Review the file functions.php into "Step2" folder and add comments to the function #gform_display_weeks explaining what it does.

Register a new sidebar that will be used for advertising, the container is a div with the class "module--primary" and the title is an h3 with the class "module__title", name and description must be translatable and have "safe2choose-test" as the value for the domain parameter.

The file "testimonials.php" is an older version of the template used for https://safe2choose.org/testimonials-on-abortion/, make the changes necessary to:

Show the extract of every testimonial instead of the whole content

Use the title as a hyperlink to see the full testimonial

Add a comment explaining what does "'posts_per_page' => -1," in line 41 for the query.

Commit and push your changes.

## Step 3: Interfaces

Considering the project https: //findmymethod.org /

It is desired to improve the usability of the Find My Method section to include 3 new filters in the preferences and add a new functionality: the user after obtaining the suggestions when playing with the filters should be able to select up to 3 methods and with one click get to the Compare Methods section, where the information of these selected methods must be shown

Make a mockup with a proposal of what elements should be integrated, here an example: https://taorunqiao.github.io/web1/assignment-7/images/home.png

There is no limit on the detail or tools used


## Step 4: Analysis

The safe2choose project has decided to use AMP to reach its audiences in the most remote regions, in order to develop a work plan it is extremely important to make certain decisions, in this case, with which framework this new version will be developed.

Make a brief analysis and make a recommendation about the chosen framework

The only two options are Jekyll and HUGO

Important note: because safe2choose is a project developed with Wordpress there is very little chance of being able to migrate the content from one side to another, the most likely is that the team will have to copy and paste each page of the site manually.


## Step 5: Work plan
Considering the new functionalities of the previous step, define a work plan, take care of the following details:

Define tasks in their simplest form, example: create a new category, assign the content to the new category, etc.

Assign a person responsible for each task, the roles could be: designer, developer, project manager, etc.

Mention the estimated time in hours

Indicate the materials you consider required for each task.

There is no limit on the use of tools.

    
## Step 6: Submission

Don't forget to  commit and push all changes to Github

Send an encrypted email to cecilia@safe2choose.org with a link to your repository.
