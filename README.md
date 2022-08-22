# live-chat-webapp-

The following project is realtime live chat web app
     The following steps that are followed 
         creating npm project 
         installing dependancies express,nodemon(dev dep.)
         creating express server (server.js)
         installing socket.io then setting up socket.io in server.js and client in client.js
         
         
 explaining the whole project here=
      starting the process by creating folder then creating npm project by command in terminal as npm_init -y
      then creating index file style.css file and client.js file coming to index file we generated basic boiler plate
      then linked css file in index.html and also linked the client.js file.After than to handle server side code we installed express
      then installed nodemon for automatic server restart .In next step created server.js file for server side handling in server.js i called 
      express and also for deplyoment time  made variable port after that making http module to to call port.In next step i created route.
      after it run by command npm run dev as dev is given name by us.For frontend part created div name for app then uploded img 
      in inext div created message area in style.css file used roboto and created basic body reset and also gave background color and font 
      then in server.js mentioned our url with express .For real time web socket used socket.io library and installed it.After installing socket.io 
      need to setup in server.js so in server.js first imported socket.io by creating io variable and called function .We also need to setup socket.io
      in client.js to so made script and mentioned to load client library.After setting up socket.io we need mention logic of it in client.js  by creating name var
      iable basically giving user name in every server .After it just used callback function to ensure that name writing.creayed html markup in client.js 
      in main div then append.also for reciving message in client.js so that it will recive message sent.So this was abount setting up real time chat web app 
      where two and more can chat at same time.master repository contain reatime cat app while text editor repository kept as branch due to below mentioned reasons
      For text editing feature i directly used ckeditor by basically writing index.html file and then using 
      already available ckeditor.js file.The text editing feature has been not kept seperatly as its files were defaults and also other
      server setup and creating live chat app files has been written from scrath and taking some help from different documentations.
      
      
         
