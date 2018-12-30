![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 31 - REDUX Practice

### Author: Ashley Breunich

### Links and Resources
* [repo](https://github.com/ashley-breunich/lab-31)
* [Assignment 1](https://codesandbox.io/s/oo3zw065mz)
* [Assignment 2](https://codesandbox.io/s/ykv771r7mx)


### Modules
## Assignment 1

#### `index.js`
##### Exported Values and Methods

###### `Main() -> <Provider>`
-> App Component

#### `components/app.js`
##### Exported Values and Methods

###### `Class App -> <div>`
-> div

###### `mapStateToProps(state)`
<- state

-> stuff: state.someStuff

###### `mapDispatchToProps(dispatch, getState)`
<- dispatch, getState

-> handleChange

#### `store/actions.js`
##### Exported Values and Methods

###### `changer(payload)`
<- payload

-> type: 'CHANGE'

-> payload

#### `store/index.js`
##### Exported Values and Methods

###### `combineReducers()`
-> someStuff

#### `store/reducers.js`
##### Exported Values and Methods

###### `export default()`
<- state, action

-> if CHANGE, returns foo

-> if DEFAULT, returns state

#### Tests
* 


#### UML
[UML Image for Assignment 1](assets/UML-assignment-1.jpg)

[UML Image for Assignment 2](assets/UML-assignment-2.jpg)