
for(i=1;i<=100;i++)
{
  a=i/3;
  b=i/5;
  c=i/15;
  
   if(Number.isInteger(a))
   {
       console.log("Fizz");
   }
   else if(Number.isInteger(b))
   {
       console.log("Buzz");
   }
   else if(Number.isInteger(c))
   {
       console.log("FizzzBuzz");
   }
   else{
       console.log(i);
   }
}
