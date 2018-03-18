# TemperatureStop
Im triying to set a startup script that runs lm-sensor, reads, the output, and runs a kill if it get to tresshold.

//**
Im triying to: 
run a script on startup
(https://askubuntu.com/questions/814/how-to-run-scripts-on-start-up), 

that runs lm-sensor
(https://wiki.archlinux.org/index.php/lm_sensors) 

and reads the temperature output
(https://wiki.archlinux.org/index.php/Lm-sensors_(Espa%C3%B1ol)#Leyendo_los_valores_SPD_desde_los_modulos_de_memoria_.28Opcional.29),

i2c tools for reading output?
modprobe eeprom
modprobe: ERROR: could not insert 'eeprom': Operatrion not permitted

and kill -9 -1 (or better option) kills all allowed proccesses(ends session)
**//


