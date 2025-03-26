# 🧠 Types of Logical Relations Between Statements

When examining how two statements relate logically, we can classify these relations into different types. Let’s explore each type, along with examples and logic trees to clarify how they work.

---

## 🎯 Identity-Based Relations

:::info Equivalence (↔) Two statements are logically equivalent if they are both true or both false.

**Example:**

- "A bachelor is an unmarried man." ↔ "An unmarried man is a bachelor."

**Logic Tree:**

```
Premise 1: A bachelor is an unmarried man.
Premise 2: An unmarried man is a bachelor.
Conclusion: The two statements are equivalent.
```

:::

:::danger Contradiction One statement must be true, and the other must be false.

**Example:**

- "The light is on." vs. "The light is off."

**Logic Tree:**

```
Premise 1: The light is on.
Premise 2: The light is off.
Conclusion: One must be true, the other false — they contradict each other.
```

:::

---

## 🔥 Logical Implication (→)

:::tip Implication If one statement is true, the other must be true.

**Example:**

- "If it rains, the ground will be wet."

**Logic Tree:**

```
Premise 1: If it rains, the ground will be wet.
Premise 2: It rains.
Conclusion: The ground is wet.
```

:::

:::info Contrapositive If Q is false, P must also be false.

**Example:**

- "If the ground isn’t wet, it didn’t rain."

**Logic Tree:**

```
Premise 1: If it rains, the ground will be wet.
Premise 2: The ground isn’t wet.
Conclusion: It didn’t rain.
```

:::

:::warning Converse Reversing the order of the implication.

**Example:**

- "If the ground is wet, then it rained." (Not necessarily true — could be sprinklers\\!)

**Logic Tree:**

```
Premise 1: If it rains, the ground will be wet.
Premise 2: The ground is wet.
Conclusion: It rained. (False assumption — converse isn’t guaranteed.)
```

:::

---

## 🛠️ Genus-Species Relation (Hierarchy)

:::info Genus and Species

- **Genus:** A broader category. (e.g., "Mammals" is the genus of "Dogs.")
- **Species:** A specific member of the genus. (e.g., "Dogs" are a species of "Mammals.")

**Logic Tree:**

```
Premise 1: Dogs are mammals.
Premise 2: Mammals are animals.
Conclusion: Dogs are animals.
```

:::

:::tip Differentia The unique characteristic separating species within a genus.

**Example:**

- Dogs bark, cats meow.

**Logic Tree:**

```
Premise 1: Dogs are mammals that bark.
Premise 2: Cats are mammals that meow.
Conclusion: Barking distinguishes dogs from cats.
```

:::

---

## 🔄 Contrariety and Subcontrariety

:::danger Contrary Both statements **cannot** be true, but they **can** both be false.

**Example:**

- "All dogs are black." vs. "No dogs are black."

**Logic Tree:**

```
Premise 1: All dogs are black.
Premise 2: No dogs are black.
Conclusion: Both cannot be true, but both can be false.
```

:::

:::info Subcontrary Both statements **can’t** be false together, but they **can** both be true.

**Example:**

- "Some dogs are black." and "Some dogs are not black."

**Logic Tree:**

```
Premise 1: Some dogs are black.
Premise 2: Some dogs are not black.
Conclusion: Both statements can be true simultaneously.
```

:::

---

## 🏗️ Subalternation (Strength of Statements)

:::tip Strength of Statements

- **Universal implies particular:** "All birds have feathers." → "Some birds have feathers." ✅
- **Particular does not imply universal:** "Some birds have feathers." → "All birds have feathers." ❌

**Logic Tree:**

```
Premise 1: All birds have feathers.
Conclusion: Some birds have feathers.
```

:::

---

## ⚡ Causal Relations (Cause and Effect)

:::info Cause → Effect One statement explains why the other happens.

**Example:**

- "The power went out." → "The lights turned off."

**Logic Tree:**

```
Premise 1: The power went out.
Conclusion: The lights turned off.
```

:::

:::warning Effect → Cause The observed event hints at a possible cause.

**Example:**

- "The lights turned off." → "The power might have gone out." :::

---

## ✅ Conclusion

Understanding logical relations helps us evaluate arguments and structure reasoning clearly. Each type — whether identity-based, hierarchical, or causal — frames how statements connect and influence one another.

Would you like a more complex example chaining multiple types together into one giant logic tree?