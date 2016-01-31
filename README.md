Even though this repo is a fork of [Wingo](https://github.com/BurntSushi/wingo), my aim is not to build a window manager. **If you're looking for a program that might be of any use to you, you will be disappointed!**

For some time, the README is pretty much the only thing I'm going to edit. I have some long-term goals, but it is not clear yet what their priorities are. Feel free to discuss whatever is written here via the issue tracker.

**This document is currently a tangle of unfinished thoughts.**

--

I'm currently spending a lot of my time in front of a computer. I want to change that.
I automate a lot of things in order to save time and mental energy. For instance, search for a song, download YouTube video, extract audio from it, rename the file, put in the music library. If I automate correctly, the time I spend doing this should only that of typing the song's title in some prompt. But I still feel that it takes too much time *to automate*. This might be only an impression.

### Goals

- spend less time in front of the computer
- allow for some multitasking, but first and foremost encourage engaging in focused activities
- an environment that favors the assessment of habits
- . This is why the term "window manager" is not suited. It describes an artifact, but I want to focus on the experience. Naming this project a "window manager" would lead me to second-guess whether some change should live in this repo or not. Artifact boundaries (configuration methods, IPC, integration with systems other than mine) are not my focus here.

### Non-goals

- build a traditional/floating/tiling window manager
- deliver or maintain a program usable by someone other than me

### Inspirations

- the way text serves as an interface in [Acme](http://plan9.bell-labs.com/sys/doc/acme/acme.html)
- the way [Sugar](), the UI used in the One Laptop Per Child project, focuses on activities rather than programs/applications.
- the way [dwm]() and other window managers allow an M-to-N relation between program windows and workspaces
- the way [`plumb(1)`]() in [Plan 9]() allows system integration by decoupling IPC from application code
- the way [namespaces]() in [Plan 9]() simplify a lot of things in Unix
- the way [CSP](), as implemented in [Go]() and [core.async](), make it easy to think about concurrency
- the way [queues]() decouple the intent to 
- the way hunter-gatherers didn't consume at the moment of acquisition. The way queues decouple the location and time where data is collected from where it is processed. Applies for automated pipelines as well as personal activities. Writing things out of your brain should be easy and quick, you can reflect on what comes out later
- our natural ability as humans to locate, move, and think about things in space
- the way post-it notes outperform other means of collective brainstorming

### Novel ideas

"Novel" meaning "that I have not seen elsewhere (yet)". If you know of projects/papers that showcase experiments of these ideas, please let me know via the issue tracker.

- 2D worlds that don't match the size of your monitor, but are infinite. A monitor is a viewport aimed at this infinite space. By zooming and click-dragging, you focus and move the viewport to explore that space. A "workspace" is a region in the space in which you do certain things. It can be as big or small as you want, it might not even be a rectangle.
- - the motivation behind this is to leverage our natural ability to locate and manipulate things in space. Post-its are a known implementation of this. Ascribing positional information to program windows allows you to visualize ad-hoc relations between them. Some examples:
- - 1) graph awareness: visualizing a social network by positioning web browser windows. This was possible in Firefox before v45 using Panorama (the feature was moved to an add-on), but the feature didn't empower further use of that positioning, and didn't integrate with the rest of the system's UI
- - 2) prioritizing 
- - 3) 
Say you open one window for each person in a list of people you're interested in. Positioning the windows

### Unreflected buzzwords / food for thought

- graph awereness
- accelerate network literacy

### License

This is a text file, yo.
