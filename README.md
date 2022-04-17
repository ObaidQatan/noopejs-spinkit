# noopejs-spinkit-react
## Discription
This package provides a bunch of loading spinners being rendered as components for React applications .

## Installation
```bash
npm install --save @noopejs/spinkit
```

## Usage
```js
// Example: RealisticDottedCircle loading spinner
// In your MyComponent.js...
import RealisticDottedCircle from '@noopejs/spinkit';

function MyComponent(){
  return(
    <div>
      <RealisticDottedCircle size={15} color="#00d8ff" />
     </div>
   )
 }
 
 export default MyComponent;
```

## Attributes
| attribute | type | discription |
| :---: | :---: | :---: |
| size | Number | <p align="left">Defines a squared size for a spinner component in pixels.<br/>[DEFAULT]: `10`</p> |
| color | String | <p align="left">Gives a color as in a regular CSS color value (i.e white, pink...,etc are allowed too).<br/>[DEFAULT]: `rgb(54, 215, 183)`</p> |

## License
[MIT](https://choosealicense.com/licenses/mit/)
