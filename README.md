# CDB-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Cristian Basualdo

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'cdb-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>
    {({
        reset,
        count,
        isMaxCountReached,
        increaseBy,
        maxCount,
    }) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>
    )}
</ProductCard>
```
