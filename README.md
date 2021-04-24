## Harmony Terra Bridge

### Requirement:

```
node >= 14
redis
```

### How to use

```
cd shuttle/eth
cp .env_example .env
npm i
```

You can change TERRA_TRACKING_ADDR in terra/.env and shuttle.harmony in bridge-web-app/src/consts/network.ts

```
cd shuttle/terra
cp .env_example .env
npm i
```

UI

```
cd bridge-web-app
npm i
```

Run shuttle/eth, shuttle/terra and bridge-web-app.
