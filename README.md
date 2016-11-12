# React Dev Stub

This is a minimal stub of an environment for bootstraping the development of
React applications with JSX.

Every time I try and set up a new project using React after not having done it
in a while, the documentation for setting up babel and plugins and everything
needed to simply compile jsx is scattered so far and wide and has fallen so far
into npm hell that I need to spend three hours sacrificing four goats and a
kitten to the gods before they let me build a hello world app.

To use:

1. Install npm using your favourite method.
2. Clone this repo.
3. Run either `make deps` or `npm install` to install all 6000 dependencies into
   whatever ridiculous places npm decides to put them.
4. Run `make` or `make all` to compile all the jsx from the `jsx` directory to
   the `js` directory. (To change the directories update the "build" step in
   the package.json)

Repeat step 4 each time you change something or add something in the `jsx`
directory.

You'll need to set up an HTML file which includes the React libraries and your
compiled components from the `js` directory yourself. The official React
documentation is usually okay about that. This is only what's required for
compiling jsx. 

I make no promises that this repo is up to date. It'll probably stop working
tomorrow.
