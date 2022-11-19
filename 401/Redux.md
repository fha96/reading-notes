# Redux
- *What is a redux?*
   *Redux provides a solid, stable, and mature solution to managing state in your React application. Through a handful of small, useful patterns, Redux can transform your application from a total mess of confusing and scattered state, into a delightfully organized, easy to understand modern JavaScript powerhouse. So it’s is a predictable state container for JavaScript apps.*

- *Why use Redux?*
1. *A lot of developers love Redux is the developer experience that comes with it. A lot of other tools have begun to do similar things, but big credits to Redux.*
2. *Some of the nice things you get with using Redux include logging, hot reloading, time travel, universal apps, record and replay — all without doing so much on your end as the developer. These things will likely sound fancy until you use them and see for yourself.*
3. *The Redux Store can be likened to the Bank Vault. It holds the state of your application — and keeps it safe.*


## State Management
* *Example:*
`{`
    `function Counter() {`
  `// State: a counter value`
  `const [counter, setCounter] = useState(0)`
  `// Action: code that causes an update to the state when something happens`
  `const increment = () => {`
    `setCounter(prevCounter => prevCounter + 1)`
  `}`
  `// View: the UI definition`
  `return (`
    `<div>`
      `Value: {counter} <button onClick={increment}>Increment</button>`
    `</div>`
 ` )`
`}`
`}`
- *It is a self-contained app with the following parts:*

1. *The state, the source of truth that drives our app.*
2. *The view, a declarative description of the UI based on the current state.*
3. *The actions, the events that occur in the app based on user input, and trigger updates in the state.*


- *This is a small example of "one-way data flow":*

1. *State describes the condition of the app at a specific point in time.*
2. *The UI is rendered based on that state.*
3. *When something happens (such as a user clicking a button), the state is updated based on what occurred.*
4. *The UI re-renders based on the new state.*


![cycle-redux](https://d33wubrfki0l68.cloudfront.net/73bb62ebc338fcd64ee95bde18684ffe3b3bb379/dac4f/assets/images/one-way-data-flow-04fe46332c1ccb3497ecb04b94e55b97.png)