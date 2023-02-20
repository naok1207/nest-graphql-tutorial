**set up**

```
yarn install
devbox add postgresql
devbox run initdb
> password
> password
```

**start**

```
devbox shell
npx prisma migrate dev --name post
npx prisma studio
yarn run start
```

`devbox run initdb`を実行すると以下の二つのエラーが出るが無視

```
Error: Service "postgresql" failed to start
source: exit status 1
```

```
Error: Service "postgresql" failed to stop
source: exit status 1
```

[参考](https://zenn.dev/rince/articles/50a66241d04f0b)
