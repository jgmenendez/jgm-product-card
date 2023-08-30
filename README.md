# JGM-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Javi García
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'jgm-product-card';
```

```
<ProductCard 
    product={ product }
    initialValues={ {
        count: 6,
        // maxCount: 10
    } }
>
    {
        ({ reset, isMaxCountReached, count, maxCount, increaseBy }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>    
        )
    }
</ProductCard>
```