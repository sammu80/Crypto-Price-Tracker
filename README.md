# 🚀 Crypto Portfolio Tracker

A simple, open-source tool to track your cryptocurrency holdings, visualize portfolio performance, and manage assets across different exchanges and wallets.

## ✨ Features

-   **Multi-Asset Tracking:** Monitor various cryptocurrencies (BTC, ETH, SOL, etc.).
-   **Exchange Integration (Planned):** Connects to popular exchanges (e.g., Binance, Coinbase, Kraken) via API keys (future development).
-   **Wallet Tracking:** Manually add or automatically sync wallet balances (e.g., MetaMask, Ledger - *manual entry in current version*).
-   **Real-time Price Updates:** Fetches live price data from CoinGecko or CoinMarketCap.
-   **Portfolio Visualization:** Simple charts to show asset distribution and performance over time.
-   **Transaction History:** Log your buys, sells, and transfers.

## 🛠 Technologies Used

-   **Frontend:** HTML, CSS, JavaScript (or a framework like React/Vue for web app)
-   **Backend:** Python (Flask/Django) or Node.js (Express)
-   **Database:** SQLite (for local storage) or PostgreSQL/MongoDB (for scalability)
-   **APIs:** CoinGecko API for market data

## ⚙️ Installation & Setup

### Prerequisites

-   Python 3.x
-   `pip` (Python package installer)
-   Git

### Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/yourusername/crypto-portfolio-tracker.git](https://github.com/yourusername/crypto-portfolio-tracker.git)
    cd crypto-portfolio-tracker
    ```

2.  **Create a Virtual Environment (Recommended):**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Up API Keys (Optional but Recommended):**
    -   Get a free API key from [CoinGecko](https://www.coingecko.com/en/api) (or your preferred data provider).
    -   Create a `.env` file in the root directory and add your key:
        ```
        COINGECKO_API_KEY=YOUR_API_KEY_HERE
        ```

5.  **Run the Application:**
    ```bash
    python main.py  # For a CLI tool
    # Or for a web app:
    # python app.py
    ```

## 📂 Project Structure
