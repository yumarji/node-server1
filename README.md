# node-server1

1- ¿Qué sucedio al usar async y await?
Tuve que crear la función async para usar dentro del return el await y luego llamar a la función asincrónica.
 async function add2(taskList){  
       await addTask(taskList)
       menu()
      }
      add2(taskList);
      
2- ¿Qué sucedió al usar el método then()?
Solamente se colocó la función promesa y el .then con la información que deseamos que resultara despúes.
  completedTask(taskList).then(menu(taskList))   

3- ¿Qué diferencias encontraste entre async, await y el método then()?
Que con el .then es muy fácil concatenar, y con el async, await se ve un código más ordenado.
