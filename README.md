# Asp.net Blazor-wasm app as web client with grpc-web(.net6 with C#)
A .NET Core-6 Blazor-WASM Web app which done an implementation with  grpc-web(.net6 with C#) for high performance and huge amount of data loading at webapp -loading huge amount data at chorme/edge browser in  windows 10 enviroment.

Give a Star! ⭐
----------------------------------------------------------------------------------------------------------------------
If you like this project, learn something or you are using it in your applications, please give it a star. Thanks!

PreFace
--------------------------------------------------------------------------------------------------------------------
**have u see that a huge amout of data are loading to a UI browser (10K count of rows  records data)** -- *NO* , It is not possible to handle  huge amount of data at web applicatuon or *http/tcp or werbshoket* protocole</br>
Normally, For loading a huge amount data at UI web app, We used to follow below tricks as.. </br>
*1) trying pagination concept at store procedure(db level) for retuning huge data as chunks by chunks to web client-</br>*
*2) trying do pagination logic at API/ UI app and used to do cashing mechanism for most viewable page's data at web client -</br>*
*3) trying do batch kind processing in background app and used to load or pushing data to UI app or storage - </br>*
If you are loading below azure histed website and try to load huge amount(click at 'Fetch data 10k') data at Browser-chrorme and Thanks to  #msft for grpc-web framework </br>
for increasing request /response msg sizing of web or many others feature like web streaming . Above UI page is taking  time(2/4 minutes) to load 10k counts of rows data.</br>

Please, Check for Azure Hosted application , Web URL- https://lnkd.in/gR_uQE_k

Description
----------------------------------------------------------------------------------------------------------------------
Code repo with  .NET Core-6 Blazor-wasm app implementation with  grpc-web(.net6 with C#) for high performance and huge amount of data loading </br>
It require below tool, process </br>
1)Windows 10/11 -64 bit OS. </br>
2)Docker desktop installed. </br>
3)Visual Studio 2022 IDE and .NET6 version installed. </br>
4)Stable internet connectivity. </br>

# Code setup Instructions of  *master* branch on dev system 
----------------------------------------------------------------------------------------------------------------------
1)First ,Make sure to install Visual Studio 2022 IDE and .NET6 version on the Local system. </br>
2)Clone this code repo to the local system by using  a CMD like **git clone <<git-url>>t** .</br>
3)After cloning the code repo ,Open .sln file with Visual studio 2022 IDE and make the  grpcBlazorClientWeb.Server (server) project as startup project .There is no depandency on sql database 
and try to rebuild on top of the solution. </br>
4)No build errors should come with Visual studio 2022 IDE and open package manager console  for database  migration purposes. </br> 
5)Run the application with Visual Studio 2022 IDE with or without debugger mode.

