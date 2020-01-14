This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `Start`

Clone this repository.

Run `npm start` and the browser open at `http://localhost:3000`

### `Test`

To test i use Enzyme. I create a file named __"setUpTests.js"__ and add these lines : 

      import { configure } from 'enzyme';
      import Adapter from 'enzyme-adapter-react-16';


      configure({ adapter: new Adapter() });
 
Files tests are : 
      * __Board.test.js__,  
      * __Game.test.js__, 
      * __Square.test.js__ .

To run test launch `npm test`


### Application demo 

The application can be tested at this address : https://morpion-game.netlify.com/

This application is hosted on [Netlify](https://app.netlify.com/). 
It's a Paas (Plate-forme en tant que service i.e Platform as a service)
