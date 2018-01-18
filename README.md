# Proyecto_0

Este es un repositorio desarrollado para ser utilizado como base en   proyectos rails, cuenta  con algunas gemas ya configuradas.

-------------------------------

## Versiones 

+ [ruby 2.4.1]
+ [rails ~> 5.1.4]

Tenga en cuenta que versiones anteriores a estas  presentan fallos de seguridad
-----------------------------------------------



## Gemas integradas
------------------------
El proyecto cuenta con:

+ [Devise](https://github.com/plataformatec/devise) - Como gema de autenticacion, con vistas y algunos mensajes traducidos al español

+ [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)- Como gema de autenticacion con facebook

+ [bootstrap 4](https://github.com/twbs/bootstrap-rubygem)- como framework para responsive design

+ [jquery-rails](https://github.com/rails/jquery-rails)- para integracion de jquery con rails

+ [certified](https://github.com/stevegraham/certified)- como solucion al error de " OpenSSL::SSL::VERIFY_PEER to verify SSL certificates " que en ocaciones produce el intento de login con facebook




### Instalacion

````````````````````````
bundle install
````````````````````````


````````````````````````
rails db:migrate
````````````````````````


````````````````````````
rails serve
````````````````````````


Agregue a config/initializers/devise.rb el APP_ID y el APP_SECRET que genera facebook para su aplicacion 

config.omniauth :facebook, "APP_ID", "APP_SECRET" 
--------------------------------------------

