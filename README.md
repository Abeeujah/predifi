# PrediFi - Decentralized outcome prediction protocol (on-chain prediction platform )

Telegram Community: [here](https://t.me/predifi_onchain_build/1)
## Project Overview:
PrediFi is a decentralized prediction protocol built on StarkNet. In a trustless, transparent, and secure environment, it allows users to predict future outcomes across various fields, including sports, finance, and global events. By utilizing starknet technology, PrediFi ensures that all predictions and their results are verifiable onchain and immutable, thus eliminating the need for intermediaries.

PrediFi is a groundbreaking decentralized platform designed to empower individuals, influencers, and communities to enter the dynamic world of prediction markets. Leveraging the transformative power of blockchain technology, PrediFi allows anyone to establish custom prediction markets focused on any event imaginable. This innovative approach provides a lively, engaging, and rewarding way to foster interaction within your community while monetizing the buzz and excitement surrounding trending topics.

In our fast-paced digital age, conversations about predictions are captivating; they span a wide range of subjects, from sports matchups and political elections to the latest pop culture phenomena. Imagine if you could transform those engaging discussions into tangible rewards! With PrediFi, you have the opportunity to create markets where individuals can wager on the outcomes of these events, turning their insights and forecasts into real-world returns.

PrediFi makes it easy to create prediction pools for a wide range of cultural and local events. You can set up pools for major sports championships and awards shows, but that's just the beginning. It's also perfect for engaging with the latest viral trends, community events, environmental happenings, and anything else that sparks buzz in your area. Whether it’s predicting the outcome of a local music festival or the next viral sensation.

## Development:

Requirements:
- Rust
- Cairo
- Starknet foundry
- Node
- Pnpm

## Installation Guide:

Step 1:

1. Fork the repo

2. Clone the forked repo to your local machine 
  ``` bash
  git clone https://github.com/your-user-name/auto-swap
  ```

3. Setup contract:

  ```
  cd contracts
  ```
  
  // Install asdf scarb and starknet foundry:
  
  ``` bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.starkup.dev | sh
  ```
  
  // Method 2:
  
  Install asdf and install scarb, and starknet foundry: https://foundry-rs.github.io/starknet-foundry/getting-started/installation.html

4. Add development tools
  ``` bash
  asdf set --home scarb 2.9.2
  
  asdf set --home starknet-foundry 0.36.0
  
  ```
   
5. Ensure installed properly

 ``` bash
 snforge --version

 scarb --version
 ```

6. Build
``` bash
scarb build
```
7. Test
``` bash
snforge test
```

# Contributing

We welcome contributions! Please follow these steps:

## Getting Started

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes with meaningful messages (`git commit -m 'feat: add new capability'`)
4. Test your changes thoroughly before submission

## Testing Requirements

Before submitting your PR:
1. Set up your environment variable: `export RPC_URL=https://api.cartridge.gg/x/starknet/mainnet`
2. All tests must pass locally before proceeding

## Pull Request Process

1. Ensure your branch is up to date with main (`git pull origin main`)
2. Include comprehensive test cases covering your changes
3. Update documentation to reflect your modifications
4. Provide a detailed description in your PR explaining:
   - The problem solved
   - Implementation approach
   - Any potential impacts
5. Request review from project maintainers

## Code Standards

- Follow the existing code style and conventions
- Write clean, readable, and maintainable code
- Include comments for complex logic
- Keep commits focused and atomic

## Support

Need help with your contribution? You can:
- Open an issue in the GitHub repository
- Join our Telegram channel for community assistance 
- Check existing documentation and discussions

We aim to review all contributions promptly and appreciate your efforts to improve the project!
