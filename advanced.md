## 🔵 Advanced TypeScript Questions

1. What happens when you explicitly annotate a variable with a wider type than the value assigned?
2. Why does this not cause a type error? → `const x: number = "123" as any;`
3. Explain why this type inference is incorrect and how to fix it (with object literals).
4. What's the risk of using `as const` vs explicit `readonly` types?
5. What happens when you combine `as const` and type widening?
6. When should you prefer explicit annotation over inference?
7. Why does this cause a type error? → `const nums = [1, 2, null];`
8. What does this function return type infer as? → `combine(a: number, b: string)`
9. How does inference work with overloaded function signatures?
10. How do you strongly type a class constructor function?
11. What’s the correct way to define and type static properties?
12. How do you enforce that a class implements a shape but also allows extra properties?
13. How do you annotate a function that takes another function and ensures both have matching parameter types?
14. What is the purpose of `Parameters<T>` and `ReturnType<T>`? Create a custom version.
15. Explain this complex function type:
    ```ts
    type Curried<T> = T extends (...args: [infer A, ...infer R]) => infer Ret
      ? (arg: A) => Curried<(...args: R) => Ret>
      : T;
    ```
16. What are union types in TypeScript? Provide an example.
17. What are intersection types in TypeScript? Provide an example.
18. How do you use type guards to narrow types?
19. What are type predicates in TypeScript?
20. What is the purpose of the `keyof` operator?
21. How do you use mapped types?
22. What are conditional types? Provide an example.
23. How do you use the `infer` keyword in conditional types?
24. What is the purpose of the `never` type?
25. How do you create and use type aliases?
26. How do you extend interfaces?
27. Can interfaces be merged? Provide an example.
28. Explain classes in TypeScript vs ES6 classes.
29. What are access modifiers (`public`, `private`, `protected`)?
30. How do you implement inheritance in TypeScript?
31. What is the purpose of `readonly` in interfaces and classes?
32. What is an abstract class and when to use it?
33. What is the purpose of `super()` in constructors?
34. How do you define and use function overloads?
35. How do you bind `this` context?
36. What is the difference between `extends` and `keyof` in generics?
37. How do you create and use generic interfaces?
38. What are utility types? Provide examples (`Partial`, `Required`, `Readonly`, `Pick`, `Omit`, etc.)
39. What are modules and how do they differ from namespaces?
40. What are decorators and how are they used? What is the Reflect API?
