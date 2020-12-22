//  rest parameter
 
 function sum(...numbers){

    return numbers.reduce(function(prev, current)
{
return prev + current;

})
 }


 console.log(sum(1, 2, 3, 5, 6, 7, 8, 9, 9, 50,));


// spread operator 
 function bum(x, y, z){

    return x +y +z;

 }

let nums = [1,2,7]

 console.log(bum(...nums));# spread-restoperators