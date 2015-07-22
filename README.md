```
# ubuntu-setup -- My Ubuntu Setup

# Disable search results in the dashboard
# Settings -> Security -> Search -> Disable Search Results

# Sublime Text
sudo add-apt-repository ppa:webupd8team/sublime-text-2
sudo apt-get -y update
sudo apt-get -y install sublime-text

# OpenJDK 8
sudo apt-get -y install openjdk-8-jdk

# Google Chrome
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list'
sudo apt-get -y update
sudo apt-get -y install google-chrome-stable

# Firefox
sudo apt-get -y install firefox

# Docker
$ wget -qO- https://get.docker.com/ | sh
sudo usermod -aG docker $USER

# Glipper (Ctrl-Alt-C)
sudo apt-get -y install glipper


# Eclipse - still no decent Debian packages for Eclipse



```
