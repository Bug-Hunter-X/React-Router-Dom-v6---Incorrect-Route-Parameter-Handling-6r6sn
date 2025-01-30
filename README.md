This repository demonstrates a common issue encountered when using React Router Dom v6: incorrect handling of route parameters.  The `bug.js` file shows the problematic code, where the route '/users/:id' fails to render properly due to a missing parameter destructuring in the `User` component.  The solution, provided in `bugSolution.js`, fixes this by correctly destructuring the `params` object using `useParams` hook. 