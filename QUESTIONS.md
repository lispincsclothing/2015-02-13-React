1. var emailType = (props, propName, componentName) => {
  warning(
    validateEmail(props.email),
    `Invalid email '${props.email}' sent to 'Gravatar'. Check the render method of '${componentName}'.`
  );
}
  1.  Call is:
    propTypes: {
      email: emailType,
      size: sizeType
    }
    How does that work?
2. 
