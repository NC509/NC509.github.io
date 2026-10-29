# Introduction
Here I will explain how you too can make an e-portfolio here on GitHub. If you follow these steps you can have a similar e-portfolio like mine to display your projects that you have been working on! I will explain the required steps that need to be taken, as well some helpful advice on how to refine your page to truly make it yours. 

Before we begin, our goal from this is to make a `github.io` e-portfolio. This requires you to have a GitHub account. In having this account please keep in mind that people will be able to view your account so make a professional username, and a picture you are comfortable with potential employers viewing. Additionally, keep in mind, for others to view your page, they will need to write out your username. The `github.io` file is structured as, `<username>.github.io`, so again please make a professional username. 

Once you have completed your account set up, we are ready to begin!
 - I will explain this through the website version of GitHub rather than using app. 

## <ins>Dictionary</ins>
1. Repository -
2. Commit -
3. Push -
4. Zipper file - A zipper file is a compressed file, reducing its size, to make the downloading process much smoother.

# Required steps to make an e-portfolio. 
In the making of this portfolio we rely on a template called, ["minimal"](https://github.com/pages-themes/minimal). This is a GitHub Repository that allows us to download the files, upload it to our page, and customize our content to represent our page. There are many templates out there that I encourage you to explore, but using this pre-made "minimal" template first is a great way to gain a foundational understanding. 

If interested, you can find other templates through the following links: ["templates on GitHub"](https://github.com/topics/jekyll-theme), ["academicpages.github.io"](https://academicpages.github.io/), ["Mundana Theme"](https://github.com/codebygina/mundana-theme-jekyll), and ["minimal-mistakes"](https://github.com/mmistakes/minimal-mistakes).

## Step 1, Creating your github.io repository
We first want to make our github.io repository. You can do this by hitting the `+` symbol at the top right corner next to your profile picture and click "New Repository". For your repository name, write your username and .github.io right after, as shown here `<username>.github.io`. Make sure the repository is public, add a README file, and it is good practice to select "MIT License" in the add license section. Adding MIT License gives us a preset of how we would like others to use our code if they wish to do so. At this point we have a simple repository, you don't have to edit anything at this point in time, we will come back to this. 

Next we are going to download this repository into our personal machine(computer), by clicking `<code>` and "Download Zip". We then want to go to that file location and press "Extract All" to get the contents of our file. This process is called "cloning", and we would like to do this step prior to the next one. When downloading please keep your files organized so it is easier to locate at a later time. 

## Step 2, Download "minimal" template

Now, we want to go to the template ["minimal"](https://github.com/pages-themes/minimal), and download the zip file from this template. Extract the contents of this folder and place it within the same folder as your cloned github.io repository from step 1. Next, let's go back to the GitHub repository page and click "Add file" then upload the file we just made into your repository. When adding the file, sometimes it may work best if you open the folder you are uploading, and select all the files within it. When highlighting all the files to upload and committing to these changes will achieve the same result. It is natural to see sometimes that there will be some files that will not upload in this step due to the file being attached to a public source, in which it won't let you upload. It is totally fine, as long as we have the files we need to edit our page and have the files that help it run. On my personal repository I trimmed down to these following folders/files:"_includes", "_layouts", "_sass", "assets", "script", "Gemfile", "README.md", "_config.yml", "index.md", and "jekyll-theme-minimal.gemspec". 

If you are on the GitHub application you can commit and push these changes to your GitHub account to meet the same outcome. 

As of this step you should see the contents of the files you have uploaded from the minimal theme to your repository. If you had any other files with the same name, such as the "README.md" that we first made for the .github.io repository it will be overwritten. When uploading files with the same name and committing the changes, the current file will be overwritten by the new files that were just uploaded. In this case this is expected and wanted for what we are trying to do, but please keep this in mind for future projects. 

## Step 3, Customization 
This is where the fun begins...if you aren't already having fun...but I hope you have been `:)`

Here in this step will be the visible customization to your page. Your current page should look like the following. 

<img width="450" height="300" alt="image" src="https://github.com/user-attachments/assets/4f3a6517-bc0a-4dfa-ba27-7499086f55dc" />

The edits we make to the `Config.yml` file will make the changes seen on the left with the "logo" and the changes we make to the `index.md` will make the changes to the right side with the "Headers". We are going to follow the directions from the minimal template from the "README.md" file under "Usage" and "Configuration".

### Config.yml file
As explained through the template file, we want to change this config file. Go to the `Config.yml` file in your repository. We want to customize your page title, insert a professional headshot photo into the "logo" section, and add a description message. There are some optional additions such as "remote_theme" and "plugins". You have some options like "show_downloads" which you can make true/false if you would like the page to display options for others to download the page. With the "google_analytics" this would allow you to insert your google analytics ID to track visitor data from your page. _I personally had downloads as "FALSE" and I did not include a google analytics tracking ID. These options are up to you._ Under "theme" we add two more parts, we add "remote_theme" and insert "pages-themes/minimal@v0.2.0"(if this is still the current version) then we add "plugins" and insert "jekyll-remote-theme". There are other optional add ins you can include, but that is up to you if you wish to add more. 

My config.yml file looks like the following. Yours should match a similar format. 

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/400b1c08-b957-43b8-a685-2bb498a7bfa2" />


### Index.md
resume stuff

## Step 4, Making final Commit
Make a final commit to your GitHub repository and check on your e-portfolio to make sure your changes have been saved on your page. You can check to see if your deployment was successful by first navigating to the "Actions" tab on your repository and seeing a successful "pages build and deployment" status. `screenshot` 

Secondly you can visit your e-portfolio page to see the changes. Keep in mind it takes a minute or two for the page to load your changes. 

## Step 5, Repository Refinement
In your repository you are going to want to customize your README file, since the file is still the same from the minimal template. It is highly advised to customize this to tell viewers what this repository does and how to access your e-portfolio. `screenshot`

# Resources Used
Here are the resources I have used to make this page as stated before:
["minimal"](https://github.com/pages-themes/minimal)

# My version (final screenshot of my portfolio)
By the end you should have an e-portfolio similar to mine!
`screenshot`
