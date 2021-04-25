```
git clone https://github.com/hasangnu/passbolt.git && cd passbolt
```

```
docker-compose up -d
```

```
docker-compose exec passbolt su -m -c "bin/cake passbolt register_user -u hasan@hasanucar.net -f Hasan -l Ucar -r admin" -s /bin/sh www-data
```
