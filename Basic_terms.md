### Basics

- it or test: describes the test itself. It takes as parameters the name of the test and a function that holds the tests.
- expect: the condition that the test needs to pass. It will compare the received parameter to a matcher.
- a matcher: a function that is applied to the expected condition.
- render: the method used to render a given component.

<!-- 
import React from 'react'
import {render} from '@testing-library/react'
import App from './App'
 
 it('should take a snapshot', () => {
    const { asFragment } = render(<App />)
    
    expect(asFragment(<App />)).toMatchSnapshot()
   })
});
 -->