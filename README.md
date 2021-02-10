# ClassComponent-vs-Hooks
Created with CodeSandbox
class Components vs Functional Components


Before functional components use to create as follow:-
example:-
import React from "react";

function App() {
return <h1>Hello</h1>
}

export default App;

Whereas in Class Component will be using extend key word with having render method

example:-

import React from "react";

class App extends React.Component {
render() {
return <h1>Hello</h1>
}
}

export default App;

