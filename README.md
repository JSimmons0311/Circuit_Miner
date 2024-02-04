# Circuit Miner

## Project Description

Circuit Miner is an educational project designed to provide an in-depth exploration of the process of mining Bitcoin. It uniquely utilizes a heterogeneous System on Chip (SoC) to interface with the Bitcoin Core, taking advantage of hardware acceleration to efficiently perform the SHA256 hashing algorithm. This project aims to offer a practical learning experience for individuals interested in understanding the technological aspects and challenges of Bitcoin mining.

## Hardware Required

- Xilinx Zynq 7020 SoC

## Software Required

- Vivado 2023.2

## Bitcoin Mining Primer

Bitcoin mining is the process by which new bitcoins are entered into circulation and involves the confirmation of transactions to the blockchain. Miners compete to add the next block to the blockchain by solving a complex computational puzzle, which requires significant processing power.

- **Block**: A block is a record in the blockchain that contains transactions. Each block is connected to the one before it, forming a chain.
- **Block Header**: The block header is a summary of a block's information. It includes the version, previous block hash, Merkle root, timestamp, difficulty target, and a nonce.
- **Block Size**: The size of a block refers to the amount of data it can hold. Bitcoin's block size is limited to 1MB, which affects the number of transactions that can be included in one block.
- **SHA256**: The SHA256 algorithm is used in Bitcoin's proof of work process. Miners must find a hash that is below a target set by the network's current difficulty level by varying the nonce in the block header.

Circuit Miner leverages the Xilinx Zynq 7020 SoC's capabilities to accelerate the SHA256 hashing process, providing a hands-on approach to understanding these concepts.

## Installation

Detailed installation instructions will be provided to set up the necessary hardware and software environment for Circuit Miner. This includes configuring the Xilinx Zynq 7020 SoC with Vivado 2023.2 and interfacing with the Bitcoin Core.

## Usage

Instructions on how to initiate the mining process, monitor mining activities, and interpret the results will be included. Users will learn how to engage with the Bitcoin network directly through the SoC, gaining insights into the mining process's computational aspects.

## Contributing

Contributions to the Circuit Miner project are welcome! Please refer to our contributing guidelines for more information on how to participate in the development and improvement of this educational tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Bitcoin Core developers for their open-source software that makes projects like this possible.

## Additional Resources

- [Bitcoin Mining Overview](https://bitcoin.org/en/how-it-works#mining)
- [Xilinx Zynq 7020 SoC Documentation](https://www.xilinx.com/products/silicon-devices/soc/zynq-7000.html)
- [Vivado Design Suite User Guide](https://www.xilinx.com/support/documentation-navigation/design-hubs/dh0002-vivado-design-hub.html)

For more information, visit our GitHub repository: [Circuit Miner](https://github.com/JSimmons0311/Circuit_Miner)
