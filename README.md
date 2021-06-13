# Priority Queue for Node.js

## Installation

```bash
npm install priority-queue-node
```

- [API](#api)
  - [constructor](#constructor)
  - [enqueue](#enqueue)
  - [dequeue](#dequeue)
  - [peek](#peek)
  - [size](#size)
  - [isEmpty](#isEmpty)

## API

### constructor

Initialize the Priority Queue.

To use the default comparator, pass no arguments to the constructor.

To use a custom comparator, pass a compare function as the only argument to the constructor

#### Example

```javascript
const PriorityQueue = require('priority-queue-node')

const priorityQueue = new PriorityQueue()

const customQueue = new PriorityQueue((a, b) => {
  return b - a
})
```
