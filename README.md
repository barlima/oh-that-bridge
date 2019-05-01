# Oh, that bridge!

**Oh, that bridge!** is an application which the main goal is to help people recognizing and finding bridges they've seen during the day.
In other words, people will find here many bridges displayed in a pleasant way.

## Why this application has ever been created?

This application has been created in order to strengthen knowledge about:
- React Hooks,
- docker-compose,
- `useQuery` and `useMutation` Apollo hooks
- some UI and UX

## Starting the application

In order to run the application, make sure you have `docker` and `docker-compose` installed on your machine.

To start the application run:
```shell
$ docker-compose up -d
```
The application should be accessible under `0.0.0.0:8000`.

---

To fill the database with example bridges, run:

```shell
$ docker-compose run api rails db:setup
```

---

If you face any issues, check if the containters are running:
```shell
$ docker-compose ps
```

or chack logs:
```shell
$ docker-compose logs
```

## Enjoy!
