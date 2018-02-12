### Some notes on Apostrophe CMS

##### What is an Apostrophe module
"Apostrophe is a modular content management system. Each meaningful component is broken into its own module, which can then be interacted with or subclassed (extended) by other modules in the system."
- modules are powered by [moog](https://github.com/punkave/moog) and [moog require](https://github.com/punkave/moog-require)
- **lib/modules** is where the project's modules live (and also where you can improve Apostrophe's modules)
- Apostrophe modules and npm modules are 2 different things
  - for example an npm module might contain several Apostrophe modules (like apostrophe-blog)

##### What's the app.js file about
- this is Apostrophe's main config file
- here is where you specify what modules you want to be present in the project
  - add -> configure via an object's options
