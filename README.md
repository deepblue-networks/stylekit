# dbn stylekit
Collection of utilites written in scss.

## How to use

Install package
````
npm i --save-dev @dareksob/stylekit

// or with yarn
yarn add --dev @dareksob/stylekit
````

Import kit to your scss file
````scss
@import '@dareksob/stylekit/src/generic';
````

## Versions

You have 3 options to integrate the kit to your setup.
- generic
- foundation
- bootstrap

The generic file has a base version of the breakpoint mixin.


### Overview of version
| Version  | Use for | 
|---|---|
|  Generic  |  To use for setup without foundation |
|  Foundation  |  To use with foundation-sites |
|  Bootstrap  |  To use with bootstrap 4 |

::: warning

The bootstrap version not in focus

:::


## content

Inside the `/*` you can all include files

Inside the `/functions/*` you have all function tools

Inside the `/mixin/*` you have all helper mixin

Inside the `/capsules/*` you find the basic abstraction tools to use it without a framework

Inside the `/foundation/*` and `/bootstrap/*` for the framework setup

 

## functions

### value
to get value by breakpoint.

```
$values: (10px 30px 50px);
$value: value($values, small); // 10px;
```

WIP