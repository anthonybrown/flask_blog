title: Hosting a Flask Application
date: 2013-11-24

# Hosting a Flask Application

Turns out I'm having a hard time hosting my flask app.
I spun up a LAMP stack on [digital ocean](https://www.digitalocean.com/) and
followed their instructions. I got the `Hello World` app to work, but when I
cloned my app, it broke. I was getting some errors about the wsgi file they
had you add.

I didn't like that setup anyways. I've been reading up on hosting python apps
in general and there's a ton of servers to use. NGIX, tornado, cherry py, twisted,
which I'm really interested in because of it's I/O and asynchronous qualities.
A bit overwelming for someone who, before a week ago, never touched Flask before.

So in the meantime, I'm going to continue making this into a static blog site and
host it on [Github](https://github.com/) or deploy it to [Amazons S3](http://aws.amazon.com/s3/)
until I have more time to figure out how to host on pythong apps on a VPS, seeing how I have
2 of them to play with :)


