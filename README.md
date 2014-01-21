getInitialState(): prepare initial state of the Component
componentWillMount() befor the state change
componentDidMount() after the state change
componentWillReceiveProps()
shouldComponentUpdate(): useful if you want to control when a render should be skipped.
componentWillUpdate() before the state change
render() 
componentDidUpdate() after the state change
componentWillUnmount()
The componentWill* methods are called before the state change and the componentDid* methods are called after.


reac.js and JSXTransformer with simple input box
Two way binding in onchange
Two way binding by using addons
Array input in properties
Multiple component usage

JavaScript and JavasScriptXML
Why JSX?
props
state
Two way binding in onchange
Two way binding by using addons
  js
  type
  annotation
  mixins - mixin is a class which contains a combination of methods from other classes
  valueLink
  linkState
Array input in properties
Multiple component usage
Methods


Why JSX?
--------
http://facebook.github.io/react/jsx-compiler.html
React works out of the box without JSX. Simply construct your markup using the functions on React.DOM. For example, here's how to construct a simple link:

var link = React.DOM.a({href: 'http://facebook.github.io/react'}, 'React');

We recommend using JSX for many reasons:

    It's easier to visualize the structure of the DOM.
    Designers are more comfortable making changes.
    It's familiar for those who have used MXML or XAML.

React DOM Components:
  To construct a <div> is to create a variable that refers to React.DOM.div.

  var div = React.DOM.div;
  var app = <div className="appClass">Hello, React!</div>;

React Composite Components:
  To construct an instance of a composite component, create a variable that references the class.

  var MyComponent = React.createClass({/*...*/});
  var app = <MyComponent someProperty={true} />;


React.DOM.p(null, message)
<p>{message}</p>

Methods:
--------
getInitialState(): prepare initial state of the Component
componentWillMount() befor the state change
componentDidMount() after the state change
componentWillReceiveProps()
shouldComponentUpdate(): useful if you want to control when a render should be skipped.
componentWillUpdate() before the state change
render()
componentDidUpdate() after the state change
componentWillUnmount()
The componentWill* methods are called before the state change and the componentDid* methods are called after.



----------------------------
1head
	

version	category	property	created_ts
1 			1111     font       ****
1           1111     leding     ****
1           1111     leftIndent	****
2           1112     font       ****
2           1112     rightIndent ***
3           1111     size       ****
4           1112     font       ****


1111  font, leding, leftIndent, size
1112  font, rightIndent, font




