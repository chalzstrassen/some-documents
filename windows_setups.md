# Getting Windows Ready for App Academy

There is a good reason why you should run away from Windows when using tools such as Ruby, Rails, Git, and others. Installing and getting them to work has been a major headache for me. However, I had plenty of time to figure out how to get the tools working on Windows. This is what happens when you don't have a day job.

If you don't feel like switching away from Windows during App Academy, read this guide which I put together based on my own experiences with Windows. The laptop I have been using is a Lenovo G580 with Windows 8.1 OS. 

## Ruby/Rails/Git

Ruby, Rails, Git, Sqlite, Devkit, and other packages can be installed as a bundle from [Rails Installer](http://railsinstaller.org). Go download it from the link. I selected Ruby 2.1 for Windows. Run the setup and add the Ruby *bin* folder to your *Path*. That way, you can run Ruby, gem, and irb from cmd.

## Gems

You need to ensure that the *gem install* command works. The Rails Installer has no SSL certificate authorities defined. You can fix the issue [here](https://gist.github.com/fnichol/867550).

# Finally

After doing all of these steps, I was able to get Rails working on my laptop. 
