SyntaxError: /home/squirtcobain/repos/javascript-exercises/04_removeFromArray/removeFromArray.js: Binding 'arguments' in strict mode. (6:43)

      4 | //const itemsToDelete = [3];
      5 |
    > 6 | const removeFromArray = function(array, ...arguments) {
        |                                            ^
      7 |       const itemsToDelete = [...arguments];
      8 |       const filteredArray = []
      9 |

    > 1 | const removeFromArray = require('./removeFromArray')
        |                                                     ^
      2 |
      3 | describe('removeFromArray', () => {
      4 |   test('removes a single value', () => {
