# JL-Product-Card

This is a package of test to deploy to NPM.

### Joel Luciano

## Ejemplo

```
import {ProductCard,
ProductImage,
ProductTitle,
ProductButtons} from jl-product-card;
```

```
<ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
>
        {({ reset, increaseBy, isMaxCountReached, count }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>
```
