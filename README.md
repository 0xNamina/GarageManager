# GarageManager

Car garage management system with struct operations for complete CRUD functionality.

## Description

This contract demonstrates struct usage in Solidity by implementing a comprehensive car garage management system. Each user can maintain their own collection of cars with full create, read, update, and delete operations.

## Features

- **Car Struct**: Stores make, model, color, and number of doors
- **Personal Garage**: Each address has its own car collection
- **CRUD Operations**: Complete Create, Read, Update, Delete functionality
- **Index Validation**: Custom error handling for invalid car indices

## Car Properties

- `make` (string) - Car manufacturer
- `model` (string) - Car model name
- `color` (string) - Car color
- `numberOfDoors` (uint256) - Number of doors

## Deployment Instructions

1. Open [Remix IDE](https://remix.ethereum.org/)
2. Create a new file and copy-paste the contract code
3. Compile the contract using Solidity ^0.8.17
4. Deploy on **Base Sepolia Testnet**
5. Interact with the functions:
   - `addCar(...)` - Add a new car to your garage
   - `getMyCars()` - Get your car collection
   - `getUserCars(address _user)` - View another user's cars
   - `updateCar(uint256 _index, ...)` - Update a specific car
   - `resetMyGarage()` - Clear all your cars

## Submit Exercise

[📖 Submit Structs Exercise](https://docs.base.org/learn/structs/structs-exercise)
