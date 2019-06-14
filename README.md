# Tool for creating boilerplates

This bash script allows you to create
custom boilerplates based on Meteor
by answering a few questions.

Currently, the script include React.js.
If someone uses Vue.js or Angular.js, it would be nice
if they could integrate them into the script to give the user a choice.

## Packages currently available

- [lodash](https://lodash.com/)
- [moment](https://momentjs.com/) (not by default)
- [date-fns](https://date-fns.org/)
- [semantic-ui-react](https://react.semantic-ui.com) (not by default)
- [react-helmet](https://www.npmjs.com/package/react-helmet)
- [styled-components](https://www.styled-components.com/)
- [react-loadable](https://www.npmjs.com/package/react-loadable)
- [tinymce](https://www.tiny.cloud/)
- [aws-sdk](https://aws.amazon.com/fr/sdk-for-node-js/)
- [react-toastify](https://fkhadra.github.io/react-toastify/)
- [react-ditepicker](https://reactdatepicker.com/) (not by default)

Install a package automatically
run the associated script in `template/packages-actions` if it exists

## Apollo (in progress)

For projects with a complex database,
apollo (GraphQl) provides powerful features.
The script installs it and configures it if you check the option.

## Server Side Rendering (todo)

Useful if you want to share your app on social networks.
This option :
  - installs `react-helmet` if it is not already done
  - configure Apollo for server-side rendering if it is installed

## Other ideas ? contribute !

Feel free to share your suggestions,
tips or other information via the issues.

If the heart tells you, fork it, code it,
and let's create a great tool !
