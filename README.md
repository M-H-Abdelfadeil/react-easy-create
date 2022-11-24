# React helper 

##### easy  create component and slice (one command)
# require : PHP

### use 
download file " helper " in root app directory  <br><br>
![alt text](images/1.png)

## Note :  delete file helper if project production 

## create component 

### EX : 

```bash
$ php helper make:component src/components/Product
```

![alt text](images/2.png)
create file  'src/components/Product.js' 
#### content file  
```js
function Product (props){
    return (
        <>
           
        </>
    );
}
export default Product;

```
![alt text](images/3.png)

## create class  component 
```bash
$ php helper make:component src/components/ProductList  --class
```
![alt text](images/4.png)
create file  'src/components/ProductList.js' 
#### content file  

```js
import React from 'react';

class ProductList extends React.Component {

    constructor(props) {
        super(props);
        this.state = {};
    }
    render() {
        return (
            <>
                
            </>
        );
    }
}

export default ProductList;
```
![alt text](images/5.png)
## create slice

```bash
$ php helper make:slice src/slices/Product
```
![alt text](images/6-.png)



create file  ' src/slices/ProductSlice.js' 
#### content file 
```js 
    import { createSlice } from '@reduxjs/toolkit'

 
    
    export const ProductSlice= createSlice({
      name: 'ProductSlice',
      initialState:{
        // state 
      }
      ,
      reducers: {
        
      },
    })
    
    export const { } = ProductSlice.actions
    
    export default ProductSlice.reducer
```
 

![alt text](images/7-.png)