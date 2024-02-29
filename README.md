# Find-the-Dentist

Write a function that takes an array of people objects (people) and returns the first person object in the array that has the isDentist property set to true. If no dentists are included in the people array, the function should return null.

findFirstDentist([]) // returns null

findFirstDentist([{name: 'Callum', isDentist: false}]) // returns null

findFirstDentist([{name: 'Callum', isDentist: false}, {name: 'Carrie', isDentist: true}]) // returns {name: 'Carrie', isDentist: true}

findFirstDentist([{name: 'Callum', isDentist: true}, {name: 'Carrie', isDentist: true}]) // returns {name: 'Callum', isDentist: true}
