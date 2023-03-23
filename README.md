# DApp

## Запуск

Выполнить в терминале

```
npm install
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
cd frontend/
npm install
npm start
```

## Запуск тестов

Выполнить в терминале

```
npx hardhat test
```
Образец вывода теста
```
  Storage contract
    ✔ Deployment (1342ms)
    ✔ The user should not have files in the newly created contract
    ✔ After sending the hash to the smart contract, it can be received when calling getter (44ms)
    ✔ The contract should emit an event when registering a hash


  4 passing (1s)
```
