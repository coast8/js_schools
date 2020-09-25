

function f1(func){
	return func();
}

function f2(){
	return 'return f2'
}

console.log(f1(f2))


