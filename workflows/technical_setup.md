# Workshop Technical Setup

Please follow these steps to setup the neccesary development environment for the Workshop. We will have limited time in the workshop to work through technical troubleshooting. The more attendees that come ready, the smoother it will go... thank you much!

#### Download and install dependencies

1. Download and install [VirtualBox][virtualbox]
2. Download and install the latest version of [Vagrant][vagrant]
3. Clone the starter_app into whatever project directory you want using the code: ` git clone git@github.com:RogueRails/starter_app.git`

#### Install the box

1. Open iTerm2 (or Terminal) and navigate to the starter_app directory: ` cd /path/to/starter_app `
2. Boot the environment: ` vagrant up`
3. After complete, ssh into the box: ` vagrant ssh`
4. Then to install all default required gems run the bundle command: ` bundle `

After completing these steps your environment is setup and ready for participation in the workshop. If you have any issues, please contact us at info@roguerails.com

  [virtualbox]: https://www.virtualbox.org/wiki/Downloads
  [vagrant]: http://vagrantup.com