         ___        ______     ____ _                 _  ___
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/
 -----------------------------------------------------------------


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.

Happy coding!

https://www.railstutorial.org/book

===

Settings = soft tab 2 spaces
  delete whitespace

rvm get stable
rvm install 3.1.2
rvm --default use 3.1.2

ruby -v
  ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x86_64-linux]

echo "gem: --no-document" >> ~/.gemrc
gem install rails -v 7.0.4

rails -v
  Rails 7.0.4

gem install bundler -v 2.3.14

Adding extra space to Cloud9

source <(curl -sL https://cdn.learnenough.com/resize)

rails _7.0.4_ new hello_app --skip-bundle

cd hello_app

bundle _2.3.14_ install

rails servers

AWS Cloud 9 disable tracking protection for preview

git --version
source <(curl -sL https://cdn.learnenough.com/upgrade_git)

git config --global user.name "Your Name"
git config --global user.email your.email@example.com
git config --global init.defaultBranch main
git config --global alias.co checkout

git add -A
git push -u origin main

username: kappajester83
password: "git-hub access token"

