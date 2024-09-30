# Important questions and their answers.
1. What is state ?
   - Data that a components can hold over time, act as components memory.
   - updating the state triggers the react to re-render the components.
2. What are the steps to use state ?
   - Add a new state variable
   - use it in the code and usually JSX
   - update that variable using setter function
3. What are hooks ?
   - function that start with use such as useEffect(), useState() etc are called as hooks.
4. Is state are mutable or immutable ?
   - Always treat state as immutable in react, something taht we cannot change directly, but can be change using tools that react gives us like setter functions.
5. Why is react called as react ?
   - React is called react because react reacts to state changes by re-rendering the UI .
6. What to do when we want to update the state based on current value in setter function of getState();
   - use callback in form of arrow functions.
7. How to create select element from 1-20 using arrays method ?
   ```
      <select>
        {Array.from({ length: 20 }, (_, i) => i + 1).map((num) => (
          <option value={num} key={num}>
            {num}
          </option>
        ))}
      </select>
      ```
8. What are controlled elements ?
   - Controlled Elements:- it is react which control and owns the state of input fields in form not longer  the DOM.
   - Steps are: -
      - Create a piece of state
      - Use that piece of state where we want to control.
      - Update state using handler function..
