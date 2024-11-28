# W14-Lab-Git

## How would you setup GIT on a mac and PC

### Setting Up Git on Mac and PC:
- **Mac**: Install Git via Terminal using `git --version` or Homebrew (`brew install git`), then configure:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- **PC**: Download Git from [git-scm.com](https://git-scm.com), install it, and configure in Git Bash with the same commands.

## Open a online github account and check in any assignment.  Please provide a screenshot of checked-in assignment on github. What commands did you use. repl.it possibly allows github integration.  Github will look like this.

### Creating GitHub Account and Checking in an Assignment:
1. **Sign up to GitHub Account**: Sign up at [github.com](https://github.com).
2. **Create Repo**: Click "New," name it (e.g., `assignment1`), and create it.
3. **Check In Assignment**:
   - Clone the repo:
     ```bash
     git clone https://github.com/Santhusha-bit/W14-Lab-Git.git
     ```
   - Add and push files:
     ```bash
     git add .
     git commit -m "Added assignment"
     git push origin main
     ```

## Which of the following is better SVN, Mercurial, github and why?

GitHub is the superior choice for modern developers because it goes beyond version control, offering a collaborative platform built on Git that integrates seamlessly with development workflows. Unlike SVN or Mercurial, GitHub provides powerful tools like pull requests, issue tracking, and CI/CD pipelines, streamlining collaboration and deployment. Its intuitive interface and massive developer community make it easy to contribute to open-source projects, showcase work, and learn from others.

GitHub's project management features, such as boards and milestones, help teams stay organized, while its integration with tools like VS Code and GitHub Copilot enhances productivity. By combining version control, collaboration, and community engagement, GitHub stands out as the go-to platform for both individual developers and teams.
