# Registro Automotor en Web3

Esta aplicación es una demostración del registro automotor basado en tecnología Web3. Utilizando contratos inteligentes y tokens no fungibles (NFT), los usuarios pueden registrar y transferir la propiedad de vehículos de manera segura y transparente en la blockchain.

## Características

- **Registro de Vehículos**: Los usuarios pueden crear un registro único para cada vehículo, almacenando información clave como el modelo, el año y la patente.
- **Registro de Wallet**: Los usuarios tendrán que asociar la wallet a un DNI; esto es necesario para cada movimiento de la propiedad.
- **Propiedad como NFT**: Cada vehículo registrado se representa como un NFT, lo que asegura la integridad y la propiedad del registro en la blockchain.
- **Transferencia de Propiedad**: Los propietarios pueden transferir la propiedad del vehículo a otros usuarios de manera segura y sin intermediarios, utilizando contratos inteligentes.

## Tecnologías Utilizadas

- **Blockchain**: Implementación en la red de prueba SEPOLIA.
- **Smart Contract**: Desarrollado en Solidity y desplegado con Hardhat.
- **Frontend**: Interfaz de usuario desarrollada con React y TailwindCSS.
- **Web3**: Integración con Ethers.js.
- **Piñata**: Utilizado como puente con IPFS para crear los NFT.
- **Alchemy**: API utilizada para recuperar los NFT de cada usuario.
