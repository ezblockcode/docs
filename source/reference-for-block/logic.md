# Logic

## ![a](./img/logic/ifdo.jpg)  
- **effect：** Used to capture changes in variables to respond When the condition is met, that is, when the parameter value is true, the content of the block will be executed 
    
***

## ![a](./img/logic/dengdengyu.jpg)  
- **effect：** Compare the left and right parameters, return a Boolean value, return true if the condition is met, otherwise return false
- **parameter：** The value type on the left and right sides must be the same, for example, both are numbers or both are characters

***

## ![a](./img/logic/and.jpg)  
- **effect：** It will return a Boolean value, and the parameters on both sides must also be Boolean values. __If both sides are true__, return __`true`__. __If either party is false or both parties are false__, return __`false`__.
## ![a](./img/logic/or.jpg)  
- **effect：** Returns a boolean value, the parameters on both sides must also be boolean values, __as long as either of them is `true`__, it will return `true`, __and only when both are `fasle`__ will it return `false`  
![a](./img/logic/andexample.jpg)  
computational results:
    ```
        true
        false
    ```

***

## ![a](./img/logic/not.jpg)  
- **effect：** Splicing before the block whose return value is Boolean will get the __opposite Boolean value__  
![a](./img/logic/notexample.jpg)  
computational results:
    ```
        false
    ```
***

## ![a](./img/logic/true.jpg)  
- **effect：** That is, the boolean value `true`.
## ![a](./img/logic/false.jpg)  
- **effect：** That is, the boolean value `false`.
***

## ![a](./img/logic/null.jpg)  
- **effect：** Generally used to compare or assign values to variables
***

## ![a](./img/logic/on.jpg)  
## ![a](./img/logic/off.jpg)  
- **effect：** In fact, it has the same function as the `true` block and the `false` block. They are all boolean values, but this block is more suitable for switch state assignment.
***

## ![a](./img/logic/test.jpg)  
- **effect：** This is a ternary expression, if the return value of `test` is `true` then the block after `if true` will be executed, and vice versa
- **example：**  
![a](./img/logic/testexample.jpg)  
computational results:
    ```
        equality
    ```
***