# Cloudflare Workers

A collection of Cloudflare Workers for serverless computing and edge functions.

## Overview

This repository contains Workers applications and configurations for deploying serverless functions on Cloudflare's global edge network.

## Features

- **Edge Computing**: Deploy JavaScript/TypeScript code to Cloudflare's edge network
- **Low Latency**: Execute code closer to your users with automatic geographic distribution
- **Serverless**: No infrastructure management required
- **Scalable**: Automatically scales to handle traffic spikes

## Getting Started

### Prerequisites

- Node.js 16.0 or higher
- npm or yarn package manager
- Wrangler CLI installed globally

```bash
npm install -g wrangler
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/onnlight/cloudflare.git
cd cloudflare
```

2. Install dependencies:
```bash
npm install
```

3. Configure your Cloudflare credentials:
```bash
wrangler login
```

### Development

To run locally:
```bash
wrangler dev
```

### Deployment

Deploy to Cloudflare:
```bash
wrangler publish
```

## Project Structure

```
├── src/
│   ├── index.js       # Main Worker entry point
│   └── ...
├── wrangler.toml      # Cloudflare Workers configuration
├── package.json
└── README.md
```

## Configuration

Edit `wrangler.toml` to configure:
- Account ID
- Zone ID
- Environment variables
- Routes
- Build settings

## License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Resources

- [Cloudflare Workers Documentation](https://developers.cloudflare.com/workers/)
- [Wrangler CLI Documentation](https://developers.cloudflare.com/workers/cli-wrangler/)
- [Cloudflare API Documentation](https://developers.cloudflare.com/api/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For issues and questions, please open an issue in this repository.