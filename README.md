# Table of Contents
1. [Skills](#skills)
2. [Projects : Checklist](#checklist)
3. [Projects : Chat App](#chat)
4. [Projects : String Calculator](#calculator)

# Skills

* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : reselect, normalizr, lodash
    * Debugger : chrome(default), reactotron
    * UI : native-base, react-native-elements, shoutem, expo
    * Map : react-native-maps(airbnb)
    * Etc : react-native-firestack, react-native-router-flux
    * Reviewed
        * Redux : redux-actions, redux-saga, redux-orm, Ducks
        * Data : immutable.js, typescript
        * Etc : react-native-background-timer, react-native-navbar
* Focus
    * coded with pureRN
    * Redux : separate Smart component, presentational component
    * Flatten objects : able to convert and restore
    * Reduce computation with memoize pattern
* Design Pattern
    * Self defining function
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
* Data Structure
    * convert to flatten objects and able to restore
    * make able to undo
* Redux
    * Multi reducers with combine reducer
    * Compose and Middleware : redux-thunk, redux-logger
    * BindActionCreators
    * Normalizing state shape
    * Updating normalized data
* React Native
    * Reusable Components : presentational component
    * Understanding on LifeCycle
    * Code without jsx
    * UI design with Flexbox
    * setState with updater function
    * controlled components
    * Reviews : Higher-Order Components
* JavaScript
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
        * Async functions
    * Etc
        * shallow copy, deep copy, shallow merge
* Firebase
    * database
    * authentication
* IDE
    * Atom(nuclide), Expo XDE
* Github
    * Create a repo, Fork a repo, branch merge

* * *    

# Checklist

* [Open App on Expo](https://expo.io/@roykim/checklist-expo)

* ![Checklist App on iPhone - 1/3](https://github.com/royjkim/Skills/blob/master/Checklist_Expo_1.gif)

* ![Checklist App on iPhone - 2/3](https://github.com/royjkim/Skills/blob/master/Checklist_Expo_2.gif)

* ![Checklist App on iPhone - 3/3](https://github.com/royjkim/Skills/blob/master/Checklist_Expo_3.gif)

* Summary
    * made with React Native, Redux.
    * Focus
        * coded with pureRN
        * Redux : separate Smart component, presentational component
        * Flatten objects : able to convert and restore
        * Reduce computation with memoize pattern.
* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : reselect, normalizr, lodash
    * Debugger : chrome(default)
    * UI : react-native-elements
* Data Structure
    * convert to flatten objects and able to restore.
    * immutable data on needed state.
    * shallow copy, deep copy, shallow merge.    
* On Expo
    * differences
        * speed
        * UI : navigation position
* JavaScript(used skills, summary)
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
        * Async functions
    * Etc
        * shallow copy
        * deep copy
        * shallow merge
* Redux(used skills, summary)
    * Multi reducers with combine reducer
    * Compose and Middleware : redux-thunk, redux-logger
    * Normalizing state shape
    * Updating normalized data
    * Transfer data with navigator and redux
* React Native(used skills, summary)
    * key points
        * Reusable Components : presentational component
        * Understanding on LifeCycle
        * Code without jsx
        * UI design with Flexbox
        * setState with updater function
        * controlled components
    * Navigate
        * Navigate with pureRN.
        * Prevent navigate when editing
            * including tab navigate.
        * Separate Each navigate by Tabs.
        * Double tap to navigate first page of each tab.
    * UI
        * with react-native-elements
        * Modal toggle customized.
        * Modal toggle area customized.
    * Etc
        * Multi Edit
            * Able to edit same data on different tab.
            * After deleted, page would be unmounted.
* Design Pattern(used skills, summary)
    * Self defining function.
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
    * encapsulation


* * *

# Chat

* [Git(pureRN)](https://github.com/royjkim/React-Native_ChatDemoFirebase)

* [Open App on Expo](https://expo.io/@roykim/chatdemo-expo)

* ![Chat App on iPhone](https://github.com/royjkim/Skills/blob/master/ChatApp_Expo.gif)

* Summary
    * made with React Native, Redux, Firebase
    * Focus
        * coded with pureRN
        * Redux : separate Smart component, presentational component
        * use unique key made by Firebase as own unique key.
        * disable shallow render to realtime update
* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : load from Firebase
    * Debugger : chrome(default), remote-redux-devtools
    * UI : shoutem
* Data Structure
    * each unique id is assigned from firebase’s unique key.
    * shallow copy, shallow merge.
* Firebase
    * for better fast loading use batch loading at initial loading. and realtime update at other case.
* On Expo
    * differences
        * speed
        * UI
            * use 'Expo loading’ instead of ‘ActivityIndicator’.
            * user custom Fonts of Expo
        * Debugger
            * remote-redux-devtools
* JavaScript(used skills, summary)
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
    * Etc
        * shallow copy
        * shallow merge
* Redux(used skills, summary)
    * Compose and Middleware : redux-thunk
    * Not Shallow render(react-redux)
* React Native(used skills, summary)
    * key points
        * Calculate View size depends on devices
        * Event listener
        * Keyboard
        * KeyboardAvodingView
        * Make own similar to KeyboardAvodingView.
        * According to Keyboard status(show, hide), scroll to last position at chat and user list.
        * Understanding on LifeCycle
        * UI design with Flexbox
        * minimize the use of setState and controlled components to speed up
    * Navigate
        * Navigate with pureRN.
        * Prevent swipe back.
        * Transfer data with navigator and redux.
    * UI
        * with react-native-elements
        * Modal toggle customized.
        * Modal toggle area customized.
* Design Pattern(used skills, summary)
    * Self defining function.
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
    * encapsulation pattern

* * *    

# Calculator

 * [Git(reactJS)](https://github.com/royjkim/Reactjs_Calculators)

 * ![Calculator on Web](https://github.com/royjkim/Skills/blob/master/Calculator_Web.gif)

 * [Git(pureRN)](https://github.com/royjkim/React-Native_Calculate_String)

 * [Open App by Expo](https://expo.io/@roykim/calculate-react-native-expo)

 * ![Calculator App on iPhone](https://github.com/royjkim/Skills/blob/master/Calculator_Expo.gif)

 * Summary
     * made with reactJS with create-react-app
     * Focus
         * coded with pure reactJS, RN
         * UI : react-bootstrap(reactJS), native-base(RN)
 * Libraries
     * UI : react-bootstrap(reactJS), native-base(RN)
 * On Expo
     * differences : speed
 * JavaScript(used skills, summary)
     * ES6
         * Spread operator, Rest params
         * Destructuring
         * arrow function
         * Template literals
         * Dynamic key of object
     * ES7
         * Object spread
 * ReactJS(used skills, summary)
     * key points
         * Regular expression
         * Understanding on LifeCycle
         * setState with updater function
         * controlled components
         * Exception handling
     * UI
         * react-bootstrap
 * React Native(used skills, summary)
     * key points
         * Customized for RN(different from reactJS)
         * Understanding on LifeCycle
         * UI design with Flexbox
         * setState with updater function
         * Exception handling
         * Replace ListView with List of native-base
      * UI : native-base
          * Floating action buttons
          * Toast
          * Drawer
 * Design Pattern(used skills, summary)
     * module pattern
