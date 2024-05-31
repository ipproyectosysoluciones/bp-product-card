# BP-Product-Card

## Bladimir G. Parra B. | IP Proyectos y Soluciones

Este es un proyecto de prueba de despliegue de NPM

### Ejemplos

```javasript
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'bp-product-card';

```

```typescript

<ProductCard
  key={ product.id }
  product={ product }
  initialValues={{
    count: 6,
    // maxCount: 10,
  }}
>
  {
    ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```

