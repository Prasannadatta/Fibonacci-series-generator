function fibonacciGenerator (n) 
{
    let fib_arr=[];
     
        if(n===1)
        {
            fib_arr=[0];
        }
        else if(n===1)
        {
            fib_arr=[0, 1];
        }
        else
        {
            fib_arr=[0, 1];
            for(var i=2;i<n;i++)
            {
                    fib_arr.push( fib_arr[fib_arr.length-1] + fib_arr[fib_arr.length-2] );
            }
        }
   
    return fib_arr;
}

let n = prompt("Insert value of n");
fib_arr = fibonacciGenerator (n);
console.log(fib_arr);
