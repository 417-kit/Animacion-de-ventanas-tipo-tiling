Animacion bonita y fluida de ventanas (es mejor si tienes un monitor de 100hz)

Estas son algunas configuraciones que tengo en mi hyprland. El archivo "general.lua" (dentro de esta ruta /TuUsuario/.config/hypr/hyprland) no tiene errores pero esta algo desordenado, si quieres lo dejas asi o lo colocas y es todo. esta configuracion es para los dots https://github.com/end-4/dots-hyprland

Si quieres  ver algo de el funcionamiento de los dots y la configuracion entonces descarga el video de 30 segundos.
Animacion de ventanas (Hyprland)

1. Descarga el archivo "general.lua"
2. Colocalo en la ruta /TuUsuario/.config/hypr/hyprland/
3. Es todo. ya deberia funcionar en tu gestor de ventanas hyprland.

 Si no quieres usar los dots de el repositorio https://github.com/end-4/dots-hyprland entonces puedes usar el default.lua

instrucciones de el default.lua:

1. Descarga el default.lua
2. Colocalo en la ruta /TuUsuario/.config/hypr/conf/animations
3. Si te pide reemplazar el archivo default.lua haz una copia de el original ya que si tienes algun scrip o algo apuntando a ese archivo entonces hara un caos, posteriormente reemplaza el original.
4. Ya esta. Normalmente este vino de los dots MlW4 los cuales son para trabajo y son aburridos.

Configuracion y comando para instalar dynamicCursor

1. Instalar dependecias:

```sudo pacman -S --needed base-devel cmake cpio git meson gcc```

2.Normalmente usaras hyprpm el cual viene comunmente ne hyprland. usa este comando para colocar el repositorio:

```hyprpm add https://github.com/VirtCode/hypr-dynamic-cursors```

3. Habilita el plugin:

```hyprpm enable dynamic-cursors```

4. Recarga hyprland:

```hyprpm reload```

5. si no inicia automaticamente al iniciar entonces coloca ell inicio automatico en tu hyprland.lua o bien puedes escribir "hyprpm reload" cada vez que enciendas la PC lo cual es molesto.

6. Ahora si es todo.

7. Atentamente: Kit
8. 
          %S*                      
          %,SS                     
         *+  SS             +##    
         #    #S         ??S#@%    
        .S    ;SS     SS%#  @S     
        @%.    ;%% ;S?:  . S@:     
        @:     ,?SS   :   .@S      
        #          %+ ,: .@@     Kit  
        #;         . .;::@@        
       .@       ;,%%S#,*S@         
       #%      S*?;%SSS?@%,        
       @?    .+?%;?++ @S#S         
       #S*    ?@##%S ;@%#S%        
         SSS.;;%#S%?*.%+#          
          :.S#####S% # *           
             %S ,?.#;%+?%          
             #   ;  #:S#,,         
