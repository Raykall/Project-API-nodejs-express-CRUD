# Football API - CRUD - NODE.JS + EXPRESS

This is a RESTful API built using Node.js and Express. The API allows for managing football players and clubs, including retrieving, creating, updating, and deleting players. It also supports basic operations on clubs.

## Features

- Retrieve all players or a specific player by ID.
- Create new players.
- Update a player's statistics.
- Delete a player by ID.
- Retrieve all clubs.

## Project Structure

The project follows a modular structure to separate concerns such as routes, controllers, services, repositories, and models. Below is a brief explanation of the structure:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm or [Yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Raykall/Project-API-nodejs-express-CRUD
    ```

2. Navigate to the project directory:
    ```bash
    cd Project-API-nodejs-express-CRUD
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

### Running the Application

To start the server, run:

```bash
npm start:dev or start:watch
```

The API will be running at http://localhost:{port}.

### Available Routes
<table>
<tr>
<th>Method</th>
<th>Endpoint</th>
<th>Description</th>
</tr>
<tr>
<td>GET</td>
<td>/players</td>
<td>Get all players</td>
</tr>
<tr>
<td>GET</td>
<td>/players/:id</td>
<td>Get player by id</td>
</tr>
<tr>
<td>POST</td>
<td>/players</td>
<td>Create a new player</td>
</tr>
<tr>
<td>PATCH</td>
<td>/players/:id</td>
<td>Update a player by ID</td>
</tr>
<tr>
<td>DELETE</td>
<td>/players/:id</td>
<td>Delete a player by ID</td>
</tr>
<tr>
<td>GET</td>
<td>/clubs</td>
<td>Get all clubs</td>
</tr>
</table>

### Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.