# Golang_Project

## Install Go
### Ubuntu
Step1: Download and extract the Go binary archive in the usr/local directory
```
wget -c https://dl.google.com/go/go1.16.2.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local
```
Step2: Adding the location of the Go directory to the $PATH environment variable
```
export PATH=$PATH:/usr/local/go/bin
```
Step3: Load the new PATH environment variable into the current shell session
```
source ~/.profile
```
### MacOS
Step1: Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

nano ~/.bash_profile
export PATH=/usr/local/bin:$PATH
source ~/.bash_profile
```
Step2: Use Homebrew to install Go
```
brew install golang
```

## How to build and run this project

