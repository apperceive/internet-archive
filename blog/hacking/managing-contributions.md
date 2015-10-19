#Hacking the Internet Archive - Managing Contributions

When it comes to online content management, we've come a long way since the early days of videoblogging. In particular, the are quite a few tools to manage your Internet Archive contributions. Some have always been there, others are new.

Here's a list of ways I am aware of to manage archive.org items:

* FTP - use tools like filezilla or cyberduck to manage your content. No longer used for downloading and it appears that <a href="https://archive.org/post/1041762/publish-items-uploaded-using-ftp-command">uploading may no longer be supported</a>. I have yet to find an official announcement of that yet.

* [www.archive.org] - web forms to manage your content and your metadata. These forms have gotten easier to use over time and allow you to do lots of cool things. On the other hand, I hate forms.

* [s3.archive.org](http://archive.org/help/abouts3.txt) - a powerful interface similar to the Amazon web service. For the truly geeky at heart. &nbsp;Mainly useful to programmers. &nbsp;Not so much code as a standard to make calls against using tools and libraries like 'curl'.<br />Python interface - built on s3.archive.org, used with curl and programming languages, powerful but very geeky. Mainly for programmers, but can be used at a higher level to make cool scripts or use within other applications. Also a great way to learn about the internal working of the Internet Archive and the Python programming language.

* [ia command line interface](https://github.com/jjjake/internetarchive) - based on the python interface, great for managing lots of items and their metadata, powerful, easy to install and use, geeky, but not too geeky. Works on mac, pc and gnu/linux. I really like this tool. Open source.

* other libraries and interfaces

* various desktop clients - can be easy to use, there have been many, they come, they go, commercial and open source projects
 
Recently, I've been using and studying the ia command line interface and it is a great tool. 
 
We'll take a look at using the Python-based command line interface in the next several posts to learn more about Internet Archive features and capabilities that we can use to do cool things with our content.
