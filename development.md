---
layout: default
---

## Welcome to development page
# Funciones comunes de TypeScript

TypeScript, como superset de JavaScript, tiene varias funciones y métodos útiles que los desarrolladores utilizan con frecuencia.

## Funciones genéricas

Las funciones genéricas le permiten escribir una función que puede funcionar en varios tipos, en lugar de un solo tipo. Aquí hay un ejemplo.

```typescript
let sum = (x: number, y: number): number => { return x + y; }

let sumGeneric = <T>(x: T, y: T): T => { return x + y; }
```

## Funciones de flecha

Las funciones de flecha son una forma más corta de escribir funciones en TypeScript. Aquí hay un ejemplo.

```typescript
let sum = (x: number, y: number): number => { return x + y; }
```
## Interfaces de TypeScript Example

Las interfaces de TypeScript son una forma de definir la estructura de un objeto. Aquí hay un ejemplo.

```typescript
interface Person {
    name: string;
    age: number;
}

let person: Person = { name: 'John', age: 30 };
```



[back](./)
