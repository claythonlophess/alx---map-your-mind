mym{
n = new array();
done=false
# //1. Count and initialize

while(done){
  long x= input('input an number, please Sr.:');
   n.add(x);
   int todo = input("add another number? response: y/n");
   if(todo="n"){
     done=true;
   }
}
sumSquares(array n){
    int x=0;
	# //2. Calculate
    for(i=0 , array.leght-1 ,i++){
       x += n[i];
     }
     x =x/ array.leght;

    # //3. Subtract 4. Square

     for(i=0 , array.leght-1 ,i++){
       n[i] = (x - n[i])^2; 
     }
	# //5. Add
     for(i=0 , array.leght-1 ,i++){
       x += n[i];
     }
return x;
}
}
flow chart Diagrama sem nome.drawio.png

# mandatory 1. Order marches with weighty and measured strides. Disorder is always in a hurry.
# reads in three numbers and writes them all in sorted order

Step 1: Input the value for variables X, Y, Z.
Step 2: Read the integers X, Y, Z.
Step 3: Check if x>y, x>z, y>z
Step 4: Print the possible order.

flow chart ex1.png
