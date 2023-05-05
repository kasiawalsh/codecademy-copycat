# codecademy-copycat
Project with React using styles, propTypes, input form, Container/Presentational components

React styling, style object variables
Container/Presentational components - how and when to separate
React forms and how the onChange event can be applied when updating a component state
PropTypes for validation and documentation of projects


When components get split, we need to give the presentation component access to state.
Presentation component has no copying or toggleape, no state for this component.
They only exist in the container component.
We need to pass them down as props from container component to presentation component to give presentation component access to them. We pass them down as props from container. 
We can do that by adding them as attributes in CopyCat. 


When we tyle , we trigger onChange event 
which we have defined as an attribute on our input element
That called handleChange function 
which we are accessing through props from our container component 
Where it is defined and it updated state -input - with e.target.value 
which is whatever text is in input 

State was updated so the component is going to render again 
State we just updated is is passed down to copycat instance through our value prop 
And that is now the new value of paragraph

When we click on the cat and make it false - value is not showing 

Proptype are useful for 
Prop validation 
Documentation 

Import library import PropTypes from 'prop-types’
One entry per prop
Key - propname
Value - data type we expect
