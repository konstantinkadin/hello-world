# hello-world


isEven()
function isEven(x){
	if(x%2!==0){
		return "Even: False";
}else{
		return "Even: True";
}
}

------------------//--------------------
factorial()
function factorial(c){
var total=1;
if(c>0){
	for(var i=1; i<=c; i++){
		total=total*i;
	}
}
if(c==0){
total=1;
}
return "The Factorial of " + c + " is " + total;
}

------------------//--------------------
kebabToSnake()
function kebabToSnake(str){
	var hip=str.replace(/-/g, "_");
	return hip;

}
