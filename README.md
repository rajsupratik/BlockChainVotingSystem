# Blockchain Voting System

## Introduction

This project is a blockchain-based voting system built using React for the frontend, Node.js for the backend, and Solidity for the smart contract. The voting system ensures transparency and security by leveraging blockchain technology.

## Features

- User authentication (register and login)
- Casting votes for candidates
- Viewing voting results

## Directory Structure

blockchain-voting-system/
├── backend/
│   ├── config/
│   │   ├── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── voteController.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Vote.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── voteRoutes.js
│   ├── .env
│   ├── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   ├── Voting.js
│   │   │   ├── Results.js
│   │   ├── App.js
│   │   ├── App.css
│   ├── .env
│   ├── package.json
├── contracts/
│   ├── Voting.sol
│   ├── migrations/
│   │   ├── 1_initial_migration.js
│   │   ├── 2_deploy_contracts.js
├── migrations/
│   ├── 1_initial_migration.js
├── truffle-config.js
├── README.md
