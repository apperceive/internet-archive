[Python](http://python.org) is a popular programming language, used in many situations these days.

Some wonderful folks have created a powerful command line interface to the Internet Archive that is built using Python.

We will talk about installing the 'ia' tool in the next post.

But first, we need to have a compatible version of Python on our computer in order to install and use the 'ia' command line interface. So that't the purpose of this post: just make sure python is installed.

This was easy on my Ubuntu servers. I already had Python 2.7.6 installed and that works fine for now. I may upgrade this, but I was able then to proceed with the 'ia' installation after that and, as they say, "if it's not broke ...". 

My older MacBook with OSX 10.6 already had python 2.5 installed and in use. This would not install ia when I tried it and so I thought it would be best to upgrade python. The current version of Python is 3.5. You can install 3.5 alongside 2.5 (do not remove the older one! your mac needs it). Just visit python.org and download their Mac installer version. Once it is installed, you must type 'python3' in all instructions where you see 'python'.  I was able then to proceed with the 'ia' installation after that.

On my Windows 7 box, I installed python via the python.org windows installer, which I downloaded and ran. On windows, you need to add the python install folder to your Path environmental variable (right click on your 'Computer' icon, select 'Properties', then click 'Advanced System Settings', then 'Environmental Variables', scroll to and select 'Path' in lower 'System Variables', double click to edit. Add a semi-colon (;) and then the new path to your python install directory binaries.

On windows, type 'py' to run python. On 'mac', type python3. Just type 'python' on Ubuntu. In all cases, you should see something like this:

[<img src='http://2.bp.blogspot.com/-DqKnvmNVodA/ViZbFP20lrI/AAAAAAAAAXA/yrtV-SQDTaM/s320/Capture.PNG' />](http://2.bp.blogspot.com/-DqKnvmNVodA/ViZbFP20lrI/AAAAAAAAAXA/yrtV-SQDTaM/s1600/Capture.PNG)

Once you verify that python is running, you can either play around and type things like 'print(1+1)' if that gets you exicted.  Type a 'Ctrl-D' ('Ctrl-Z' on windows) to exit or type 'exit()'. I guess everything is a function in python. :)

Learning the 'ia' tool will give us an opportunity to learn more about python as we continue out explorations.

If you want to learn more about python, check out [this cool learning guide](http://docs.python-guide.org/en/latest/intro/learning/) that is also on GitHub.




