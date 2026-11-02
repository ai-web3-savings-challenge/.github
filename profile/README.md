# AI × Web3 Savings Challenge

Starter project for the French Tech Lagos AI × Web3 Developers Challenge. It combines a React dashboard, an AI savings-insights backend, simulated bank data and a savings-goal smart contract on the Celo Sepolia test network.

All data is synthetic and the blockchain part uses a test network. No real money moves.

## Get started

**Navigate to [`docs/setup.md`](https://github.com/ai-web3-savings-challenge/docs/blob/main/setup.md) to set up and run the project.** It covers installing the prerequisites, setting up MetaMask on Chrome, and running the backend and the frontend.

## Documentation

| File | What it covers |
|---|---|
| [`docs/setup.md`](https://github.com/ai-web3-savings-challenge/docs/blob/main/setup.md) | Step-by-step setup for the backend, frontend and wallet |
| [`docs/api-reference.md`](https://github.com/ai-web3-savings-challenge/docs/blob/main/api-reference.md) | Mock API, AI endpoint and smart contract reference |
| [`docs/mentor-guide.md`](https://github.com/ai-web3-savings-challenge/docs/blob/main/mentor-guide.md) | Guide for mentors: checklist, demo script and common problems |

## Project structure

- `frontend/`: the dashboard (React + Vite)
- `backend/`: the AI analysis endpoint and the contract event listener
- `contracts/`: the `SavingsGoal` smart contract source
- `mock-api/`: the mock API resources
- `docs/`: all documentation
