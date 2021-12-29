# gebi
gebi (Get Element By Id) is a tiny js package that enables you to use the short function `gebi(<eid>)` instead of the long `document.getElementById(<eid>)` whenever you need to get a dom object.

## How to use
### Install
Install gebi by running
```
npm i gebi
```
### Loading
Load gebi using either
```
import { gebi } from 'gebi';
```
or
```
const { gebi } = require('gebi');
```
### Usage
After it has been loaded, you can use gebi anywhere that you would use `document.getElementById()`.
Instead of 
```
const myelem = document.getElementById('myElementId')
```
you would write
```
const myelem = gebi('myElementId');
```
