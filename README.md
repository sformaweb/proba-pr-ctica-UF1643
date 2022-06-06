### Novo plantexamento aplicación SOL

Tras varios meses traballando na nova aplicación do SOL, vaise realizar un novo enfoque para aportar ideas que nos permitan refrescar o plantexamento. Para isto, serán necesarios distintos cambios con respecto á aplicación actual:

Partimos tendo en conta que as persoas que van utilizar a aplicación serán orientadores laborais que precisan un CRM que permita xestionar a BBDD que contén os usuarios do Servizo de Orientación Laboral. Xunto a eles deberanse almacenar os seus datos persoais, académicos e laborais, o que permitirá suxerirlle ofertas de emprego e formación adecuándose ás súas condicións. Ademáis, por parte dos orientadores deberán poderse realizar seguimentos dos distintos procesos polos que pasan os usuarios. Para poder ofrecer ofertas de emprego tamén será necesario almacenar datos de empresas colaboradoras. O contacto coas empresas e cos usuarios poderase realizar por vía telemática (vía SMS ou e-mail), presencial ou telefónica. Para a xestión das citas empregarase o sistema que se usa a nivel xeral no Concello de Vigo.

A nivel de permisos, o ideal sería contar con dous niveis de permisos: usuario e administrador. O primeiro serán os traballadores habituais do SOL e o segundo será o encargado de resolver cuestións técnicas como cambios de contrasinais, problemas na BBDD, etc.

Ademáis, dentro do aspecto técnico, sería interesante crear a BBDD dende cero, xa que tras analizala concluiuse que contén demasiadas táboas con interrelacións complexas, polo que se podería simplificar para que responda só ao que se precisa.

#### Cambios



* Modificar a palabra “usuarios” por “persoas”, a petición do cliente.
* Modificar a palabra “logout” por “saír” para unha maior coherencia lingüística.
* Cambiar por completo o deseño gráfico, implementando tipografías e unha paleta de cores corporativas.
* Outorgarlle unha maior relevancia ao filtrado por familias profesionais, por petición explícita do cliente.
* Engadir novos filtros para a xeración de informes: información sobre cantas persoas se apuntan a unha oferta, que formacións teñen máis éxito entre as persoas usuarias do servizo, cantas atoparon traballo/formación, etc. 
* Eliminar seccións e subseccións do menú redundantes ou con pouca utilidade para ofrecer unha visión máis clara dos contidos. Do mesmo xeito, poderíanse fusionar subseccións que actualmente están separadas, como por exemplo as de experiencia laboral e formación dentro de usuarios. 
* Tamén se podería reubicar a sección de cambio de contrasinal, que ten máis sentido incluíla dentro dunha páxina de perfil para o usuario que iniciou a sesión.Cifrar ou impedir o acceso a datos sensibles segundo a operación que se esté a realizar (número do DNI, datos persoais privados…)
* Actualmente, tras realizar o inicio de sesión, a páxina de inicio está en branco, dando a sensación de que se produciu un erro. Por este motivo, sería preciso engadir unha cabeceira e distintas seccións.
* Engadir unha función que permita facer limpeza na base de datos (información obsoleta, baixas do sistema, etc.) Sería interesante programar rutinas para isto que de xeito automático eliminasen datos ao pasar un certo tempo.
* Posibilidade de xerar informes para visualizar na propia páxina, sen necesidade de descargalos. Así mesmo, seleccionar a información que se mostra neses informes, posto que non sempre se precisan todos os datos.
* Engadir un pequeno botón de axuda nas distintas seccións que, ao facer *hover*, se mostre unha breve explicación do contido que sirva de guía para novos usuarios.Facela responsiva, usable e accesible.
