# PySnapshot Downloader
> EN | This is a simple tool to download snapshots/frames from video/streaming of security cameras by example.  
> BR | Esta é ferramenta simples para baixar frames de videos/streaming de cameras de segurança por exemplo.
</br> 

### Usage | Uso
### 1)  
EN | Go to "URLs" array, customize image name and after period you put the andress.  
BR | Vá no array "URLs", customize o noem da imagem, conforme os exemplos abaixo, e depois da vírgula, coloque o endereço da imagem. 

_"image name + Date and hour + extension, image andress"_
</br>
#### Ex: 

```
URLs = [
"Photo-Hall-" + tstamp + ".jpg","http://site:7002/Interface/Cameras/GetSnapshot?Camera=01&Width=640&Height=480&Quality=70&AuthUser=user&AuthPass=@password",
"Photo-Entrance-" + tstamp + ".jpg","http://site:7002/Interface/Cameras/GetSnapshot?Camera=02&Width=640&Height=480&Quality=70&AuthUser=user&AuthPass=@password",
.
.
.
"Photo-Garden-" + tstamp + ".jpg","http://site:7002/Interface/Cameras/GetSnapshot?Camera=02&Width=640&Height=480&Quality=70&AuthUser=user&AuthPass=@password"
]
```
</br>  

### 2)
   
EN | After that just run the program through the CMD: python pysnapshot_downloader  
It creates multiple processes to download at the same time, so snaps can be delayed for seconds depending on the amount, processing and connection.  
  
  
BR | Após isso basta rodar o programa através do CMD: python pysnapshot_downloader  
Ele cria vários processos para baixar ao mesmo tempo, portanto os snaps podem ter atrasos de segundos dependendo da quantidade, do processamento e da conexão.  
  
 
   
*EN | You can download images from the web too, just just put the addresses in the array.  
*BR | Você pode baixar imagens da web também, basta apenas colocar somente os endereços no array.

