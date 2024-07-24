# Swisstronik test nest
1. Add your private key in `.env`
2. Run deploy contract
```shell
npx hardhat run scripts/deploy.js --network swisstronik
```
3. Test send messages:
```shell
npx hardhat run scripts/setMessage.js --network swisstronik
```
```shell
npx hardhat run scripts/getMessage.js --network swisstronik

```


