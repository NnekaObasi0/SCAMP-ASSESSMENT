# SCAMP-ASSESSMENT

var Fibonacci_series = function (n)
{
 If (n===1)
   {
     return [0, 1]
   }
     else
   { var s = Fibonacci_series (n -1);
     s.push(s[s.length - 1] + s[s.length - 2);
     return s;
   }
  };
     console.log(Fibonacci_series (8));
     
     
         
