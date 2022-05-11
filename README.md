<img src="https://img.gta5-mods.com/q95/images/wheels-custom-pack-ganjahouse/3cf56b-ganja.png" />

# Wheels Custom Pack - Addon [FIVEM READY]

## ENGLISH ⬇️
### Wheels Custom Pack + Fix Null in esx_lscustom

⬇️Tutorial for the less experienced⬇️
<details>
  <summary><h1>TUTORIAL</h1></summary>
Client ▶️ tuning.lua

When we enter tuning.lua we will find this:
```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "Drift Benz 06")
```
That's easy to figure out, but if you don't know much, just modify this:
```
AddTextEntryByHash(GetHashKey("CHANGE"), "CHANGE")
```
In the first "CHANGE" you have to put the name of the tuning.
To do this, we are going to go directly to the "STREAM" file and choose one. I'm going to take the one from "wheel_drft_benz_06.ydr" and the code would stay like this:
```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "CHANGE") 
```
The other "CHANGE" is the name, so let's add for example "Drift Benz 06" and it would look like this:

```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "Drift Benz 06")	
```
And with that, it should work :3
### IMPORTANT: do not put a comma after to go to the next. it won't work like that
</details>

## SPANISH ⬇️
### Pack de llantas Custom + Fix Null en esx_lscustom

⬇️Tutorial para los que no tienen experiencia⬇️
<details>
  <summary><h1>TUTORIAL</h1></summary>

Client ▶️ tuning.lua

Cuando entremos en tuning.lua nos encontrarémos esto:
```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "Drift Benz 06")
```
Eso es facil de descifrar, pero si no sabes mucho, solo modifica esto:
```
AddTextEntryByHash(GetHashKey("CAMBIAR"), "CAMBIAR")
```
En el primer "CAMBIAR" hay que poner el nombre del tuneo.
Para ello, vamos a ir directamente al archivo "STREAM" y escogemos uno. Yo voy a coger el de "wheel_drft_benz_06.ydr" y el codigo se quedaría así:
```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "CAMBIAR")
```
El otro "CAMBIAR" es el nombre, así que vamos a añadir por ejemplo "Drift Benz 06" y así quedaría:
```
AddTextEntryByHash(GetHashKey("wheel_drft_benz_06"), "Drift Benz 06")	
```
Y con eso, ya debería funcionar :3
### IMPORTANTE: no poner una coma despues para ir al siguiente. Así no funcionará
</details>

# Link original:
https://es.gta5-mods.com/vehicles/wheels-custom-pack-ganjahouse

# ALGUNAS FOTOS | ALGUNAS FOTOS:
<img src="https://img.gta5-mods.com/q95/images/wheels-custom-pack-ganjahouse/f87448-benz.jpg" />
<img src="https://img.gta5-mods.com/q95/images/wheels-custom-pack-ganjahouse/390577-lowrider%20org2.jpg" />
