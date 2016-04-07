# Install and configure all required software for my web development environment

## Installing software packages

    sudo apt-add-repository -y ppa:webupd8team/sublime-text-3
    sudo apt-get update
    sudo apt-get install -y mysql-server apache2 php5 php5-curl php5-gd php5-mysql php5-tidy git sublime-text-installer

## Configure software

    git config --global user.name "Pedro Rodrigues"
    git config --global user.email "prodrigues1990@gmail.com"
    
    
    sudo usermod -a -G www-data prodrigues
