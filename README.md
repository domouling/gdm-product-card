# GDM-Product-Card

Paquete de pruebas de despliegue en NPM

### Gilberto Domoulin


## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'gdm-product-card'
```

```
<ProductCard
    product={ product }
    initialValues={{
        count: 4,
        maxCount: 10
    }}
>

    {
        ( { reset, increaseBy, count, isMaxCountReached, maxCount } ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```