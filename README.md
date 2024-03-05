### Project Description: **Real-Time Crypto Price Tracker WebApp**

#### Overview
Develop a Next.js web application that connects to the Kraken WebSockets API to fetch and display real-time price information for a selected cryptocurrency. The app should include dynamic routing to handle different cryptocurrencies and use Redux for state management, emphasizing a clean architectural approach.

#### Core Features
1. **WebSocket Integration**: Implement WebSocket connection to Kraken API for real-time updates on cryptocurrency prices.
2. **Dynamic Routing**: Use Next.js dynamic routes (e.g., `/crypto/[symbol]`) to display a page for each cryptocurrency. The symbol in the route (`btc`, `eth`, etc.) determines which cryptocurrency's data to fetch and display.
3. **Redux for State Management**: Utilize the Redux Toolkit to manage the application state, including the WebSocket connection status, the current cryptocurrency prices, and any error messages.
4. **Real-Time Price Display**: On each cryptocurrency's page, display its current price, updating in real-time as data is received via WebSocket.
5. **Deployment**: Deploy the web application on Vercel or a similar platform and ensure the application is accessible online.

#### Architecture & Libraries
- **Next.js** for the React framework, supporting SSR and SSG, with dynamic routing.
- **Redux Toolkit** for state management, to store and manage the data received from the WebSocket connection.
- **cookies** or a similar library for managing cookies (if needed for saving user preferences or state).

#### Evaluation Criteria
- **Functionality**: The application must accurately fetch and display real-time price data for selected cryptocurrencies, with dynamic routing allowing for viewing different cryptocurrencies.
- **Code Organization**: Adherence to a structured approach, with clear separation between the application's logic (akin to ViewModel), state management (Model), and presentation (View).
- **Performance**: Efficient use of WebSockets and state management to handle real-time data without causing performance issues.
- **UI/UX Design**: The interface should be clean, responsive, and user-friendly.
- **Deployment**: The application should be deployed and accessible online, demonstrating the candidate's ability to launch a production-ready web application.

#### Deliverables
Candidates should submit:
- A link to the live site deployed on Vercel or another platform.
-

The GitHub repository URL containing the source code, including a README.md with:
  - Set up instructions for running the project locally.
  - An overview of the project structure and key decisions regarding the architecture and libraries used.
  - Any necessary documentation for understanding custom components or services.

