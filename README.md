# Minimalistic React Multiviews component

_Estimated duration: 2 hours_

Your task is to build a reusable React component following the best practices and idioms.

The component should work exactly like below:

<pre><Multiviews
  onSelect={function(e) {}}
  defaultView="view2"
  views={{
    view1: {
      name: 'First View',
      view: () => (<div>This is the content of the first subview</div>)
    },
    view2: {
      name: 'Second view',
      view: () => (<div>This is the content of the second subview</div>)
    },
    views3: ...
  }}
/></pre>

*   The component should render a view where one subview is displayed, and provide links to switch from a view to another.
*   The component should render defaultView at boot.
*   onSelect should be triggered when the user changes the selected view.

### Rules

*   Use the best practices and react idioms - no jQuery !
*   Build an example application with the wizard component, this is to exemplify re-usability of the component and can serve as developer documentation
*   Use Webpack to transpile your code and bundle your React application
*   The example application should be working "out-of-the-box". Make sure your dependencies are in the package.json file and that the application compiles and runs correctly.

### What we follow

*   Understanding the requirements and implement them as expected
*   Good understanding of react component architecture
*   Awareness of UI design patterns
*   Speed of adaptation to modern technology
*   Idiomatic solutions following best practices
*   Clean, Reusable & Testable code

### Tech stack

*   **React** (obviously), **npm**, **ES6**, **webpack**, **babel**
*   If you test your component, use **mocha** and **chai**

_Even if you do not know **ES6**, this should not scare you, it is easy to pick up, considering previous JavaScript experience!_

### What we consider a plus

*   Good architecture
*   Good code quality (consider **eslint**)
*   Tested component
*   Good documentation (imagine you are going to open source this component)
*   Usage of software design patterns
*   Usage and emphasis on well established UI design patterns
*   Any other feature you find interesting to add !

Good luck !
