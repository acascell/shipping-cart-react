# shopping-cart-react
Create a shopping cart to make purchases using Vite, typescript, react

### 🚀 Overview
The shopping cart is essentially a react based application built using Vite with the support typescript.
It defines multiple components such as header,footer, navbar, product, productlist, cart emulating a more complex
e-commerce website using simple react components

![products.png](shopping-cart%2Fsrc%2Fassets%2Fproducts.png)
![cart.png](shopping-cart%2Fsrc%2Fassets%2Fcart.png)
![confirmation.png](shopping-cart%2Fsrc%2Fassets%2Fconfirmation.png)

### ✨ Features
The application utilise react hooks  use -> state, context, reducer to perform react operations utilising 
latest react function based hooks. Defined a context layer wrapping up both "cart" and "product" functionalities defned as "provider"
The main entrypoint glues up all the components, context and provider to spin up the acppication

```
ReactDOM.createRoot(document.getElementById('root')!).render(
  <React.StrictMode>
      <ProductsProvider>
          <CartProvider>
              <App />
          </CartProvider>
      </ProductsProvider>
  </React.StrictMode>,
)
```

### 🚀 Technology Stack
- react
- typescript
- html/css
- vite

### 🔎 TODO
- provide api endpoints maybe with fastpi
- define a db layer using sqlite/psql
