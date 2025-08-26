A lightweight, zero-dependency math utility library for TypeScript and JavaScript — starting simple, scaling smart.

Whether you're building games, crunching data, or just need a reliable random number generator, this package is designed to be clean, fast, and developer-friendly. It’s the beginning of a modular math toolkit that grows with your needs.

---

### ✨ Features

- 🎲 `randomInt(min, max)` — Generate a random integer between two bounds (inclusive)
- 🧠 Type-safe and framework-agnostic
- 🪶 Lightweight and tree-shakable
- 📦 Ready for expansion: vectors, geometry, number theory, and more

---

### 📦 Installation

```bash
npm install @ludeschersoftware/math
# or
yarn add @ludeschersoftware/math
```

---

### 🔧 Usage

```ts
import { randomInt } from '@ludeschersoftware/math';

const roll = randomInt(1, 6);
console.log(`You rolled a ${roll}`); // → e.g., "You rolled a 4"
```

---

### 📐 Function Reference

#### `randomInt(min: number, max: number): number`

Returns a random integer between `min` and `max`, inclusive.

- ✅ Inclusive of both bounds
- ⚠️ Assumes `min ≤ max`
- 🧪 Uses `Math.random()` internally

```ts
randomInt(0, 10); // → 0 to 10
randomInt(100, 200); // → 100 to 200
```

---

### 🧱 Roadmap

This package is just getting started. Planned additions include:

- `clamp`, `lerp`, `roundTo`
- `Vector2`, `Vector3`, matrix operations
- Geometry helpers: distance, angle, collision
- Seeded random, noise generators
- Number theory: GCD, LCM, modular arithmetic

Want to contribute or suggest a feature? Open an issue or drop a pull request!

---

### 🧼 License

MIT © Johannes Ludescher

---

### 💬 Feedback & Contributions

This is just the beginning. If you’ve got ideas, improvements, or want to help shape the future of `@ludeschersoftware/math`, your input is more than welcome.