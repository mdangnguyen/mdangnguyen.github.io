# GitHub Resume

This is a guide on how to host your own resume on GitHub.

## Getting Started

These instructions will enable you to write, host, and format your resume in Markdown using Atom, GitHub, and GitHub themed Jekyll. This guide is meant for anyone with little to no experience in coding and familiar with basic website interactions. However, there is a few things you need to know and set up before following this guide.

### Prerequisites

#### Knowledge of Markdown

If you aren't familiar with Markdown, please complete this [tutorial](https://www.markdowntutorial.com/) and get used to the language. It is very intuitive and can take less than an hour to learn.

#### Atom Text Editor

1. Download the Atom installer from [here](https://atom.io).
2. Run the installer.

#### GitHub Account

1. Sign up at [GitHub](https://github.com/).
2. Fill out the fields and select "Next: Select a Plan".
3. Choose your plan. For the purpose of this project, a free plan should be sufficient.
4. Complete the questionnaire.  
   * You can skip by selecting "Skip this step".
5. Verify your email address to complete registration.  

### Instructions

#### Step 1: Writing your resume in Markdown
1. Launch Atom.
2. Go to File, then select "New File".
3. Write your resume in Markdown.  
   * Refer to **Prerequisites** for a tutorial on Markdown.
4. Save your file as `index.md` once you're finished.  
   * You can preview your work using `Ctrl + Shift + M` once the file is saved as .md format.

#### Step 2: Setting up your GitHub repository
1. Go to [GitHub](https://github.com/).
2. Sign into your account.
3. Select "Create a repository" at the top left corner.
4. Enter repository name as `yourusername.github.io`.  
   * Ie. if your name is ABC, the repository name should be `ABC.github.io`.  
5. Check "Public" option.
6. Select "Create repository" to finalize your creation.

#### Step 3: Uploading your resume to GitHub
1. On your repository page, select "uploading an existing file".  
   * If you already have some files in your repository, select the "Upload files" button instead.
2. Select your `index.md` file.
3. Select "Commit Changes".

#### Step 4: Formatting your resume
You can refer to the gif below for a visual representation of this step.
1. Go to your repository page (`github.com/yourusername/yourusername.github.io`).
2. Select Settings.
3. Navigate down to "GitHub Pages" section.
4. Under "Theme Chooser", select "Choose a theme".
5. Pick a theme and select "Select theme".
6. Go to `yourusername.github.io` on any web browser to see the result.

![](demo.gif)

#### Step 5: Editing your website header
1. Go to your repository page (`github.com/yourusername/yourusername.github.io`).
2. Select `_config.yml`.
3. Select the pencil icon to edit.
4. Add the following line: `title: Your Website Title`
   * Change `Your Website Title` to your preferred title.
5. Scroll down and select "Commit changes".
6. Go to `yourusername.github.io` on any web browser to see the result.

## Frequently Asked Questions (FAQ)

**Q: Do I have to name my resume file as index.md?**  
A: Yes, because GitHub won't be able to load your resume onto the website otherwise.

**Q: Can I use other text editors besides Atom?**  
A: Yes, you can use any text editor of your preference. But for the purpose of this guide, I think Atom is the most appropriate as it is linked to GitHub and also allows you to preview your work in real time

**Q: Why can't I see my changes on the website?**  
A: If you have correctly followed all the steps in the instructions above, then it is most likely a problem on GitHub's side. Unfortunately, there isn't much you can do besides waiting for the change to eventually come. If you have waited for a long time with no progress, I recommend deleting your repository and create a new one to see if the problem persists.

## More Resources

For more information on GitHub Flavored Markdown, visit [here](https://github.github.com/gfm/).

## Author

* **Minh Dang Nguyen** - [My GitHub](https://github.com/mdangnguyen)

## Acknowledgments
* Luke Morrow and Duy Thai Nguyen for reviewing my work.
* Christina Penner for providing numerous resources for this assignment.
