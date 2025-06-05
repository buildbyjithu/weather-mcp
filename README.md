# Weather MCP

Weather MCP is a simple Node.js application built with TypeScript that fetches the current weather for a given location.

## Features

- Fetches real-time weather data for any city.
- Written in TypeScript for type safety and maintainability.
- Easy to set up and use via the command line.

## Tech Stack

- Node.js
- TypeScript
- (Optional) axios or node-fetch for HTTP requests
- (Optional) dotenv for environment variable management

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-mcp.git
   cd weather-mcp
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables (if using a weather API key):

   Create a `.env` file in the root directory and add:
   ```
   WEATHER_API_KEY=your_api_key_here
   ```

### Usage

Run the app with:

```bash
npm start --location="London"
# or
yarn start --location="London"
```

You can also build and run manually:

```bash
npm run build
node dist/index.js --location="London"
```

### Example Output

```
Current weather in London:
Temperature: 22°C
Condition: Clear sky
Humidity: 60%
```

## Configuration

- The application uses an environment variable `WEATHER_API_KEY` for authenticating with the weather API.
- You can change the default city or add more CLI options as needed.

## Contributing

Contributions are welcome! Please open issues or pull requests with improvements.

## License

[MIT](LICENSE)
