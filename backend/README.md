# Backend Server Instructions

## Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/jrkaseva/Velkakartta-TIEA207_Projekti.git
    cd TIEA207_Projekti/backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```
    
    if errors occur, add `express axios cors`

## Running the Server

1. Navigate to the backend directory:
    ```sh
    TIEA207_Projekti/backend
    ```

2. Start the server:
    ```sh
    npm start
    ```

The deafult port for the server is 3001, as seen in the .env content
The server should now be running and accessible at `http://localhost:3001`.

Fetched API data can be observed at `localhost:3001/api/<data>` where <data> can be one of the following:
- population (Population countries)
- gdp (Gross domestic product countries)
- debt (1st general government debt dataset)
- total_debt (Central government debt data)
- indicator (IMF indicators for datasets)
- gg_debt (2nd general government debt dataset)

The previous can also be seen in this directory's server.js file.
