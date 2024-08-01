# Espi-product-card

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'espi-product-card';
```


```
<ProductCard
                product={product}
                initialValues={{
                    count: 7,
                    maxCount: 10,
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
