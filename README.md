# Mini Blog

Requerimientos : 

* Ruby - version 2.3.1p112 
* Rails - version 5.0.7
* Postgresql Database - client version 10.5
                      - server version 10.1

Comandos para correr la aplicación:
  *Posicionarse en directorio principal(~mini-Blog) y ejecutar:
   $ rake db:create 
   $ rake db:migrate 
   $ rake routes
   $ rails s 
  
Abrir en navegador: http://localhost:3000

#Paths 

GET /posts  -> ejecuta las acciones en posts#index 
GET /posts/new  -> ejecuta las acciones en posts#new 
GET /posts/:id  -> ejecuta las acciones en posts#show 
GET /posts/:id/edit  -> ejecuta las acciones en posts#edit 
POST /posts  -> ejecuta las acciones en posts#create 
PATCH or PUT /posts/:id  -> ejecuta las acciones en posts#update 
DELETE /posts/:id  -> ejecuta las acciones en posts#destroy 
