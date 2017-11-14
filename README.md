# pman

> Simple project management system

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

#Project description
The project manager is capable of tracking personal and collaborate projects.
Projects are divided by subprojects and tasks.
All elements could be configured as one-time only or repeat by flexible scheduller.
Projects could be viewed in various forms:
 * List
 * Mindmap
 * Board
 * etc.
Projects could reference to other projects and tasks.
Projects and tasks could be eternal, so they could not be marked as finished, but could be deleted, so they could be used as lists.
Projects may contain media information as description.
Projects may contain references to websites.
Projects may contain custom fields.
Custom fields can be set to contain specific data, format, lists.
Custom fields could get data from eternal objects.
Project views could be configured by predefined and/or custom fields.
Projects may define schemas for their tasks.
Subprojects may redefine schemas for their tasks.
Subprojects could be promoted to Projects.
Tasks could be promoted to Projects, and gain additional options.
Projects could be demoted to subprojects of another project.
Projects could be demoted to tasks with loosing some options.
Projects could be linked one to another.
Projects could be chained one after another.

