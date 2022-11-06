# projet-reseau

> This is an ad hoc network topology simulator. t is first established the network then found possible routes between sender and receiver nodes finally chosee optimal route among them.

### Setting-up the Nodes and the Neighbors
Each of our node carries two key informations:

1. location,
2. transmission range,

those informations are represented with: east (x1), west (x2), north (y1), and south (y2) coordinate limits.

To represent a neighbourhood we constructed a dictionary where key is node label and its corresponding value is its neighbors. (as in: 'A':['B', 'C'])


### Setting-up the Optimal Route
deciding the best route that a message must pass through from the sending node to reciever.