# programaci-n-web
Tarea

listas= [1,4,6,2,7,9,3,11]
for x in range(8):
	for a in range(8):
		if listas[x]+ listas[a] ==10:
			print(f"{listas[x]} + {listas[a]} =10")




let myArray = [1,8,8,5,4,6,7,2,2,8]
let num;
let contador=1;
let numaux;
let contaux=1;

for(let i = 0; i < myArray.length; i++){
    contaux = 0;
    for (let j = 0; j < myArray.length; j++) {
        if (myArray[i] === myArray[j]) {
            contaux++;
        }
        if (contaux>contador) {
            num=myArray[i]
            contador=contaux;
        }
    }
}

console.log(num);
console.log(contador);












let myArray=[1,2,1,3,3,1,2,1,5,1]
let uno="1: ", dos="2: ", tres="3: ", cuatro="4: ", cinco="5: ";
let booleano = true;
for (let i = 0; i < myArray.length; i++){
    if (myArray < 1 || myArray > 5) {
        booleano = false;
        break;
    }
    switch (myArray[i]) {
        case 1:
        uno += "*";
        break;
        case 2:
        dos += "*";
        break;
        case 3:
        tres += "*";
        break;
        case 4:
        cuatro += "*";
        break;
        case 5:
        cinco += "*";
        break;
    }
}
console.log(uno);
console.log(dos);
console.log(tres);
console.log(cuatro);
console.log(cinco);

