function destroyer(arr) {
  // Remove all the values
  let args = Array.prototype.slice.call(arguments);
  let newArr = arr.filter(a => {
    return args.indexOf(a) === -1
  });
  return newArr
}
destroyer([1, 2, 3, 1, 2, 3], 2, 3);

//This algorithm looks at an array for elements that exist in the arguments object and removes them from the array
//First you have to convert the Arguments object to an array because the Arguments object's only property is '.length'
//Once you convert it to an array, it can use the Array prototype's '.filter()' method
//Then you filter out the elements that are shared by 'args' and return an array with elements NOT shared by 'args'
