# METODOS DE MUTACION EN ARRAYS

	const characters =[{
		name: "Nataly",
		age: 33,
		job: "Data science"
	},
	{
		name: "Adrián",
		age: 17,
		job: "Frontend"
	}]

## push() 

Agrega el elemento al final del array	

	characters.push({
		name: "Ivan D.",
		age: 33,
		job: "Full-Stack Developer"
	})

## pop()

Eliminar el ultimo elemento de un array

	let deleteCharacter= characters.pop()
	console.log(deleteCharacter)


## unshift()

Agregar un nuevo elemento al array en la primer posicion

	characters.unshift({
		name: "Iván S. Nieto",
		age: 60,
		job: "Artist"

	})

## shift()

Quita el primer elemento de un array

	let deleteFirstCharacter = characters.shift()
	console.log(deleteFirstCharacter)