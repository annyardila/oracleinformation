# oracleinformation

1. Busca PowerShell 
![image](https://user-images.githubusercontent.com/57542602/132620328-365595ec-8fa9-4738-8ac5-7f8b6c5bac11.png)

2. Ejecuta PowerShell
![image](https://user-images.githubusercontent.com/57542602/132620420-9b53c80d-fa88-4f65-b301-7b4fc857b5f3.png)

3. Ejecuta el comando ssh-keygen desde la terminal. Preste especial atención a dónde se guardará el archivo para que pueda localizarlo más tarde. 
**ssh-keygen** se establecerá de forma predeterminada en el directorio .ssh estándar en el directorio base del usuario. 
![image](https://user-images.githubusercontent.com/57542602/132620588-3baea9b6-8358-445b-9439-7d769edea0a4.png)

4. Al ejecutar el comando, deje el nombre por defecto, que será id_rsa_test 
![image](https://user-images.githubusercontent.com/57542602/132620816-7cf98d92-ff79-41d0-97f5-50e8c419db16.png)

5. La carpeta por defecto donde se alojarán las llaves es .ssh, valide con el comando cd .ssh que tenga las llaves id_rsa y id_rsa.pub
 ![image](https://user-images.githubusercontent.com/57542602/132620915-8651907b-729e-4a21-9daf-b7cda4c1ee15.png)
 
6. Cuando cree la instancia en OCI asegurese de cargar la llave id_rsa.pub
![image](https://user-images.githubusercontent.com/57542602/132621200-692b6060-6cd7-45c9-8d36-a9b8684af38a.png)

7. Valide la IP Publica de la VM 
![image](https://user-images.githubusercontent.com/57542602/132621406-74330836-2b6d-44a4-9e18-9da082707161.png)

8. En Powershell ubiquese en directorio por defecto de .ssh y ejecute el comando ssh -i id_rsa opc@(IP de la VM)
![image](https://user-images.githubusercontent.com/57542602/132621513-0b6bfa8f-688f-4b9b-83e2-f0ee093b7a71.png)

y listo ;) 

![done-and-done-spongebob](https://user-images.githubusercontent.com/57542602/132621726-59351e0f-3930-4ba8-b170-d031da3b1c8f.gif)




