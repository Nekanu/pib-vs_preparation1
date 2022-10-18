# PIB-VS - Preparation exercise 1

File-query service implemented over websocket communication in C

## Exercise

### Description

- A server provides a "file query" service over a websocket connection.
- Clients can connect to it, search for files and request the first `n` bytes of files.

### Request parameters

- file names (up to 5)
- integer number `n` (≤ 10)

### Response
Per file:

- If found, the first `n` bytes of the file
- If not found, a message that the file does not exist

### Requirements

- The server must be implemented in `C`
- The communication must be done over a websocket connection
