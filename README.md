# Linq.js

Linq.js is a TypeScript library that provides LINQ-like query capabilities for arrays, allowing you to perform powerful data manipulations and transformations with ease.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Author](#author)

## Features

- Fluent and functional programming style for array operations.
- Filter, project, order, group, join, and more.
- Chain multiple operations together for complex transformations.
- Simplify common array manipulations.
- Supports TypeScript and modern JavaScript.

## Installation

Install the library using npm [Currnetly Not Available]

## Usage

Import the `Linq` class and start chaining operations:

```typescript
import { Linq } from 'linqjs';

const data = [/* your data array */];
const query = new Linq(data)
    .where(item => /* predicate function */)
    .select(item => /* selector function */)
    .orderBy((a, b) => /* comparer function */);

const result = query.toArray();
console.log(result);
```

## License

Linq.js is released under the MIT License. You can find the full license details in the [LICENSE](LICENSE) file.

## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

---

Open For Contribution

---

## Author

Linq.js is made with ❤️ by [NightmareGaurav](https://github.com/nightmaregaurav).
