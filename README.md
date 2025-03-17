# psitransfer
PsiTransfer Compartir archivos  mediante Docker
```
git clone https://github.com/mclitos/psitransfer
```

```
cd psitransfer
```
### Editar el parametro PSITRANSFER_ADMIN_PASS con una contraseña deseada 
```
sudo nano  docker-compose.yaml
```
Contraseña por defecto; secret

```
docker compose up -d
```
### Importante cambiar permisos a la carpeta ./data
```
sudo chown -R 1000 ./data
```

Ver en: IP:7426
