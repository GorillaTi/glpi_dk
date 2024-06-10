```bas
$$$$$$$$\ $$\   $$\ $$$$$$\ $$$$$$$$\ 
$$  _____|$$ | $$  |\_$$  _|\__$$  __|
$$ |      $$ |$$  /   $$ |     $$ |   
$$$$$\    $$$$$  /    $$ |     $$ |   
$$  __|   $$  $$<     $$ |     $$ |   
$$ |      $$ |\$$\    $$ |     $$ |   
$$$$$$$$\ $$ | \$$\ $$$$$$\    $$ |   
\________|\__|  \__|\______|   \__|
```

---

# GLPI con Docker compose

Ver en 

```url
Localhost:8200 
```

o 

```url
[IP]:8200 
```

## Configurando GLPI

### MySQL

host: `mysql`

usuario: `glpi`
contraseña: `glpi`

### GLPI

Los usuarios / contraseñas predeterminadas son: 

| Cuenta        | Usuario    | Contraseña |
| ------------- |:----------:|:----------:|
| administrador | `glpi`     | `glpi`     |
| técnico       | `tech`     | `tech`     |
| normal        | `normal`   | `normal`   |
| sólo lectura  | `postonly` | `postonly` |

Puedes suprimir o modificar estas cuentas así como los datos iniciales.
