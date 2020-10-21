[corebine-web-templates-core](README.md) › [Globals](globals.md)

# corebine-web-templates-core

-------------------------------------------------------------

# INSTALLATION
* Requirements
    - install Node JS >= 0.12
    - install *npm* (if it isn't provided with Node JS)
    - install *gulp* globally using npm including "-g" flag
```
$ npm install -g gulp
```
* Install npm dependencies
```
$ npm install
```
* Run default gulp task to build, start dev server and file watcher
```
$ gulp
```

#PROJECT STRUCTURE

Build directives are located in /gulp folder. Source files are located in /src folder and contain JS and template files, HBS helpers, styles, config and other files placed in corresponding folders.
Client-specific files could be added by overriding existing files in a separate git forks. 
For easier overriding and inheriting there exist index.js files for all modules and components; client-specific.js files for HBS helpers.

# BUILD

## BUILD OPTIONS

You can add *skin*, *task* or *config* arguments to run any task with any configuration.
There are predefined configurations:

* dev (default) : for development
* corebine : for production build

When using corebine with web rendering server for development it is possible to specify a folder where files are built.
Default value is 'corebine'.
You can use --folder parameter to build demo client using white-lion theme into dist/demo folder.

    $ gulp corebine --folder=demo

Also aliases can be used to run any task with any config, please see *gulpfile.js* for an example.
    
## SKINS

Any files could be overridden (JS, LESS, HBS, images, etc) or merged (JSON) by placing file with same name into skin folder *skin.name*
    
    $ gulp --skin=sample-skin
    
# DEVELOPMENT

There are few build options for development purposes:

## SSR for dev build

To enable SSR for development build should be used flag *--devssr* (for production build it is enabled by default). Pay attention that watcher does not work proper in this build mode, will be fixed later.
    
    $ gulp --devssr
    
## RTL
        
To enable RTL mode should be used flag *--lang* with arabic language key *ar*
            
    $ gulp --lang=ar

## Remote page emulation

It is possible to fetch remote page's JSON and bootstrap to build and emulate it locally. Page will be available as /devpage.html on local server.

    $ gulp --devpage=https://demo2-web-dev.corebine.com/en

## Usage corebine-web-templates-core to build external client (usage as node_module)

Corebine-web-templates-core could be used as a part of client's build. Set corebine-web-template-core as 
`dependency` filed in package.json, create proxy-task in the `scrtips` section to run:
        
      "scripts": {
        "build-dev": "cd node_modules/corebine-web-templates-core && gulp default --external",
        "build-corebine": "cd node_modules/corebine-web-templates-core && gulp corebine --external",
        "build-static": "cd node_modules/corebine-web-templates-core && gulp static --external"
      }
      
The `--external` build flag allows to distinguish between external and internal use of corebine-web-templates-core and to resolve paths.

Any packages can be used as a part of client's build too. Set {{package}} as `dependency` filed in 
package.json, create proxy-task in the `scrtips` To run: `--package={package1} --package={package2}`
Example: 
 - in package.json add as `dependency`: `corebine-web-templates-amp": "git+ssh://git@stash.omnigon.com:7999/plat/corebine-web-templates-amp.git`
 - to run the task: `--package=corebine-web-templates-amp`

# TROUBLESHOOTING

- check console for errors
- make sure that all main libraries were installed (see "INSTALLATION" point)
- delete *node_modules* folder and reinstall all packages invoking command:
```
npm install
```
