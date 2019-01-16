# JavaScript Object/Scope In Class

1. What’s the result of executing this code and why.
  ```
  function test() {
     console.log(a);
     console.log(foo());
     
     var a = 1;
     function foo() {
        return 2;
     }
  }
  
  test();
  ```

2. What’s the result of executing this code and why.
  ```
  var a = 1; 
  
  function someFunction(number) {
    function otherFunction(input) {
      return a;
    }
    
    a = 5;
    
    return otherFunction;
  }
  
  var firstResult = someFunction(9);
  var result = firstResult(2);
  ```

3. Create a new empty array called ```pet_list```. Add 3 ```pet``` objects to the ```pet_list``` array (each ```pet``` should have a ```type``` and a ```breed property```) You can choose the pets.

* Add a new property called ```age``` to each pet instance in ```pet_list'''

* Assign a number for the ```age``` for all of the pets

* Iterate the list of pets and print the properties for each pet


