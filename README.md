This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Clone this repository.

Run `npm start` and the browser open at `http://localhost:3000`

### `npm test`

Files tests are : __Board.test.js__,  __Game.test.js__, __Square.test.js__ .

To test i use Enzyme. I create a file named __"setUpTests.js"__ and add these lines : 

      import { configure } from 'enzyme';
      import Adapter from 'enzyme-adapter-react-16';


      configure({ adapter: new Adapter() });

To run test launch `npm test`


