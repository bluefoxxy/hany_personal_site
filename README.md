# Setup and Run Instructions for Jekyll Site on Mac

This guide covers installing required tools, cloning the repo, and running the site locally.

---

## Prerequisites

- You need a Mac with internet access.

---

## Step 1: Install Homebrew

Homebrew is a package manager for Mac that makes installing software easy.

Run this command in your terminal:

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

---

## Step 2: Install Ruby

Use Homebrew to install Ruby:

$ brew install ruby

After installation, add Ruby to your shell path by adding this line to your `~/.zshrc` or `~/.bash_profile` file:

$ export PATH="/usr/local/opt/ruby/bin:$PATH"

Then, reload your shell config:

$ source ~/.zshrc

(or `source ~/.bash_profile` if using bash)

---

## Step 3: Verify Ruby Installation

Check Ruby version:

$ ruby -v

You should see Ruby 2.6 or later.

---

## Step 4: Install Bundler and Jekyll

Install Bundler gem:

$ gem install bundler

Install Jekyll gem:

$ gem install jekyll

---

## Step 5: Install Git (if you don't have it)

Check if Git is installed:

$ git --version

If not installed, install via Homebrew:

$ brew install git

---

## Step 6: Clone the Repository

Run the following commands to clone the repo and enter its directory:

$ git clone git@github.com:bluefoxxy/hany_personal_site.git  
$ cd hany_personal_site

---

## Step 7: Install Project Dependencies

Inside the project directory, run:

$ bundle install

---

## Step 8: Serve the Site Locally

Start the local Jekyll server with:

$ bundle exec jekyll serve

---

## Step 9: View the Site

Open your browser and visit:

http://localhost:4000/hany_personal_site/

---

## Notes

- The `/hany_personal_site/` in the URL is required because of the `baseurl` setting in `_config.yml`.  
- To stop the local server, press `Ctrl + C` in the terminal.  
- If you run into missing gem errors, run `bundle install` again.  
- Feel free to edit files locally, then commit and push your changes.

---