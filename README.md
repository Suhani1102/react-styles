# react-styles
This app is built to learn various ways to style react application.

# 1.Dynamic styles using .css file
We can add styles to our react component by assigning className to elements in component, then providing styles for those classes in .css file.<br/>
But using this method all the elements across your application with same name will inherit styles from .css file.<br/>
To avoid this we have other two methods for styling.

# 2. Styled Components
Styled Components is a library for React & React Native to write and manage your CSS.<br/>
Get Info:<a href="https://styled-components.com/" target="blank">@Styled_Components</a>

# 3. CSS Modules
These are the CSS files in which all class names and animation names are scoped to the component which import the [name].module.css file.<br/>
It wraps your style to the newly generated class name. The classes are dynamically generated, unique, and mapped to the correct styles.<br/>
This approach is designed to fix the problem of the global scope in CSS.

